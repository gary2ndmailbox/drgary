---
dg-publish: true
title: "Wide Complex Tachycardia"
tags: [wide-complex-tachycardia, ventricular-tachycardia, supraventricular-tachycardia, electrocardiography, ECG-algorithm]
source_count: 10
last_updated: 2026-05-22
---

# Wide Complex Tachycardia (WCT)

## Definition
Wide QRS complex tachycardia (WCT) is defined as a regular tachycardia with QRS duration ≥120 ms. It constitutes a diagnostic emergency: ventricular tachycardia (VT) accounts for **50–80% of cases depending on clinical context** — approximately 80% in tertiary EP referral series and patients with known structural heart disease, but 50–70% in unselected emergency department populations. The remainder includes SVT with aberrant conduction (bundle branch block), pre-excited SVT (antidromic AVRT, Mahaim), ventricular-paced rhythms, and drug- or electrolyte-induced QRS widening. Misdiagnosis carries potentially lethal consequences — treating VT as SVT (e.g., verapamil in VT, adenosine in antidromic AVRT) may precipitate haemodynamic collapse or VF.

## Epidemiology
- VT prevalence is population-dependent: **50–80% of cases depending on clinical context** — ~80% in tertiary EP referral series and known structural heart disease; 50–70% in unselected emergency department populations
- Published algorithm sensitivity/specificity figures mainly reflect EP centre populations (VT ~74–75%); real-world community prevalence is lower, creating systematic referral bias in all algorithm studies ([[sources/wct-kashou-jaha-2020]] — medium)

## Pathophysiology

### Causes of WCT
- **VT:** Scar-based re-entry (most common in structural heart disease), automaticity, or triggered activity in the ventricular myocardium
- **SVT with aberrant conduction (~15–20%):** Pre-existing or rate-related bundle branch block — activation initially via His-Purkinje, resulting in rapid early QRS deflection
- **Pre-excited SVT (<5%):** Antidromic AVRT (accessory pathway antegrade), Mahaim fiber tachycardia — entirely via accessory pathway, muscle-to-muscle initiation
- **Ventricular-paced rhythm:** Pacemaker artefact; QRS morphology depends on lead position
- **Electrolyte/drug-induced QRS widening:** Hyperkalemia, sodium channel blocker toxicity

### Physiological Basis for ECG Differentiation
- **VT:** Initial ventricular activation via muscle-to-muscle spread (slow) → prolonged, broad initial QRS deflection → **delayed time to first peak** in leads II and aVR; terminal activation mediated by His-Purkinje after impulse engages conduction system → steeper terminal QRS
- **SVT with BBB:** Impulse enters via His-Purkinje → rapid initial ventricular activation → **short time to first peak** (<40 ms) in leads II and aVR; QRS widening from delayed muscle-to-muscle spread in the blocked bundle's territory (terminal widening)
- This physiological distinction is the mechanistic basis of all time-to-peak ECG algorithms
- **Electrical constraint vs electrical freedom:** SWCT is constrained by the His-Purkinje network → limited QRS/T-wave morphology options, often near-identical to the patient's baseline ECG; VT has electrical freedom — origin and propagation unconstrained → almost always produces markedly different depolarisation and repolarisation patterns vs baseline; **exceptions:** fascicular VT and bundle branch re-entry closely resemble the baseline ECG even during tachycardia ([[sources/wct-baseline-jecg-2021]] — low)

## Diagnosis

### Clinical Assessment
Haemodynamic status (syncope, hypotension, clinical appearance) is **NOT** useful for determining tachycardia mechanism — VT can be haemodynamically stable and SVT can present in shock.

**AV dissociation signs on physical examination** are of limited bedside utility during acute WCT. Cannon A waves (forceful irregular jugular pulsation from simultaneous AV contraction) suggest AV dissociation when present, but are intermittent and unreliable. The frog sign (regular jugular pulsation with every beat) is more characteristic of AVNRT. Both findings require a cooperative, adequately perfused patient and are rarely decisive at the bedside.

