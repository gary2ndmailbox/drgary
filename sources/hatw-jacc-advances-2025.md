---
dg-publish: true
title: "Hyperacute T Waves Are Specific for Occlusion Myocardial Infarction, Even Without Diagnostic ST-Segment Elevation"
date_ingested: 2026-05-03
source_type: original article
Citation: "Meyers HP, Šimunčík F, Herman R, Rafajdus A, Frick WH, de Alencar JN, Aslanger EK, Smith SW. Hyperacute T Waves Are Specific for Occlusion Myocardial Infarction, Even Without Diagnostic ST-Segment Elevation. JACC: Advances. 2025;4(10):102120."
DOI: "https://doi.org/10.1016/j.jacadv.2025.102120"
tags: [hyperacute-T-waves, occlusion-MI, ECG-diagnosis, acute-coronary-syndrome, STEMI-criteria]
rating: very high
raw_path: raw/HyperacuteT-JACC-Advances-2025.md
---

# Hyperacute T Waves Are Specific for Occlusion Myocardial Infarction, Even Without Diagnostic ST-Segment Elevation

## Authors, Journal, Affiliations, Type, DOI
- H. Pendell Meyers (Carolinas Medical Center), František Šimunčík (Powerful Medical), Robert Herman (Powerful Medical / OLV Hospital Aalst), Adam Rafajdus (Powerful Medical), William H. Frick (SSM Health St. Louis), José Nunes de Alencar (Instituto Dante Pazzanese), Emre K. Aslanger (Basaksehir Pine and Sakura City Hospital), Stephen W. Smith (Hennepin Healthcare / University of Minnesota)
- JACC: Advances, Vol. 4, No. 10, October 2025
- Multi-center international: 5 PCI centers (Belgium, Italy, Lebanon, 2 US)
- Original Research — retrospective derivation/validation study
- DOI: 10.1016/j.jacadv.2025.102120

## Overview
First study to derive and validate a quantitative, objective definition of hyperacute T-waves (HATWs) using T-wave magnitude (area under the curve relative to QRS amplitude) and T-wave symmetry (position of T-wave peak relative to entire T-wave duration). In 2,656 suspected ACS patients across 5 international PCI centers, the HATW score (≥0.7 mean in 2 contiguous leads) achieved 98.4% specificity and 20.7% sensitivity for OMI in patients without STEMI criteria — matching the specificity of STEMI criteria (97%) while identifying additional OMI cases. Simple T-wave amplitude alone was insufficient; the HATW score requires automated software measurement. The study provides the first clinically useful objective definition of this ACC/ESC-endorsed STEMI equivalent finding.

## Keywords
acute coronary syndrome, hyperacute T-waves, occlusion myocardial infarction, ST-segment elevation myocardial infarction equivalent, ST-segment elevation myocardial infarction

## Key Takeaways

### Methods
- Retrospective analysis of 3,274 adults undergoing ED assessment for possible ACS across 5 PCI centers (Belgium, Italy, Lebanon, 2 US). After exclusions (missing pre-angiogram ECG, QRS ≥110 ms, elevated troponin without angiogram), 2,656 patients remained.
- Derivation group: 1,261 patients (2,079 ECGs); validation group: 1,395 patients (separate site, per FDA best practices for ML).
- Primary OMI definition: acute culprit lesion with TIMI flow grade 0–1. Secondary definitions: TIMI 0–1 or TIMI 2–3 with peak troponin T >1,000 ng/L; expert contextual chart review.
- ECG experts (H.P.M. and S.W.S.) annotated each lead for HATW presence/absence with severity rating 0–5. ECGs with any HATW were ineligible as controls.
- HATW features measured: T-wave magnitude (area under curve J-point to T-wave end, relative to total QRS amplitude) and T-wave symmetry (time from T-wave peak to end relative to time from J-point to T-wave peak).
- HATW score trained via 2-layer feedforward neural network with logistic activation, weighted by expert severity ratings. Leads from STEMI-criteria ECGs excluded from training to optimize performance in non-STEMI subgroup.
- Lead eligibility: not aVR, QRS ≤110 ms, QRS amplitude ≥0.1 mV, positive T-wave ≥0.1 mV, T-wave start-to-peak and peak-to-end each ≥40 ms, T-wave neither inverted nor biphasic. Lead V₁ excluded due to insufficient HATW annotations.

