---
dg-publish: true
title: "HCM Risk-SCD (and HCM Risk-Kids)"
tags: [sudden-cardiac-death, HCM, diagnostics, risk-stratification, guideline]
source_count: 3
last_updated: 2026-04-11
---

# HCM Risk-SCD (and HCM Risk-Kids)

## Definition
HCM Risk-SCD is a validated, quantitative risk-prediction calculator that provides individualized 5-year sudden cardiac death probability estimates for patients with hypertrophic cardiomyopathy (HCM) aged ≥16 years. HCM Risk-Kids is the paediatric equivalent for patients <16 years. These tools are the mandated first step in SCD prevention decision-making in HCM per ESC 2023 guidelines and differ from the AHA/ACC approach that treats the tool as an aid to qualitative decision-making rather than a primary threshold-based recommendation.

## Key Concepts

### HCM Risk-SCD (Adults ≥16 years)
- **ESC Recommendation:** Class I, Level B — required as first step in SCD risk estimation. ([[sources/esc-cmp-2023]])
- **Calculator URL:** https://qxmd.com/calculate/calculator_303/hcm-risk-scd
- **Input variables:** Age, maximum LV wall thickness, left atrial diameter, peak LVOT gradient, family history of SCD, unexplained syncope, NSVT on Holter. ([[sources/esc-cmp-2023]])
- **ICD thresholds:**
  - 5-year risk ≥6% → ICD should be considered (Class IIa, Level B)
  - 5-year risk ≥4% to <6% (intermediate) → shared decision-making (ICD may be considered, Class IIb)
  - 5-year risk <4% (low) → ICD may be considered if extensive LGE ≥15% or LVEF <50% (Class IIb) ([[sources/esc-cmp-2023]])
- Re-evaluation at 1–2-year intervals or whenever clinical status changes (Class I, Level B). ([[sources/esc-cmp-2023]])