**VA dissociation prevalence:** Retrograde ventriculo-atrial conduction (1:1, 2:1, or Wenckebach) occurs in up to **50% of all VTs** — true AV dissociation is therefore absent in half of VT cases. Even when true AV dissociation is present, dissociated P waves are identifiable on 12-lead ECG in only approximately **1 in 5 VTs** — the remainder are hidden within overlapping QRS complexes and T waves, or obscured by coexistent atrial arrhythmia ([[sources/wct-kashou-jaha-2020]] — medium). IV adenosine may assist diagnosis when VA conduction is present, by establishing complete VA block and revealing underlying AV dissociation.

**Lewis lead for P-wave detection:** Modify lead I (right arm electrode at right 2nd ICS adjacent to sternum, left arm electrode at right 4th ICS; calibrate 1 mV = 20 mm) to amplify P-waves and facilitate AV dissociation detection. AV dissociation is also detectable echocardiographically (M-mode, mitral valve, tissue Doppler).

### ECG Differentiation — Principles
Seven hallmark ECG features form the building blocks of all WCT differentiation algorithms:

1. **AV dissociation** — confirms VT when unequivocally identified; absent in ~50% of VTs (retrograde VA conduction) and visible on 12-lead ECG in only ~20% of VTs
2. **Morphological criteria (V1–V2, V6)** — QRS configuration incompatible with typical RBBB or LBBB favours VT; exceptions: fascicular VT, bundle branch re-entry
3. **QRS duration** — >140 ms for RBBB-pattern, >160 ms for LBBB-pattern favours VT (Akhtar 1988); broad overlap limits use in isolation; fascicular VT can produce QRS <120 ms
4. **Chest lead concordance** — highly specific (>90%) but insensitive (<20%) for VT; positive concordance → posterobasal LV origin; negative concordance → near-diagnostic for anteroapical LV origin
5. **QRS axis** — northwest axis (−90° to −180°) highly predictive of VT; left-axis deviation + RBBB, or right-axis deviation + LBBB, quite specific for VT
6. **Ventricular activation velocity** — VT: RWPT ≥50 ms in II, RS interval ≥100 ms in precordials, Vi/Vt <1; SWCT: r wave duration <30 ms in V1/V2 (rapid His-Purkinje initiation)
7. **Baseline ECG comparison** — SWCT constrained to near-baseline morphology; VT almost always differs markedly; QRS axis change ≥40° from baseline is an independent VT predictor (Griffith 1991: 83% VT vs 36% SWCT); Sandler & Marriott 1965: same initial vector as baseline in 44% of SVT aberrant beats vs only 4% of PVCs ([[sources/wct-baseline-jecg-2021]] — low)
![](/raw/assets/WCT-JAMA-2020.pdf-2-0.png)
([[sources/wct-kashou-jaha-2020]])
### ECG Algorithm Overview

| Algorithm              | Year     | Design                     | Key Criteria                                                                    | Leads          | Complexity               |
| ---------------------- | -------- | -------------------------- | ------------------------------------------------------------------------------- | -------------- | ------------------------ |
| Brugada                | 1991     | Multistep                  | RS absent in precordials; RS>100 ms; AV dissociation; morphological criteria    | All 12         | High                     |
| Griffith (default)     | 1994     | VT-as-default              | SWCT only if typical LBBB or RBBB criteria met; all others = VT                 | V1, V6         | Low                      |
| Lau (Bayesian)         | 2000     | Multiplicative probability | Pretest LR=4 × serial criterion LRs; final LR ≥1 = VT                           | All 12         | Very high                |
| Vereckei (aVR)         | 2008     | Multistep                  | Initial R in aVR; initial r/q width >40 ms; notching; Vi/Vt ≤1                  | aVR only       | High                     |
| Pava (RWPT)            | 2010     | Single criterion           | RWPT in lead II ≥50 ms                                                          | Lead II        | Very low                 |
| Jastrzebski (VT score) | 2016     | Point-based                | 5 criteria; RBBB-pattern only; PPV 100% score ≥4                                | Multiple       | Moderate                 |
| Pachón                 | 2019     | Point-based                | 7 criteria (4 use baseline ECG comparison); PPV 100% VT (≥2), PPV 98% SWCT (−1) | All 12         | Moderate                 |
| Chen (LLA)         | 2019 | Multistep              | Monophasic R aVR; OR neg I+II+III; OR OQL                                   | Limb leads | Low — no measurement |
| Basel              | 2022 | Multistep              | Clinical high-risk + Lead II TFP >40 ms + Lead aVR TFP >40 ms               | II + aVR   | Very low             |

