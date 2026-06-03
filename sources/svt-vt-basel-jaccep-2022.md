---
dg-publish: true
title: "Simplified Integrated Clinical and Electrocardiographic Algorithm for Differentiation of Wide QRS Complex Tachycardia — The Basel Algorithm"
date_ingested: 2026-05-21
source_type: original article
Citation: "Moccetti F, Yadava M, Latifi Y, et al. Simplified Integrated Clinical and Electrocardiographic Algorithm for Differentiation of Wide QRS Complex Tachycardia — The Basel Algorithm. JACC Clin Electrophysiol. 2022;8(7):831–839."
DOI: "https://doi.org/10.1016/j.jacep.2022.03.017"
tags: [wide-complex-tachycardia, ventricular-tachycardia, supraventricular-tachycardia, electrocardiography, ECG-algorithm]
rating: high
raw_path: raw/SVT-VT-JACCEP-2022.md
---

# Simplified Integrated Clinical and Electrocardiographic Algorithm for Differentiation of Wide QRS Complex Tachycardia — The Basel Algorithm

## Authors, Journal, Affiliations, Type, DOI
- **Authors:** Federico Moccetti, Mrinal Yadava, Yllka Latifi, Ivo Strebel, Nikola Pavlovic, Sven Knecht, Babken Asatryan, Beat Schaer, Michael Kühne, Charles A. Henrikson, Frank-Peter Stephan, Stefan Osswald, Christian Sticherling, Tobias Reichlin
- **Journal:** JACC: Clinical Electrophysiology, Vol. 8, No. 7, July 2022, pp. 831–839
- **Affiliations:** Division of Cardiology, University Hospital Basel, Basel, Switzerland; Knight Cardiovascular Institute, Oregon Health & Science University, Portland, Oregon, USA; Inselspital Bern University Hospital, Bern, Switzerland
- **Type:** Original research — derivation and validation cohort study
- **DOI:** https://doi.org/10.1016/j.jacep.2022.03.017

## Overview
Wide QRS complex tachycardia (WCT) represents a diagnostically challenging emergency, as ~80% of cases are ventricular tachycardia (VT) while the remainder are SVT with aberrant conduction or other causes. Existing algorithms (Brugada 1991, Vereckei 2008) have high reported sensitivity/specificity in original cohorts but demonstrate poor real-world reproducibility due to their complexity. Moccetti et al. derived and externally validated a 3-criterion algorithm combining one clinical parameter and two ECG measurements. In a head-to-head clinical applicability test against 5 existing algorithms performed by 8 physicians across training levels, the Basel algorithm achieved superior or equivalent diagnostic accuracy in significantly shorter time.

## Keywords
ECG, cardiac arrhythmia, wide QRS complex tachycardia, ventricular tachycardia, supraventricular tachycardia, sudden cardiac death, algorithm

## Key Takeaways

### Study Design and Patient Population
- **Derivation cohort:** 206 WCT episodes (153 VT, 53 SVT) from 124 patients at University Hospital Basel, Switzerland (2010–2014); all EP-confirmed diagnoses.
- **Validation cohort:** 203 WCT episodes (151 VT, 52 SVT) from 112 patients at Knight Cardiovascular Institute, OHSU, Portland, Oregon.
- WCT is VT in ~80% of cases; misdiagnosis (e.g., treating VT as SVT with adenosine or verapamil) carries potentially lethal consequences.

### Derivation of the Basel Algorithm
- From multiple ECG candidate criteria tested in the derivation cohort, **lead II time to first peak** and **lead aVR time to first peak** had the best performance (AUC 0.91 each). ROC-derived optimal cutoffs were 51 ms (lead II) and 46 ms (lead aVR); a 40 ms cutoff was chosen to facilitate user-friendly clinical application.
- **Three criteria of the Basel Algorithm:**
  1. **Clinical high-risk feature** — prior myocardial infarction, OR congestive heart failure with LVEF ≤35%, OR implanted ICD or CRT-D
  2. **Lead II time to first peak >40 ms** — positive if time from QRS onset to first peak (positive or negative deflection) exceeds 40 ms
  3. **Lead aVR time to first peak >40 ms** — same measurement applied to aVR
