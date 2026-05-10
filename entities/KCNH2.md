---
dg-publish: true
title: "KCNH2 (hERG)"
tags: [genetics, ion-channels, channelopathies, potassium-channel, long-qt-syndrome, short-qt-syndrome, KCNH2, hERG]
source_count: 3
last_updated: 2026-05-07
---

# KCNH2 (hERG)

## Details
KCNH2 (human ether-à-go-go-related gene; also known as hERG) encodes the Kv11.1 alpha-subunit of the rapid delayed rectifier potassium channel (IKr), located on chromosome 7q35-q36. It is one of the three primary channelopathy genes and uniquely produces two opposing clinical phenotypes depending on mutation direction: loss-of-function causes LQT2 (the second most common LQTS subtype, 25-30%), while gain-of-function causes SQTS1. This bidirectional phenotype means that a novel variant of uncertain significance cannot be safely managed without functional characterisation — the direction of effect determines whether the patient requires QT-prolonging or QT-shortening therapy.

## Key Facts

### LQT2 (Loss-of-Function)
- **Epidemiology:** LQT2 accounts for 25-30% of all LQTS — the second most common subtype after LQT1. Autosomal dominant inheritance; loss-of-function reduces IKr during phase 3, delaying repolarization and prolonging QT. ([[sources/channelopathies-jaha-2025]], rating: high)
- **Variant risk stratification:** Variants affecting the transmembrane pore of KCNH2 carry the greatest relative risk of cardiac events compared with non-pore transmembrane domain variants — a clinically actionable genotype-risk finding. ([[sources/channelopathies-jaha-2025]])
- **Trigger specificity:** LQT2 cardiac events are predominantly triggered by sudden auditory stimuli (alarm clocks, ringing phones, doorbells) and sudden emotional arousal — distinct from LQT1 (exercise/sympathetic activation) and LQT3 (rest/sleep). This trigger pattern informs activity counselling and alarm management in affected patients. ([[sources/channelopathies-jaha-2025]])
- **Sex and hormonal modulation:** IKr is inhibited by estrogen, the primary mechanism explaining higher LQT2/TdP risk in women of reproductive age compared with men and prepubertal females. The postpartum fall in progesterone further elevates risk in the 9-month postpartum window. ([[sources/channelopathies-jaha-2025]])

### Pharmacotherapy for LQT2
- **Lumacaftor (pharmacological chaperone):** LQT2 mutations frequently cause protein misfolding and trafficking deficiency — the mutant Kv11.1 subunit is retained in the endoplasmic reticulum rather than reaching the sarcolemma. Lumacaftor rescued the LQT2 phenotype in iPSC-derived cardiomyocytes and is currently in a phase II clinical trial (NCT04581408) for QTc shortening in LQT2 patients. ([[sources/channelopathies-jaha-2025]], rating: high)
- **Mexiletine:** Recently shown to reduce QTc specifically in LQT2 patients (via INaL blockade reducing the competing inward depolarizing current, allowing faster net repolarization). ([[sources/channelopathies-jaha-2025]])

### SQTS1 (Gain-of-Function)
- **Mechanism:** Gain-of-function KCNH2 mutations accelerate IKr, shortening the action potential plateau and producing QTc <=360 ms. SQTS1 is the most common subtype of Short QT Syndrome. ([[sources/channelopathies-jaha-2025]], rating: high)
- **Pharmacotherapy:** Quinidine is first-line; it prolongs QTc by IKr blockade and is effective in SQTS1. Amiodarone and sotalol are both IKr blockers but are clinically ineffective in SQTS1 — the gain-of-function mutation alters drug-channel binding kinetics, preventing these agents from exerting their expected effect. This is counter-intuitive and clinically important: reflexive prescription of sotalol or amiodarone for SQTS1 arrhythmias will not work. ([[sources/channelopathies-jaha-2025]])
- See [[entities/Short-QT-Syndrome]] for the full SQTS diagnostic criteria (ESC 2022), Gollob score, and management algorithm.

### Rare Associations
- **Brugada syndrome overlap:** KCNH2 gain-of-function can produce phenotypic overlap with BrS through Ito interaction (rare). ([[sources/channelopathies-jaha-2025]], rating: high)
- **Early repolarization syndrome:** Missense variant p.V392I has been identified in ERS — part of the broader overlap between gain-of-function IKr and the early repolarization spectrum. ([[sources/channelopathies-jaha-2025]])

