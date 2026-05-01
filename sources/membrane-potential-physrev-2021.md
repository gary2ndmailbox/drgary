---
dg-publish: true
title: "Cardiac Transmembrane Ion Channels and Action Potentials: Cellular Physiology and Arrhythmogenic Behavior"
date_ingested: 2026-04-30
source_type: review article
Citation: "Varró A, Tomek J, Nagy N, Virág L, Passini E, Rodriguez B, Baczko I. Cardiac Transmembrane Ion Channels and Action Potentials: Cellular Physiology and Arrhythmogenic Behavior. Physiol Rev. 2021;101(3):1083-1176."
DOI: "https://doi.org/10.1152/physrev.00024.2019"
tags: [cardiac-electrophysiology, ion-channels, arrhythmia-mechanisms, channelopathies, electrical-remodeling]
rating: very high
raw_path: raw/Membrane-potential-Physiological-review-2019.md
---

# Cardiac Transmembrane Ion Channels and Action Potentials: Cellular Physiology and Arrhythmogenic Behavior

## Authors, Journal, Affiliations, Type, DOI
- András Varró, Jakub Tomek, Norbert Nagy, László Virág, Elisa Passini, Blanca Rodriguez, István Baczko
- Physiological Reviews, 2021; 101(3):1083–1176
- Department of Pharmacology and Pharmacotherapy, University of Szeged, Hungary; MTA-SZTE Cardiovascular Pharmacology Research Group; Department of Computer Science, BHF Centre of Research Excellence, University of Oxford, UK
- Comprehensive review article
- DOI: 10.1152/physrev.00024.2019

