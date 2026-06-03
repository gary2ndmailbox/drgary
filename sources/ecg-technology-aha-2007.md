---
dg-publish: true
title: "AHA/ACCF/HRS Recommendations for the Standardization and Interpretation of the Electrocardiogram: Part I: The Electrocardiogram and Its Technology"
date_ingested: 2026-05-16
source_type: guideline
Citation: "Kligfield P, Gettes LS, Bailey JJ, Childers R, Deal BJ, Hancock EW, van Herpen G, Kors JA, Macfarlane P, Mirvis DM, Pahlm O, Rautaharju P, Wagner GS. Recommendations for the standardization and interpretation of the electrocardiogram: part I: the electrocardiogram and its technology. J Am Coll Cardiol 2007;49:1109–27."
DOI: "https://doi.org/10.1016/j.jacc.2007.01.024"
tags: [electrocardiography, ECG-technology, ECG-standardization, digital-ECG, lead-placement]
rating: high
raw_path: raw/ECG-AHA-2009.md
---

# AHA/ACCF/HRS Recommendations for the Standardization and Interpretation of the ECG: Part I: The Electrocardiogram and Its Technology

## Authors, Journal, Affiliations, Type, DOI
- **Authors:** Paul Kligfield, Leonard S. Gettes, James J. Bailey, Rory Childers, Barbara J. Deal, E. William Hancock, Gerard van Herpen, Jan A. Kors, Peter Macfarlane, David M. Mirvis, Olle Pahlm, Pentti Rautaharju, Galen S. Wagner
- **Journal:** Journal of the American College of Cardiology, Vol. 49, No. 10, 2007:1109–27 (co-published in Circulation and Heart Rhythm, March 2007)
- **Affiliations:** Cornell, North Carolina, Northwestern, Chicago, Stanford, Erasmus, Glasgow, Tennessee, Lund, Wake Forest, Duke — multi-institutional
- **Type:** Multi-society scientific statement (AHA/ACCF/HRS); endorsed by International Society for Computerized Electrocardiology
- **DOI:** https://doi.org/10.1016/j.jacc.2007.01.024

## Overview
Part I of the 6-part AHA/ACCF/HRS ECG Standardization series, addressing the technical standards for ECG recording and signal processing. Establishes requirements for digital sampling rates, filtering, representative complex formation, global versus single-lead interval measurement, standard and alternative lead placement, the Cabrera lead display sequence, and computer-assisted ECG interpretation. Key clinical impact: global measurement of QRS/PR/QT is preferred over single-lead and gives systematically longer values — meaning existing diagnostic criteria (derived from single-lead studies) require recalibration. Computer ECG interpretation is an adjunct only; physician overreading is mandatory.

## Keywords
Electrocardiography, digital ECG, signal processing, lead placement, global measurement, Cabrera sequence, Mason-Likar, computerized interpretation, ECG standards, sampling rate

## Key Takeaways

### Digital Signal Acquisition and Filtering

#### Sampling Rate
- Front-end analog-to-digital conversion: typically 1000–2000 samples/sec; newer converters up to 10,000–15,000 samples/sec
- **Recommendation:** Oversample by significant multiple of upper-frequency cutoff; preserve pacemaker pulse detection; low-amplitude pacemaker spikes must NOT be artificially amplified

#### High-Frequency Filtering
- QRS fundamental frequency ~10 Hz; most diagnostic information <100 Hz; high-frequency components up to 500 Hz exist
- **High-frequency cutoff ≥150 Hz required** for adults and adolescents to reduce amplitude error to <1%; ≥250 Hz required for children/infants
- Monitor ECG at 40 Hz cutoff **invalidates amplitude measurements** (smooths Q waves and notches, underestimates R-wave peaks) — electrocardiographs should alert the user and automatically restore proper cutoff between recordings

#### Low-Frequency Filtering
- Low-frequency cutoff 0.5 Hz (once standard for monitors) causes artifactual ST-segment distortion
- **Recommendation:** 0.05 Hz for routine diagnostic ECGs using analog or standard digital filters; relaxed to ≤0.67 Hz acceptable for linear-phase zero-distortion digital filters (ANSI/AAMI 1991/2001 standard)

### Formation of a Representative Complex (Template)
- Beat-to-beat variability reduced by averaging or median-complex template formation from multiple aligned dominant complexes
- Average complex: mean amplitude at each digital sampling point; median complex: median amplitude — both reduce noise to allow deflections of 20 µV estimated with <10% error
- Automated measurements are made from templates, not from individual complexes
- **Fidelity standard for representative beat construction has not yet been formally established**

