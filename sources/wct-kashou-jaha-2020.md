---
dg-publish: true
title: "Wide Complex Tachycardia Differentiation: A Reappraisal of the State-of-the-Art"
date_ingested: 2026-05-22
source_type: review article
Citation: "Kashou AH, Noseworthy PA, DeSimone CV, Deshmukh AJ, Asirvatham SJ, May AM. Wide Complex Tachycardia Differentiation: A Reappraisal of the State-of-the-Art. J Am Heart Assoc. 2020;9:e016598."
DOI: "https://doi.org/10.1161/JAHA.120.016598"
tags: [wide-complex-tachycardia, ventricular-tachycardia, ECG-algorithm, automated-ECG-interpretation, electrocardiography]
rating: medium
raw_path: raw/WCT-JAMA-2020.md
---

# Wide Complex Tachycardia Differentiation: A Reappraisal of the State-of-the-Art

## Authors, Journal, Affiliations, Type, DOI
- Kashou AH, Noseworthy PA, DeSimone CV, Deshmukh AJ, Asirvatham SJ, May AM
- Journal of the American Heart Association, 2020;9:e016598
- Department of Medicine and Cardiovascular Diseases, Mayo Clinic, Rochester, MN; Cardiovascular Division, Washington University School of Medicine, St. Louis, MO
- Mini review article
- DOI: 10.1161/JAHA.120.016598
- **Conflict of interest:** DeSimone, May, and Deshmukh are declared beneficiaries of intellectual property related to the automated WCT differentiation methods described

## Overview
A 2020 JAHA mini review providing a comprehensive taxonomy of traditional and novel automated WCT differentiation methods. The review catalogues all major hallmark ECG criteria, systematically classifies algorithm structural designs (multistep, VT-as-default, Bayesian, single-criterion, point-based), critiques practical limitations of manual methods, and introduces the authors' automated approaches (WCT Formula and VT prediction model). The central critique is that all traditional methods were derived and validated exclusively in EP laboratory settings, leaving real-world performance largely unknown.

## Keywords
ECG, supraventricular tachycardia, ventricular tachycardia, wide complex tachycardia

## Key Takeaways

