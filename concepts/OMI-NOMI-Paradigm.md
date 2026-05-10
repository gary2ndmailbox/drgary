---
dg-publish: true
title: "OMI/NOMI Paradigm"
tags: [occlusion-MI, STEMI-criteria, ECG-diagnosis, acute-coronary-syndrome, artificial-intelligence-ECG]
source_count: 2
last_updated: 2026-05-03
---

# OMI/NOMI Paradigm

## Definition
The OMI/NOMI (Occlusion Myocardial Infarction / Non-Occlusion Myocardial Infarction) paradigm is a proposed reclassification of acute MI that replaces the STEMI/NSTEMI framework. Rather than stratifying patients by the presence of ST-elevation on ECG (a single morphological criterion), the OMI/NOMI framework stratifies by the underlying pathophysiology: **OMI = persistent acute coronary occlusion without adequate collateral perfusion, causing imminent and ongoing infarction**. NOMI = non-occlusive ischaemia without complete artery occlusion. The key argument is that ST-elevation is an imperfect surrogate for occlusion and therefore a poor gatekeeper for emergent reperfusion.

## Key Concepts

### Why STEMI Criteria Fail
- Standard STEMI criteria (4th Universal Definition of MI): ≥1 mm STE at J-point in ≥2 contiguous leads (≥2 mm in men ≥40y; ≥2.5 mm in men <40y; ≥1.5 mm in women in V2–V3)
- A recent meta-analysis documented only **43% sensitivity** of traditional STEMI ECG quantitative criteria for acute coronary occlusion. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)
- **38% of total LAD occlusions (TIMI-0 flow)** never met STEMI criteria on any serial pre-angiography ECG; serial ECGs did not evolve to STEMI criteria in any of these 20 cases. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)
- Sensitivity of STEMI criteria by TIMI flow (all arteries, n=808): TIMI-0 → 49%; TIMI-1 → 35%; TIMI-2 → 29%; TIMI-3 → 27%. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)
- Among patients with NSTEMI (non-STE), 25–34% have TIMI-0/1 flow at angiography — this subgroup has nearly **twice the mortality** of NSTEMI with TIMI ≥2, despite younger age and fewer comorbidities. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)
- Only 64% of definite STEMI have TIMI-0 flow at angiography; 16–20% have TIMI-3 flow — spontaneous reperfusion during transfer is common. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)
- The LAD territory is the highest-risk occlusion site due to larger myocardial territory: LAD OMI produces larger infarcts with higher mortality than occlusions of other epicardial arteries. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)
- **Meyers et al. 2025 confirm STEMI criteria sensitivity of 41%** (97% specificity) in an independent 1,395-patient validation cohort — consistent with all prior studies. The HATW score matched this specificity (97%) with 45% sensitivity; combining both yielded 96% specificity and 53% sensitivity. ([[sources/hatw-jacc-advances-2025]], rating: very high)

### OMI ECG Features Beyond ST-Elevation
The following ECG findings, assessed by expert or AI, reliably identify OMI even in the absence of diagnostic STE criteria. Prevalence in 20 subtle LAD OMI cases (TIMI-0, no STEMI criteria): ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)

| ECG Finding | Prevalence in Subtle LAD OMI |
|---|---|
| Subtle STE (<1 mm, not meeting criteria) | 85% |
| Hyperacute T-waves (incl. de Winter pattern) | 85% |
| Pathologic Q-waves (with subtle STE) | 70% |
| Reciprocal STD and/or T-wave inversion | 50% |
| Terminal QRS distortion | 20% |
| Inferior STE + aVL STD/T-inversion | 20% |
| Posterior OMI pattern (STD maximal V2–V4) | 0% |
| Modified Sgarbossa criteria (LBBB/VPR) | 0% |

- **Hyperacute T-waves** are not defined by amplitude alone; the T/R amplitude ratio is a key feature (anterior OMI T-waves are not taller than normal variant early repolarization, but R-waves are smaller → elevated ratio). See [[concepts/Hyperacute-T-waves]].
- **The HATW score** (Meyers et al. 2025) is the first objective, validated definition: T-wave magnitude (AUC/QRS amplitude) + T-wave symmetry, ≥0.7 in 2 contiguous leads → 98.4% specificity, 20.7% sensitivity in non-STEMI patients; 99.6% specificity, 30.3% sensitivity using expert chart review OMI definition. ([[sources/hatw-jacc-advances-2025]], rating: very high)
- **Terminal QRS distortion:** absence of both J-wave and S-wave in a lead where an S-wave would be expected, preceding any subtle STE.
- **Posterior OMI:** STD maximal in V1–V4 (formerly "posterior MI") — not seen in the LAD sub-group but an important OMI pattern for circumflex occlusion.
- **Modified Sgarbossa criteria:** concordant STE ≥1 mm, concordant STD ≥1 mm in V1–V3, or discordant STE:S ratio ≥0.25 — applies when LBBB or ventricular paced rhythm present.

