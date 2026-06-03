---
dg-publish: true
title: "Wearable Digital Health Technologies for Monitoring in Cardiovascular Medicine"
date_ingested: 2026-05-17
source_type: review article
Citation: "Spatz ES, Ginsburg GS, Rumsfeld JS, Turakhia MP. Wearable Digital Health Technologies for Monitoring in Cardiovascular Medicine. N Engl J Med. 2024;390(4):346-356."
DOI: "https://doi.org/10.1056/NEJMra2301903"
tags: [wearable-digital-health, remote-patient-monitoring, atrial-fibrillation, heart-failure, cardiovascular-monitoring]
rating: high
raw_path: raw/Wearable-NEJM-2024.md
---

# Wearable Digital Health Technologies for Monitoring in Cardiovascular Medicine

## Authors, Journal, Affiliations, Type, DOI
- Erica S. Spatz, Geoffrey S. Ginsburg, John S. Rumsfeld, Mintu P. Turakhia
- N Engl J Med 2024;390:346–56
- Yale School of Medicine (New Haven); National Institutes of Health (Bethesda); University of Colorado / Meta Platforms (Aurora/Menlo Park); Stanford Center for Digital Health / iRhythm Technologies (Stanford/San Francisco)
- Review article with illustrative clinical vignettes
- DOI: 10.1056/NEJMra2301903
- Conflict of interest: Turakhia is an employee of iRhythm Technologies (ambulatory ECG manufacturer)

## Overview
This NEJM review uses a three-part clinical vignette (62-year-old woman with decompensated HF and new AF) to illustrate how wearable digital health technologies (DHTs) and remote patient monitoring (RPM) can transform cardiovascular care from episodic to continuous. The authors systematically cover wearable ECG devices, PPG-based monitoring, and cuffless blood pressure technologies across three target conditions: hypertension, heart failure, and atrial fibrillation. Key performance data are reviewed (PPG AF screening PPV 84–98%; single-lead ECG sensitivity 78–88%), and substantial barriers to adoption are identified including nascent reimbursement frameworks, unproven long-term outcome benefit, and health equity concerns (pulse oximetry racial bias).

## Keywords
Wearable devices, digital health technology, remote patient monitoring, atrial fibrillation, heart failure, hypertension, photoplethysmography, ambulatory ECG, cuffless blood pressure, hub model, telehealth

## Key Takeaways

### Remote Patient Monitoring (RPM) — Context and Rationale
- Traditional care is episodic: visits occur during stability; disease progression (AF recurrence, HF decompensation) occurs between visits, undetected
- CHAMP-HF registry: <50% of HF patients are prescribed GDMT; even fewer achieve target doses
- GUIDE-IT trial: despite 10–12 in-person visits over 15 months, GDMT targets not reached in majority — frequent episodic visits alone do not optimise medical therapy
- RPM goal: capture lifestyle behaviours, control risk factors, detect clinical deterioration before worsening; three main CV conditions: hypertension, heart failure, atrial fibrillation
- RPM may reduce structural inequities: transport barriers, geographic distance from care centres

### Wearable DHT Taxonomy
- **Nonwearable DHTs:** Blood pressure cuff, scale, fingertip pulse oximeter — episodic, patient-initiated
- **Wearable DHTs:** Smartwatches/wrist bands, skin-surface patches, ambulatory ECG leads — continuous or semicontinuous, often passive
- DHT = hardware (sensors, monitors, wearables) + software (mobile health apps, predictive analytics) + telehealth platforms

### ECG Recording Devices
- **Consumer-facing (OTC):** 30-second rhythm strip using lead I vector; FDA-cleared as prediagnostics only; require clinician interpretation before medical decision making
- **Performance:** Sensitivity 78–88%, specificity 80–86% for AF across 3 commercial single-lead devices; 2–15% uninterpretable ECGs; performance improves when unclassified ECGs are excluded and when interpreted by cardiac electrophysiologists
- **Wear compliance:** Mean 19.5±4.2 hours/day; 66.7% responsiveness to alert prompts for ECG recording
- **Ambulatory ECG (clinical-grade):** 24h–30 days; single or multiple lead vectors; lead or patch systems; continuous or non-continuous recording; cellular relay enables real-time transmission and 24h technician review
- **Hospital-at-home monitoring:** Patch ECG devices combining continuous ECG + respiratory rate + skin temperature
- FDA extended guidance for OTC ECG devices indefinitely in October 2023

