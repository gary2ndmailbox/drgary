---
dg-publish: true
title: "Cardiac Output Monitoring Using Indicator-Dilution Techniques: Basics, Limits, and Perspectives"
date_ingested: 2026-05-27
source_type: review article
Citation: "Reuter DA, Huang C, Edrich T, Shernan SK, Eltzschig HK. Cardiac Output Monitoring Using Indicator-Dilution Techniques: Basics, Limits, and Perspectives. Anesth Analg. 2010;110(3):799–811."
DOI: "https://doi.org/10.1213/ANE.0b013e3181cc885a"
tags: [hemodynamic-monitoring, cardiac-output, thermodilution, pulmonary-artery-catheter, critical-care]
rating: high
raw_path: raw/CO-Indicator-AnesthAnalg-2010.md
---

# Cardiac Output Monitoring Using Indicator-Dilution Techniques: Basics, Limits, and Perspectives

## Authors, Journal, Affiliations, Type, DOI
- **Authors**: Daniel A. Reuter, Cecil Huang, Thomas Edrich, Stanton K. Shernan, Holger K. Eltzschig
- **Journal**: Anesthesia & Analgesia, 2010;110(3):799–811
- **Affiliations**: Hamburg-Eppendorf University Hospital (Hamburg); Brigham and Women's Hospital / Harvard Medical School (Boston); Tuebingen University Hospital; University of Colorado Denver
- **Type**: Review article
- **DOI**: https://doi.org/10.1213/ANE.0b013e3181cc885a

## Overview
This review covers the theoretical basis and clinical application of indicator-dilution techniques for cardiac output (CO) monitoring in critically ill and perioperative patients. It reviews three methods based on this principle: (1) intermittent bolus PA thermodilution (IB-PATD) via pulmonary artery catheter — the longstanding clinical standard; (2) continuous PA thermodilution (CPATD) using the Vigilance II or Q2plus systems; and (3) transcardiopulmonary thermodilution (TCPTD, PiCCO) and lithium dilution (LiDCO) as less-invasive alternatives. The technical principles, measurement error sources, and clinical advantages/limitations of each method are outlined. The review concludes that PAC-free techniques (TCPTD, LiDCO) provide accurate CO measurement while TCPTD uniquely adds global end-diastolic volume (GEDV) and extravascular lung water (EVLW) as volumetric preload and pulmonary oedema markers.

## Keywords
Cardiac output, thermodilution, indicator dilution, pulmonary artery catheter, transcardiopulmonary, PiCCO, lithium dilution, hemodynamic monitoring, critically ill, extravascular lung water

## Key Takeaways

### Stewart-Hamilton Principle — Mathematical Basis
- All indicator-dilution methods use the same principle: inject a known amount of indicator → measure downstream concentration-time curve → CO = amount injected / area under dilution curve
- **Stewart (1897)**: bolus injection; collection of diluted indicator; F = C₀V₀ / (C₁ × t)
- **Hamilton modification (1928)**: introduced explicit time-concentration curve c(t) to capture laminar flow, variable transit times, and continuous dilution downstream
- **Stewart-Hamilton equation**: CO = C₀V₀ / ∫c(t)dt

### Intermittent Bolus PA Thermodilution (IB-PATD)
- Cold indicator (iced or room-temperature saline) injected into the right atrium via PAC proximal port; thermistor at PA detects temperature change
- CO inversely proportional to the area under the thermodilution curve
- **De facto clinical standard** for >40 years; measures **right heart output** (pulmonary blood flow), not systemic CO — clinically equivalent in absence of shunts
- PAC additionally provides PA pressures and mixed venous O₂ saturation

