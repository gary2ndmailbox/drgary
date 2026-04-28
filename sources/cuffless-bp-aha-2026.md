---
dg-publish: true
title: "Cuffless Devices for the Measurement of Blood Pressure: A Scientific Statement From the American Heart Association"
date_ingested: 2026-04-24
source_type: consensus
Citation: "Cohen JB, Byfield RL, Hardy ST, Juraschek SP, Houston Miller N, Mukkamala R, Picone DS, Thiele RH, Yang E, Brady TM; on behalf of the American Heart Association Council on Hypertension et al. Cuffless devices for the measurement of blood pressure: a scientific statement from the American Heart Association. Hypertension. 2026;83:876–886."
DOI: "https://doi.org/10.1161/HYP.0000000000000254"
tags: [hypertension, blood-pressure-monitoring, digital-health, wearable-technology, photoplethysmography]
rating: high
raw_path: raw/Cuffless-BP-AHA-2026.md
---

# Cuffless Devices for the Measurement of Blood Pressure: A Scientific Statement From the American Heart Association

## Authors, Journal, Affiliations, Type, DOI
- Jordana B. Cohen (Chair), Tammy M. Brady (Vice Chair), Rushelle L. Byfield, Shakia T. Hardy, Stephen P. Juraschek, Nancy Houston Miller, Ramakrishna Mukkamala, Dean S. Picone, Robert H. Thiele, Eugene Yang
- *Hypertension.* 2026;83:876–886
- On behalf of the AHA Council on Hypertension; Council on Cardiovascular and Stroke Nursing; Council on Cardiovascular Surgery and Anesthesia; Council on Clinical Cardiology
- AHA Scientific Statement
- DOI: 10.1161/HYP.0000000000000254

## Overview
This AHA Scientific Statement provides a comprehensive overview of cuffless blood pressure (BP) measurement technologies — including photoplethysmography (PPG), tonometry, pulse transit time (PTT), and pulse arrival time (PAT) — and their theoretical clinical applications across research, inpatient/perioperative, underresourced communities, and pediatric settings. The central clinical conclusion mirrors the 2025 AHA/ACC Hypertension Guideline: cuffless BP devices are currently **not recommended** for hypertension diagnosis or management (COR 3: No Benefit), due to insufficient validation standards, absence of outcomes data, and unresolved technical barriers including calibration drift, PPG bias by skin tone, and hydrostatic positioning error. The statement also catalogs the gaps remaining before clinical use can be justified, including the pending ISO 81060-7 intermittent-device validation protocol.

## Keywords
AHA Scientific Statements; ambulatory blood pressure monitoring; blood pressure; blood pressure determination; hypertension; photoplethysmography; pulse wave analysis; tonometry

## Key Takeaways

### Mechanisms of Cuffless BP Measurement
- Cuffless devices measure BP via cardiac/pulsatility sensors (no inflatable cuff): two output types — continuous beat-to-beat, or intermittent (>30 s apart) ([[sources/cuffless-bp-aha-2026]], rating: high)
- **Pulse Arrival Time (PAT):** elapsed time from R-wave (ECG) to distal pulse (PPG/tonometry); requires 2 sensors; embeds preejection period (PEP), which is highly variable with stress, activity, age, hydration, and vasoactive drugs — making PAT-based devices susceptible to error independent of BP
- **Pulse Transit Time (PTT):** proximal-to-distal propagation time; inversely related to BP but confounded by smooth muscle contraction; PTT ≠ PAT
- **PPG sensors:** most common; measure blood volume oscillations via reflected/transmitted light; accuracy degraded by melanin (skin tone bias), cold temperatures (vasoconstriction), obesity (skin thickness), vessel stiffness, and sensor contact pressure; lowest fidelity at back-of-wrist (popular site)
- **Tonometry sensors:** measure radial artery net force; reliable waveforms but require precise artery positioning — difficult for typical users
- **Machine learning:** widely applied; physiological doubts remain — blood volume oscillation amplitude does not consistently change with BP due to smooth muscle contraction; most devices do not disclose algorithmic details
- **Calibration:** most devices require initial and repeated cuff calibration (daily to monthly) for absolute mmHg output; without calibration, only BP *changes* (not absolute values) can be inferred; "cuff-calibrated" vs "demographic-calibrated" devices have fundamentally different assumptions