## Overview
This 94-page landmark review comprehensively covers cardiac transmembrane ion channels, action potentials, and arrhythmogenesis with a deliberate focus on human-relevant data. The first half systematically details every major ionic current (INa, INaL, Ito, ICa,L, ICa,T, IKr, IKs, IK1, IKur, IK,Ach, If, IK,ATP, NCX, KATP), their molecular subunits, regional and tissue-specific differences (SAN, AV node, Purkinje, atrial, ventricular including transmural layers), and interspecies limitations. The second half addresses cellular arrhythmia mechanisms (EAD, DAD, reentry, alternans, repolarization heterogeneity), computer simulation frameworks (O'Hara–Rudy, ToR-ORd, Courtemanche), and electrical remodeling in atrial fibrillation, heart failure, HCM, myocardial infarction, and aging. Inherited channelopathies (LQT1–16, SQT1–8, Brugada, CPVT, ARVC), sex hormone effects, electrolyte disturbances, and drug-induced arrhythmia are also discussed.

## Keywords
Action potential; arrhythmia; heart; ion channels; remodeling

## Key Takeaways

### Section 1–2: Introduction and Cardiac Action Potential
- The cardiac AP has 5 phases: Phase 0 (rapid depolarization via INa), Phase 1 (early repolarization via Ito), Phase 2 (plateau via balance of ICa,L and K⁺ currents), Phase 3 (terminal repolarization via IKr, IKs, IK1), Phase 4 (resting potential or spontaneous depolarization in pacemakers)
- There is no single "cardiac action potential" — shape differs across cardiac regions and between species
- RMP is maintained by IK1 and the electrogenic Na⁺-K⁺ pump (exports 3 Na⁺, imports 2 K⁺)
- APD determines ERP in healthy conditions; this relationship can break down in hyperkalemia causing postrepolarization refractoriness
- AP recording techniques: microelectrode (most accurate), monophasic AP (Franz catheter for in vivo), patch clamp whole-cell (single-cell dialysis limitation), optical mapping (multi-site; motion artifact requires blebbistatin)

### Section 3: Transmembrane Ion Channels and Transporters

**INa (Nav1.5 / SCN5A):**
- Most important current for impulse conduction; encoded by SCN5A + β1–4 subunits
- Nav1.5 expressed throughout atria, ventricles, specialized conduction system; absent from SAN and AVN
- Fast INa activates within <1 ms at >−60 mV; inactivation time constant 0.6/4 ms; recovery 2–20 ms
- INaLate (<0.5% of peak INa): sustained depolarizing current during plateau; enhanced in HF and HCM; augments intracellular Na⁺ → increased Ca²⁺ via NCX → DADs/EADs
- Loss-of-function SCN5A → Brugada syndrome (~20% of BrS), sick sinus syndrome, progressive cardiac conduction defect
- Gain-of-function SCN5A → LQT3
- INaLate selective blockers: ranolazine, GS967 — potentially therapeutic in LQT3, HF, HCM

**Ito (Kv4.3 / KCND3, Kv4.2 / KCND2, Kv1.4 / KCNA4):**
- Drives Phase 1 repolarization; more prominent in Purkinje fibers, atrial, midmyocardial, and subepicardial cells; absent in SAN/AVN
- Kv4.3 fast-recovering; Kv1.4 slow-recovering (seconds) — contributes to frequency-dependent APD regulation
- Reduced in HF, HCM, diabetes → contributes to APD prolongation
- KChIP2 auxiliary subunit lower in females → higher epicardial Ito in males → male predominance in Brugada syndrome
- No selective inhibitor clinically available

**ICa,L (Cav1.2 / CACNA1C):**
- Critical for plateau maintenance, CICR trigger for excitation-contraction coupling, and SAN/AV nodal depolarization
- Rapid activation; Ca²⁺-dependent inactivation via calmodulin → auto-regulates plateau
- Regulated by CaM, CaMKII, PKA (β-adrenergic: increases ICa,L via Rad/cAMP)
- Loss-of-function CACNA1C → SQT4, BrS overlap; Gain-of-function G406R → LQT8 (Timothy syndrome): slow inactivation → coupled gating → tachyarrhythmia + multi-organ defects
- ICa,L blockers: verapamil, diltiazem, dihydropyridines; activator: Bay K8644

**IKr (hERG Kv11.1 / KCNH2):**
- Unique rapid inactivation during AP plateau; recovers during repolarization → provides essential repolarizing current at end of AP
- Does not fully deactivate between beats → residual IKr shortens next AP at fast rates (key for rate-dependent APD regulation)
- Loss-of-function mutations → LQT2 (most drug-susceptible LQTS); Gain-of-function → SQT1
- Blocked by: dofetilide, E-4031, and over 100 non-cardiac drugs (antibiotics, antipsychotics, antimalarials) → drug-induced TdP
- Decreased in hypokalemia (accelerated inactivation), ischemia (acidosis), HF

**IKs (Kv7.1 / KCNQ1 + MinK / KCNE1):**
- Slow activation (hundreds of ms to seconds); small at baseline; becomes critical repolarization reserve during sympathetic stimulation
- β-adrenergic stimulation (PKA/Yotiao phosphorylation) increases IKs — provides rate-adaptation of APD during exercise
- IKs block alone at baseline has minimal APD effect; becomes proarrhythmic when combined with IKr block ("repolarization reserve" concept)
- Loss-of-function → LQT1 (most common; most sympathetically triggered); Gain-of-function → SQT2, familial AF
- Progesterone increases IKs → protective in pregnancy for LQT1; testosterone increases IKs → QTc shorter in men

**IK1 (Kir2.1 / KCNJ2):**
- Secures RMP and terminal Phase 3 repolarization; inward rectification due to Mg²⁺/polyamine block at positive potentials
- Loss-of-function KCNJ2 → Andersen-Tawil syndrome (LQT7): QTc prolongation but relatively benign TdP risk
- Gain-of-function → SQT3, upregulated in chronic AF (contributes to APD shortening)
- Downregulated in HF → APD prolongation and DAD formation
- Inhibited by Ba²⁺ (μM) and PA-6 (nM)

**IKur (Kv1.5 / KCNA5):**
- Primarily expressed in atria and Purkinje; minimal in ventricles
- Rationale for atrial-selective antiarrhythmic for AF (would shorten atrial ERP without ventricular effect)
- Clinical trials with XEN-D0101/D0103 disappointing — variable effects depending on AF remodeling state
- Under adrenergic control: α1-receptor decreases, β1-receptor increases IKur

**If (HCN4 / HCN2 / HCN1):**
- Pacemaker "funny" current; activated by hyperpolarization; mixed Na⁺/K⁺ current
- Present in SAN (primary pacemaker), AV node, Purkinje fibers (subsidiary pacemakers)
- Upregulated in HF and HCM ventricles → ectopic depolarizations, triggers for arrhythmia
- Ivermectin, ivabradine block If → rate reduction
- Loss-of-function HCN4 mutations → sick sinus syndrome; Gain-of-function → inappropriate sinus tachycardia

**IK,ATP (Kir6.2/SUR2A):**
- Closed by physiological ATP; activates during ischemia (↓ATP/ADP ratio)
- Shortens APD during ischemia → reduces Ca²⁺ overload (protective) but also promotes arrhythmia
- Cardioprotective in ischemic preconditioning; relevant to ICD-type arrhythmia suppression

**NCX (Na⁺/Ca²⁺ exchanger):**
- Electrogenic: 3 Na⁺ exchanged for 1 Ca²⁺ → forward mode (Ca²⁺ extrusion, inward current) dominant at rest
- Critical for EAD and DAD formation: Ca²⁺ overload activates forward NCX → depolarizing current
- Upregulated in HF → increases proarrhythmic triggered activity

### Section 4: Tissue-Specific Action Potentials

**Sinoatrial node:**
- No fast INa; depolarization driven by ICa,L and ICa,T plus If "clock" and SR Ca²⁺ "clock"
- Nav1.5 absent from central SAN; HCN4 and Cav1.3 dominant
- Stretch activates SACs → can increase automaticity → role in AF initiation

**Pulmonary veins:**
- Less negative RMP and shorter APD than atria; lack plateau phase
- Lower IK1, IKr, IKs; similar ICa,L and Ito vs atria
- Sympathetic stimulation → DADs/EADs → trigger for AF (Haïssaguerre)
- PV isolation by catheter ablation is the cornerstone of AF ablation

**AV node:**
- No Nav1.5; slow conduction dependent on ICa,L
- IK,ACh highly expressed → adenosine/acetylcholine hyperpolarizes AV node → clinical basis for IV adenosine in AVNRT
- Dual fast/slow pathway → anatomic basis for AVNRT

**Purkinje fibers:**
- Fastest conduction (300–750 V/s); large INa, large Ito, prominent Phase 1
- Longer APD than ventricle (protective against retrograde stimuli but source of repolarization inhomogeneity)
- Robust If → subsidiary pacemaker function; EADs in Purkinje can propagate to ventricular muscle via electrotonic coupling
- IK,Ach expressed (unlike ventricle) → responds to acetylcholine

**Ventricular — Transmural heterogeneity:**
- Subepicardium: larger Ito → prominent phase 1 notch; shorter APD
- M cells (midmyocardium): larger INaLate, larger NCX, smaller IKs → longest APD → transmural dispersion
- Subendocardium: smallest Ito; AP closest to plateau-dominant morphology
- In intact heart, transmural gradient is electrically coupled → less absolute dispersion than wedge preparations suggest
- In pathological settings (drugs, mutations, ischemia): uncoupling → larger dispersion → EADs and TdP

**Species differences:**
- Mice/rats: very short AP (Ito and IKur dominant; no plateau; no functional IKr/IKs) — not valid models for repolarization arrhythmia research
- Guinea pig: no Ito; large IKs (unlike human)
- Rabbit: Ito primarily Kv1.4 (unlike human Kv4.3 dominant)
- Dog: closest to human but larger IK1 than human → stronger repolarization reserve → less drug-induced APD prolongation vs human
- HiPSC-CMs: immature phenotype; low IK1; spontaneous beating; improving with 3D tissue engineering (engineered heart tissue)

### Section 5: Computer Simulations
- Hodgkin-Huxley gating variables represent major ionic currents; Markov models for complex gating (hERG)
- Human ventricular models: ten Tusscher (2004), O'Hara–Rudy (ORd, 2011), ToR-ORd (2020) — dominant in drug safety assessment (CiPA initiative)
- Key challenge for human models: IKr dominates repolarization reserve (unlike IKs in other species) — critical for drug cardiotoxicity simulation
- Populations of models approach: captures biological variability; calibrated to experimental data range; used in HCM and AF arrhythmia risk prediction
- Computational models provide "perfect observability and controllability" — identify gaps between hypotheses and experimental data

### Section 6: Cellular Arrhythmia Mechanisms

**EADs (Early Afterdepolarizations):**
- Occur during Phase 2 or 3 of prolonged AP (e.g., IKr block)
- Mechanism: L-type ICa,L reactivation ("reactivation-driven EAD") at slow rates; or SR Ca²⁺ release → NCX depolarization ("release-driven EAD") at fast rates
- CaMKII and PKA dysregulation in HF facilitates EADs
- EADs in Purkinje fibers → ectopic beats → TdP trigger in intact heart via electrotonic coupling
- ~70 synchronized cells needed to trigger propagating EAD in a fiber; ~700,000 in 3-D tissue (limits arrhythmia risk in healthy myocardium)

**DADs (Delayed Afterdepolarizations):**
- Occur during diastole after Ca²⁺ overload → SR Ca²⁺ sparks/waves → NCX forward mode → depolarization
- IK1 normally opposes DAD formation; when Ca²⁺-driven depolarization exceeds IK1 → triggers new AP
- Promoted by: HF, chronic AF, ischemia, catecholamines, CPVT (RyR2 mutations), digitalis
- CPVT mechanism: RYR2 gain-of-function → catecholamine-triggered SR Ca²⁺ leaks → DADs → bidirectional VT

**Reentry:**
- Requires: (1) substrate = repolarization heterogeneity or anatomic obstacle + (2) trigger = premature beat
- Functional reentry (no anatomic obstacle): zig-zag conduction through heterogeneous repolarization
- Electrical restitution: APD depends on preceding diastolic interval; steep restitution curve is proarrhythmic

**Repolarization alternans:**
- Beat-to-beat oscillation of long/short APD at rapid rates; concordant → discordant → reentry
- Two competing mechanisms: (1) steep APD restitution slope; (2) Ca²⁺-driven alternans (SR Ca²⁺ cycling refractoriness)
- Short-term APD variability (Poincaré plot of QT intervals) is an emerging proarrhythmic biomarker

### Section 7: Electrical Remodeling in Disease

**Atrial Fibrillation:**
- Electrical remodeling: ↓ICa,L, ↓IKr?, ↑Ito (atria), ↓INa, ↑IK,ACh (constitutive activation), ↑Kir2.1 → shorter triangular AP
- Shortened AP + reduced ERP → AF self-perpetuation ("AF begets AF")
- INaLate reduction → less EAD; but ↑IK,ACh and structural remodeling (fibrosis) are dominant drivers of persistent AF

**Heart Failure:**
- ↓Ito, ↓IKr?, ↓IKs, ↓IK1 → APD prolongation
- ↑INaLate, ↑NCX, ↑If → enhanced EAD/DAD triggers
- CaMKII hyperactivation → phosphorylates Nav1.5 → ↑INaLate; phosphorylates RyR2 → Ca²⁺ leakage → DADs
- Combined electrical + structural remodeling (fibrosis, gap junction remodeling) = proarrhythmic substrate

**HCM:**
- ↑INaLate (pre-structural — detectable before hypertrophy develops)
- ↑INaLate → ↑intracellular Ca²⁺ → Ca²⁺ overload → EADs/DADs
- Ranolazine/mexiletine (INaLate blockers) reverse electromechanical dysfunction in human HCM tissue
- ↓Ito in HCM → slowed Phase 1 → altered driving force for CICR → asynchronous SR Ca²⁺ release

**Myocardial Infarction:**
- Surviving subendocardial cells in infarct border zone: depolarized RMP → partial INa inactivation → slow conduction → reentry substrate
- Purkinje fibers survive ischemia better than ventricular myocytes → ectopic pacemaker activity in survivors
- Reduced IKr in infarcted zone → prolonged APD → EAD substrate

### Section 8: Inherited Channelopathies
- LQT1 (KCNQ1 LOF): exercise/swimming-triggered; IKs reduction; beta-blockers most effective
- LQT2 (KCNH2 LOF): auditory triggers; IKr reduction; most drug-susceptible; most common acquired LQTS gene
- LQT3 (SCN5A GOF): bradycardia/sleep-triggered; INaLate increase; ranolazine/mexiletine effective; arrhythmia often fatal
- LQT4–16: rare subtypes (Ankyrin-B, calmodulin 1/2/3, KATP channel, etc.)
- SQT1 (KCNH2 GOF): ↑IKr; short QT; sudden death; quinidine may be effective
- SQT2 (KCNQ1 GOF): ↑IKs; very rare
- SQT3 (KCNJ2 GOF): ↑IK1; very rare
- SQT4-6 (CACNA1C/CACNB2b/CACNA2D1 LOF): ICa,L loss; Brugada overlap
- Brugada: SCN5A LOF ~20%; Ito GOF contributes (repolarization hypothesis); INa LOF (depolarization hypothesis) — unresolved debate
- CPVT: RYR2 GOF (CPVT1) or CASQ2 LOF (CPVT2) → DADs under catecholamines → bidirectional VT → SCD

### Section 9: Other Factors
**Sex differences:**
- Women: longer QTc; lower Ito/IK1/IKr/IKs expression → less repolarization reserve → more drug-induced TdP
- Estradiol: reduces IKr, increases ICa,L → proarrhythmic (EAD/TdP risk)
- Testosterone: increases IKr, IKs, SERCA function → antiarrhythmic
- Progesterone: increases IKs → antiarrhythmic (protective in pregnancy)
- Male Brugada predominance: stronger Ito in epicardium (KChIP2 lower in females)
- Women have higher SAN automaticity; shorter sinus cycle length

**Electrolytes:**
- Hypokalemia: ↓IKr (accelerated inactivation), ↓IK1 → APD prolongation → TdP risk; exacerbates drug-induced QT prolongation
- Hyperkalemia: depolarizes RMP → partial INa inactivation → slow conduction → VF risk
- Hypomagnesemia: reduced Ca²⁺ antagonism → enhanced ICa,L → EAD/DAD

**Drug-induced arrhythmia:**
- Most drugs cause TdP via IKr/hERG block (Class III antiarrhythmics, antibiotics, antihistamines, antipsychotics, antimalarials)
- HERG safety screening now mandatory in drug development (CiPA)
- Class I antiarrhythmic drugs (INa blockers): can convert areas of depressed conduction to unidirectional block → proarrhythmic reentry
- CAST trial: cautionary lesson — flecainide/encainide increased SCD despite suppressing PVCs post-MI

## Limitations of the Document
- Highly detailed mechanistic content but limited direct clinical outcome data (focuses on cellular physiology, not trial evidence)
- Species-dependent limitations extensively acknowledged but many cited studies still use animal models
- Computer models remain imperfect representations; population-of-models approach still relies on assumed parameter distributions
- Human-specific ion current data are limited (human tissue obtained from surgery patients; may not represent the general population)

## Key Concepts Mentioned
- [[concepts/Cardiac-Action-Potential]] — comprehensive mechanistic basis of all 5 phases; human-specific channel details
- [[concepts/Torsades-de-Pointes]] — EAD mechanism; sex hormone modulation; drug-induced IKr block
- [[concepts/Ion-Channel-Mutations]] — complete table of channelopathy genes and ionic mechanisms (Table 1)
- [[concepts/Ion-Channel-Remodeling-in-HCM]] — INaLate upregulation pre-structural change; ranolazine reversal
- [[concepts/Cardiac-Repolarization]] — repolarization reserve concept; IKr/IKs interplay; transmural heterogeneity
- [[concepts/Electrical-Remodeling]] — AF/HF/HCM/MI-specific remodeling tables (Table 2)
- [[concepts/iPSC-Derived-Cardiomyocytes]] — HiPSC limitations (immature phenotype, low IK1); engineered heart tissue progress

## Key Entities Mentioned
- [[entities/Atrial-Fibrillation]] — PV triggers; electrical remodeling; IK,ACh; structural remodeling
- [[entities/Long-QT-Syndrome]] — mechanistic basis for all 16 subtypes; trigger patterns; treatment basis
- [[entities/Short-QT-Syndrome]] — ionic mechanisms for SQT1–8
- [[entities/Brugada-Syndrome]] — SCN5A LOF; Ito GOF; unresolved repolarization vs depolarization debate
- [[entities/CPVT]] — RYR2/CASQ2; DAD mechanism; catecholamine-triggered
- [[entities/HCM]] — INaLate; Ca²⁺ overload; ranolazine therapeutic implication
- [[entities/Heart-Failure]] — comprehensive electrical remodeling summary

## Wiki Pages Updated
- wiki/sources/membrane-potential-physrev-2021.md (created)
- wiki/sourceindex.md (updated)
- wiki/wikiindex.md (updated)
- wiki/concepts/Cardiac-Action-Potential.md (updated — detailed phase/channel content)
- wiki/concepts/Electrical-Remodeling.md (created — new page)
- wiki/entities/Long-QT-Syndrome.md (updated — mechanistic basis all subtypes)
- wiki/entities/Brugada-Syndrome.md (updated — Ito/INa debate)
- wiki/entities/CPVT.md (updated — DAD mechanism detail)
- wiki/entities/Atrial-Fibrillation.md (updated — electrical remodeling)
- wiki/entities/HCM.md (updated — INaLate)
- wiki/entities/Heart-Failure.md (updated — electrical remodeling)
