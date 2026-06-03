---
dg-publish: true
title: "Explainable AI identifies and localizes LV scar in HCM using 12-Lead ECG"
date_ingested: 2026-05-30
source_type: original article
Citation: "Nezamabadi K, Sivalokanathan S, Lee J, et al. Explainable artificial intelligence identifies and localizes left ventricular scar in hypertrophic cardiomyopathy using 12-Lead electrocardiogram. Sci Rep. 2025;15:33918."
DOI: "https://doi.org/10.1038/s41598-025-09282-7"
tags: [hypertrophic-cardiomyopathy, artificial-intelligence, ECG, LV-scar, explainability]
rating: high
raw_path: raw/LVH-Scar-AIECG-NatureSR-2025.md
---

# Explainable AI Identifies and Localizes LV Scar in HCM Using 12-Lead ECG

## Authors, Journal, Affiliations, Type, DOI
- Kasra Nezamabadi, Sanjay Sivalokanathan, Jiwon Lee, Talha Tanriverdi, Meiling Chen, Daiyin Lu, Jadyn Abraham, Neda Sardaripour, Pengyuan Li, Parvin Mousavi, M. Roselle Abraham
- Scientific Reports (Nature portfolio), 2025; 15:33918
- University of Delaware (Computational Biomedicine Lab); UCSF HCM Center of Excellence; Johns Hopkins HCM Center of Excellence; Vanderbilt University; IBM Research; Queen's University, Kingston
- Original article — retrospective multi-center ML model development and external validation
- DOI: https://doi.org/10.1038/s41598-025-09282-7

## Overview
LV scar (detected by LGE-MRI) is a major risk factor for sudden death and heart failure in HCM, but MRI is expensive, unavailable worldwide, and artifact-prone with implanted devices. This paper introduces **XplainScar**, an explainable ML framework that detects and localizes LV scar from standard 12-lead ECG. Trained on 500 HCM patients from Johns Hopkins and externally validated on 248 from UCSF, XplainScar achieves F1=89%, sensitivity=91%, specificity=78% on the held-out set, running in <1 min for 10 patients on a standard PC. The model uses unsupervised ECG clustering (Dirichlet Process GMM), self-supervised contrastive learning (SCARF), and SHAP-based explainability to identify regional ECG signatures of basal, mid, and apical LV scar.

## Keywords
Left ventricular scar, Hypertrophic cardiomyopathy, Machine learning, Explainable AI, Unsupervised clustering, Self-supervised learning

## Key Takeaways

### Background and Clinical Motivation
- LV scar in HCM is patchy, mid-myocardial, and not in a vascular territory — unlike ischemic scar — which is why Q waves, predictive in ischemic cardiomyopathy, do not predict LV scar in HCM
- AHA/ACC guidelines recommend longitudinal LGE-MRI monitoring because LV scar >15% of LV mass and LV wall thickness >3 cm are major SCD risk factors
- MRI limitations: cost, limited global availability, susceptibility to artifacts from pacemakers/ICDs
- Small prior studies linked QRS fragmentation, low QRS voltage, T wave inversion, and strain pattern with LV scar in HCM, but no validated ECG-based prediction method existed

### Patient Population
- Training (JH dataset): n=500 HCM patients; MRI and ECG within 1 year; 5-fold cross-validation
- External validation (UCSF dataset): n=248; left-out test set; included paced rhythms, LBBB/RBBB (not in training)
- Excluded: ventricular-paced rhythms and LBBB from training; excluded LGE confined exclusively to RV insertion points (may not represent true scar)
- Ground truth: LGE quantified by experienced cardiologist within 1 year of ECG; labeled separately for basal, mid, apical LV regions

### XplainScar Pipeline (5 steps)
1. **ECG feature extraction**: 23 features per lead (QRS duration, amplitude, energy, AUC; ST segment; T wave amplitude, inversion, energy; TP segment slope) → 276-dimensional feature vector per patient
2. **Confounder adjustment**: Multiple linear regression to remove LVMI, age, sex effects from ECG features during training only (not applied at inference)
3. **Unsupervised clustering**: Dirichlet Process GMM partitions patients into homogeneous ECG-similarity subgroups; recursive merging until 2 merged groups per regional scar task; this step critical — removing it drops F1 from 92% to 41%
4. **Self-supervised + supervised learning (SCARF)**: Per-cluster neural network using SCARF (corrupts 60% of features randomly, contrastive pretraining), then fine-tunes with cross-entropy classification; self-supervised step adds ~10% F1
5. **Explainability (SHAP)**: Shapley values assigned to each of the 276 ECG features per prediction, identifying which features pushed toward Scar vs NoScar