### Theoretical Applications
- **Research:** unprecedented capture of BP during high-activity states, sleep (without disrupting sleep unlike ABPM), and continuous monitoring to identify novel hypertensive phenotypes and environmental/behavioural triggers
- **Nocturnal monitoring:** cuffless devices could eliminate sleep disruption from ABPM cuff inflation — a recognised cause of inadequate ABPM studies; critical for studying nocturnal hypertension and morning BP surge
- **Inpatient/perioperative:** volume-clamp finger-cuff devices (established noninvasive continuous BP) compared to arterial catheterisation led to unnecessary treatments in 0.1–3% of cases; cuffless technologies could replace invasive BP monitoring in many patients
- **Underresourced communities:** portable wearable integration (watches, smartphones) could expand access in rural/low-income/minority populations with higher hypertension prevalence; however, lack of validated oscillometric calibration devices and training are barriers
- **Children:** standard ABPM poorly tolerated in paediatrics; cuffless devices showed some correlation with standard BP but wide intrasubject variability (up to 20 mmHg); paediatric-specific validation protocols needed
- All potential benefits listed above are **theoretical and not supported by empirical outcomes evidence**

### Cuffless Device Validation — Current Standards
| Protocol | Target device | Reference standard | Key limitation |
|---|---|---|---|
| ISO 81060-2:2018 (cuff oscillometric) | Seated intermittent cuff | Auscultation | Designed for cuff, not cuffless |
| ISO 81060-3:2022 | Continuous cuff/cuffless (hospital) | Intra-arterial line | Requires invasive monitoring; hospital only |
| IEEE 1708a-2019 | Wearable cuffless (intermittent) | Auscultation | Tests immediately post-calibration; no ambulatory conditions standardised |
| ISO 81060-7 (in development) | Intermittent cuffless (all types) | TBD | Not yet published |

- FDA clearance ≠ measurement accuracy; formal validation testing not required for 510(k) clearance
- ~80% of cuff-based devices globally have never published formal validation results; cuffless device percentage even higher
- European Society of Hypertension (2023) recommends 6 validation test types for cuffless devices: static, position, treatment (1–4 weeks post-antihypertensive), awake/asleep, exercise, and recalibration tests

### Crucial Gaps (Table 2 Summary)
- Studies demonstrate poor cuffless performance tracking: exercise-induced, sleep-time, antihypertensive treatment-induced, activity-of-daily-living-associated, and 24-hour continuous BP changes
- Performance often no better than baseline model using only cuff BP at calibration
- No international protocol for intermittent cuffless devices (ISO 81060-7 pending)
- No validation of skin tone diversity, special populations (pregnancy, arrhythmia, paediatric, elderly) for most devices
- Clinical outcomes data linking cuffless BP readings to hard cardiovascular endpoints: essentially absent
- Data privacy, ownership, consent for continuous passive monitoring: unaddressed
- Calibration stability over time: not tested by current protocols (only immediately post-calibration)

### Conclusion
- Until above gaps are resolved, cuffless devices for guiding treatment "could lead to inappropriate care and may pose safety risks to patients"
- The 2025 AHA/ACC Hypertension Guideline explicitly recommends **against** cuffless device use for hypertension diagnosis/management (COR 3: No Benefit) ([[entities/Hypertension]])

## Limitations of the Document
- Scientific statement (not systematic review/meta-analysis); no formal evidence grading methodology
- Rapidly evolving field — specific device data may already be outdated
- No head-to-head comparison of specific commercial devices
- Industry representation in writing group (Apple Inc, Philips, Edwards) — acknowledged COI

## Key Concepts Mentioned
- [[concepts/Cuffless-BP-Monitoring]] — primary concept of this source; full mechanism, validation, and gaps overview
- [[concepts/Perioperative-Cardiovascular-Assessment]] — inpatient/perioperative BP monitoring context

## Key Entities Mentioned
- [[entities/Hypertension]] — regulatory and clinical context; COR 3: No Benefit recommendation

## Wiki Pages Updated
- Created: `wiki/sources/cuffless-bp-aha-2026.md`
- Created: `wiki/concepts/Cuffless-BP-Monitoring.md`
- Updated: `wiki/entities/Hypertension.md`
- Updated: `wiki/wikiindex.md`
- Updated: `wiki/sourceindex.md`
