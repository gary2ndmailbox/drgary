---
dg-publish: true
title: "Methods in pharmacology: measurement of cardiac output"
date_ingested: 2026-05-29
source_type: review article
Citation: "Geerts BF, Aarts LP, Jansen JR. Methods in pharmacology: measurement of cardiac output. Br J Clin Pharmacol. 2011;71(3):316-330."
DOI: "https://doi.org/10.1111/j.1365-2125.2010.03798.x"
tags: [cardiac-output, hemodynamic-monitoring, thermodilution, pulse-contour-analysis, fick-principle]
rating: high
raw_path: raw/CO-BJCP-2010.md
---

# Methods in pharmacology: measurement of cardiac output

## Authors, Journal, Affiliations, Type, DOI
- Bart F. Geerts MD MSc, Leon P. Aarts MD, Jos R. Jansen PhD
- Departments of Anaesthesiology and Intensive Care Medicine, Leiden University Medical Center, Leiden, the Netherlands
- British Journal of Clinical Pharmacology, Vol 71(3):316–330
- Review article
- DOI: https://doi.org/10.1111/j.1365-2125.2010.03798.x

## Overview
This comprehensive 2010 review evaluates every commercially available cardiac output (CO) measurement method for pharmacological studies: Fick principle (direct O₂ and CO₂ rebreathing), indicator dilution (PAC thermodilution, continuous PAC, transpulmonary thermodilution, lithium dilution), pulse contour analysis (PiCCO, PRAM, LiDCO, Vigileo/FloTrac, Modelflow), echo-Doppler (transoesophageal and transthoracic), and thoracic bioimpedance. The "holy grail" — accurate, precise, non-invasive, continuous, fast responding, cheap, and safe — does not exist today. Comparative data against intermittent PAC thermodilution (Table 1) show that no method surpasses the averaged triplicate thermodilution synchronized to the ventilatory cycle (2 SD-precision ≤10%); transpulmonary methods and calibrated Modelflow/LiDCOplus can substitute for randomly applied triplicate thermodilution (2 SD-precision ≤20%). A key statistical insight: the commonly cited ±30% Bland-Altman acceptability threshold is an oversimplification of Critchley-Critchley, which requires the new method's error not to exceed the reference method's error (correct limit ≈ ±28% when reference precision is ±20%).

## Keywords
cardiac output, measurement method, methods

## Key Takeaways

### Fick Principle
- **Direct Fick (O₂)**: CO = VO₂ / (CaO₂ − CvO₂); VO₂ measured by indirect calorimetry; requires PAC for mixed venous blood sampling; most accurate method (reference standard to which others are compared in laboratory settings); labour-intensive; inaccurate at FiO₂ > 60%; requires haemodynamic stability during acquisition
- **Partial CO₂ rebreathing (NICO)**: CO = ΔVCO₂ / (S × ΔEtCO₂); uses disposable rebreathing loop with CO₂ infrared sensor + differential pressure transducer + pulse oximeter; CvCO₂ eliminated by paired baseline/rebreathing measurements; actually measures effective lung perfusion, not total CO — anatomic shunts cause underestimation; clinically acceptable only in mechanically ventilated patients with minor lung abnormalities; lacks agreement with reference techniques overall

