---
dg-publish: true
title: "PMCardio Queen of Hearts"
tags: [artificial-intelligence-ECG, occlusion-MI, ECG-diagnosis]
source_count: 2
---

# PMCardio Queen of Hearts

## Details of the Concept
PMCardio Queen of Hearts is an AI-powered 12-lead ECG analysis model developed by Powerful Medical (Slovakia), designed specifically to identify acute coronary occlusion myocardial infarction (OMI) — including cases that do not meet standard STEMI ECG criteria. The model was trained and validated to detect OMI beyond ST-elevation, incorporating subtle ECG features such as hyperacute T-waves, subtle STE, terminal QRS distortion, and reciprocal changes. It is the central AI tool evaluated in the DOMI-ARIGATO sub-study investigating STEMI criteria failure for LAD OMI.

The PMcardio software platform also provides automated ECG feature extraction — including construction of median beats and precise measurement of amplitudes, area under the curve, and wave durations — which was used in the Meyers et al. 2025 study to derive and validate the first quantitative HATW score. ([[sources/hatw-jacc-advances-2025]], rating: very high)

## Key Facts

### Performance in DOMI-ARIGATO Sub-Study
- **100% sensitivity** for all 53 cases of total LAD occlusion (TIMI-0 flow) on the first available 12-lead ECG. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)
- **100% sensitivity** in the 20 LAD TIMI-0 cases that never met STEMI criteria on any serial ECG — equivalent to the blinded expert interpreter (S.W. Smith). ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)
- This is statistically superior to STEMI criteria (62% sensitivity for LAD TIMI-0; P<0.0001). ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)

### Validation Cohort Performance
- In the full international validation study (Herman et al., Eur Heart J Digital Health 2023), the AI model achieved **double sensitivity (67% vs 33%)** of STEMI millimetre criteria for OMI (defined as TIMI-0/1 or TIMI-2/3 with culprit intervention) at fixed specificity. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)

### Mechanism and Explainability
- The model uses a deep learning approach applied to the standard 12-lead ECG.
- **Saliency maps** (explainability outputs) show that the model identifies hyperacute T-waves in V2–V4 as key features in subtle LAD OMI — the exact computational mechanism is not fully characterised. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)
- The model appears to integrate the T/R amplitude ratio, T-wave morphology, reciprocal changes, and QRS features — analogous to the multi-feature expert ECG interpretation framework.
- **HATW score measurement role:** In Meyers et al. 2025, the PMcardio platform provided automated construction of median beats and measurement of all ECG features (T-wave area under curve, QRS amplitude, T-wave symmetry, STEMI criteria per 4th Universal Definition). This automated feature extraction was essential to the HATW score — the score cannot be calculated by hand and requires dedicated software. ([[sources/hatw-jacc-advances-2025]], rating: very high)
- Expert–automated STEMI criteria agreement: 97.3% in derivation (κ=0.80); 98.4% in validation (κ=0.88). ([[sources/hatw-jacc-advances-2025]], rating: very high)

### Conflict of Interest Context
- H.P. Meyers and S.W. Smith (lead authors of the DOMI-ARIGATO sub-study) and R. Herman are equity holders and/or consultants for Powerful Medical.
- R. Herman is the Chief Medical Officer of Powerful Medical.
- This financial relationship should be considered when interpreting AI performance claims; however, the equivalence between AI and expert interpretation — and the expert's blinded performance independent of the AI — provides some internal validation. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)

## Contradictions / Open Questions
- **Specificity not assessable in this sub-study:** The DOMI-ARIGATO LAD sub-analysis excluded non-OMI patients, so specificity could not be calculated. The full validation study reports specificity at fixed thresholds, but real-world false positive rates for cath lab activations are not reported. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)
- **Generalisability:** Performance was assessed in a high-risk, enriched academic centre cohort. Real-world performance in community EDs and prehospital settings has not been prospectively validated.
- **Black box concern:** The AI identifies hyperacute T-waves via saliency mapping, but the exact model architecture and feature weightings are proprietary, limiting independent reproducibility.

## Connections
- Related to [[concepts/OMI-NOMI-Paradigm]] — AI as a tool to implement the OMI paradigm
- Related to [[concepts/Hyperacute-T-waves]] — primary ECG feature identified by saliency mapping
- Related to [[entities/Acute-Coronary-Syndrome]] — clinical application context
- Related to [[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]]
- Related to [[sources/hatw-jacc-advances-2025]] — PMcardio software used for HATW score automated measurement

## Sources
- [[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]]
- [[sources/hatw-jacc-advances-2025]]
