---
dg-publish: true
title: "Hyperacute T-waves"
tags: [occlusion-MI, ECG-diagnosis, LAD-occlusion, myocardial-ischemia, hyperacute-T-waves]
source_count: 2
last_updated: 2026-05-03
---

# Hyperacute T-waves

## Definition
Hyperacute T-waves (HATWs) are tall, broad, often symmetric T-waves that appear in the earliest phase of acute myocardial ischaemia due to coronary occlusion. They represent one of the earliest ECG manifestations of OMI, preceding — or in many cases replacing — diagnostic ST-elevation. They are **not defined by amplitude alone**; the critical feature is a disproportionately large T-wave relative to the QRS complex, particularly an elevated T-wave to R-wave amplitude ratio in the anterior leads, combined with excessive symmetry and increased T-wave "bulk" (area under the curve relative to QRS amplitude).

The first validated quantitative definition (Meyers et al. 2025) defines HATWs by two components: **T-wave magnitude** (area under the curve from J-point to T-wave end, relative to total QRS amplitude) and **T-wave symmetry** (time from T-wave peak to end relative to time from J-point to T-wave peak), combined via logistic regression into a unitless HATW score between 0 and 1. A per-ECG threshold of ≥2 contiguous leads with mean HATW score ≥0.7 achieves 98–99% specificity for OMI, matching the specificity of STEMI criteria. ([[sources/hatw-jacc-advances-2025]], rating: very high)

## Key Concepts

### Mechanism and Timing
- Hyperacute T-waves reflect early subepicardial ischaemia: the still-intact subendocardium repolarizes before the ischaemic subepicardium → T-wave vectors are directed toward the ischaemic zone → tall, wide T-waves in leads facing that zone.
- They are classically described as a transitional finding preceding ST-elevation. However, **this transition is not reliable**: in a cohort of 20 total LAD occlusions (TIMI-0) with hyperacute T-waves on their first ECG, 16/16 (100%) who had subsequent serial ECGs never evolved to STEMI criteria. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)
- Prevalence: **85% of total LAD occlusions not meeting STEMI criteria** had hyperacute T-waves — making it the single most common OMI ECG finding in subtle cases. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)

### Morphologic Features
- The T/R amplitude ratio is the key discriminator between hyperacute T-waves and normal variant early repolarization (benign early repolarization): in anterior OMI, R-wave amplitude is reduced (loss of septal/anterior voltage) while T-wave amplitude is preserved or increased → elevated ratio. In benign early repolarization, both R-wave and T-wave amplitudes are large. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)
- The "bulk" of the T-wave — its width and area under the curve relative to QRS size — is considered more important than peak amplitude.
- Excessive T-wave symmetry (equal ascending and descending limbs) distinguishes hyperacute T-waves from the typical asymmetric T-wave of normal repolarisation.
- Smith's formula (for subtle anterior OMI vs benign early repolarization): uses R-wave amplitude in V4, corrected QT interval, and STE 60 ms after the J-point in V3. Driver et al. added total QRS amplitude in V2 to improve the model.

### de Winter Pattern (Hyperacute T-wave Variant)
- A specific hyperacute T-wave variant signifying proximal LAD occlusion: upsloping ST depression in V1–V6 + peaked ("hyperacute") T-waves, with or without STE in aVR.
- The mechanism is identical to hyperacute T-waves; the upsloping STD reflects the specific pattern of ischaemia in tight proximal LAD occlusion.
- Recognised in the 2022 ACC Chest Pain guideline as a criterion for emergent cath lab activation. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)
- Listed as an OMI ECG finding in the STEMI criteria failure cohort (included within the hyperacute T-wave category). ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)

### AI Recognition
- The PMCardio Queen of Hearts AI model correctly identified hyperacute T-waves in all 20 subtle LAD OMI cases, as demonstrated by saliency maps highlighting the T-wave morphology in V2–V4. The exact computational mechanism by which the model recognises hyperacute T-waves is not fully understood. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high)