### Gene Therapy
- **SupRep for LQT2 (AAV9):** Suppress-and-replace therapy using AAV9-SupRep (shRNA silencing of endogenous KCNH2 + replacement with shRNA-resistant wild-type KCNH2 cDNA) normalised QTc (470 → 414 ms), APD90 (519 → 424 ms), restored beta-adrenergic APD shortening, and suppressed EADs and TdP inducibility in KCNH2-mutant rabbits (Bains 2023). Addresses all KCNH2 LOF mutations regardless of specific variant — mutation-agnostic approach. ([[sources/gene-therapy-arrhythmia-2025]], rating: high)
- **SQTS1 silencing — shRNA-only (no replacement):** Silencing gain-of-function KCNH2-N588K with shRNA alone (no replacement cDNA needed) prolonged QTc from 283 → 333 ms and reduced TdP inducibility from 5/7 to 1/8 animals in transgenic rabbits. Over-silencing KCNH2 in SQTS1 risks inducing iatrogenic LQT2 — the therapeutic silencing window has not been established in humans. ([[sources/gene-therapy-arrhythmia-2025]])
- **Dominant-negative KCNH2 for AF (preclinical):** Adenoviral delivery of dominant-negative KCNH2-G628S in porcine AF models prolonged atrial APD and reduced AF relative risk to 0.44 (Amit 2010; Soucek 2012). Therapeutic effect was transient (~21 days) due to adenoviral expression loss. Not clinically viable in current form. ([[sources/gene-therapy-arrhythmia-2025]])

### KCNH2-K897T as Intragenic Modifier
- **KCNH2-K897T (p.Lys897Thr)** is a common coding variant that acts as an intragenic modifier of both LQTS and ischaemic arrhythmia risk. On the allele opposite a primary KCNH2 LOF mutation (p.A1116V), K897T converted asymptomatic latent LQT2 to symptomatic disease with cardiac arrest; co-expression studies demonstrated markedly reduced IKr. ([[sources/modifier-genes-scd-ehj-2018]], rating: high)
- K897T also **aggravates LQT1 in trans**: in Finnish KCNQ1-G589D carriers, K897T was associated with longer QTc at maximal exercise — demonstrating cross-subtype modifier effects beyond its own gene.
- K897T is additionally associated with **life-threatening arrhythmias post-AMI**, showing that this modifier variant operates across congenital LQTS and acquired ischaemic arrhythmia contexts.
- **Population data:** K897T is associated with shorter QTc in most European cohorts (except Framingham), suggesting its deleterious effect requires the background of a primary disease-causing mutation to manifest. In isolation it may even be mildly protective. ([[sources/modifier-genes-scd-ehj-2018]])

## Contradictions / Open Questions
- **Bidirectional KCNH2 phenotype — opposite mutations requiring opposite treatments:** KCNH2 loss-of-function (LQT2) is managed by avoiding QT-prolonging drugs and using beta-blockers to prevent TdP; gain-of-function (SQTS1) is managed with quinidine to lengthen QT. A novel KCNH2 variant of uncertain significance cannot be safely managed without functional characterisation — prescribing in the wrong direction is potentially fatal. ([[sources/channelopathies-jaha-2025]])
- **SQTS1 amiodarone/sotalol paradox:** Both are IKr blockers and would theoretically lengthen QT, yet are clinically ineffective in SQTS1. The gain-of-function mutation alters drug-channel binding kinetics so that standard IKr-blocking agents cannot exert their expected effect. This counter-intuitive pharmacology creates prescribing confusion and undermines the assumption that channel-blocking drugs reliably reverse channel gain-of-function — a lesson relevant across channelopathies. ([[sources/channelopathies-jaha-2025]])
- **SQTS1 silencing therapeutic window — iatrogenic LQT2 risk:** SupRep for LQT2 requires shRNA silencing followed by wild-type KCNH2 replacement. SQTS1 requires silencing only (no replacement). Over-silencing endogenous KCNH2 in SQTS1 risks inducing iatrogenic LQT2. The minimum silencing threshold needed for SQTS1 arrhythmia suppression without over-suppressing IKr has not been established in humans. ([[sources/gene-therapy-arrhythmia-2025]])
- **Dominant-negative KCNH2 for AF — transient effect without clinical viability:** Adenoviral delivery of dominant-negative KCNH2-G628S reduced AF inducibility in porcine models but the effect was transient (~21 days) due to adenoviral expression loss. This approach has not been developed further; KCNH2-based AF gene therapy remains preclinical and short-lived. ([[sources/gene-therapy-arrhythmia-2025]])

## Connections
- Related to [[concepts/Cardiac-Action-Potential]]
- Related to [[concepts/Cardiac-Repolarization]]
- Related to [[concepts/Ion-Channel-Mutations]]
- Related to [[concepts/Torsades-de-Pointes]]
- Related to [[concepts/iPSC-Derived-Cardiomyocytes]]
- Related to [[concepts/SupRep-Therapy]]
- Related to [[concepts/AAV-Gene-Delivery]]
- Related to [[concepts/Gene-Silencing-Therapy]]
- Related to [[concepts/Modifier-Genes]]
- Related to [[entities/Long-QT-Syndrome]]
- Related to [[entities/Short-QT-Syndrome]]
- Related to [[entities/Brugada-Syndrome]]
- Related to [[entities/Early-Repolarization-Syndrome]]
- Related to [[sources/channelopathies-jaha-2025]]
- Related to [[sources/gene-therapy-arrhythmia-2025]]
- Related to [[sources/modifier-genes-scd-ehj-2018]]

## Sources
- [[sources/channelopathies-jaha-2025]]
- [[sources/gene-therapy-arrhythmia-2025]]
- [[sources/modifier-genes-scd-ehj-2018]]
