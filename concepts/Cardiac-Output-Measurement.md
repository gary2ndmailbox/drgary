---
dg-publish: true
title: "Cardiac Output Measurement"
tags: [cardiac-output, hemodynamic-monitoring, thermodilution, pulmonary-artery-catheter, fick-principle, pulse-contour-analysis, critical-care]
source_count: 4
last_updated: 2026-05-29
---

# Cardiac Output Measurement

## Definition
Cardiac output (CO) measurement methods fall into five classes: (1) Fick principle (direct O₂ and CO₂ rebreathing), (2) indicator dilution (thermodilution via PAC, transpulmonary thermodilution, lithium dilution, ultrasound dilution), (3) pulse contour analysis (PiCCO, PRAM, LiDCO/PulseCO, Vigileo/FloTrac, Modelflow), (4) echo-Doppler (transoesophageal, transthoracic), and (5) thoracic bioimpedance/bioreactance. The "holy grail" — a method that is accurate, precise, operator-independent, fast-responding, non-invasive, continuous, easy to use, cheap, and safe — does not exist. Every method involves trade-offs between accuracy, invasiveness, and practicality.

## Key Concepts

### Ideal Method Criteria and Statistical Evaluation
- **Critchley-Critchley criterion**: a new CO method is acceptable only if its 2 SD-precision does not exceed that of the reference method; when the reference (PAC thermodilution) has 2 SD-precision of ±20%, the Bland-Altman limits of agreement for the new method must be <√(20² + 20²) = **±28%** — not the commonly used ±30% threshold (which is an oversimplification) [[sources/co-bjcp-2010]] (high)
- **Reference precision tiers** (PAC thermodilution): 2 SD-precision 10% = 3 injections synchronized to ventilatory cycle; 20% = 3 random injections; 30% = single injection [[sources/co-bjcp-2010]] (high)
- Linear regression/correlation coefficients are insufficient for method comparison; Bland-Altman plot (bias ± 2 SD) is the appropriate approach [[sources/co-bjcp-2010]] (high)

### Fick Principle

#### Direct Fick for Oxygen
- **Formula**: CO = VO₂ / (CaO₂ − CvO₂), where VO₂ = O₂ uptake (mL O₂ min⁻¹), CaO₂ and CvO₂ = arterial and mixed venous O₂ content (mL O₂ L⁻¹) [[sources/co-bjcp-2010]] (high)
- VO₂ measured by spirometry (CO₂ absorber) or indirect calorimetry monitor; mixed venous blood (CvO₂) requires PAC for sampling [[sources/co-bjcp-2010]] (high)
- **Most accurate method** — laboratory reference standard to which all other methods are compared; not practical for routine clinical monitoring [[sources/co-bjcp-2010]] (high)
- Accuracy caveats: (i) many variables → compound permutation of errors; (ii) FiO₂ >60% decreases accuracy; (iii) haemodynamic stability required; (iv) labour-intensive
- **Summary**: invasiveness +++, accuracy high, precision moderate; requires PAC + spirometer/mechanical ventilator

#### Partial CO₂ Rebreathing (NICO)
- Applies Fick principle to CO₂: **CO = ΔVCO₂ / (S × ΔEtCO₂)**, where ΔVCO₂ = change in CO₂ production, ΔEtCO₂ = change in end-tidal CO₂ during rebreathing, S = slope of CO₂ dissociation curve [[sources/co-bjcp-2010]] (high)
- Disposable rebreathing loop with CO₂ infrared sensor + differential pressure transducer + pulse oximeter; CvCO₂ eliminated mathematically (CO₂ diffuses 22× faster than O₂ → CvCO₂ unchanged during brief rebreathing) [[sources/co-bjcp-2010]] (high)
- **Measures effective lung perfusion, not total CO** — anatomic shunts and V/Q inequality cause underestimation; clinically acceptable only in mechanically ventilated patients with minor lung abnormalities [[sources/co-bjcp-2010]] (high)
- **Comparative performance** (vs PAC thermodilution): bias −4.35%, limits of agreement ±35%; 2 SD-precision 29% (ref 20%) — cannot replace triplicate thermodilution [[sources/co-bjcp-2010]] (high)
- **Summary**: invasiveness +, accuracy low, precision low; requires mechanical ventilation

### Indicator Dilution