### Hallmark ECG Criteria
- **AV dissociation** confirms VT when identified; however, it is visible on 12-lead ECG in only approximately **1 in 5 VTs** — dissociated P waves are frequently hidden within overlapping QRS complexes and T waves, or absent due to coexistent atrial arrhythmia; retrograde VA conduction accounts for up to 50% of VTs
- Capture beats (single narrow QRS identical to baseline from a perfectly timed supraventricular impulse) and fusion beats (hybrid QRS from colliding supraventricular and ventricular wavefronts) are pathognomonic manifestations of AV dissociation
- **Morphological criteria (V1–V2 and V6):** QRS configuration incompatible with typical RBBB or LBBB favours VT; typical RBBB/LBBB morphology favours SWCT — with notable exceptions (bundle branch reentry VT, fascicular VT both engage His-Purkinje and produce typical aberrant morphology)
- **QRS duration cutoffs (Akhtar 1988):** >140 ms for RBBB-pattern WCT; >160 ms for LBBB-pattern WCT — but broad overlapping ranges between VT and SWCT make sole reliance on duration unsatisfactory; idiopathic VT variants can produce QRS <140 ms; fascicular VT can produce QRS <120 ms
- **Chest lead concordance:** Highly specific (>90%) but insensitive (<20%) for VT; positive concordance → posterobasal LV VT origin; negative concordance → near-diagnostic for anteroapical LV origin (exceptions: Mahaim, flecainide toxicity, chest wall deformity)
- **QRS axis:** Northwest axis (−90° to −180°; Akhtar 1988) highly predictive of VT; coexistence of left-axis deviation + RBBB or right-axis deviation + LBBB is quite specific for VT; several algorithms (Vereckei aVR, Jastrzebski, LLA) incorporate dominant R in aVR as a surrogate northwest axis criterion
- **Ventricular activation velocity:** VT (muscle-to-muscle origin) → slurred initial QRS (RWPT ≥50 ms in II, RS interval ≥100 ms in precordials, Vi/Vt <1); SWCT (His-Purkinje activation) → rapid initial deflections (r wave duration <30 ms in V1/V2, RS interval <100 ms)
- **Baseline ECG comparison (Dongas 1985):** Unchanged QRS morphology in V1/II/III vs preexisting BBB in sinus rhythm → nearly always SWCT; noticeably different morphology → usually VT; QRS axis change ≥40° is an independent VT predictor (Griffith 1991 multivariate)![](/raw/assets/WCT-JAMA-2020.pdf-2-0.png)
### Algorithm Design Taxonomy — The Complete Classification
- **Multistep decision-tree (Brugada, Vereckei aVR, LLA):** Sequential VT-specific steps; VT confirmed at first positive step; SWCT only after all steps are negative. *Key limitation:* narrow criterion scope may paradoxically override other VT findings (e.g., using Vereckei aVR alone risks ignoring overt AV dissociation)
- **VT as default (Griffith 1994):** SWCT diagnosed only if typical LBBB (rS/QS in V1/V2, r onset to S nadir <70 ms, monophasic R in V6) or RBBB (rSR' in V1, RS in V6, R>S in V6) present; all others → VT. High sensitivity, poor specificity — SWCTs with non-classical aberrancy or preexcitation misclassified as VT
- **Bayesian algorithm (Lau 2000):** Pretest odds of VT (LR=4, reflecting ~80% EP-referral prevalence) multiplied by serial individual criterion LRs to yield a posttest VT odds; VT if final LR ≥1. *Advantage:* accounts for uncertain criteria and evaluates all ECG features without truncating at one step. *Limitation:* requires complex mental arithmetic under duress; treats criteria as independent variables → LRs likely overvalued
- **Single criterion (Pava RWPT ≥50 ms in lead II):** Simple and fast; high specificity but limited sensitivity; sole reliance risks missing VT when criterion is absent
- **Point-based scoring (Jastrzebski VT score, Pachón):** Avoids absolute binary diagnosis for ambiguous WCTs; identifies near-certain VT or SWCT for a substantial subset while acknowledging indeterminate cases. Jastrzebski: PPV 100% for VT score ≥4. Pachón: PPV 100% for score ≥2 (VT) and PPV 98% for score −1 (SWCT)

### Practical Limitations of Traditional Methods
- All traditional methods depend entirely on ECG interpreter competency → vulnerable to improper execution or abandonment under clinical pressure
- **EP-lab validation bias:** All standard WCT algorithms derived and validated exclusively in EP laboratory populations (patients undergoing EP study, under controlled conditions); only **one real-world validation study** has assessed algorithms in a broader non-EP-selected WCT population; true performance in actual clinical practice is largely unknown and a prospective real-world validation is likely not feasible
- This means published sensitivity/specificity figures systematically overestimate real-world performance, particularly for non-cardiologists and emergency medicine settings

### Automated WCT Differentiation — Novel Methods (May/DeSimone/Kashou/Deshmukh et al.)
- **WCT Formula:** Uses computerized ECG interpretation (CEI) software to quantify frontal-plane and horizontal-plane percent amplitude change between paired WCT and baseline ECGs → logistic regression model yields continuous VT probability (0.00–99.99%); designed for embedding in automated ECG software
- **VT prediction model:** Quantifies change in QRS axis, T axis, and QRS duration between WCT and baseline ECGs → VT likelihood estimate via logistic regression
- **Critical limitation:** Both methods require a paired baseline ECG (pre- or post-WCT) — not always available in acute emergency presentations
- **Machine learning future direction:** Deep learning has already demonstrated detection of LV systolic dysfunction, HCM, age, and sex from 12-lead ECG; automated real-time WCT differentiation via machine learning (neural networks, random forests) is a projected next step and may eventually replace manual methods

## Limitations of the Document
- Mini review format — no systematic search, no meta-analysis
- Authors (May, DeSimone, Deshmukh) have declared intellectual property interests in the automated methods described — potential publication bias toward their own novel approaches
- Published before Basel algorithm (Moccetti 2022) and Chen LLA 2019 paper (though LLA appears in the reference list as ref #10, Chen 2019/2020)
- No new primary data

## Key Concepts Mentioned
- [[concepts/wide-complex-tachycardia]] — primary subject; algorithm taxonomy, limitations, automated methods
- [[concepts/ECG-Conduction-Disturbances]] — BBB morphology as SVT mimic in WCT algorithms
- [[concepts/Fascicular-Ventricular-Tachycardia]] — diagnostic challenge for all WCT algorithms

## Key Entities Mentioned
- None specific

## Wiki Pages Updated
- `wiki/sources/wct-kashou-jaha-2020.md` — created
- `wiki/concepts/wide-complex-tachycardia.md` — added Lau Bayesian algorithm, Pachón scoring, automated methods (WCT Formula, VT prediction model), AV dissociation ~1/5 ECG visibility, QRS duration cutoffs; updated algorithm table; updated limitations
- `wiki/sourceindex.md` — updated
- `wiki/wikiindex.md` — updated