### Derivation Results
- Derivation group: 21% OMI prevalence, 7.4% STEMI(+) OMI. Expert annotations: 1,401 HATW leads, 18,062 controls.
- Expert–automated STEMI criteria agreement: 97.3% (Cohen's κ = 0.80).
- T-wave amplitude alone was insufficient: could not achieve 98% specificity and >10% sensitivity simultaneously. The ratio of T-wave area to QRS amplitude significantly outperformed simple T-wave amplitude on all metrics.
- At threshold score 0.5, per-lead HATW score: 98.6% specificity, 57.1% sensitivity vs expert annotations.
- Optimal per-ECG threshold: ≥2 contiguous leads with mean HATW score ≥0.7 → 99.2% specificity, 27.4% sensitivity for OMI in derivation subgroup without STEMI criteria.
- HATWs generally have greater symmetry and magnitude than control T-waves.

### Validation Results
- Validation group: 1,395 patients, 10.6% OMI prevalence, 6.8% STEMI(+) OMI. Expert–automated STEMI criteria agreement 98.4% (κ = 0.88).
- All patients (with and without STEMI): HATW score 97% specificity, 45% sensitivity; STEMI criteria 97% specificity, 41% sensitivity — no significant difference by McNemar's test. STEMI criteria and/or HATW score: 96% specificity, 53% sensitivity.
- **Primary analysis — patients without STEMI criteria (n=1,300):** HATW score 98.4% specificity, 20.7% sensitivity, 47.4% PPV, 94.5% NPV, LR+ 12.54, LR− 0.81.
- Secondary OMI definitions: using TIMI 0–1 or TIMI 2–3 + TnT >1,000 ng/L → 98.8% specificity, 16.3% sensitivity; using expert chart review → 99.6% specificity, 30.3% sensitivity, LR+ 72.10.
- Exploratory (AMI with PCI): 99% specificity, 8.6% sensitivity.

### Clinical Outcome Analysis
- Of 38 patients with negative STEMI criteria but positive HATW score: 32 (84%) had a culprit lesion causing AMI; only 5 (13%) ruled out by serial negative troponins.
- OMI patients with STEMI criteria were far more likely to undergo angiography ≤90 min than OMI patients without STEMI criteria (86.9% vs 16.1%, P<0.001).
- 55.5% of OMI patients without STEMI criteria but with positive HATW score underwent angiography within 90 minutes (median 1.5 h, IQR 0.9–2.5).
- 42% of HATW-positive OMI patients with TIMI 0–1 did not receive angiography within 90 minutes despite ACC guideline recommendation — representing untreated STEMI-equivalent patients.

### Discussion
- First quantifiable HATW definition achieving clinically useful diagnostic performance. HATWs cannot be simply defined by T-wave amplitude — they require measurement of magnitude and symmetry.
- The HATW score components should be measured automatically by dedicated software; not simple enough for untrained human hand measurement.
- 58% of HATW-positive (non-STEMI) patients undergoing angiography within 90 minutes suggests some physicians are attempting to follow ACC/ESC STEMI-equivalent guidance, but 42% still do not receive timely reperfusion.
- Adds further evidence for low sensitivity of STEMI criteria for OMI (41% in this study, consistent with prior literature).
- Contradicts the "precursor" theory: prior published cohort of 17 TIMI-0 LAD patients with diagnostic HATWs on first ECG — none developed diagnostic STE on subsequent serial ECGs.
- de Winter T-waves (a HATW subset with ST depression) were not well-captured by the 2-variable score; a 3-variable score adding ST-segment depression is available in the supplement.
- T-wave magnitude and symmetry do not capture all HATW morphology features used by experts (e.g., concavity, reciprocal changes). Comparison with prior ECG (often unavailable) would improve assessment.

## Limitations of the Document
- Retrospective chart review design with inherent limitations.
- High-risk ACS cohort (10.6% OMI prevalence) — results may not generalize to all-comer ED populations with lower ACS prevalence.
- Race/ethnicity data not uniformly available — prior work shows distinct ECG morphologies in Black adults (greater T-wave amplitude), and generalizability to underrepresented populations warrants further study.
- T-wave magnitude and symmetry do not capture all expert-used morphology features (concavity, reciprocal findings). The study could not incorporate comparison with prior ECGs.
- HATW score requires dedicated software for T-wave area measurement — not currently feasible as a bedside hand calculation.
- External funding by Powerful Medical; multiple authors have financial relationships with Powerful Medical.

## Key Concepts Mentioned
- [[concepts/Hyperacute-T-waves]] — primary subject; first quantitative definition derived and validated
- [[concepts/OMI-NOMI-Paradigm]] — HATW score as objective tool within the OMI framework; confirms 41% STEMI sensitivity
- [[concepts/ST-T-Changes]] — T-wave amplitude vs. magnitude/symmetry distinction
- [[concepts/Cardiac-Repolarization]] — T-wave morphology physiology underlying HATW features

## Key Entities Mentioned
- [[entities/PMCardio-Queen-of-Hearts]] — PMcardio software used for automated ECG median beat construction and feature measurement
- [[entities/Acute-Coronary-Syndrome]] — clinical context for HATW score application

## Wiki Pages Updated
- [[concepts/Hyperacute-T-waves]] — added quantitative HATW score definition, derivation/validation performance, updated open questions
- [[concepts/OMI-NOMI-Paradigm]] — added HATW score evidence, STEMI sensitivity confirmation
- [[entities/PMCardio-Queen-of-Hearts]] — added HATW score measurement role