#### Mathematical Basis — Stewart-Hamilton Equation
- CO = amount of indicator / ∫c(t)dt, where ∫c(t)dt = area under the concentration-time curve; assumes complete mixing, no indicator loss, and constant blood flow between injection and detection sites [[sources/co-indicator-anesthanalg-2010]] (high)
- **Stewart 1897**: CO = C₀V₀ / (C₁ × t); **Hamilton 1928 modification**: CO = C₀V₀ / ∫c(t)dt — accounts for laminar flow and variable path lengths
- Thermodilution substitutes temperature change for chemical indicator concentration: CO inversely proportional to blood temperature depression × transit duration [[sources/co-indicator-anesthanalg-2010]] (high)

#### PAC Revival and Modern Features
- PAC declined after outcome studies in medical ICUs showed no survival benefit; however use in cardiac ICUs has been revisited for RV failure, PAH, LV failure, and mixed shock [[sources/co-cocc-2022]] (medium)
- **RV port**: allows simultaneous display of PA and RV pressure waveforms; overlap of RV end-diastolic pressure over PA end-diastolic pressure = earliest indicator of RV decompensation [[sources/co-cocc-2022]] (medium)
- **Continuous CO Monitoring (CCOM) algorithm**: temperature filament adds heat to blood flow; rapid response thermistor detects downstream temperature change; displays CO, SV, SvO₂, SVR, and RVEF **every 20s** without cold saline volume overload [[sources/co-cocc-2022]] (medium)
- PAC preferred in cardiac surgical ICU for differentiating mixed shock; misinterpretation of PAC data is the leading cause of complications — training essential [[sources/co-cocc-2022]] (medium)
- PAC CO measures RV output — not a valid surrogate for LV CO in intracardiac shunts or tricuspid valve abnormalities [[sources/co-cocc-2022]] (medium)
- **Wedging contraindicated** in PAH and severe MR: PA rupture risk; in severe MR, wedged waveform resembles PA waveform and is prone to misinterpretation [[sources/co-cocc-2022]] (medium)

#### Intermittent Bolus PA Thermodilution (IB-PATD)
- Cold saline (10 mL, iced or room-temperature) injected into right atrium via PAC; thermistor near tip in pulmonary artery records dilution curve [[sources/co-indicator-anesthanalg-2010]] (high)
- **Clinical gold standard for >40 years**; measures RV output (= systemic CO except in intracardiac shunts); PAC additionally measures PA pressures and mixed venous O₂ saturation [[sources/co-indicator-anesthanalg-2010]] (high)
- Best precision: 3 injections equally distributed over ventilatory cycle → 2 SD-precision 3.5%; 3 random injections → 10%; single injection → 15% [[sources/co-bjcp-2010]] (high)
- Reproducibility threshold: 22% change required for statistical significance (single measurement); 13% for triplicate [[sources/co-indicator-anesthanalg-2010]] (high)
- **PAC complications**: PA rupture, pulmonary embolism, catheter-related infection; 3 major RCTs showed no mortality benefit vs no PAC — may reflect interpretation failure rather than device failure [[sources/co-bjcp-2010]] (high)

**Nine sources of measurement error:**
1. **Pre-injection indicator loss** — injectate warming (1°C rise → ~3% CO overestimate); discard first measurement in each series [[sources/co-indicator-anesthanalg-2010]] (high)
2. **Intra-catheter conductive warming** — 9–17% loss → ~20% CO overestimate; corrected by catheter-specific computation constant K₂ [[sources/co-indicator-anesthanalg-2010]] (high)
3. **Post-injection conductive rewarming** — worse in low-flow states and longer transit distances (especially TCPTD) [[sources/co-indicator-anesthanalg-2010]] (high)
4. **Injectate volume error** — 9 mL assumed to be 10 mL → 11% CO overestimate [[sources/co-indicator-anesthanalg-2010]] (high)
5. **Recirculation** — L→R intracardiac shunt → indicator detected multiple times → CO underestimate [[sources/co-indicator-anesthanalg-2010]] (high)
6. **Malpositioning** — catheter in collapsed lung branch → prolonged curve → CO underestimate [[sources/co-indicator-anesthanalg-2010]] (high)
7. **Tricuspid regurgitation** — conflicting direction of error (overestimate in low-flow, underestimate in high-flow); severity-dependent; unresolved [[sources/co-indicator-anesthanalg-2010]] (high) — *see contradiction below*
8. **Baseline temperature fluctuations** — concurrent IV infusions, respiratory oscillations; requires stable baseline [[sources/co-indicator-anesthanalg-2010]] (high)
9. **Respiratory cycle variation** — SV varies up to 50% across respiratory cycle; 3 synchronized injections standard but may be insufficient [[sources/co-indicator-anesthanalg-2010]] (high)

