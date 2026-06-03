---
dg-publish: true
title: "Sgarbossa Criteria"
tags: [myocardial-ischemia, LBBB, ECG-diagnosis, acute-coronary-syndrome, electrocardiography]
source_count: 3
last_updated: 2026-05-30
---

# Sgarbossa Criteria

## Definition
The Sgarbossa criteria are ECG rules for diagnosing acute myocardial infarction in the presence of complete left bundle-branch block (LBBB), where secondary ST-T changes normally confound ischemia detection. Developed from retrospective GUSTO-I data by Elena Sgarbossa et al. (1996), they identify concordant and excessively discordant ST changes as markers of ischemia superimposed on LBBB. Modified Sgarbossa criteria replace the absolute discordant threshold with a ratio-based criterion offering better diagnostic accuracy.

## Key Concepts

### Why LBBB Confounds Ischemia Detection
- LBBB causes abnormal (cell-to-cell, slow) endocardium-to-epicardium LV depolarization → subendocardial myocytes repolarize before subepicardial → reversed repolarization direction → **discordant secondary ST-T changes** (T wave and ST deviation opposite to main QRS deflection)
- This secondary discordance is expected in LBBB and does not indicate ischemia; only **excessively** concordant or disproportionately large discordant changes are diagnostic
- Fascicular blocks and RBBB do NOT affect standard ST-elevation criteria; Sgarbossa criteria apply specifically to LBBB (and ventricular paced rhythms with identical mechanism)

### Original Sgarbossa Criteria (GUSTO-I Retrospective, 1996)
Three ECG findings; each scored as independent criteria:

| Criterion | Finding | Performance |
|---|---|---|
| 1 | Concordant ST elevation ≥1 mm in leads with positive QRS complex | High specificity, low sensitivity |
| 2 | Concordant ST depression ≥1 mm in V1–V3 (leads with dominant S wave) | High specificity, low sensitivity |
| 3 | Discordant ST elevation ≥5 mm in leads with negative QRS complex | Very low specificity and sensitivity (HERO-2 data) |

([[sources/ecg-ischemia-aha-2009]], rating: very high)

- Criteria 1 and 2 (concordant changes) are clinically useful; criterion 3 (5 mm discordant STE) has been shown in HERO-2 analysis to have very low specificity and sensitivity and is no longer recommended as the primary discordant criterion
- LBBB + concordant ST changes = **higher 30-day mortality** than LBBB + enzyme rise without concordant changes ([[sources/ecg-ischemia-aha-2009]], rating: very high)

### Aggregate Performance — Meta-Analysis (10 Studies)
- Total Sgarbossa score **≥3 → sensitivity 20% (95% CI 18–23%), specificity 98% (95% CI 97–99%)** for MI diagnosis in LBBB
- Very high specificity but very low sensitivity — a significant proportion of true STEMI in LBBB will be missed by ECG alone
- Concordant ST elevation ≥1mm (criterion 1, score 5): highest positive likelihood ratio for ongoing ischaemia — most clinically useful criterion
- Discordant ST elevation ≥5mm (criterion 3, score 2): relatively poor predictor; assigned lowest score
- In patients with LBBB of uncertain origin, decision-making cannot rely on ECG criteria alone; point-of-care troponin at 1–2 hours after symptom onset should be used when considering emergency angiography
- ([[sources/lbbb-europace-2017]], high)

### Proposed Modifications to Improve Diagnostic Accuracy
- **Smith modification:** Discordant STE ≥25% of the preceding S-wave amplitude (replaces absolute 5mm threshold); rationale — ischemic injury current should produce STE exceeding the proportion expected from LBBB alone
- **Selvester criterion:** Standard STEMI STE threshold + 10% × (S amplitude − R amplitude)
- **Philips QRS area criterion:** QRS area (rather than amplitude) used as the basis for ST comparison — better correlation with ST level
- All proposed modifications maintain high specificity but have not eliminated the fundamental sensitivity limitation
- ([[sources/lbbb-europace-2017]], high)

### Modified Sgarbossa Criteria (Smith et al.)
- Criterion 3 is replaced by: **ST elevation:S wave depth ratio ≥0.25** in any lead with a negative QRS complex (excessive discordant STE relative to QRS magnitude)
- Key principle: normal LBBB produces a discordant ST shift that is proportional to (and smaller than) the S wave depth; ischemia produces ST changes that exceed this proportion
- Also applicable to ventricular paced rhythms
- Integrated into the OMI ECG recognition framework (see [[concepts/OMI-NOMI-Paradigm]] and [[concepts/ST-T-Changes]])

![](/raw/assets/LBBB-Europace-2017.pdf-15-0.png)
### AHA 2009 Position
- Automated ECG algorithms should flag possible acute ischemia/infarction in patients with LBBB meeting Sgarbossa concordant criteria ([[sources/ecg-ischemia-aha-2009]], rating: very high)
- The original discordant criterion (≥5 mm) is acknowledged to have poor performance; the modified ratio criterion is not yet formalized in this 2009 document (pre-dates Smith modification)
- **AHA/ACCF/HRS Part III (2009) formally defines the basis:** LBBB criterion 7 states explicitly — "Depressed ST segment and/or negative T wave in leads with negative QRS (negative concordance) are **ABNORMAL**" — this is the multi-society consensus endorsement that concordant negative ST-T in LBBB indicates pathology, not secondary repolarization ([[sources/ecg-bbb-aha-2009]], rating: high). See [[concepts/ECG-Conduction-Disturbances]] for the full LBBB criteria table.

## Contradictions / Open Questions
- Original criterion 3 (discordant ≥5 mm) shown to have very low specificity and sensitivity (HERO-2); already superseded by modified ratio criterion in most contemporary ECG teaching, yet AHA 2009 document retains it
- **Fundamental sensitivity limitation:** Meta-analysis of 10 studies shows score ≥3 sensitivity only 20% — the majority of true STEMI in LBBB will not be detected by any version of Sgarbossa criteria alone; all proposed modifications (Smith, Selvester, QRS area) maintain high specificity but have not resolved the sensitivity problem ([[sources/lbbb-europace-2017]], high)
- Performance of modified Sgarbossa criteria in modern OMI paradigm and AI systems (PMCardio Queen of Hearts) vs. original criteria is incompletely characterized in prospective studies
- No prospective RCT validating that Sgarbossa-triggered reperfusion decisions improve outcomes vs. standard clinical judgement

## Connections
- Related to [[concepts/ST-T-Changes]] — LBBB secondary ST-T mechanism; ischemia recognition in LBBB
- Related to [[concepts/OMI-NOMI-Paradigm]] — Sgarbossa modified criteria integrated into OMI recognition toolkit
- Related to [[concepts/Wellens-Syndrome]] — parallel OMI ECG toolkit for recognizing occlusion beyond STEMI criteria
- Related to [[concepts/Cardiac-Repolarization]] — LBBB secondary ST-T changes mechanism
- Related to [[concepts/ECG-Conduction-Disturbances]] — AHA 2009 LBBB criterion 7 as formal basis; full IVCD criteria

## Sources
- [[sources/ecg-ischemia-aha-2009]]
- [[sources/ecg-bbb-aha-2009]]
- [[sources/lbbb-europace-2017]] — meta-analysis performance (score ≥3: sensitivity 20%, specificity 98%); Selvester and Philips QRS area modifications
