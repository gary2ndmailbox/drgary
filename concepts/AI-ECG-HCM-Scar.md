---
dg-publish: true
title: "AI-ECG Detection of LV Scar in HCM"
tags: [hypertrophic-cardiomyopathy, artificial-intelligence, ECG, LV-scar, explainability]
source_count: 1
last_updated: 2026-05-30
---

# AI-ECG Detection of LV Scar in HCM

## Definition
Machine learning approaches to detect and localize left ventricular (LV) scar in hypertrophic cardiomyopathy (HCM) using 12-lead electrocardiogram data, as an alternative to gold-standard late gadolinium enhancement (LGE) MRI. The key model in this space is **XplainScar**, the first explainable ML framework validated for this purpose.

## Key Concepts

### Why ECG-Based Scar Detection Matters in HCM
- LV scar (>15% of LV mass) and severe LVH (wall thickness >3 cm) are established risk factors for SCD and heart failure in HCM, driving ICD indication decisions in both ESC 2023 and AHA 2024 guidelines
- LGE-MRI, the current gold standard, is expensive, globally limited, and artifact-prone in patients with pacemakers or ICDs — the very patients at highest risk who most need monitoring
- In HCM, LV scar is patchy and mid-myocardial (not transmural or vascular in distribution), which explains why Q waves — reliable in ischemic scar — are **not** predictive in HCM ([[sources/lvh-scar-aiecg-naturesr-2025]])
- Small prior studies linked QRS fragmentation, low QRS voltage, T wave inversion, and strain pattern with LV scar in HCM, but no validated individual-level ECG prediction method existed before XplainScar

### XplainScar: Architecture and Pipeline
- Input: standard 10-second 12-lead ECG; output: probability of scar in basal, mid, and apical LV regions
- **Step 1 — Feature extraction**: 23 interpretable features per lead (QRS duration, amplitude, slope, energy, AUC; ST segment; T wave amplitude/inversion/energy; TP segment slope) → 276-dimensional feature vector; no compound features (avoids Selvester score bias) ([[sources/lvh-scar-aiecg-naturesr-2025]])
- **Step 2 — Confounder adjustment**: Multiple linear regression removes LV mass index, age, sex effects during training only
- **Step 3 — Unsupervised ECG clustering**: Dirichlet Process GMM partitions patients into ECG-similar subgroups; recursive merging produces 2 groups per regional task; this step is the most critical — removing it drops F1 from 92% to 41% ([[sources/lvh-scar-aiecg-naturesr-2025]])
- **Step 4 — Self-supervised learning (SCARF)**: Per-cluster contrastive pretraining (corrupts 60% of features, contrastive loss), then fine-tunes with supervised classification; removes need for large labeled datasets in each subgroup; adds ~10% F1 over supervised-only approach
- **Step 5 — Explainability (SHAP)**: Shapley values quantify feature contributions per prediction, enabling clinician-interpretable ECG signatures

### Performance (XplainScar)
- Training: n=500 (Johns Hopkins); External validation: n=248 (UCSF) — all real-world ECG patterns including paced/RBBB/LBBB
- **Global LV scar (JH)**: F1=92%, Se=95%, Sp=80%
- **Global LV scar (UCSF, external)**: F1=89%, Se=91%, Sp=78%, PPV=88%
- Regional UCSF: Basal F1=87%; Mid F1=85%; Apical F1=85%
- Processing time: <1 minute for 10 patients on standard PC ([[sources/lvh-scar-aiecg-naturesr-2025]])
- Outperforms all 5 state-of-the-art deep learning comparators (prior F1 range 41–69% vs XplainScar 92% on JH)

### ECG Signatures of Regional LV Scar (SHAP Findings)
- **Basal scar** → features in leads I, V1, aVR: deeper Q waves; prolonged non-terminal (intrinsicoid) QRS duration; smaller/less negative QRS area under curve; smaller T wave amplitude
  - Lead aVR is underutilized clinically but reflects basal septum + RV outflow tract activity — a novel physiologically-accurate finding
- **Apical scar** → T wave features dominate: T wave inversion in V2–V6; positive QRS complex area; TP segment slope variation
  - Consistent with prior ECG-based studies linking T wave inversion to apical HCM scar; XplainScar suggests fibrosis inverts the repolarization sequence
- **Mid scar**: T wave amplitude features in V5, V6, aVL, aVR
- **Higher scar burden (>15% LV mass)**: T wave inversion more frequent across chest AND limb leads; Q amplitude selected 14% more often; QRS energy (V5) higher
- **Lower scar burden (<15%)**: Non-terminal QRS duration selected 10% of the time

### Cross-Modal Validation of ECG Clusters
- ECG-derived patient clusters (created purely from ECG features) can be re-predicted from EHR/ECHO/MRI data with F1=0.86
- Top clinical correlates of ECG clusters: scar tissue %, LV end-systolic volume, NSVT history, maximal IVS thickness, LV apical wall thickness — none showed significant univariate difference; neural networks capture multivariate correlations ([[sources/lvh-scar-aiecg-naturesr-2025]])
- Validates that unsupervised ECG phenotyping reflects true biological structure

### Longitudinal Potential
- XplainScar detected LV scar in 74/86 patients with MRI-confirmed scar on ECGs taken ≥4 years later
- LGE represents irreversible replacement fibrosis — the model correctly identifies persistent scar over time
- 13/35 MRI-scar-negative patients flagged as positive; no follow-up MRI to determine if scar developed subsequently
- Prospective longitudinal validation required before clinical deployment as serial monitoring tool

## Contradictions / Open Questions
- **Wall-level localization unresolved**: XplainScar predicts segment-level (basal/mid/apical) but not wall-specific scar; septal wall F1~68%, anterior wall F1<30% due to data imbalance. Wall-specific model needed for therapeutic guidance ([[sources/lvh-scar-aiecg-naturesr-2025]])
- **RV insertion point LGE status**: XplainScar classified 28% of excluded RV insertion point LGE cases as scar-positive. Whether RV insertion point LGE represents true myocardial fibrosis remains debated; this finding is preliminary
- **Scar quantification gap**: XplainScar detects/localizes scar but cannot quantify scar percentage. The clinically relevant thresholds (>15% LV mass for SCD risk) require quantification — this cannot yet be replaced by ECG
- **Prospective validation absent**: All data are retrospective. ECG-based scar monitoring for longitudinal risk tracking requires prospective multicenter validation before guideline adoption
- **Training/validation scanner discrepancy**: 1.5T at JH vs 3T at UCSF likely contributes to performance difference — ground truth label quality may vary by scanner and reader
- **T wave inversion in apical HCM**: XplainScar identifies T wave inversion in V4–V6 as an apical scar signature, but deep T wave inversion is also seen in apical HCM without scar. Whether fibrosis is causal or a confounder of repolarization abnormality remains an open question

## Connections
- Related to [[concepts/HCM-Risk-SCD]] — LGE scar burden (>15% LV mass) as ICD indication driver; XplainScar as potential adjunct
- Related to [[concepts/ST-T-Changes]] — T wave inversion physiology and apical HCM pattern
- Related to [[concepts/ECG-Ventricular-Hypertrophy]] — ECG abnormalities in HCM
- Related to [[concepts/OMI-NOMI-Paradigm]] — parallel development of AI-ECG tools for cardiac pathology detection
- Related to [[entities/HCM]]
- Related to [[entities/XplainScar]]

## Sources
- [[sources/lvh-scar-aiecg-naturesr-2025]]