#### Continuous PA Thermodilution (CPATD)
- Electric filament on PAC heats blood intermittently in SVC; thermistor at tip detects downstream response; stochastic cross-correlation reconstructs dilution curve [[sources/co-indicator-anesthanalg-2010]] (high)
- Systems: Vigilance II (Edwards; pseudorandom 1–4s pulses) and Q2plus (Hospira; 20s pulses every 40s)
- **Main limitation — response delay**: 50% response at ~9 min; 80% response at ~12 min → unsuitable for detecting rapid haemodynamic changes; displayed value = averaged previous 1–6 min (up to 12 min in extreme conditions) [[sources/co-indicator-anesthanalg-2010]] (high) [[sources/co-bjcp-2010]] (high)
- In hypothermia (post-CPB, liver transplantation): IB-PATD more reliable until temperature normalises
- **CCOM (2022)**: newer fast CCOM algorithm claims CO/SV/SvO₂/SVR/RVEF display every 20s via temperature filament — *see contradiction below re: response lag* [[sources/co-cocc-2022]] (medium)

#### Transcardiopulmonary Thermodilution (TCPTD) — PiCCO
- Cold indicator injected centrally; femoral (or axillary/brachial) arterial thermistor records dilution curve after traversing entire cardiopulmonary circuit; **no PAC required** [[sources/co-indicator-anesthanalg-2010]] (high)
- Correlation with IB-PATD: r >0.9, bias <10%; slight LV vs RV CO difference (cold-induced sinus slowing affects RV more) [[sources/co-indicator-anesthanalg-2010]] (high)
- **Unique additional variables**: GEDV = ITTV − PTV (superior to PAWP/CVP as preload estimate); EVLW = ITTV − GEDV − intrathoracic blood volume (EVLW-guided management: shorter extubation, decreased ICU stay) [[sources/co-indicator-anesthanalg-2010]] (high)
- Also provides pulse contour CO (see below); combined system = PiCCO device
- Requires femoral arterial catheter; cannot measure PA pressures or mixed SvO₂

#### Transpulmonary Ultrasound Dilution — COstatus (Paediatric/Shunt Detection)
- Isotonic saline at body temperature injected into venous port of extracorporeal AV loop (existing arterial + central venous lines); saline/blood ultrasound velocity difference (1,530 vs 1,560–1,585 m/s) produces measurable transient signal [[sources/co-indicator-anesthanalg-2010]] (high)
- CO by Stewart-Hamilton; L→R shunts cause delayed descent of arterial dilution curve (recirculation) → Qp/Qs estimated from curve asymmetry [[sources/co-indicator-anesthanalg-2010]] (high)
- **Shunt detection (n=44, mean age 12 months, ASD/VSD)**: sensitivity 95.7%, specificity 97.6%, AUC 0.97; significantly underestimates Qp/Qs magnitude in moderate/small shunts ([[sources/shunt-nature-sr-2020]] — medium)

#### Lithium Dilution (LiDCO)
- 1–2 mL isotonic LiCl (150–300 mmol) via venous bolus; ion-selective electrode in peripheral arterial line; **CO = (Li dose × 60) / [(1 − PCV) × ∫Δc_li dt]** — corrected for PCV because lithium distributes only in plasma [[sources/co-indicator-anesthanalg-2010]] (high)
- Peripheral venous injection feasible — only requires arterial + peripheral venous access; 3 measurements needed for precision [[sources/co-bjcp-2010]] (high)
- LiDCO-Plus combines lithium dilution calibration with continuous pulse contour CO
- **Contraindications**: active lithium therapy, high-dose neuromuscular blockers (electrode drift), weight <40 kg, first trimester pregnancy

### Pulse Contour Analysis

