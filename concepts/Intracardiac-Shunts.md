---
dg-publish: true
title: "Intracardiac Shunts"
tags: [intracardiac-shunt, congenital-heart-disease, pediatric-hemodynamics, cardiac-output, hemodynamic-monitoring]
source_count: 2
last_updated: 2026-05-28
---

# Intracardiac Shunts

## Definition
An intracardiac shunt is an abnormal communication between cardiac chambers or great arteries that permits mixing of systemic and pulmonary blood flows. The Qp/Qs ratio — pulmonary blood flow (Qp) divided by systemic blood flow (Qs) — quantifies shunt magnitude and guides clinical decision-making, including the indication for surgical or catheter-based correction.

## Key Concepts

### Qp/Qs Ratio — Classification and Clinical Significance
- **Qp/Qs <1.0** = Right-to-left shunt (desaturated blood bypasses pulmonary circulation → arterial desaturation)
- **Qp/Qs = 1.0** = No net shunt
- **Qp/Qs 1.0–1.5** = Small left-to-right shunt
- **Qp/Qs 1.5–2.0** = Moderate left-to-right shunt
- **Qp/Qs ≥2.0** = Large left-to-right shunt — generally considered an indication for surgical correction ([[sources/shunt-nature-sr-2020]] — medium)
- **Qp/Qs is a relative index** — it does not capture absolute pulmonary blood flow volume, which may be the more pathophysiologically relevant metric. Two patients with identical Qp/Qs 1.8:1 but cardiac outputs of 4 L/min and 6 L/min have absolute pulmonary flows of 7.2 L/min and 10.8 L/min — a 50% difference in right heart volume burden. CMR is required to measure absolute Qp and Qs ([[sources/asd-japc-2025]] — medium)

### Pathophysiology by Defect Level
- **Atrial-level defects (ASD, anomalous pulmonary venous drainage):** Oxygen-saturated blood re-enters pulmonary circulation → increased right-heart volume load ([[sources/shunt-nature-sr-2020]] — medium)
- **Ventricular/great artery defects (VSD, PDA, aortopulmonary collaterals):** Left heart volume overload or combined volume + right heart pressure overload depending on defect size ([[sources/shunt-nature-sr-2020]] — medium)
- **Right-to-left shunts:** Desaturated blood bypasses pulmonary circulation; occurs with large defects + elevated right-sided pressures (pulmonary hypertension), elevated central venous pressure, or bidirectional mixing
- **Bidirectional shunts:** Saturated and desaturated blood mix; seen with large defects + Eisenmenger physiology or dynamic pressure shifts between cardiac chambers

### Methods for Qp/Qs Estimation

#### Oximetric Shunt Equation (OSE) — Catheterization Laboratory Standard
- Uses arterial and mixed venous blood gases collected from pulmonary artery, IVC, SVC, and arterial catheter
- Mixed venous O₂ saturation estimated by Flamm's formula: (3 × SVC saturation + IVC saturation) / 4
- **Formula:** Qp/Qs = (CaO₂ − CmvO₂) / (CpvO₂ − CpaO₂)
- Requires cardiac catheterization and usually general anaesthesia; invasive
- Assumes steady-state (O₂ uptake = O₂ consumption); Flamm's formula may underestimate mixed venous saturation → falsely elevated Qp/Qs ([[sources/shunt-nature-sr-2020]] — medium)

#### Perivascular Flow Probes (PVFP) — Intraoperative Reference
- Transit-time ultrasound probes placed surgically around ascending aorta (Qs) and pulmonary truncus (Qp)
- Directly measures blood flow; Qp/Qs = Qp/Qs flow probe ratio
- Key limitation: aortic probe excludes coronary blood flow (~7% of cardiac output; higher in L→R shunt due to myocardial strain) → underestimates Qs → artificially elevates reported Qp/Qs ([[sources/shunt-nature-sr-2020]] — medium)
- Mean Qp/Qs PVFP vs OSE bias: only 0.07 in this cohort but percentage error 58.8% — considerable variability even between the two reference methods