### Algorithm Details

#### Brugada 4-Step Algorithm (1991) ([[sources/vt-brugada-circ-1991]] — very high)
554 BCTs; sensitivity 0.987, specificity 0.965:
1. Is there an RS complex in ANY precordial lead? → If NO: **VT**
2. Is the RS interval >100 ms in any precordial lead? → If YES: **VT**
3. Is AV dissociation present? → If YES: **VT**
4. Morphological VT criteria in both V1 AND V6? → If YES: **VT**; If NO: **SVT with aberrant conduction**
![](/raw/assets/SVT-VT-Europace-2011.pdf-3-0.png)
Grimm et al. compared Wellens 1978 and Brugada 1991 in 240 BCTs — both >90% sensitivity but ~70% specificity for RBBB, 87% for LBBB; combining did not improve performance. Real-world specificity 59.5% overall, 48.1% RBBB-pattern (Chen 2019; [[sources/vt-chen-hrs-2019]]) — Step 4 is the single point of failure, driven by SVT with RBBB+LAFB misclassified as VT.

#### Vereckei aVR Algorithm (2007/2008) ([[sources/vt-vereckei-ehj-2007]] — high)
- *2007 12-lead version:* (1) AV dissociation; (2) initial R-wave in aVR; (3) Vi/Vt ≤1
- *2008 aVR-only simplification:* (1) initial R-wave; (2) initial r- or q-wave width >40 ms; (3) notching on initial downstroke; (4) Vi/Vt ≤1. Same accuracy as 2007 in 313 patients.
![](/raw/assets/SVT-VT-Europace-2011.pdf-4-0.png)
Accuracy 90.3% vs Brugada 84.8% (P=0.006); Step 4 Vi/Vt 82.2% vs Brugada morphological 68%. Limitation: Vi/Vt measurement problematic — aVR near-isoelectric in 15/528 patients; q duration near 40 ms in 32/528; κ=0.90 vs LLA κ=0.98.

#### Pava RWPT (2010)
RWPT ≥50 ms in lead II → VT; <50 ms → SWCT. Simple and fast; good sensitivity but limited specificity — sole reliance risks missing VT.

#### Lau Bayesian Algorithm (2000) ([[sources/wct-kashou-jaha-2020]] — medium)
Pretest odds of VT (LR=4) multiplied serially by individual criterion LRs; final LR ≥1 → VT. Example: monophasic QS in V6 → LR=50; typical RBBB in V1 → LR <1. **Advantages:** evaluates all ECG features without truncating at first positive step; accounts for uncertain findings. **Limitations:** requires complex arithmetic under pressure; treats criteria as independent — individual LRs likely overestimated.

#### Jastrzebski VT Score (2016)
5-criterion score designed for RBBB-pattern WCT; PPV 100% for score ≥4 — near-certain VT for a subset while acknowledging indeterminate cases.

#### Chen Limb Lead Algorithm (LLA, 2019) ([[sources/vt-chen-hrs-2019]] — high)
Purely frontal-plane; no measurements; VT diagnosed if **any one** of three criteria present (n=528 EP-confirmed; Sn 87.2%, Sp **90.8%**, PPV **96.7%**, κ **0.98**):
1. **Monophasic R wave in lead aVR** — entirely positive QRS; represents extreme superiorly-directed VT axis
2. **Predominantly negative QRS in leads I, II, AND III simultaneously** — northwest axis
3. **Opposing QRS in Limb leads (OQL):**
   - ALL inferior leads (II, III, aVF): concordant monophasic QRS (all R or all QS)
   - AND ≥2 of remaining limb leads (I, aVL, aVR): concordant monophasic QRS with **opposite** polarity
   - Basis: VT spreads muscle-to-muscle vertically → maximally opposite inferior/superior limb leads; SVT with aberrancy spreads via His-Purkinje horizontally → at least one limb lead perpendicular to the axis is biphasic, breaking concordance