#### General Principles
- CO estimated from arterial pressure waveform using a mathematical model — **not a mass balance**; deviations from model assumptions (rapid SVR change, valve disease, arrhythmias, poor signal quality) directly cause error [[sources/co-bjcp-2010]] (high)
- Origin: Otto Frank's Windkessel model (1899) — aorta as compliant reservoir + peripheral resistance; peripheral arterial pressure substitutes for aortic pressure (backward filtering required)
- **Calibrated systems** (PiCCO, LiDCO): patient-specific calibration factor from independent CO; recalibration needed with SVR changes
- **Uncalibrated systems** (PRAM, Vigileo/FloTrac): rely on demographic data or pressure morphology alone; higher susceptibility to error in haemodynamic instability
- Key advantage: beat-to-beat CO, continuous, requires only arterial catheter ± central venous catheter

#### PiCCO (Pulsion Medical Systems)
- Modified Wesseling cZ algorithm; **COpi = K × HR × ∫[P(t)/SVR + C(P) × dP/dt]dt**; K = transpulmonary TD calibration factor [[sources/co-bjcp-2010]] (high)
- Recalibration required at ≤1h intervals and after major SVR changes; radial or femoral artery usable
- **Comparative performance** (Table 1): bias 0.73%, limits ±32%, 2 SD-precision 30% (ref 20%) — replaces single but not triplicate thermodilution [[sources/co-bjcp-2010]] (high)

#### PRAM (Pressure Recording Analytical Method, Vytech Health)
- **SV = A[(P/t) × K(t)]**; characteristic impedance Z derived from pressure curve morphology without external calibration; CO = mean of 12 beats [[sources/co-bjcp-2010]] (high)
- Vulnerable to signal quality and valve disease (aortic stenosis, regurgitation alters waveform morphology); sparse validation (3 studies as of 2010; excluded from Table 1)

#### LiDCO/PulseCO (LiDCO, London)
- Remington-Noback non-linear arterial pressure-volume relationship; nominal SV converted to actual SV by calibration factor (from thermodilution or lithium dilution) [[sources/co-bjcp-2010]] (high)
- Recalibration every 8h or with major haemodynamic changes; no PAC needed
- **Comparative performance** (Table 1): bias 0.91%, limits ±24%, 2 SD-precision 22% (ref 20%) — can replace averaged triplicate thermodilution [[sources/co-bjcp-2010]] (high)

#### Vigileo/FloTrac (Edwards Lifesciences)
- **No external calibration**; **SV = σAP × Khi**; σAP = SD of arterial pressure over 20s; Khi = multivariate polynomial (HR, σAP, MAP, Langewouters compliance, BSA, waveform skewness/kurtosis) updated on rolling 60s average [[sources/co-bjcp-2010]] (high)
- **Worst performer in Table 1**: bias 4.55%, limits ±41%, 2 SD-precision 40% (ref 20%) — only acceptable at single-thermodilution reference precision; note: reflects software version ≥1.07 (pre-2009); algorithm substantially revised since [[sources/co-bjcp-2010]] (high)

#### Modelflow (FMS, Amsterdam)
- 3-element Windkessel: characteristic impedance + Windkessel compliance + peripheral resistance; aortic compliance is pressure- and demographics-dependent (Langewouters equation) [[sources/co-bjcp-2010]] (high)
- Can be used calibrated (independent CO) or uncalibrated (demographics only)
- **Best pulse contour performer calibrated** (Table 1): bias 0.00%, limits ±17%, 2 SD-precision 16% (ref 20%) — can replace averaged triplicate thermodilution; uncalibrated: limits ±31% [[sources/co-bjcp-2010]] (high)

#### Comparative Performance vs PAC Thermodilution (Table 1, Geerts 2010)
| Method | N | Bias (%) | Limits of agr. (%) | Replaces 3-sync TD? | Replaces 3-random TD? | Replaces single TD? |
|---|---|---|---|---|---|---|
| Modelflow-calibrated | 995 | 0.00 | 17 | No | **Yes** | Yes |
| LiDCOplus | 452 | 0.91 | 24 | No | **Yes** | Yes |
| Modelflow-uncalibrated | 924 | 5.63 | 31 | No | No | Yes |
| PiCCOplus | 1802 | 0.73 | 32 | No | No | Yes |
| FloTrac-Vigileo | 1777 | 4.55 | 41 | No | No | Yes |
| CO₂ rebreathing | 601 | −4.35 | 35 | No | No | Yes |
| Transpulmonary TD (3 avg) | — | — | — | No | **Yes** | Yes |