#### COstatus Ultrasound Dilution — Minimally Invasive Bedside Alternative
- Extracorporeal AV loop connected to existing arterial and central venous catheters; saline bolus detected by ultrasound sensors
- Normal dilution curve is symmetric; L→R shunt causes delayed descent of the arterial dilution curve due to indicator recirculating through the pulmonary circuit
- Qp/Qs estimated from a:b ratio asymmetry at half-peak level: Qp/Qs ≈ (b/a)/1.4 ± 13%; reported as a categorical range value (not a continuous number)
- **Sensitivity 95.7%, specificity 97.6%, AUC 0.97** for detecting L→R shunts in young children (n=44, mean age 12 months) ([[sources/shunt-nature-sr-2020]] — medium)
- **Significantly underestimates Qp/Qs magnitude** in moderate and small shunt groups vs PVFP and OSE (p<0.05); algorithm likely requires paediatric optimisation
- No cardiac catheterisation required; needs only existing central venous + arterial access; also provides cardiac output and blood volume data ([[sources/shunt-nature-sr-2020]] — medium)

#### Echocardiography — Morphological Diagnosis, Not Quantitative
- First-line modality; color Doppler detects shunt presence, direction, and defect morphology
- **Cannot accurately quantify Qp/Qs** — fundamental clinical limitation; clinical decisions cannot rely on echo alone ([[sources/shunt-nature-sr-2020]] — medium)
- CMR is the non-invasive gold standard for Qp/Qs quantification but impractical in critically ill or mechanically ventilated patients

### Clinical Decision-Making
- Qp/Qs ≥1.5–2.0 is the threshold conventionally indicating surgical or catheter correction of ASD and VSD
- For ASD specifically, PVR <5 WU (ESC 2020) is an additional prerequisite for safe closure — see [[concepts/Atrial-Septal-Defect]]
- Echocardiography alone is insufficient for Qp/Qs quantification in borderline cases; invasive or semi-invasive methods are required

## Contradictions / Open Questions
- **Direction of error in dilution methods — overestimation (historical) vs underestimation (COstatus):** Older indicator dilution techniques in children overestimated Qp/Qs vs oximetric methods, caused by rapid systemic recirculation inflating the area under the dilution curve. COstatus underestimates Qp/Qs — the opposite direction — reflecting a corrected AUC algorithm that avoids overestimation but overcorrects in young children. Algorithm optimisation for the paediatric age group has not been published ([[sources/shunt-nature-sr-2020]] — medium)
- **No true reference standard for Qp/Qs:** Even between PVFP and OSE (both accepted reference methods), percentage error is 58.8%, reflecting systematic biases in both — coronary flow exclusion in PVFP and Flamm's formula limitations in OSE. The "gold standard" for Qp/Qs validation is itself imprecise ([[sources/shunt-nature-sr-2020]] — medium)
- **Utility of COstatus for complex congenital lesions:** This study was limited to simple ASD/VSD; performance in single-ventricle physiology, complex mixing lesions, or post-Fontan circulation is unknown
- **Qp/Qs ratio vs absolute flow — no validated absolute threshold:** While the relative Qp/Qs threshold of ≥1.5 guides closure decisions, no validated absolute pulmonary flow threshold has been defined. Individuals with high cardiac output (athletes, hyperdynamic states) may have clinically significant absolute right heart burden at the same Qp/Qs as low-output patients ([[sources/asd-japc-2025]] — medium)

## Connections
- Related to [[concepts/Cardiac-Output-Measurement]] — Stewart-Hamilton principle; COstatus as ultrasound dilution variant; shunt as source of thermodilution error
- Related to [[concepts/Atrial-Septal-Defect]] — Qp/Qs thresholds guiding ASD closure; non-invasive vs invasive Qp/Qs measurement in ASD evaluation
- Related to [[concepts/Right-Heart-Catheterization]] — cardiac catheterization as standard Qp/Qs method via oximetric shunt equation

## Sources
- [[sources/shunt-nature-sr-2020]]
- [[sources/asd-japc-2025]] — absolute vs relative shunt volume; exercise-induced shunt dynamics