### Indicator Dilution Techniques
All four commercially available methods compute CO from the Stewart-Hamilton equation: CO = indicator injected / ∫c(t)dt
- **Intermittent PAC thermodilution**: cold saline injected into right atrium via PAC; thermistor in pulmonary artery; 40-year clinical standard; best precision achieved by averaging 3 injections equally distributed over ventilatory cycle (2 SD-precision 3.5% vs 10% for 3 random injections vs 15% for single); PAC complications include arrhythmias, valvular lesions, PA rupture, lung infarction
- **Continuous PAC thermodilution (Vigilance)**: pseudorandom on/off thermal pulses via PAC filament; cross-correlation with PA thermistor output recreates dilution curve; continuous but NOT instantaneous — displayed value represents averaged previous 1–6 min (up to 12 min under extreme conditions); no user intervention required; safety of PAC debated (3 major RCTs showed no mortality difference with vs without PAC — may reflect interpretation failure rather than device failure)
- **Transpulmonary thermodilution (PiCCO)**: cold saline injected centrally; detection at femoral artery; PAC-free; broader dilution curve (lower SNR) but less affected by respiratory cycle; slightly overestimates PAC thermodilution due to indicator loss between aorta and femoral artery; 3 measurements averaged (3–10 min); additionally measures GEDV and EVLW
- **Transpulmonary lithium dilution (LiDCO)**: 1–2 mL isotonic LiCl (150–300 mmol) via venous bolus; ion-selective electrode in peripheral arterial line; CO = (Li dose × 60) / [(1 − PCV) × ∫Δc_li dt]; corrected for PCV because lithium distributes only in plasma; 3 measurements needed for precision; contraindicated with high-dose neuromuscular blockers, active lithium therapy, weight <40 kg; repetitive blood sampling required

### Pulse Contour Cardiac Output
All pulse contour methods use a mathematical model (NOT a mass balance), deriving CO from arterial pressure waveform shape. Origin: Windkessel model (Otto Frank 1899). Peripheral arterial pressure (radial or femoral) substitutes for aortic pressure, requiring backward filtering.

- **PiCCO**: Modified Wesseling cZ algorithm; COpi = K × HR × ∫[P(t)/SVR + C(P) × dP/dt]dt; calibration factor K determined by transpulmonary thermodilution; recalibration required after major SVR changes and at ≤1h intervals; radial or femoral artery usable; moderate accuracy/precision (limits of agreement ~32%)
- **PRAM (Vytech Health)**: Wesseling cZ variant; SV = A[(P/t) × K(t)]; characteristic impedance Z derived from pressure curve morphology without external calibration; K(t) derived from mean arterial pressure ratio to expected pressure (arctangent function of Langewouters data); CO presented as mean of 12 beats; vulnerable to signal quality and valve disease (aortic stenosis, regurgitation)
- **LiDCO/PulseCO**: Remington-Noback non-linear arterial pressure-volume relationship; nominal stroke volume multiplied by calibration factor derived from independent CO (thermodilution or lithium dilution); recalibration every 8h or with major haemodynamic changes; limits of agreement ~24%
- **Vigileo/FloTrac (Edwards)**: No external calibration; SV = σAP × Khi; σAP = standard deviation of arterial pressure over 20s; Khi is a multivariate polynomial (HR, σAP, MAP, Langewouters compliance, BSA, skewness, kurtosis of waveform) updated on rolling 60s average; worst performance in Table 1 (limits of agreement ~41%); highly dependent on high-fidelity arterial line signal
- **Modelflow (FMS Amsterdam)**: 3-element Windkessel (characteristic impedance + Windkessel compliance + peripheral resistance); compliance is pressure- and demographics-dependent (Langewouters equation); can be used uncalibrated (demographics only) or calibrated (independent CO or aortic diameter); calibrated Modelflow = best pulse contour performance in Table 1 (limits of agreement ~17%)

### Echo-Doppler Ultrasound Methods
- **Transoesophageal Doppler (TOD)**: probe orally/nasally in oesophagus at 35–45 cm; V = (Fd × c) / (2 × Fo × cosθ); CO from aortic blood flow × nomogram-based cross-sectional area (age, weight, height) × heart rate; minimal bias but limited agreement (meta-analysis Dark & Singer 2004); trend monitoring reliable if probe position unchanged; operator-dependent; poorly tolerated in awake patients; contraindicated with oesophageal disorders; 3 commercial systems (Deltex CardioQ, TECO Medicina, HemoSonic [discontinued])
- **Transthoracic Doppler (TTD)**: non-invasive; jugular notch probe; larger inter/intra-observer variability than TOD; measures aortic or pulmonary valve outflow; difficult anatomy in some subjects; portable