No method replaces 3-synchronized-injection thermodilution (2 SD-precision ≤10%). Impedance excluded (pre-existing meta-analysis: insufficient agreement). Ultrasound excluded (insufficient comparative data).

### Echo-Doppler Ultrasound
- **Transoesophageal Doppler (TOD)**: probe at 35–45 cm in oesophagus; V = (Fd × c) / (2 × Fo × cosθ); aortic CSA from nomogram (age, weight, height); minimal bias but limited agreement (meta-analysis Dark & Singer 2004); trend monitoring reliable if probe position unchanged; poorly tolerated in awake patients; operator-dependent; contraindicated with oesophageal disorders [[sources/co-bjcp-2010]] (high)
- EDM: NICE guidelines support use in complex/high-risk surgical procedures to reduce complications, hospital stay, and central line use; limitations include 10–12% operator-dependent variability, alignment error >20° → poor accuracy [[sources/co-cocc-2022]] (medium)
- **Transthoracic Doppler (TTD)**: non-invasive; jugular notch probe; larger inter/intra-observer variability than TOD; measures aortic or pulmonary valve outflow; portable [[sources/co-bjcp-2010]] (high)
- **Summary**: TOD — invasiveness +, accuracy high, precision low; TTE — non-invasive, accuracy moderate, precision low

### Critical Care Echocardiography (CCE)
- CCE is both a CO monitor and a differential diagnostic tool — uniquely valuable in ICU hemodynamic assessment [[sources/co-cocc-2022]] (medium)
- TTE most commonly used; TEE preferred in intubated/ventilated patients [[sources/co-cocc-2022]] (medium)
- **TTE vs PAC accuracy**: percentage error **25%** (within the ≤30% acceptable threshold) — accurate and precise for CO estimation in critically ill mechanically ventilated patients [[sources/co-cocc-2022]] (medium)
- Severely ill pregnant women: TTE CO shows excellent agreement with PAC [[sources/co-cocc-2022]] (medium)
- Focused Doppler/VTI training added to basic TTE training allows noncardiologist ICU physicians to achieve reproducible, accurate CO assessment in most mechanically ventilated patients [[sources/co-cocc-2022]] (medium)
- CCE is complementary to PAC (not exclusive) in septic shock requiring advanced hemodynamic monitoring [[sources/co-cocc-2022]] (medium)
- **Proposed future role**: given its noninvasive nature and acceptable agreement with PAC, TTE is proposed as a future reference method for validating other CO techniques [[sources/co-cocc-2022]] (medium)
- **Barriers**: most countries lack formal CCE training programs and clearly defined competencies; ESICM published core critical care ultrasound competency recommendations; ASE offers CCE certification [[sources/co-cocc-2022]] (medium)

### Thoracic Electrical Bioimpedance / Bioreactance
- Alternating current applied across thorax; bioimpedance changes converted to CO by mathematical formula; inaccurate — motion artifacts, abnormal thoracic anatomy, valve disease, arrhythmias; meta-analysis (Raaijmakers): 3 decades of validation insufficient for clinical acceptance [[sources/co-bjcp-2010]] (high)
- Meta-analysis (Sanders 2020): modest agreement and inadequate percentage error for bioimpedance — not interchangeable with bolus thermodilution; electrical interference and increased lung water render devices ineffective in ICU [[sources/co-cocc-2022]] (medium)
- **Bioreactance** (Cheetah Medical): phase-shift based; less susceptible to thoracic fluid artifacts vs bioimpedance; awaits larger validation [[sources/co-bjcp-2010]] (high)
- **NICOM study (cardiogenic shock)**: bioreactance showed poor correlation with both Fick and PAC thermodilution; likely due to thoracic fluid overload and low-flow state in cardiogenic shock [[sources/co-cocc-2022]] (medium)

### Pulse Wave Transit Time (esCCO)
- esCCO (Nihon Kohden): noninvasive continuous CO using R-wave to pulse oximeter waveform rise-point interval; also incorporates ECG and arterial pressure [[sources/co-cocc-2022]] (medium)
- Poor accuracy and precision vs invasive TPT CO monitoring in cardiac surgery and liver transplant patients [[sources/co-cocc-2022]] (medium)
- Cannot track CO changes induced by preload increase or vasomotor tone variations in ICU patients [[sources/co-cocc-2022]] (medium)
- Not suitable for clinical decision-making in settings where CO monitoring matters