**Sources of Measurement Error:**
1. **Loss before injection** — underfilling syringe, warming of iced injectate (each 1°C increase in 0–4°C range contributes ~3% CO overestimate); discard first measurement in a run
2. **Loss during injection** — catheter dead space (0.7–1 mL), conductive warming through intravascular catheter wall → 9–17% indicator loss → ~20% CO overestimate; corrective constant K₂ precomputed per catheter type
3. **Loss after injection** — conductive rewarming by surrounding tissue (worse in low-flow states and with TCPTD due to longer transit distance)
4. **Injectate temperature/volume variation** — 10 mL iced injectate provides highest reproducibility; room temperature acceptable but larger percent error in high/low-flow states
5. **Recirculation and detainment** — left-to-right shunt → CO underestimation; one-lung ventilation (catheter in collapsed lung branch) → underestimation due to prolonged thermodilution curve
6. **Tricuspid regurgitation** — conflicting data on direction; reverse regurgitant flow prolongs indicator transit; both over- and underestimates reported; one-flow-state study: overestimates in low-flow, underestimates in high-flow; severity-dependent effects unresolved
7. **Baseline temperature fluctuations** — exogenous (CPB cooling, concurrent IV infusions) or endogenous (respiratory oscillations); stable respiratory pattern required in pre-measurement period
8. **Cyclic CO changes** — stroke volume varies up to 50% across respiratory cycle (more prominent for RV); 3 injections at same respiratory phase recommended (clinically performed); averaging asynchronous measurements over full cycle is theoretically correct but optimal n unclear — 3 may be insufficient
9. **Curve truncation/extrapolation** — manufacturer-specific algorithms apply; many truncate when curve returns to 50% of peak then add empirically derived correction

**Reproducibility limitations:**
- 22% CO change needed for statistical significance (single measurement, Stetz 1982)
- 13% change needed for triplicate measurements
- No confirmatory data published since 1982 (limitation noted by authors)

### Continuous PA Thermodilution (CPATD)
- Heating filament on PAC (15–25 cm from tip) intermittently heats blood in superior vena cava; thermistor at tip detects response
- **Vigilance II (Edwards)**: flat filament, 1–4s pseudorandom pulses; stochastic analysis
- **Q2plus (Hospira)**: coiled filament, 20s pulses in repetitive on-off cycle every 40s; averaging algorithm
- Correlates well with IB-PATD across wide CO range; less affected by TR (pig model data)
- In hypothermia (post-CPB, liver transplantation): IB-PATD exceeds CPATD until resolution — large cold bolus less susceptible to thermal noise than small heat signals
- **Key limitation — time delay**: 50% response at ~9 minutes, 80% response at ~12 minutes (Vigilance, Haller et al.); in vitro: 2.9 vs 3.3 min (20% response), 4.7 vs 11.2 min (80% response) → unsuitable for detecting rapid hemodynamic changes
- Eliminates need for fluid boluses, reduces contamination risk, provides continuous CO trend

### Transcardiopulmonary Thermodilution (TCPTD) — PiCCO System
- Cold indicator injected into superior vena cava via central venous catheter; thermistor in femoral (or axillary/brachial) artery records thermodilution curve after transit through right heart, pulmonary circulation, and left heart
- **No PAC required** — less invasive; avoids PA rupture, pulmonary embolism
- **Currently available system**: PiCCO monitor (Pulsion Medical Systems, Munich)
- Performs monoexponential extrapolation on TCPTD curve before CO calculation
- Combines TCPTD with pulse contour analysis for continuous real-time LV CO assessment

**Additional variables (unique to TCPTD):**
- **GEDV (global end-diastolic volume)**: sum of all four cardiac chamber volumes = ITTV − PTV
  - ITTV = CO × mean transit time (MTT); PTV = CO × exponential decay time (EDT)
  - GEDV superior to filling pressures (PAWP, CVP) as preload estimate (multiple studies)
- **EVLW (extravascular lung water)**: ITTV − GEDV − intrathoracic blood volume; quantifies pulmonary oedema
  - EVLW-guided protocols: hasten oedema resolution, shorten time to extubation, decrease ICU stay vs filling pressure-guided management (Goepfert 2007)
- **Right-to-left intracardiac shunt detection**: double peaks in TCPTD curves indicate right-to-left shunting

