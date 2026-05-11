---
dg-publish: true
title: "Calmodulinopathy"
tags: [calmodulinopathy, calcium-handling, long-qt-syndrome, CPVT, channelopathies]
source_count: 3
last_updated: 2026-05-10
---

# Calmodulinopathy

## Definition
Calmodulinopathy is a rare, severe, predominantly de novo inherited cardiac channelopathy caused by heterozygous mutations in any of the three CALM genes (CALM1, CALM2, CALM3), all encoding identical calmodulin (CaM) protein. Despite heterozygosity (1 mutant allele per 6 encoding the same protein), penetrance is near-complete — explained by the dominance of mutant CaM within the pre-bound pool at cardiac ion channel targets. Clinical presentation is severe electrical instability in children and young adults, with high SCD risk. ClinGen classifies CALM1/2/3 as Definitive for LQTS and Moderate for CPVT (2026).

## Key Concepts

### CaM Structure and the Pre-Bound Pool
- CaM: 149 amino acids, 17 kDa; 100% vertebrate sequence conservation; encoded by CALM1/2/3 — all producing identical protein (redundancy by design)
- Two lobes (N and C), each with 2 EF-hand Ca²⁺ binding domains; C-lobe has 10× higher Ca²⁺ affinity and is the primary Ca²⁺-sensing lobe for channel modulation
- At least 3 of 4 Ca²⁺ sites must be occupied ("holo-CaM") for downstream activation
- In cardiomyocytes, **99% of CaM is pre-bound** to cellular proteins; only ~50–100 nM is free — most CaM exists as pre-bound apo-CaM at diastolic Ca²⁺ levels
- Pre-bound apo-CaM at channel IQ/preIQ motifs positions the C-lobe to sense local Ca²⁺ during channel opening — bulk cytosolic CaM diffusion is too slow for CDI kinetics
- [[sources/CALM-FCVM-2018]], rating: high

### Mechanism of High Penetrance
- A 1:7 mutant:WT CaM ratio (heterozygous) is sufficient to impair CDI at Cav1.2 because mutant CaMs occupy the pre-bound pool equally with WT CaM — and even a minority of Ca²⁺-affinity-compromised CaMs prevent adequate C-lobe signalling during CDI
- Targets requiring holo-CaM (e.g., CaMKII) are relatively spared — mutant CaM with reduced Ca²⁺ affinity forms fewer holo-CaM molecules, leaving WT holo-CaM to dominate
- RyR2 inhibition by apo-CaM is Ca²⁺-independent → LQTS mutations spare RyR2 (Ca²⁺ affinity reduction does not disrupt apo-CaM–RyR2 binding); CPVT mutations disrupt RyR2 via a distinct conformational mechanism
- [[sources/CALM-FCVM-2018]], rating: high

### LQTS Phenotype — CDI Loss Mechanism
- **Core mechanism:** Mutations reduce C-lobe Ca²⁺ affinity (EF III/IV residues) → pre-bound mutant CaM cannot sense Ca²⁺ at Cav1.2 cytoplasmic mouth → CDI abolished → ICaL gain of function → APD prolongation → QT prolongation → EADs → TdP/VF
- **Key mutations:** CALM1-p.D130G (also CALM3), CALM2-p.D96V, CALM1-p.F142L, CALM2-p.D130V, CALM1-p.E141G, CALM2-p.D132H, CALM1-p.D132V
- **hiPSC-CM data (CALM1-p.F142L):** CDI severely impaired; APD prolonged and non-rate-adaptive; Ca²⁺ transient amplitude increased but SR Ca²⁺ content normal; no spontaneous Ca²⁺ release events (RyR2 intact); IKs unaffected; CaMKII preserved/enhanced. Confirms CDI loss — not SR instability — as the sole arrhythmogenic mechanism in LQTS calmodulinopathy
- **IKs (Kv7.1) sparing:** IKs modulation also requires C-lobe Ca²⁺ sensing — yet IKs appears unaffected in LQTS calmodulinopathy; PIP2-dependent IKs activation likely compensates for lost CaM–IKs signalling
- **Verapamil** (ICaL blocker) shortens QT in CALM1-p.F142L hiPSC-CMs; selective sustained ICaL blockade (analogous to mexiletine for INaL in LQT3) is the theoretical ideal but not yet clinically available
- [[sources/CALM-FCVM-2018]], rating: high; [[sources/arrhythmia-genetics-mgenetik-2025]], rating: high