### Transthoracic Doppler (USCOM)
- USCOM (continuous-wave Doppler): suprasternal notch (trans-aortic, left heart CO) or left sternal edge (trans-pulmonary, right heart CO); SV = VTI × valve CSA (from height-indexed nomogram) [[sources/co-cocc-2022]] (medium)
- Meta-analysis of 10 studies: pooled weighted percentage error **42.7%** vs bolus thermodilution (threshold for acceptable precision: ≤30%) — does not achieve acceptable agreement [[sources/co-cocc-2022]] (medium)
- Operator-dependent in ICU; observational data show strong USCOM-echocardiography SV correlation, suggesting CO estimates could be practitioner-dependent

## Contradictions / Open Questions
- **Tricuspid regurgitation and thermodilution accuracy**: [[sources/co-indicator-anesthanalg-2010]] reports significant TR makes IB-PATD generally unreliable with conflicting error direction (overestimate low-flow, underestimate high-flow); [[sources/rhc-hf-ehj-2025]] states thermodilution "remains accurate even in significant TR — contrary to common belief." Contradiction unresolved; likely reflects TR severity studied and publication year gap.
- **CCOM response latency vs stated 20s update interval**: [[sources/co-indicator-anesthanalg-2010]] (high) reports continuous PAC thermodilution has 50% response at ~9 min and 80% response at ~12 min — unsuitable for detecting rapid changes. [[sources/co-cocc-2022]] (medium) states the modern CCOM algorithm displays CO/SV/SvO₂/SVR/RVEF "every 20s." This likely reflects a technology generation gap (older stochastic cross-correlation vs newer fast filament algorithm), but the 2022 source does not provide validation data for the 20s claim; the underlying response delay may persist.
- **CO₂ rebreathing — effective lung perfusion vs total CO**: underestimation magnitude from shunts is unpredictable without concurrent arterial shunt measurement; limits utility in the most common critical care patients (pulmonary disease)
- **Direct Fick vs thermodilution — no large prospective comparison**: direct Fick accepted as gold standard by convention and physiological logic, not a prospective RCT
- **Optimal injection number for thermodilution**: 3 injections at same respiratory phase is standard; averaging over full ventilatory cycle is theoretically superior but optimal asynchronous injection number is unknown [[sources/co-indicator-anesthanalg-2010]] (high)
- **EVLW by lithium dilution**: promising animal data (Maddison 2008) not confirmed clinically — EVLW by LiDCO should not be used clinically [[sources/co-indicator-anesthanalg-2010]] (high)
- **Uncalibrated pulse contour in haemodynamic instability**: all models assume stable pressure-flow relationship; threshold of instability that invalidates each system is undefined [[sources/co-bjcp-2010]] (high)
- **Pulse contour software version confound**: major algorithm updates (especially Vigileo) make cross-version comparisons unreliable; ±41% for Vigileo reflects pre-2009 software and may not represent current performance [[sources/co-bjcp-2010]] (high)
- **PAC survival benefit**: multiple RCTs show no mortality benefit in medical ICUs; [[sources/co-cocc-2022]] (medium) argues this reflects misinterpretation of data rather than device failure, and PAC is regaining acceptance in cardiac ICUs. No RCT has specifically evaluated PAC in cardiac ICU populations.

## Connections
- Related to [[concepts/Right-Heart-Catheterization]] — thermodilution as standard CO method; pitfalls in PAWP/CO measurement; TR accuracy contradiction
- Related to [[concepts/Invasive-Hemodynamic-Monitoring-CS]] — CO monitoring in cardiogenic shock; CPO = (MAP × CO)/451 requires accurate CO
- Related to [[concepts/Pulmonary-Artery-Pulsatility-Index]] — PAPi derived from PAC data; same catheter used for IB-PATD
- Related to [[concepts/Intracardiac-Shunts]] — COstatus exploits L→R shunt recirculation for Qp/Qs estimation; recirculation is also a thermodilution error source
- Related to [[entities/Heart-Failure]] — hemodynamic monitoring; EVLW in acute/critical HF
- Related to [[concepts/ECPELLA]] — CO monitoring in VA-ECMO + Impella; pulse contour unreliable on ECMO circuit

## Sources
- [[sources/co-indicator-anesthanalg-2010]]
- [[sources/shunt-nature-sr-2020]]
- [[sources/co-bjcp-2010]]
- [[sources/co-cocc-2022]]