### Global Measurement From Simultaneously Acquired Leads
- Simultaneous 12-lead acquisition allows detection of earliest onset and latest offset across all leads — the **preferred standard** ("global measurement")
- Global measurements of P-wave, PR interval, QRS duration, and QT interval are systematically **longer** than single-lead measurements because individual leads underestimate waveform duration when the lead vector is perpendicular to the heart vector at onset or offset
- **Implication:** Population-based reference values for PR, QRS, QT, and Q-wave duration — most derived from single-lead, single-channel recordings — must be recalibrated for simultaneous-lead digital measurement
- Global QT measurement remains problematic due to T-wave offset algorithm variability; alternative single-lead QT methods may be prescribed for special purposes (drug trials)
- **Recommendation:** Global measurements of P, PR, QRS, QT should be stated on all ECG reports

### Standard 12-Lead Anatomy

#### Independent Information Content
- The 12-lead ECG contains **8 independent signals**: 2 measured potential differences from which the 4 remaining limb leads are derived (via Kirchhoff's law / Einthoven's law) + 6 independent precordial leads
- The 6 frontal plane leads contain only 2 independent measured signals; augmented limb leads are mathematically derived — new vectorial perspective but no new information
- **"Unipolar" terminology for augmented limb leads and precordial leads is discouraged** — all leads are effectively "bipolar"; this term should not be used

#### Standard Limb Lead Definitions
| Lead | Definition |
|---|---|
| I | LA − RA |
| II | LL − RA |
| III | LL − LA |
| aVR | RA − (LA+LL)/2 = −(lead I + lead II)/2 |
| aVL | LA − (RA+LL)/2 = (lead I − lead III)/2 |
| aVF | LL − (RA+LA)/2 = (lead II + lead III)/2 |

### Lead Placement Standards

#### Recommended Precordial Lead Positions
- **V1:** 4th intercostal space (ICS), right sternal border
- **V2:** 4th ICS, left sternal border
- **V3:** Midway between V2 and V4
- **V4:** 5th ICS, midclavicular line
- **V5:** Horizontal plane of V4, anterior axillary line; **OR midway between V4 and V6** when anterior axillary line is not well defined (preferred over 5th ICS course — 5th ICS is variable and discouraged)
- **V6:** Horizontal plane of V4, midaxillary line

#### Common Misplacement Errors and Clinical Consequences
- **V1/V2 superior misplacement (2nd or 3rd ICS)** — most common error; results in ~0.1 mV amplitude reduction per interspace; produces rSr′ with T-wave inversion resembling aVR; causes false poor R-wave progression / erroneous anterior infarction pattern
- **V5/V6 inferior misplacement (6th ICS or lower)** — alters voltages used for ventricular hypertrophy diagnosis (LVH criteria compromised)
- **V3/V4 above ventricular boundaries in low diaphragm (COPD)** — may produce negative deflections simulating anterior infarction
- Variation in precordial lead placement of as little as 2 cm can produce important diagnostic errors (anteroseptal infarction, ventricular hypertrophy criteria); alters computer-based statements in up to 6% of recordings
- **Periodic retraining in lead positioning recommended**; skin marking for serial tracings in acute/subacute settings

#### Limb Lead Placement
- Standard limb electrodes may be placed anywhere distal to shoulder and hip (not restricted to wrist/ankle per 1975 AHA)
- Proximal vs. distal limb placement can alter voltages and durations (most importantly limb leads), but effect on diagnostic criteria is unresolved — studies ongoing
- **Electrodes under the breast** recommended in women pending additional comparative studies

#### Lead Switches
- Left-right arm switch: inverts lead I; switches II and III; switches aVR and aVL; aVF unaffected; precordial leads unaffected (central terminal unchanged)
- Transposed V1/V2 or V2/V3 wires → reversed R-wave progression simulating anteroseptal infarction; recognized by distorted precordial P-wave and T-wave progression
- **Lead-switch detection algorithms should be incorporated into digital electrocardiographs** with real-time alerts

### Cabrera Lead Display Sequence
- Reorients frontal plane leads into anatomically progressive array: **aVL → I → −aVR → II → aVF → III** (left-to-right)
- −aVR (inverted aVR) represents a perspective anatomically between leads II and I; improves spatial quantification of acute infarction localization; facilitates frontal plane axis calculation
- **"Highly recommended" as alternative display standard** — endorsed by Part I, and used in the ischemia localization conventions of Part VI
- Currently underused; manufacturers should make this a routine option

### Alternative Lead Applications