- **Diagnosis: VT if ≥2 of 3 criteria are met; SVT if 0 or 1 criterion is met.**
- Observer agreement was excellent: r² = 0.94 (lead II) and r² = 0.92 (lead aVR); Bland-Altman bias ≤0.8 ms.

### Physiological Rationale
- In SVT with bundle branch block: impulse enters via the His-Purkinje system → rapid initial ventricular activation → steep initial QRS → narrow first peak in both leads.
- In VT: initial activation is muscle-to-muscle → slow initial spread → broad, delayed first peak (>40 ms); conduction system mediates only the terminal portion → steeper terminal QRS.
- This is the same theory underlying the Vereckei aVR step (RWPT >40 ms) and the Pava RWPT algorithm (>50 ms in lead II); the Basel algorithm integrates both into a 2-ECG-lead measurement framework.

### Performance in Derivation and Validation Cohorts
- **Basel algorithm:** SN 91.5%, SP 88.7% (derivation); SN 93.3%, SP 90.4% (validation) — comparable to Brugada and Vereckei algorithms (see Supplemental Table 3 in original article).
- No statistically significant difference in SN, SP, or overall accuracy vs Brugada or Vereckei in either cohort.

### Clinical Applicability (Head-to-Head vs 5 Algorithms, 8 Physicians)
- 8 physicians (2 EPs, 2 general cardiologists, 2 cardiology fellows, 2 internal medicine residents) analyzed 50 WCT ECGs (25 VT, 25 SVT) at 6 time points using Brugada, Vereckei, Pava, Jastrzebski, Chen, and Basel algorithms.
- **Diagnostic accuracy:** Basel 81% (IQR 76.5–83.5%) vs Vereckei 72% (IQR 65–76%; P=0.002) and Chen 72% (IQR 58–73%; P=0.03); no significant difference vs Brugada.
- **Specificity:** Basel 80% vs Vereckei 58% (P=0.007).
- **Time to diagnosis:** Basel **38 sec** (IQR 29–47) vs Brugada **106 sec** (IQR 76–135; P=0.002) vs Vereckei **48 sec** (IQR 43–59; P=0.02). Benefit most pronounced in fellows and internal medicine residents.

### Clinical Implications
- Suitable for emergency settings due to reliance on only limb leads II and aVR (no precordial morphology assessment required).
- Potentially compatible with Holter and telemetry software that includes only limb leads.
- Low complexity makes it particularly valuable for physicians in training and non-EP practitioners.

### Special Situations — Poor Performance
- All three compared algorithms (Brugada, Vereckei, Basel) performed poorly in:
  - **Fascicular VT** (n=3)
  - **Antidromic AV re-entrant tachycardia** (n=1)
  - **Mahaim fiber tachycardia** (n=3)
- These rare preexcitation and fascicular entities represent important exceptions requiring additional clinical context.

## Limitations of the Document
- Derivation and validation cohorts were both from tertiary EP centres — referral bias cannot be excluded; prevalence of VT (74–75%) may exceed community-based settings.
- Only EP-confirmed diagnoses included — selection bias since not all WCT patients undergo EP study.
- Relatively low number of preexcitation-related tachycardias in both cohorts; algorithm needs further evaluation in this subgroup.
- Some patients contributed multiple ECGs (different VT morphologies counted separately).
- No prospective validation in diverse community/emergency medicine settings.
- No automated application tested; potential for software integration noted as future direction.

## Key Concepts Mentioned
- [[concepts/Wide-Complex-Tachycardia]] — primary focus; Basel Algorithm development and validation
- [[concepts/ECG-Conduction-Disturbances]] — LBBB/RBBB pattern relevance in WCT differential
- [[concepts/Cardiac-Action-Potential]] — physiological basis of slow initial vs rapid terminal QRS activation in VT vs SVT with BBB

## Key Entities Mentioned
- [[entities/Brugada-Syndrome]] — Brugada algorithm (1991) for WCT differential, not Brugada syndrome per se; frequently referenced as standard of care comparator

## Wiki Pages Updated
- Created: `wiki/sources/svt-vt-basel-jaccep-2022.md`
- Created: `wiki/concepts/Wide-Complex-Tachycardia.md`
- Updated: `wiki/wikiindex.md`
- Updated: `wiki/sourceindex.md`
- Updated: `log.md`