### Expert vs AI vs STEMI Criteria Performance
- Expert OMI interpretation: **100% sensitivity** for all 53 LAD TIMI-0 cases on the first ECG; roughly double the sensitivity of STEMI criteria overall at near-equal specificity. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)
- PMCardio Queen of Hearts AI model: **100% sensitivity** for all 53 LAD TIMI-0 cases on the first ECG (P<0.0001 vs STEMI criteria). ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)
- In the validation cohort, AI model demonstrated **double sensitivity (67% vs 33%)** of STEMI millimetre criteria for OMI (TIMI-0/1 or TIMI-2/3 with culprit + intervention) at fixed specificity. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)
- See [[entities/PMCardio-Queen-of-Hearts]] for AI model details.

### Clinical Consequences of the STEMI-Only Model
- Patients with LAD occlusion not meeting STEMI criteria had **median DBT 97 min vs 40 min** (P<0.001) for those with STEMI criteria; DBT >90 min in 55% vs 21% (P=0.012). ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)
- Despite longer delays, **infarct size was equivalent**: peak troponin (P=0.52–0.53) and post-angiography EF (P=0.94) did not differ.
- 55% of the 20 missed cases had EF <50% post-angiography; 1 death during index hospitalisation.
- The majority of electrocardiographically subtle LAD OMI cases did not undergo timely reperfusion because they lacked diagnostic STE.
- **Diagnostic label paradox:** Among the 20 STEMI(−) OMI cases, those with DBT <120 min received a "STEMI" discharge diagnosis in 75% of cases; those with DBT >120 min received "NSTEMI" in 88% — suggesting diagnostic labels are sometimes retrospectively shaped by treatment speed, not ECG findings. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)

### Guideline Recognition
- 2022 ACC Chest Pain guideline acknowledged limited STE sensitivity and proposed additional criteria: hyperacute T-waves (including de Winter T-waves), posterior MI findings, LBBB/paced rhythm meeting modified Sgarbossa criteria — but provides no quantitative definition for hyperacute T-waves or posterior MI patterns. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)
- 2024 SCAI Expert Consensus on Managing STEMI patients similarly acknowledged limited STE sensitivity for occlusion. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)
- Neither document provides actionable criteria for the most common subtle OMI finding (hyperacute T-waves), leaving most physicians unable to act on the updated guidance.

## Contradictions / Open Questions
- **Specificity of expert and AI interpretation:** This sub-study could not calculate specificity (no non-OMI control group in the LAD TIMI-0 sub-analysis). In the full DOMI-ARIGATO study, expert interpretation had nearly equal specificity to STEMI criteria; AI model achieved double sensitivity at fixed specificity in the validation cohort. The tradeoff remains to be fully characterised in prospective real-world data. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)
- **Hyperacute T-wave definition:** No validated quantitative criteria exist for hyperacute T-waves. Smith et al. propose the T/R amplitude ratio as a key feature; the AI model recognises them via saliency mapping, but the exact computational mechanism is unexplained. Clinicians find this the hardest OMI criterion to apply. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)
- **Partially resolved:** The Meyers et al. 2025 HATW score (T-wave magnitude + symmetry, ≥0.7 in 2 contiguous leads) now provides the first validated quantitative definition, achieving 98–99% specificity. However, external validation in independent cohorts and diverse populations is still needed. ([[sources/hatw-jacc-advances-2025]], rating: very high)
- **Outcomes evidence for OMI-based vs STEMI-based strategy:** This paper documents DBT delay and equivalent infarct size, but prospective RCT evidence that switching to an OMI-based activation strategy improves mortality or LV function does not yet exist. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)
- **Conflict of interest:** Key authors (Meyers, Herman, Smith) have equity in Powerful Medical, the company that manufactures the Queen of Hearts AI model. This does not invalidate the finding that expert interpretation alone achieves 100% sensitivity, but the AI performance data should be interpreted with that context.

## Connections
- Related to [[concepts/ST-T-Changes]] — STEMI criteria measurement; OMI ECG patterns; de Winter pattern
- Related to [[concepts/Hyperacute-T-waves]] — the most prevalent OMI ECG finding in subtle cases
- Related to [[entities/Acute-Coronary-Syndrome]] — STEMI/NSTEMI classification context; prehospital ECG triage
- Related to [[entities/PMCardio-Queen-of-Hearts]] — AI ECG model achieving 100% sensitivity for OMI
- Related to [[concepts/MINOCA]] — differential for AMI without obstructive CAD
- Related to [[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]]
- Related to [[sources/hatw-jacc-advances-2025]] — HATW score as objective OMI diagnostic tool; confirms 41% STEMI sensitivity

## Sources
- [[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]]
- [[sources/hatw-jacc-advances-2025]]