### Model Performance
- **JH dataset (internal)**: Global LV scar — F1=92%, Se=95%, Sp=80%
- **UCSF dataset (external)**: Global LV scar — F1=89%, Se=91%, Sp=78%, PPV=88%
- Regional (UCSF): Basal F1=87% (Se 85%, Sp 82%); Mid F1=85% (Se 85%, Sp 83%); Apical F1=85% (Se 82%, Sp 92%)
- Processes 10 patient ECGs in <1 minute on standard PC (8 GB RAM, no GPU)
- Outperforms 5 state-of-the-art deep learning comparators (F1 41–69% vs XplainScar 92% on JH)

### ECG Signatures of LV Scar (SHAP Analysis)
- **Basal LV scar**: Deeper Q waves in leads I, V1, aVR; prolonged non-terminal (intrinsicoid) QRS duration; less negative QRS area under curve in V1–V2; smaller T wave amplitude
- **Apical LV scar**: T wave inversion in V2–V6; positive QRS complex area; TP segment slope variations; confirms prior studies on T wave inversion in apical HCM
- **Lead aVR**: Frequently selected for basal scar (R upstroke slope, absence of S wave, QRS fragmentation in V1) — a clinically underutilized lead; physiologically accurate as aVR reflects basal septum + RV outflow tract activity
- **High scar burden (>15% LV mass)**: T wave inversion selected more frequently across chest AND limb leads; Q amplitude selected 14% more often; QRS energy (V5) prominent

### Scar Burden and Detection Sensitivity
- Near-perfect detection when scar >10% LV mass; sensitivity drops proportionally with smaller scar burden
- Threshold of 15% LV mass (established SCD risk threshold) used for stratified ECG feature analysis

### Cross-Modal Validation
- ECG-derived patient clusters (unsupervised) predict EHR/ECHO/MRI cluster membership with F1=0.86 (supervised networks)
- Top clinical parameters correlating with ECG clusters (by region): scar tissue %, LV end-systolic volume, NSVT history, maximal IVS thickness (basal/mid); LV apical wall thickness, LV mass (apical)
- Validates that ECG clusters capture genuine clinical structure, not arbitrary partitions

### Longitudinal Testing
- 124 JH patients with ECGs ≥4 years after MRI: XplainScar detected scar in 74/86 with MRI-confirmed scar
- 13/35 without initial MRI scar labeled positive by XplainScar — no follow-up MRI to confirm whether scar developed
- Prospective longitudinal validation required

## Limitations of the Document
- Retrospective design; single time-point scar assessment (not true longitudinal validation)
- Cohort: 748 total — adequate for HCM studies but not large by ML standards
- Cannot quantify LV scar (detection/localization only)
- Wall-level localization limited: septal wall F1~68%; anterior wall F1<30% (data imbalance + model designed for segment-level)
- Training excluded LBBB/paced rhythms (though UCSF validation included them)
- Excluded RV insertion point LGE (28% labeled as scar-positive by XplainScar in post-hoc analysis of 39 cases — unclear significance)
- MRI scanner differences between centers (1.5T Siemens at JH vs 3T GE at UCSF) may explain small validation performance drop
- SHAP uses a linear importance model — does not reveal inter-feature nonlinear relationships

## Key Concepts Mentioned
- [[concepts/AI-ECG-HCM-Scar]] — the primary concept page for this paper
- [[concepts/HCM-Risk-SCD]] — LGE-MRI scar burden (>15% LV mass) as SCD risk factor; XplainScar as potential non-invasive adjunct
- [[concepts/ECG-Ventricular-Hypertrophy]] — ECG abnormalities in HCM context
- [[concepts/ST-T-Changes]] — T wave inversion in apical HCM scar

## Key Entities Mentioned
- [[entities/XplainScar]] — the ML framework described in this paper
- [[entities/HCM]] — hypertrophic cardiomyopathy

## Wiki Pages Updated
- Created: `wiki/sources/lvh-scar-aiecg-naturesr-2025.md`
- Created: `wiki/concepts/AI-ECG-HCM-Scar.md`
- Updated: `wiki/concepts/HCM-Risk-SCD.md` — added XplainScar as novel AI-ECG scar detection method
- Updated: `wiki/sourceindex.md`
- Updated: `wiki/wikiindex.md`