#### Mason-Likar Torso Lead Placement
- Arm electrodes placed in infraclavicular fossae (medial to deltoid); left leg electrode between costal margin and iliac crest — reduces motion artifact in exercise and ambulatory ECGs
- **NOT interchangeable with standard 12-lead ECG**: distorts the central terminal → alters augmented limb leads and all precordial leads; affects QRS morphology; can produce false-positive and false-negative infarction criteria
- Must be clearly labeled; cannot be used for serial comparison with standard ECGs

#### Synthesized 12-Lead ECG (EASI / Frank Systems)
- EASI 5-lead system (E, A, S, I electrodes + ground): orthogonal signals; 12-lead ECG reconstructed via transfer coefficients — adequate for rhythm monitoring but NOT equivalent to standard ECG
- Frank lead system: 7 electrodes; vectorcardiographic orthogonal leads X, Y, Z
- **Synthesized 12-lead ECGs not recommended as substitute for routine standard ECGs**; must be labeled as derived

#### Right-Sided and Posterior Precordial Leads
- **V3R–V6R**: mirror-image right chest placement; V1 = equivalent to V2R; V2 = equivalent to V1R
- **STE ≥0.1 mV in right-sided leads** = moderately sensitive and specific for right ventricular injury; associated with RV dysfunction and greater in-hospital complications
- **Recommendation:** Right-sided leads **recommended in acute inferior STEMI** due to value for diagnosing RV involvement; not recommended routinely without acute inferior infarction
- **V7–V9 posterior leads** (posterior axillary, subscapular, paravertebral, same horizontal plane as V6): moderate sensitivity / high specificity for posterior wall infarction; STE may be only finding in some cases
- **Recommendation:** Posterior leads appropriate when treatment depends on STE documentation; not recommended routinely

### Computerized ECG Interpretation
- Two-stage process: (1) signal processing / feature extraction → (2) diagnostic classification (heuristic deterministic, statistical/probabilistic, neural net)
- CSE study (15 ECG programs vs reference database): **cardiologists 96.0% accuracy vs computers 91.3%** — computers perform less well than expert readers for individual diagnoses
- Computer assistance improves diagnostic performance of less expert readers
- **Recommendation:** All computer-based ECG reports require **physician overreading** — computer interpretation is an adjunct, not a substitute
- Algorithms should be validated on data not used for development; documented with reference critical measurements; serial comparisons require trained observers

### Data Compression
- Digitized at 500 samples/sec: ~80–100 kB per 10-second 12-lead ECG
- Compression ratios 8:1–10:1 achievable with <2% root mean square error; lossless compression now feasible
- **Compression affects high-frequency (QRS) components more than ST/T-wave components** — risk of altering Q-wave duration, R-wave amplitude, pacemaker spike detection more than ST-segment level
- **Recommendation:** Retrieved compressed ECGs must adhere to ≤10 µV fidelity relative to original signal

## Limitations of the Document
- Published 2007; global QRS/QT reference values for simultaneous-lead digital systems "still needed" — acknowledgment that single-lead-derived diagnostic criteria require recalibration not yet completed
- Normal range data for children with ≥250 Hz sampling rates largely absent at time of publication
- EASI lead performance for ST monitoring in acute ischemia was under investigation at time of publication
- Effect of distal vs. proximal limb lead electrode placement on diagnostic criteria — stated as unresolved at time of publication

## Key Concepts Mentioned
- [[concepts/ECG-Lead-Standards]] — primary repository for lead placement, Cabrera sequence, global measurement, alternative lead sets
- [[concepts/ECG-Conduction-Disturbances]] — global QRS measurement preferred and systematically longer; existing QRS duration criteria (e.g., CRT QRS ≥150 ms) derived from single-lead studies require recalibration
- [[concepts/ECG-Ventricular-Hypertrophy]] — lead misplacement (V5/V6 inferior; V1/V2 superior) alters voltage criteria validity
- [[concepts/ST-T-Changes]] — Mason-Likar not interchangeable for serial ST comparison; right-sided leads for RV infarction; Cabrera sequence for infarction localization

## Key Entities Mentioned
None specific (technical standards document)

## Wiki Pages Updated
- `wiki/sources/ecg-technology-aha-2007.md` — created
- `wiki/concepts/ECG-Lead-Standards.md` — created
- `wiki/concepts/ECG-Conduction-Disturbances.md` — global QRS measurement technical basis added to contradictions
- `wiki/concepts/ECG-Ventricular-Hypertrophy.md` — lead misplacement effects on voltage criteria added
- `wiki/concepts/ST-T-Changes.md` — Mason-Likar limitation and Cabrera note added
- `wiki/sourceindex.md` — new entry added
- `wiki/wikiindex.md` — ECG-Lead-Standards entry added