### HCM Risk-Kids (Children <16 years)
- **ESC Recommendation:** Class I, Level B — recommended as first step in SCD risk estimation in children. ([[sources/esc-cmp-2023]])
- **Calculator URL:** https://hcmriskkids.org
- Validated in independent external cohorts since its development in 2019.
- Alternative: PRIMaCY Childhood HCM Sudden Cardiac Death Risk Prediction tool (https://primacy.shinyapps.io/calculator/). ([[sources/esc-cmp-2023]])
- ICD approach in children follows similar risk-threshold logic as adults, adjusted for pediatric context.

### Important Limitations and Caveats
- **Early-stage HCM limitation:** Existing SCD risk scoring systems have limited accuracy for patients with modest structural remodeling and mild disease manifestations. Many young asymptomatic patients can suffer SCD even without advanced LV remodeling, fibrosis, or severe microvascular dysfunction — these patients are missed by current tools. ([[sources/HCM-VA-FCVMed-2022]])
- **ACC/AHA vs. ESC discrepancy:** Major differences exist between ACC/AHA and ESC guidelines on SCD risk classification and ICD indications; real-world ICD implantation decisions from North American and European experts are often inconsistent. ([[sources/HCM-VA-FCVMed-2022]])
- Should NOT be used in: elite athletes; metabolic/infiltrative diseases (Anderson-Fabry disease, ATTR amyloidosis); syndromic cardiomyopathies (Noonan syndrome). ([[sources/esc-cmp-2023]])
- Does not incorporate exercise-induced LVOT gradients; not validated before/after myectomy.
- Validated after ASA in one study; LGE on CMR adds incremental prognostic value over the model but is not in the current calculator. ([[sources/esc-cmp-2023]])
- ESC 2023 vs. AHA/ACC 2020 divergence: ESC mandates the tool as threshold-driven; AHA/ACC treats it as one element of shared decision-making — reflecting different philosophical stances on quantitative vs. qualitative risk assessment. ([[sources/esc-cmp-2023]])

### Novel Risk Markers for Early-Stage HCM (Under Investigation)
- **Ion channel remodeling:** ↑INaL and ↑ILTCC detectable before structural changes; CaMKII-mediated and may reflect direct effect of gene mutation. See [[concepts/Ion-Channel-Remodeling-in-HCM]]. ([[sources/HCM-VA-FCVMed-2022]])
- **Specific high-risk mutations:** MYH7-R403Q, MYH7-R453C, MYH7-G716R, MYH7-R719W, TNNT2-R92W associated with high SCD incidence. MYBPC3 carriers: ↑ventricular arrhythmia and syncope. Multiple pathogenic variants = ↑risk. ([[sources/HCM-VA-FCVMed-2022]])
- **hiPSC-CM + machine learning:** Ca²⁺ transient signal analysis by machine learning can differentiate HCM subtypes; functional genomics platforms (e.g., TNNT2 variant screening) may enable scalable early-risk assessment. ([[sources/HCM-VA-FCVMed-2022]])
- **High-resolution ECG + whole-heart simulation:** Anatomically-corrected computerized simulations using individual MRI data may personalize arrhythmia risk assessment. ([[sources/HCM-VA-FCVMed-2022]])

### Additional Risk Markers (for shared decision-making in intermediate/low-risk patients)
- Extensive LGE ≥15% of LV mass on CMR ([[sources/esc-cmp-2023]])
- LVEF <50% ([[sources/esc-cmp-2023]])
- LV apical aneurysm (NOT recommended as sole indication by ESC 2023) ([[sources/esc-cmp-2023]])
- Note: sarcomeric variant presence alone does NOT change ICD recommendation independent of risk score. ([[sources/esc-cmp-2023]])

### AHA 2024 SCD Risk Framework (vs ESC 2023 Threshold-Driven Approach)
- AHA 2024 uses a **major risk factor framework** rather than a primary threshold-driven calculator. The 5-year SCD estimate is an **aid to shared decision-making** (Class IIa), not a decision threshold. ([[sources/HCM-AHA-2024]])
- **AHA 2024 major SCD risk factors for adults (Class IIa for ICD):**
  1. Prior cardiac arrest or sustained VT (Class I — secondary prevention)
  2. Arrhythmic syncope (especially within 6 months; >5 years in past = minimal significance)
  3. Family history of premature HCM-related SCD in first-degree or close relatives ≤50 years
  4. Massive LVH ≥30 mm (any segment); borderline consideration ≥28 mm
  5. LV apical aneurysm with transmural scar or LGE ← **Class IIa in AHA 2024** (contrast with ESC 2023: not recommended as sole ICD indication)
  6. LV systolic dysfunction EF <50%
  7. NSVT: ≥3 beats at ≥120 bpm; greater weight given to frequent, longer (≥10 beats), or faster (≥200 bpm) runs
  8. Extensive LGE ≥15% of LV mass (Class IIb when no other major risk factors)
- **Prespecified risk score thresholds should NOT be the sole arbiter of ICD decisions** (AHA 2024 consensus). ([[sources/HCM-AHA-2024]])
- ICD explicitly NOT recommended without risk factors (Class III: Harm); ICD for sole purpose of competitive sports also NOT recommended (Class III: Harm). ([[sources/HCM-AHA-2024]])
- **Pediatric genotype:** Genotype-positive status IS incorporated in the pediatric HCM risk calculator (unlike adult AHA tools). In children, sarcomeric variants are more closely associated with SCD. ([[sources/HCM-AHA-2024]])
- LV apical aneurysm and LGE/EF are **not included** in the current 5-year SCD risk calculator inputs; their independent quantitative impact on 5-year risk estimates is undetermined. ([[sources/HCM-AHA-2024]])

## Contradictions / Open Questions
- **ESC 2023 (threshold-driven) vs. AHA 2024 (decision aid):** ESC 2023 mandates the calculator as a Class I requirement with specific ICD thresholds (≥6% = Class IIa; 4–6% = Class IIb). AHA 2024 explicitly states prespecified risk score thresholds should NOT be the sole arbiter of ICD decisions and treats the 5-year SCD estimate as a Class IIa aid to shared decision-making. The same calculator, trained on the same data, is used in fundamentally different ways by two major guidelines — producing different ICD implantation rates for identical risk estimates. ([[sources/esc-cmp-2023]], [[sources/HCM-AHA-2024]])
- **LV apical aneurysm discordance:** AHA 2024 includes LV apical aneurysm with transmural scar/LGE as a major SCD risk factor (Class IIa for ICD). ESC 2023 does NOT recommend it as a sole ICD indication, noting insufficient data. Neither guideline includes apical aneurysm in the HCM Risk-SCD calculator inputs, meaning its quantitative contribution to 5-year risk is unknown. ([[sources/HCM-AHA-2024]], [[sources/esc-cmp-2023]])
- **Calculator not validated for early-stage disease:** The HCM Risk-SCD model was trained on patients with established phenotypic HCM; its accuracy for patients with early-stage or mild structural remodeling is limited. Young asymptomatic patients can suffer SCD without meeting any traditional risk threshold, suggesting the model has a systematic blind spot for the highest-stakes population. ([[sources/HCM-VA-FCVMed-2022]])

## Connections
- Related to [[entities/HCM]]
- Related to [[concepts/Sudden-Cardiac-Death]]
- Related to [[concepts/Late-Gadolinium-Enhancement]]
- Related to [[concepts/Ion-Channel-Remodeling-in-HCM]]
- Related to [[entities/MYBPC3]]
- Related to [[entities/MYH7]]