### Quantitative HATW Score (Meyers et al. 2025)
- The first objective, validated HATW definition was derived from 1,261 patients (2,079 ECGs) with expert-annotated HATWs across 5 international PCI centers, and validated in a separate 1,395-patient cohort. ([[sources/hatw-jacc-advances-2025]], rating: very high)
- **Components:** T-wave magnitude (area under curve J-point to T-wave end, relative to total QRS amplitude) + T-wave symmetry (time from T-wave peak to end relative to time from J-point to T-wave peak). Combined via 2-layer feedforward neural network into a score 0–1.
- **Lead eligibility criteria:** not aVR; QRS ≤110 ms; QRS amplitude ≥0.1 mV; positive T-wave ≥0.1 mV; T-wave start-to-peak and peak-to-end each ≥40 ms; T-wave neither inverted nor biphasic. Lead V₁ excluded (insufficient HATW annotations).
- **Per-ECG threshold:** ≥2 contiguous leads with mean HATW score ≥0.7.
- **Performance (validation, non-STEMI patients, n=1,300):** 98.4% specificity, 20.7% sensitivity, 47.4% PPV, 94.5% NPV, LR+ 12.54, LR− 0.81. Using expert chart review OMI definition: 99.6% specificity, 30.3% sensitivity, LR+ 72.10.
- **All-patients comparison:** HATW score (97% spec, 45% sens) vs STEMI criteria (97% spec, 41% sens) — not statistically different. HATW score and/or STEMI criteria: 96% spec, 53% sens.
- **T-wave amplitude alone is insufficient:** could not achieve 98% specificity and >10% sensitivity simultaneously. The ratio of T-wave area to QRS amplitude significantly outperformed simple amplitude.
- **Clinical yield:** Of 38 patients with negative STEMI criteria but positive HATW score, 32 (84%) had a culprit lesion causing AMI; only 5 (13%) ruled out by serial negative troponins.
- **Practical limitation:** The HATW score requires automated software for T-wave area measurement — not feasible as a bedside hand calculation. Intended as a tool for AI/automated ECG interpretation systems rather than manual use.
- Analysis divided into 3 lead groups (limb leads, V₁–V₃, V₄–V₆) because HATW characteristics differ by lead group.
- A 3-variable version adding ST-segment depression (to capture de Winter T-waves and reciprocal STD) was also developed (see supplement). ([[sources/hatw-jacc-advances-2025]], rating: very high)

### Clinical Significance
- Hyperacute T-waves in the appropriate clinical context (chest pain, risk factors) should prompt expert ECG review or AI-assisted interpretation, even in the absence of STEMI criteria.
- The 2022 ACC Chest Pain guideline and 2017 ESC STEMI guideline acknowledged hyperacute T-waves as a STEMI equivalent requiring emergent reperfusion, but previously provided no quantitative definition — the Meyers et al. 2025 HATW score is the first to fill this gap. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high) ([[sources/hatw-jacc-advances-2025]], rating: very high)
- 42% of HATW-positive OMI patients (TIMI 0–1) did not receive angiography within 90 minutes despite ACC recommendations — a significant care gap. ([[sources/hatw-jacc-advances-2025]], rating: very high)

## Contradictions / Open Questions
- **First quantitative definition now exists, but external validation needed:** The Meyers et al. 2025 HATW score (T-wave magnitude + symmetry, ≥0.7 in 2 contiguous leads) is the first validated quantitative HATW definition with clinically useful performance. However, it requires external validation in independent cohorts, lower-prevalence populations, and diverse racial/ethnic groups (race-stratified performance data were not available). ([[sources/hatw-jacc-advances-2025]], rating: very high)
- **Software dependency:** The HATW score cannot be calculated by hand — it requires automated software measurement of T-wave area. This limits bedside applicability; the primary near-term use is in AI/automated ECG interpretation systems. ([[sources/hatw-jacc-advances-2025]], rating: very high)
- **Incomplete morphology capture:** T-wave magnitude and symmetry do not capture all HATW features used by experts (T-wave concavity, reciprocal negative hyperacute T-waves, comparison with prior ECG). A 3-variable score adding ST-segment depression partially addresses this. ([[sources/hatw-jacc-advances-2025]], rating: very high)
- **Do hyperacute T-waves evolve to STEMI criteria?** The traditional teaching is that hyperacute T-waves are a transitional stage that will evolve to classic ST-elevation. The DOMI-ARIGATO sub-study directly contradicts this: 16/16 cases with serial ECGs never evolved to STEMI criteria. Meyers et al. 2025 reinforce this: a separate published cohort of 17 TIMI-0 LAD patients with diagnostic HATWs on first ECG — none developed diagnostic STE on subsequent serial ECGs. ([[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]], rating: high) ([[sources/hatw-jacc-advances-2025]], rating: very high)
- **de Winter T-waves not fully captured:** The 2-variable HATW score does not optimally identify de Winter T-waves (which feature ST depression in leads with hyperacute T-waves). A 3-variable score incorporating ST-segment depression is under development. ([[sources/hatw-jacc-advances-2025]], rating: very high)

## Connections
- Related to [[concepts/OMI-NOMI-Paradigm]] — hyperacute T-waves are the most common OMI ECG finding in subtle cases
- Related to [[concepts/ST-T-Changes]] — mechanism of T-wave changes in ischaemia; de Winter pattern
- Related to [[entities/PMCardio-Queen-of-Hearts]] — AI model that reliably identifies hyperacute T-waves via saliency mapping
- Related to [[entities/Acute-Coronary-Syndrome]] — clinical context for hyperacute T-waves
- Related to [[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]]
- Related to [[sources/hatw-jacc-advances-2025]] — first quantitative HATW definition and validation

## Sources
- [[sources/failure-stemi-criteria-lad-omi-ehjacc-2025]]
- [[sources/hatw-jacc-advances-2025]]