### Thoracic Electrical Bioimpedance
- High-frequency alternating current applied across thorax; resulting bioimpedance changes converted to CO by formula; inaccurate — movement artifacts, abnormal thoracic anatomy, valve disease, arrhythmias; meta-analysis (Raaijmakers et al.) — 3 decades of validation: better model needed; excluded from Table 1 comparison due to insufficient agreement
- **Bioreactance** (Cheetah Medical): phase-shift based (blood volume changes alter propagating electrical signal phase); correlates with SV; promising but awaits larger validation

### Statistical Evaluation of CO Methods
- **Bland-Altman analysis**: bias (mean difference) ± 2 SD-precision = limits of agreement; linear regression/correlation coefficients are insufficient and can be misleading (Bland & Altman 1995)
- **Critchley-Critchley criteria**: a new method's 2 SD-precision must not exceed the reference method's 2 SD-precision; if reference = ±20%, the limits of agreement (by Pythagoras) must be <√(20² + 20²) = ±28%; the commonly used ±30% threshold is an oversimplification and should not be applied without knowing the reference precision
- **Reference precision tiers**: 2 SD-precision 10% = 3 synchronized thermodilution measurements; 20% = 3 random thermodilution measurements; 30% = single thermodilution measurement

### Comparative Performance (Table 1 — against intermittent PAC thermodilution)
| Method | N | Bias (L/min) | Bias (%) | Limits of agreement (%) | 2SD at ref 20% |
|---|---|---|---|---|---|
| CO₂ rebreathing | 601 | −0.25 | −4.35 | 35 | 29 |
| Modelflow-calibrated | 995 | 0.00 | 0.00 | 17 | 16 |
| Modelflow-uncalibrated | 924 | 0.31 | 5.63 | 31 | 29 |
| PiCCOplus | 1802 | 0.04 | 0.73 | 32 | 30 |
| LiDCOplus | 452 | 0.05 | 0.91 | 24 | 22 |
| FloTrac-Vigileo | 1777 | 0.25 | 4.55 | 41 | 40 |

## Limitations of the Document
- 2010 publication — pulse contour software versions have evolved substantially since; Vigileo FloTrac algorithm in particular has seen multiple major updates (paper uses version ≥1.07)
- No ultrasound methods in Table 1 (insufficient head-to-head thermodilution comparisons, except HemoSonic which is discontinued)
- Bioimpedance excluded from Table 1 due to pre-existing meta-analysis conclusion of insufficient agreement
- Continuous CO method evaluation methodology "still awaited" (Cecconi & Rhodes 2009 cited) — Table 1 data drawn from heterogeneous studies with variable reference precision
- PRAM data sparse (only 3 studies); not included in Table 1

## Key Concepts Mentioned
- [[concepts/Cardiac-Output-Measurement]] — all CO measurement methods: Fick, indicator dilution, pulse contour, echo-Doppler, bioimpedance; comparative performance table

## Key Entities Mentioned
- Pulmonary artery catheter (Swan-Ganz, 1970)
- Vigilance system (Edwards Lifesciences)
- PiCCO system (Pulsion Medical Systems)
- PRAM (Vytech Health)
- LiDCO system (LiDCO, London)
- FloTrac/Vigileo (Edwards Lifesciences)
- Modelflow (FMS, Amsterdam)
- NICO (Novametrix Medical Systems) — CO₂ rebreathing
- Deltex CardioQ — transoesophageal Doppler
- Bioreactance (Cheetah Medical)

## Wiki Pages Updated
- `wiki/sources/co-bjcp-2010.md` — created (this file)
- `wiki/concepts/Cardiac-Output-Measurement.md` — updated (consolidated from Fick-Principle-Cardiac-Output, Pulse-Contour-Cardiac-Output, Indicator-Dilution-Cardiac-Output)
- `wiki/sourceindex.md` — updated
- `wiki/wikiindex.md` — updated