### Photoplethysmography (PPG) for AF Detection
- Mechanism: Optical sensor detects pulse rate; algorithm passively scans semicontinuous tachograms for irregularity pattern consistent with AF; surrogate (not direct) ECG
- **Apple Heart Study** (n>400,000; no prior AF): PPV 84% for AF on subsequent ambulatory ECG; diagnostic yield of subsequent ambulatory ECG 32–34%
- **Fitbit Heart Study** (n>400,000; no prior AF): PPV 98%; diagnostic yield 32–34%
- The 32–34% ambulatory ECG diagnostic yield is partly attributable to paroxysmal AF returning to sinus rhythm after the notification
- **Post-cardiac surgery:** Episode-level sensitivity 41% vs inpatient telemetry (specificity 100%) — very poor sensitivity in this clinical scenario
- **Prescription smartwatch algorithm (Poh 2023):** Episode-level sensitivity 96.1%, specificity 98.1% for 15-minute AF intervals vs continuous ambulatory ECG — higher performance than consumer algorithms
- Consumer irregular-pulse notification algorithms: FDA-cleared **only for patients without previously diagnosed AF** (screening use only)
- AF burden smartwatch algorithms for patients with known AF are available but **not intended for medical decision making**

### Cuffless Blood Pressure Monitoring
- Traditional upper-arm oscillometric devices miss diurnal/nocturnal BP variation; cuff inflation itself may alter readings
- Wrist-worn oscillometric devices: overestimate BP in normotensives, underestimate in hypertensives; >5 mmHg discrepancy in 40–50% of readings compared with upper-arm methods
- **Cuffless technologies:** ML-based indirect estimation using PPG ± ECG/bioimpedance/ultrasound sensors
- No cuffless device is on the AMA validated device list (www.validatebp.org) as of 2024
- FDA clearance does not require proof of clinical utility in remote patient monitoring context

### Pulse Oximetry and Health Equity
- Pulse oximetry overestimates SpO2 in patients with dark skin pigmentation — a recognised source of health disparities
- Patients may not receive appropriate intervention because their measured SpO2 appears adequate despite lower true saturation

### Practical Challenges and Barriers
- **Reimbursement:** Medicare RPM requires physiological data transmission on >50% of calendar days — may be excessive for some conditions, insufficient for others; monthly reimbursement structure
- **Long-term outcomes:** Observational data show short-term physiological improvement; whether RPM reduces long-term cardiovascular events, hospitalisations, or death is **unproven**
- **Trial design limitations:** DHT trials vulnerable to enrollment bias (motivated patients), unblinded interventions, Hawthorne effect, and non-generalisable results; cluster/implementation study designs preferred
- **Program heterogeneity:** Device, software, care protocol, and engagement strategies vary widely — difficult to compare across programmes

### Hub Model for RPM Implementation
- Modelled on the established remote monitoring infrastructure for pacemakers and ICDs (in use since the 1990s)
- Centralised hub team receives and manages data; applies protocols and decision-support tools; adjusts medications remotely
- After adjustment period, patient returns to primary care team; low-intensity RPM may continue
- Hub model advantages: scalable resource allocation, simplified training, single accountability, aligned incentives
- Already adopted by Veterans Health Administration and selected academic health systems
- More scalable and potentially more effective than clinic-by-clinic implementation

## Limitations of the Document
- Narrative review using clinical vignettes — not systematic; inherits the limitations of cited primary studies
- Technology advances rapidly; performance data (e.g., algorithm accuracy) may date within 2–3 years
- Senior author (Turakhia) is employed by iRhythm Technologies, a manufacturer of ambulatory ECG monitors; potential conflict of interest in interpretation of ambulatory ECG evidence
- Review focuses on three conditions (HTN/HF/AF); does not cover DHTs for other cardiovascular conditions
- Cited consumer trial data (Apple/Fitbit) derive from self-selected, predominantly white populations; generalisability uncertain

## Key Concepts Mentioned
- [[concepts/Remote-Patient-Monitoring]] — central concept of the review
- [[concepts/Subclinical-AF]] — wearable PPG screening for AF; OTC vs prescription algorithms
- [[concepts/Cuffless-BP-Monitoring]] — wrist oscillometric and cuffless BP; validation gap
- [[entities/Heart-Failure]] — principal target condition for RPM; GUIDE-IT and CHAMP-HF context
- [[entities/Atrial-Fibrillation]] — ECG monitoring for rhythm and burden assessment

## Key Entities Mentioned
- iRhythm Technologies — ambulatory ECG patch manufacturer; employs senior author
- Apple Inc. — Apple Heart Study (PPG AF screening PPV 84%)
- Google Fitbit — Fitbit Heart Study (PPG AF screening PPV 98%)
- Veterans Health Administration — early adopter of hub model for cardiovascular RPM

## Wiki Pages Updated
- Created `wiki/sources/wearable-cv-nejm-2024.md`
- Created `wiki/concepts/Remote-Patient-Monitoring.md`
- Updated `wiki/concepts/Subclinical-AF.md` — added wearable/PPG screening section
- Updated `wiki/concepts/Cuffless-BP-Monitoring.md` — added wrist oscillometric comparison data and wearable-cv-nejm-2024 source
- Updated `wiki/sourceindex.md`
- Updated `wiki/wikiindex.md`