**LLA performance:** Highest specificity (90.8% vs Brugada 59.5%, Vereckei 76.3%), highest PPV (96.7%), best κ (0.98); lower sensitivity (87.2% vs Brugada 94.0%); **fails for** conduction-system VTs (fascicular, para-Hisian, papillary muscle), VTs without extreme axis; **advantage:** limb leads only — usable on Holter/telemetry.

#### Pachón Scoring Algorithm (2019) ([[sources/wct-baseline-jecg-2021]] — low)
PPV 100% for score ≥2 (VT); PPV 98% for score −1 (SWCT); indeterminate cases fall between. Four of seven criteria explicitly compare WCT to the patient's baseline ECG:
1. **Sudden QRS normalisation in patients with baseline AF** — 11% sensitive, **100% specific** for VT
2. **QRS duration narrower during WCT vs baseline rhythm** — 10% sensitive, **99% specific** for VT
3. **Discordant BBB pattern vs preexisting BBB** — 15% sensitive, **99% specific** for VT
4. **WCT QRS morphology identical to baseline ECG** — 37% sensitive, **99% specific** for SWCT

All four are individually low-sensitivity but near-perfect specificity — useful as rule-in criteria when present.

#### Basel Algorithm (Moccetti et al., JACC CEP 2022) ([[sources/svt-vt-basel-jaccep-2022]] — high)
VT diagnosed if **≥2 of 3** criteria present; SVT if 0 or 1:
1. **Clinical high-risk feature:** history of MI, CHF with LVEF ≤35%, or implanted ICD/CRT-D
2. **Lead II TFP >40 ms** — time from QRS onset to first change in polarity; equivalent to RWPT for R-initial leads or first Q-wave duration for QS-initial leads
3. **Lead aVR TFP >40 ms** — same measurement in aVR

![](/raw/assets/SVT-VT-JACCEP-2022.pdf-2-0.png)
**Performance:** Sn 93.3%, Sp 90.4% (validation cohort, n=203, 151 VT/52 SVT); comparable to Brugada/Vereckei accuracy. **Clinical applicability test (8 physicians, 50 ECGs):** accuracy superior to Vereckei (81% vs 72%; P=0.002) and Chen (72%; P=0.03); **time to diagnosis 38 sec vs 106 sec (Brugada; P=0.002) and 48 sec (Vereckei; P=0.02)** — speed advantage most pronounced for cardiology fellows and internal medicine residents.

#### Historical Classical Morphological Criteria (1965–1997)
The pre-algorithm era established morphological patterns embedded in all current tools ([[sources/svt-vt-europace-2011]] — high):