**Accuracy vs IB-PATD**: Correlation coefficient >0.9 and bias <10% in most studies; 96–97% of indicator reaching PA recovered in aorta; TCPTD measures LV CO vs IB-PATD measuring RV CO → transient cold-induced sinus slowing affects RV more than LV → TCPTD slightly higher values in some studies

**Limitations vs IB-PATD:**
- Cannot measure PA pressures, PA occlusion pressure, or mixed venous O₂ saturation (central venous O₂ saturation can approximate SvO₂)
- Femoral arterial cannulation: infection risk (requires diligent nursing); contraindicated in severe peripheral vascular disease (thromboembolism risk)

### Transcardiopulmonary Lithium Dilution (LiDCO)
- Isotonic lithium chloride (0.002–0.004 mmol/kg) injected via central or peripheral venous route; detected by ion-selective electrode in arterial line flow-through cell (peristaltic pump at 4 mL/min)
- Voltage related to plasma lithium concentration via Nernst equation; CO from lithium dilution curve area (50% peak cut-off to limit recirculation effect)
- Plasma flow converted to blood flow via haematocrit: CO = plasma flow / (1 − PCV)
- **LiDCO-Plus**: combines lithium dilution with pulse contour analysis for continuous CO
- **Peripheral venous injection feasible**: comparable accuracy to central injection (two studies); only arterial + peripheral venous access required
- EVLW measurement described (Maddison animal study) but could not be confirmed clinically

**Limitations:**
- Contraindicated in patients on lithium therapy (background lithium → CO overestimation)
- Manufacturer limits repeated measurements over short period (lithium accumulation); precise number not specified
- Contraindicated: weight <40 kg; first trimester pregnancy
- Electrode drift with certain muscle relaxant infusions — inaccurate measurements

## Limitations of the Document
- **2010 publication date**: does not cover newer minimally invasive/non-invasive CO technologies (transesophageal Doppler, thoracic bioimpedance/bioreactance, non-invasive pulse contour analysis, near-infrared spectroscopy)
- **PAC outcome data limited**: large trials questioning PAC effect on outcome in critically ill are discussed but not updated; ESCAPE trial referenced (decompensated HF); no definitive CS-specific RCT data available at time of publication
- **Tricuspid regurgitation effects**: authors acknowledge unresolved direction and severity-dependent impact on thermodilution accuracy
- **Reproducibility data**: Stetz 1982 findings on measurement reproducibility (22% threshold for significance) had not been confirmed by subsequent studies at time of publication
- **Technical detail level**: highly mathematical; practical implementation guidance (e.g., catheter-specific K₂ correction constants, injection technique) may not reflect contemporary practice in all centres

## Key Concepts Mentioned
- [[concepts/Cardiac-Output-Measurement]] — comprehensive review of all indicator-dilution CO methods
- [[concepts/Invasive-Hemodynamic-Monitoring-CS]] — PAC-guided monitoring; CO measurement limitations in CS
- [[concepts/Right-Heart-Catheterization]] — thermodilution CO technique; sources of error in PAC-based CO

## Key Entities Mentioned
- **PiCCO Monitor** (Pulsion Medical Systems, Munich) — transcardiopulmonary thermodilution + pulse contour
- **LiDCO-Plus** (LiDCO, Cambridge) — lithium dilution + pulse contour
- **Vigilance II** (Edwards Lifesciences) — continuous PA thermodilution; pseudorandom heating
- **Q2plus** (Hospira, Lake Forest) — continuous PA thermodilution; repetitive 20s pulses

## Wiki Pages Updated
- Created: `wiki/sources/co-indicator-anesthanalg-2010.md`
- Created: `wiki/concepts/Indicator-Dilution-Cardiac-Output.md`
- Updated: `wiki/concepts/Right-Heart-Catheterization.md` — added thermodilution error sources and source cross-reference
- Updated: `wiki/concepts/Invasive-Hemodynamic-Monitoring-CS.md` — added cross-reference to indicator-dilution concept
- Updated: `wiki/sourceindex.md`
- Updated: `wiki/wikiindex.md`