### CPVT Phenotype — RyR2 Destabilisation Mechanism
- **Mutations:** CALM1-p.N98S, CALM1-p.N54I, CALM3-p.A103V — smaller C-lobe Ca²⁺ affinity reduction vs. LQTS mutations; CDI relatively preserved
- **Mechanism:** Mutant CaM alters the CaM–RyR2 3D binding interface → disrupts apo-CaM–dependent stabilisation of RyR2 closed state ("unzipping") → spontaneous diastolic Ca²⁺ waves → NCX-mediated transient inward current (ITI) → DADs → bidirectional VT
- **Mechanism elusive:** CALM1-p.N98S shows inconsistent affinity changes (decreased vs. increased) across studies; CALM3-p.A103V strongly increases Ca²⁺ release events with normal RyR2 affinity → conformational binding interface changes (not affinity) are likely the true determinant
- **Treatment:** Beta-blockers + flecainide/carvedilol by analogy to RYR2-CPVT; no calmodulinopathy-specific CPVT trial data as of 2018
- [[sources/CALM-FCVM-2018]], rating: high

### Mixed Phenotype and IVF
- Some mutations (CALM2-p.D132E, CALM2-p.Q136P) produce combined QT prolongation + CPVT-type Ca²⁺ instability — likely impaired CDI with secondary SR instability when homeostatic compensation fails
- CALM2-p.N98S (LQTS) vs. CALM1-p.N98S (CPVT) — identical protein product → same mutation can produce different phenotypes; modifier factors unknown, confirming calmodulinopathy is not gene-determined
- CALM1-p.F90L → IVF only (mild QTc prolongation during exercise recovery only); impairs C-lobe conformational stability + CaM–RyR2 interface + SK channels
- [[sources/CALM-FCVM-2018]], rating: high

### ClinGen Gene-Disease Validity (2026)
- CALM1/2/3 **Definitive for LQTS** (classified 09/25/2018)
- CALM1/2/3 **Moderate for CPVT** — supported but not yet Definitive
- Neonatal LQTS with QTc >600 ms without identifiable cause → CALM1/2/3 sequencing mandatory
- [[sources/clingen-summary-2026-05-09]], rating: high

### Clinical Presentation and Management
- Onset: infancy to early childhood; neonatal presentation with recurrent cardiac arrest possible; high SCD risk in the young
- Extreme QTc (>600 ms) in LQTS phenotype; bidirectional VT in CPVT phenotype
- Predominantly de novo mutations — negative family history does not exclude diagnosis
- **LQTS management:** Beta-blockers (non-selective); verapamil empirically; avoid QT-prolonging drugs; LCSD and ICD per standard LQTS escalation
- **CPVT management:** Beta-blockers (non-selective) + flecainide; LCSD and ICD per standard CPVT protocol
- No calmodulinopathy-specific treatment guidelines; management extrapolated from standard channelopathy algorithms
- [[sources/CALM-FCVM-2018]], rating: high; [[sources/arrhythmia-genetics-mgenetik-2025]], rating: high

## Contradictions / Open Questions
- **Same mutation → different phenotype (p.N98S across CALM1/2):** CALM2-p.N98S reported as LQTS; CALM1-p.N98S as CPVT — identical protein product. Modifier genes, environmental factors, or ascertainment bias could all contribute, but mechanism is unknown. [[sources/CALM-FCVM-2018]]
- **Mechanism of RyR2 destabilisation unresolved:** CaM–RyR2 affinity changes are contradicted across labs; CALM3-p.A103V destabilises without affinity change. The nature of the 3D binding interface disruption has not been structurally characterised. [[sources/CALM-FCVM-2018]]
- **IKs sparing by PIP2 — theoretical:** PIP2-dependent IKs activation may compensate for lost CaM-mediated IKs enhancement in LQTS calmodulinopathy, but direct testing under PIP2 depletion conditions has not been reported. [[sources/CALM-FCVM-2018]]
- **No clinical outcome data for any treatment (2018):** Verapamil efficacy is hiPSC-CM–based only; no systematic clinical series for beta-blockers, ICaL blockers, or CPVT regimens in calmodulinopathy. [[sources/CALM-FCVM-2018]]

## Connections
- Related to [[entities/Long-QT-Syndrome]]
- Related to [[entities/CPVT]]
- Related to [[entities/RYR2]]
- Related to [[entities/KCNQ1]]
- Related to [[concepts/Cardiac-Action-Potential]]
- Related to [[concepts/Calcium-Homeostasis-in-HCM]]
- Related to [[concepts/iPSC-Derived-Cardiomyocytes]]
- Related to [[concepts/Left-Cardiac-Sympathetic-Denervation]]
- Related to [[concepts/ClinGen-Gene-Disease-Validity]]
- Related to [[concepts/Sudden-Cardiac-Death]]
- Related to [[concepts/Ion-Channel-Mutations]]

## Sources
- [[sources/CALM-FCVM-2018]]
- [[sources/arrhythmia-genetics-mgenetik-2025]]
- [[sources/clingen-summary-2026-05-09]]