**Sandler & Marriott (1965):** Monophasic or biphasic V1 in 92% of VEBs with RBBB morphology; triphasic (rsR', rSR', RsR') in only 6% → triphasic V1 favours SVT. Also first introduced baseline ECG comparison: 44% of SVT aberrant beats shared the same initial QRS activation vector as the baseline sinus complex vs only 4% of PVCs — same initial vector implies unchanged ventricular septal activation → aberrancy ([[sources/wct-baseline-jecg-2021]] — low).

**Precordial concordance (Marriott):**
- Positive concordance (all precordials upright): almost diagnostic for VT; exception — antidromic AVRT with left posterior or lateral AP
- Negative concordance (all precordials inverted): nearly always VT (exception: pectus excavatum + SVT with LBBB — one case report)

**"Rabbit ears" sign (Marriott 1971):** V1 double-peaked R: taller right peak ("good rabbit") = typical RBBB aberrancy; taller left peak ("bad rabbit") = suggests ventricular origin.

**Swanick et al. (1972):** VT favoured in RBBB-like BCT when: (1) S in V4 deeper than S in V1; (2) r-wave ≥0.03 s in V1; (3) negative QRS in lead I.

**Wellens (1978):** First to use His-bundle recording to confirm tachycardia origin. QR or QS in V5–V6 during VT in 89% with old MI; absent in idiopathic VT (Coumel et al. 1984).
![](/raw/assets/SVT-VT-Europace-2011.pdf-2-0.png)

**Griffith multivariate (1991):** Independent VT predictors: (1) prior MI; (2) predominantly negative aVF; (3) monophasic/biphasic V1 in RBBB pattern; (4) QRS axis change ≥40° from baseline — 83% of VT vs 36% of SWCT. Predictive accuracy 93–95%. Note: classical criteria have only 50% sensitivity in fascicular VT or structurally normal hearts.

**Alberca specificity analysis (1997):** Among 12 published morphological criteria, only 5 achieved >90% specificity: (1) Rsr'/Rr' in V1 with RBBB (98%); (2) QS/QR/R in V6 with RBBB (98%); (3) any Q in V6 with LBBB (92%); (4) full precordial concordance (100%); (5) no RS complex in any precordial lead (91%).

#### Automated WCT Differentiation — Novel Methods ([[sources/wct-kashou-jaha-2020]] — medium; [[sources/wct-baseline-jecg-2021]] — low)
Three logistic regression models from Mayo Clinic/Washington University; all use CEI software measurements on paired WCT and baseline ECGs:

| Method | Year | Key Variables | AUC |
|---|---|---|---|
| WCT Formula | 2019 | Frontal & horizontal percent amplitude change (PAC) | **0.97** |
| VT Prediction Model | 2020 | QRS duration change, QRS axis change, T-wave axis change | **0.90** |
| WCT Formula II | 2020 | Frontal & horizontal percent time-voltage area change (PTVAC) | **0.96** |

Key derivation data: VT frontal PTVAC 226.5% vs SWCT 53.6% (p<0.001); VT T-wave axis change 92° vs SWCT 41° (p<0.001). **Critical limitation:** All three require a paired baseline ECG — unavailable in many acute presentations. **Future direction:** Machine learning (deep learning already detects LV dysfunction, HCM, age/sex from ECG) is an active research priority for automated real-time WCT differentiation.

### Special Diagnostic Challenges

#### Class Ic Antiarrhythmic Drugs (flecainide, propafenone) ([[sources/svt-vt-europace-2011]] — high)
Use-dependent conduction delay greater in ventricular myocardium than His-Purkinje → exaggerated QRS asynchrony → bizarre BBB pattern (QRS 180–240 ms, bizarre RBBB with right/northwest axis, or atypical LBBB with left axis) closely mimicking VT. Class Ic agents also cause true proarrhythmia (monomorphic VT). The two may be indistinguishable by surface ECG alone.

#### Class III Antiarrhythmic Drugs (dofetilide — pure IKr blocker)
Prolongs Purkinje refractory period >> ventricular myocardium. Differential effects within the Purkinje system (L vs R, distal vs proximal, left posterior vs anterior fascicle) produce bizarre QRS complexes; sequential bilateral bundle branch block creates repetitive multimorphology BCTs mimicking multiple monomorphic VTs; atypically long coupling interval and long BCT cycle length further confound diagnosis.

#### Bundle Branch Reentry Tachycardia
Uncommon VT in patients with acquired heart disease and significant conduction system disease. QRS morphology is a **typical** BBB pattern (usually LBBB), often identical to sinus rhythm morphology — all morphological VT criteria are therefore inapplicable. Key distinguishing ECG feature: **rapid intrinsicoid deflection in right precordial leads** (initial activation via conduction system, not myocardium — opposite of myocardial VT origin). Interfascicular tachycardia has RBBB morphology; axis depends on circuit direction.

#### Fascicular Ventricular Tachycardia ([[sources/lpfvt-svt-circep-2017]] — high)
Relatively narrow QRS VT (100–140 ms) from the left fascicular Purkinje network in young patients without structural heart disease. Three subtypes: (1) LPF-VT (~80%) → RBBB + superior/left axis; (2) left anterior fascicle → RBBB + right-axis deviation; (3) upper septal → narrow QRS + normal axis. See [[concepts/Fascicular-Ventricular-Tachycardia]] for full details.

All standard WCT algorithms fail because fascicular VT exits via Purkinje → initial activation is FAST, not slow:
- RS interval median 62 ms — below Brugada >100 ms threshold; NOT statistically different from RBBB+LAHB aberrancy (P=0.4)
- Vi/Vt typically >1 (fast Purkinje activation) → Vereckei algorithm classifies as SVT
- QRS mean 127.5 ms — RBBB+LAHB aberrancy is actually WIDER (144 ms); Wellens' >140 ms criterion is inverted

**LPF-VT vs RBBB+LAHB aberrancy — 4-criterion model (Michowitz 2017; Sn 82.1%/Sp 78.3%; ≥3 of 4 = high probability LPF-VT):**
1. Atypical V1 morphology — R′ not taller than R (OR 5.1); note: 54% of LPF-VT still have typical V1
2. Positive QRS in aVR — R>S or R>Q (OR 19.2); narrow q <40 ms means Vereckei "initial R" still NOT triggered
3. V6 R/S ratio ≤1 (OR 6.7); R/S <0.15 seen ONLY in LPF-VT (21.9%)
4. QRS ≤140 ms (OR 7.7); QRS <120 ms and axis <−100° seen ONLY in LPF-VT

AV dissociation present in ~70% of LPF-VT when sought — always check first. Capture/fusion beats confirm VT when visible. Bifascicular VT (alternating focus) seen in digitalis toxicity or Andersen–Tawil syndrome.

#### Pre-Excited SVT (Antidromic AVRT, Mahaim, Pre-Excited AF)
Distinct WCT category with different management requirements. All standard WCT algorithms fail — variable morphology determined by accessory pathway location; entirely muscle-to-muscle activation via AP mimics VT on all morphological criteria.

- **Antidromic AVRT:** Maximally pre-excited wide QRS (entirely over AP); regular; may mimic VT. Key clue: delta wave morphology on resting ECG; known pre-excitation history
- **Pre-excited AF:** Irregular wide complex tachycardia with variable QRS morphology; rates can exceed 300 bpm → VF risk

#### ECG Artefact
Artefact mimicking BCT was misdiagnosed as VT by 94% of internists, 58% of cardiologists, and 38% of electrophysiologists in a physician simulation study (Knight et al.).

### Default Diagnosis Principle
Practical recommendation to achieve >95% PPV for VT: combine **(1) any morphological criterion + (2) AV dissociation detected clinically, by ECG, or echocardiographically + (3) history of myocardial disease (MI, cardiomyopathy, congenital heart disease, prior cardiac surgery)** ([[sources/svt-vt-europace-2011]] — high).

When diagnosis remains uncertain and **typical BBB morphology is absent → diagnose VT by default** (Griffith et al. 1994; adopted by ESC 2019).

## Management

### Acute Pharmacological Management (ESC 2019) ([[sources/svt-esc-2019]] — very high)

**PROCAMIO trial:** First RCT comparing IV procainamide vs IV amiodarone in haemodynamically stable wide QRS tachycardia. Procainamide associated with fewer major cardiac adverse events and higher termination rate within 40 minutes. This downgraded IV amiodarone from Class I (2003) to **IIb/B** in ESC 2019.

**ESC 2019 Recommendations (haemodynamically stable WCT):**
- Vagal manoeuvres: **I/C**
- Adenosine (only if no pre-excitation on resting ECG): **IIa/C** — upgraded from IIb in 2003; risk of AF induction → VF if pre-excitation suspected
- Procainamide IV: **IIa/B** — preferred pharmacological option based on PROCAMIO
- Amiodarone IV: **IIb/B** — downgraded from Class I; inferior outcomes in PROCAMIO
- DC cardioversion: **I/B** — always available, always appropriate
- **Verapamil in unknown-aetiology WCT: Class III/B — contraindicated**

**Drug of choice when diagnosis uncertain:** Procainamide — prolongs refractory period of myocardium, accessory pathway, and retrograde fast AV nodal pathway; avoids risks of verapamil (haemodynamic collapse in VT) and adenosine (VF in antidromic AVRT or pre-excited AF) ([[sources/svt-vt-europace-2011]] — high).

### Pre-Excited SVT — Distinct Management Requirements ([[sources/svt-aha-2015]] — very high)

Pre-excited SVT (antidromic AVRT, Mahaim, pre-excited AF) requires a fundamentally different drug strategy from VT or SVT with aberrancy:

- **IV verapamil, diltiazem, digoxin, amiodarone, or beta-blockers in pre-excited AF: Class III/Harm** — accelerate AP conduction → VF
- **Procainamide or DC cardioversion** are the safe options in pre-excited AF
- ACC/AHA/HRS 2015: "when doubt exists, it is safest to assume any wide-complex tachycardia is VT, particularly in patients with known cardiovascular disease"
- Adenosine may be used diagnostically for monomorphic, regular, haemodynamically stable WCT (ACLS); however, in antidromic AVRT adenosine may convert to pre-excited AF — cardioversion must be immediately available

## Limitations of Current WCT Algorithms
- **All algorithms underperform in:** fascicular VT (RS duration <80 ms; Purkinje initiation mimics SVT), antidromic AVRT, Mahaim fiber tachycardia, class Ic/III drug-induced BCT, bundle branch reentry VT (typical BBB morphology identical to sinus rhythm — morphological criteria inapplicable)
- **Brugada:** Step 4 is the single point of failure — SVT with RBBB+LAFB misclassified as VT; real-world specificity 59.5% overall, 48.1% RBBB-pattern vs 75.9% LBBB ([[sources/vt-chen-hrs-2019]]); Steps 1–3 retain good specificity (98%/94%/94%)
- **Vereckei:** Vi/Vt measurement problematic (isoelectric aVR, borderline q duration); κ=0.90 vs LLA κ=0.98 ([[sources/vt-chen-hrs-2019]])
- **Pava:** Single criterion; high specificity but limited sensitivity
- **Automated methods:** All three require a paired baseline ECG — not applicable in many acute presentations
- **EP-lab validation bias:** All standard algorithms derived and validated exclusively in EP laboratory populations; only one real-world validation study exists; true performance in unselected acute practice is largely unknown ([[sources/wct-kashou-jaha-2020]] — medium)
- **Referral bias:** Tertiary EP centre VT prevalence ~74–75% vs lower in community — published figures systematically overestimate real-world performance

## Contradictions / Open Questions
- Whether the Basel algorithm's time advantage translates into clinically meaningful outcome improvements (time-to-treatment) has not been tested in RCT or prospective registry settings
- All algorithms perform poorly in pre-excitation-related tachycardias and fascicular VT — clinical context (known pre-excitation, delta waves in sinus rhythm) remains essential
- Automated ECG software integration of WCT algorithms has been proposed; no validated real-time automated WCT diagnostic tool is currently available
- The Basel clinical high-risk criterion conflates SHD severity (LVEF ≤35%) with ICD presence — sensitivity in less-selected populations is unknown
- **Procainamide availability:** PROCAMIO establishes superiority over amiodarone, but procainamide is unavailable in many countries; amiodarone remains commonly used in many centres despite guideline downgrade [[sources/svt-esc-2019]]

## Connections
- Related to [[concepts/ECG-Conduction-Disturbances]] — BBB patterns are the primary SVT-mimic in WCT
- Related to [[concepts/Cardiac-Action-Potential]] — physiological basis of time-to-peak differences
- Related to [[concepts/Fascicular-Ventricular-Tachycardia]] — exception entity where all standard WCT algorithms fail
- Related to [[concepts/AVRT-Accessory-Pathway]] — antidromic AVRT and pre-excited AF as causes of WCT with distinct management
- Related to [[concepts/SVT-Management]] — WCT differentiation within the SVT management framework
- Related to [[concepts/Electrical-Storm]] — WCT differentiation is essential in ES management
- Related to [[entities/Brugada-Syndrome]] — Brugada algorithm (Brugada P 1991) is the most commonly used comparator; distinct from Brugada syndrome

## Sources
- [[sources/vt-brugada-circ-1991]] — Brugada P et al. 1991 Circulation; original prospective paper (n=554 EP-confirmed); introduces and validates the 4-step algorithm; defines RS interval measurement; morphological criteria tables for RBBB and LBBB patterns; overall Sn 98.7% Sp 96.5% (rating: very high)
- [[sources/vt-vereckei-ehj-2007]] — Vereckei et al. 2007 EHJ; prospective head-to-head comparison vs Brugada (n=453 EP-confirmed); introduces Vi/Vt criterion and initial-R-in-aVR criterion; 90.3% vs 84.8% accuracy; Step 4 Vi/Vt 82.2% vs Brugada morphological 68%; superior in pre-existing BBB and AAD subgroups; aVR criterion absent in all 17 PXTs; led to 2008 aVR-only simplification (rating: high)
- [[sources/lpfvt-svt-circep-2017]] — Michowitz/Belhassen et al. 2017 Circ EP; first systematic ECG characterisation of LPF-VT vs RBBB+LAHB (n=183 vs 61); 4-criterion model: atypical V1 + positive aVR + V6 R/S ≤1 + QRS ≤140 ms; Sn 82.1%/Sp 78.3%; confirms RS <80 ms and Vi/Vt >1 in LPF-VT → all standard algorithms fail (rating: high)
- [[sources/vt-chen-hrs-2019]] — Chen/Natale et al. 2019 Heart Rhythm; introduces LLA (3-criterion frontal-plane, no-measurement algorithm); n=528 EP-confirmed; Sn 87.2%, Sp 90.8% (highest), PPV 96.7%, κ 0.98 (best); AUC 0.89; most granular independent Brugada specificity validation: 59.5% overall, 48.1% RBBB-pattern; LLA fails for conduction-system VTs (rating: high)
- [[sources/svt-vt-europace-2011]] — Alzand & Crijns 2011 Europace review; 45-year historical evolution of BCT criteria; classical criteria, Brugada algorithm, Vereckei aVR algorithm, limitations (AAD-induced BCT, fascicular VT, bundle branch reentry, pre-excited SVT), default diagnosis principle (rating: high)
- [[sources/svt-vt-basel-jaccep-2022]] — Basel Algorithm derivation and validation; JACC CEP 2022 (rating: high)
- [[sources/svt-aha-2015]] — ACC/AHA/HRS 2015 SVT guideline; WCT differentiation principles and pre-excited AF management (rating: very high)
- [[sources/svt-esc-2019]] — ESC 2019 SVT guideline; procainamide vs amiodarone (PROCAMIO trial); adenosine IIa for unknown WCT without pre-excitation (rating: very high)
- [[sources/wct-kashou-jaha-2020]] — Kashou/May et al. 2020 JAHA mini review; algorithm design taxonomy (multistep, Bayesian, default, single-criterion, point-based); Lau Bayesian algorithm (2000); Pachón point-based scoring; AV dissociation ~1/5 visible on ECG; real-world validation gap; automated methods (WCT Formula, VT prediction model); machine learning future direction (rating: medium)
- [[sources/wct-baseline-jecg-2021]] — Evenson/Kashou/May et al. 2021 J Electrocardiol correspondence; SWCT electrical constraint vs VT electrical freedom conceptual framework; historical basis for baseline ECG comparison (Sandler 1965 44% vs 4%; Dongas 1985; Griffith 1991 ≥40° axis shift); Pachón 4 baseline-comparison criteria with specificity; WCT Formula II (AUC 0.96; PTVAC 226.5% vs 53.6%); all 3 automated methods AUC data (0.97/0.90/0.96) (rating: low)
