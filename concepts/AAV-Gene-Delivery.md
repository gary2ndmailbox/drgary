---
dg-publish: true
title: "AAV Gene Delivery"
tags: [gene-therapy, viral-vectors, cardiac-delivery, channelopathies, gene-editing]
source_count: 3
last_updated: 2026-05-09
---

# AAV Gene Delivery

## Definition
Adeno-associated virus (AAV) vectors are the dominant platform for cardiac gene therapy. They are non-integrating (largely episomal), low-immunogenicity, replication-deficient viral vectors capable of transducing post-mitotic cardiomyocytes. AAV9 is the most widely used serotype for cardiac gene delivery due to its cardiotropism. As of January 2024, AAV9 was used in 92% of published cardiac arrhythmia gene therapy studies; 88% of those studies relied on small-animal (mouse/rat) models — the dominant translational gap.

## Key Concepts

### Vector Biology

- **Packaging capacity — 4.7 kb ceiling:** Standard AAV vectors accommodate ~4.7 kilobases of genetic payload. This precludes direct gene replacement for large disease-causing genes: RYR2 (~15,000 nt) and SCN5A (~6,048 bp) both exceed this limit, making packaging size the principal determinant of therapeutic strategy selection. ([[sources/gene-therapy-arrhythmia-2025]])
- **Workarounds for large genes:**
  - *Dual-vector (trans-splicing) and split-vector systems:* Divide large constructs across two AAV vectors that reconstitute in the cell. Performance is inconsistent relative to single-vector delivery. ([[sources/gene-editing-cv-tcm-2025]])
  - *Mini-gene constructs:* Truncated functional domains; unpredictable expression dynamics.
  - *Pathway-targeted therapy:* Bypasses size constraints by targeting shared molecular nodes — e.g., MOG1 (Nav1.5 trafficking chaperone) for BrS instead of full-length SCN5A; CASQ2 overexpression for CPVT1 instead of RYR2. ([[sources/gene-therapy-arrhythmia-2025]])
- **AAV9 — de facto standard serotype:** Used in 92% of cardiac arrhythmia gene therapy studies. Demonstrated efficacy for CASQ2 replacement (CPVT), SupRep for LQTS, PKP2 replacement (ARVC), CaMKII peptide inhibitor delivery, SCN5A base editing (LQT3), and CRISPR-SaCas9 for CPVT1. ([[sources/gene-therapy-arrhythmia-2025]], [[sources/aav-gene-therapy-arrhythmia-hr-2024]])
- **AAV2i8 — chimeric next-generation vector:** Combines AAV2 and AAV8 capsid elements; broad striated muscle tropism; reduced liver transduction compared to AAV8 → improved cardiac specificity for systemic delivery. Not yet used in arrhythmia studies. ([[sources/aav-gene-therapy-arrhythmia-hr-2024]])
- **AAVMYO — striated muscle-specific vector:** Improved tropism for cardiac and skeletal muscle; reduces mosaicism by improving homogeneity of cardiac transduction compared to AAV9; used in combination with cardiac-specific peptides. ([[sources/gene-editing-cv-tcm-2025]])
- **Non-viral alternatives:**
  - *Lipid nanoparticles (LNPs) encapsulating mRNA:* Transient, non-integrating expression; low immunogenicity; repeated dosing feasible. Safety demonstrated in EPICCURE trial (VEGF-A mRNA).
  - *Naked mRNA:* TBX18 mRNA (unformulated) established biological pacing in rats and pigs — proof-of-concept for mRNA-based cardiac reprogramming. ([[sources/gene-therapy-arrhythmia-2025]])

### Routes of Delivery

- **Intravenous:** Least invasive; suitable for systemic disease. Significant off-target liver accumulation; lower cardiac transduction efficiency — requiring higher doses with greater immune and hepatic exposure. ([[sources/gene-therapy-arrhythmia-2025]])
- **Intracoronary:** Catheter-delivered directly to coronary circulation; better cardiac uptake and reduced hepatic distribution than IV. Less effective in the presence of coronary artery disease (reduced perfusion limits vector distribution). Requires cath lab access. ([[sources/gene-therapy-arrhythmia-2025]])
- **Intramyocardial:** Targeted regional delivery; used intraoperatively. Most precise spatial control but invasive; limited spread from injection site; risk of localised inflammation and arrhythmias at injection site. ([[sources/gene-therapy-arrhythmia-2025]])
- No head-to-head RCT defines the optimal route for any cardiac gene therapy indication — route selection is currently extrapolated from animal studies and manufacturing constraints. ([[sources/gene-therapy-arrhythmia-2025]])

### Delivery Challenges & Limitations

- **Immune responses — single-dose constraint:** Pre-existing or treatment-induced anti-AAV neutralising antibodies limit efficacy and prevent re-dosing with the same serotype. Mitigations under development: transient immunosuppression, capsid re-engineering, extracellular vesicle shielding — none validated in humans. For chronic cardiac diseases requiring lifelong therapy (HCM, LMNA cardiomyopathy), the single-dose constraint is a major unresolved barrier. ([[sources/gene-therapy-arrhythmia-2025]])
- **Mosaicism — >70% correction threshold for structural disease:** In vivo cardiac gene editing produces heterogeneous transduction — cells in lower-penetration regions remain unedited. In structural cardiac conditions (DMD, ARVC), >70% phenotypic correction is required to restore function. Below this threshold:
  - Heterogeneous electrophysiological properties between edited/unedited cells → arrhythmia risk
  - Maladaptation in partially corrected tissue → compensatory fibrosis
  - Partially edited cells may express neoantigens → enhanced immunogenicity
  - In DMD and ARVC specifically, sub-threshold mosaicism has caused myofiber necrosis and fibrosis ([[sources/gene-editing-cv-tcm-2025]])
- **Episomal dilution in paediatric patients:** AAV remains primarily episomal. In growing paediatric patients, cardiomyocyte division dilutes episomal transgene copies over time — durability of childhood-administered therapy is uncertain, and re-treatment is blocked by pre-existing immunity. ([[sources/gene-therapy-arrhythmia-2025]])
- **Integration risk:** Rare genomic integration events have been reported despite AAV's predominantly episomal persistence — theoretical insertional mutagenesis risk requiring long-term follow-up. ([[sources/gene-therapy-arrhythmia-2025]])
- **Human translation gap:** AAV9 cardiac tropism is established in mice but human myocardium transduction efficiency is not explicitly confirmed. Human anatomical scale, receptor expression variation, active disease states, and antibody prevalence are all proposed to reduce efficacy. Sex, age, delivery route, and dose independently influence AAV performance — all require characterisation before human application. ([[sources/gene-editing-cv-tcm-2025]])

### Preclinical Efficacy Data

- **Meta-analysis (26 studies, search to Jan 2024):** AAV gene therapy reduced AF inducibility by **81%** (OR 0.19, 95% CI 0.08–0.45; I²=0%; p<0.01) and combined VA inducibility by **94%** (OR 0.06, 95% CI 0.03–0.11; I²=27.3%; p<0.01). Inherited VA: 96% reduction; acquired VA: 89%. Low heterogeneity in the AF analysis (I²=0%) suggests consistent effect across diverse molecular targets. ([[sources/aav-gene-therapy-arrhythmia-hr-2024]], rating: medium)
- **Publication bias:** No study in the 2024 systematic review reported a failure of AAV-mediated gene therapy. Funnel plots trend symmetric but n=26 is insufficient to exclude bias definitively. The consistently positive ORs almost certainly overestimate true effect size. ([[sources/aav-gene-therapy-arrhythmia-hr-2024]])
- **LQT3 base editing — 20% correction sufficient:** AAV9 dual-vector adenine base editing of SCN5A p.T1307M at ~20% editing efficiency prevented fatal arrhythmias in mice — substantially below the >70% structural correction threshold. Mechanism: electrotonic coupling spreads electrophysiological benefit from edited cells to adjacent unedited cells, a population-level effect not available for structural protein repair. ([[sources/aav-gene-therapy-arrhythmia-hr-2024]])

### Gene Targets by Disease

- **AF targets (7, all preclinical):** SERCA2a (Ca²⁺ cycling, intrapericardial delivery, rabbit), TASK-1 (K⁺ channel silencing, pig — strongest translational model), NLRP3 (inflammasome knockdown, cardiomyocyte-specific), miR-27b (Smad-2/3 anti-fibrotic pathway), IGF1 (atrial fibrosis inhibition), Myl4 (familial AF gene replacement), SIRT3 (alcohol-AF pathway via SIRT3-AMPK and mitochondrial dynamics). All address AF *prevention* — treatment of established persistent/permanent AF has not been tested. ([[sources/aav-gene-therapy-arrhythmia-hr-2024]])
- **Acquired VA targets (4, all preclinical):** TBX5 (transcription factor restoration post-DCM/ischaemia); dystrophin activation via CRISPR/dCas9 (restored Nav1.5 membrane localisation → normalised conduction); adiponectin overexpression in left stellate ganglion (inhibited post-MI neural activity — potential non-surgical sympathectomy alternative); SERCA2a (post-MI electrophysiological improvement, AAV1, pig). ([[sources/aav-gene-therapy-arrhythmia-hr-2024]])
- **Inherited VA targets (15 studies, CPVT/ACM/PRKAG2/BrS/LQT3):**
  - *CPVT:* CASQ2 replacement (single injection → curative ≥1 year); triadin replacement; allele-specific RYR2 silencing; CRISPR-SaCas9 RYR2-R4496C; engineered CaM protein; CaMKII inhibitory peptide (note: 10% QTc prolongation under β-agonist stimulation — proarrhythmic signal).
  - *ACM:* PKP2 replacement (only arrhythmia target in clinical trial); PLN-R14del CRISPR; GJA1-20k (Cx43 trafficking); BAG5.
  - *PRKAG2 syndrome:* CRISPR correction at postnatal day 4 and 42 → 2× reduction in ventricular preexcitation.
  - *BrS:* MOG1 (Nav1.5 chaperone) — pathway workaround for SCN5A size constraint.
  - *LQT3:* SCN5A p.T1307M adenine base editing — 20% efficiency sufficient (see above). ([[sources/aav-gene-therapy-arrhythmia-hr-2024]])

### Clinical Translation

- **Only PKP2 has reached clinical trial for arrhythmia (as of Jan 2024):** Among 22 identified molecular targets, PKP2 gene replacement (ACM — LEXEO/Rocket trial) is the sole arrhythmia target in a clinical trial. SERCA2a entered clinical trial (AskBio Phase 1) for heart failure — not arrhythmia. All remaining 20 targets are preclinical. ([[sources/aav-gene-therapy-arrhythmia-hr-2024]])
- **Future directions:** Next-generation cardiotropic capsids with enhanced cardiac specificity; antibody-oligonucleotide conjugates; image-guided and magnetically guided delivery systems; extracellular vesicle-shielded vectors to evade pre-existing immunity. ([[sources/gene-therapy-arrhythmia-2025]])

## Contradictions / Open Questions

- **IV vs. intracoronary route — no head-to-head data:** Intravenous delivery offers the lowest procedural risk but produces significant off-target liver transduction and lower cardiac uptake. Intracoronary delivery improves cardiac specificity but requires cath lab access and is less effective with coronary disease. No head-to-head RCT defines the optimal route for any cardiac gene therapy indication; route choice is extrapolated from animal studies and manufacturing constraints. ([[sources/gene-therapy-arrhythmia-2025]])
- **Re-dosing prevented by immune responses:** Anti-AAV neutralising antibodies preclude re-dosing with the same serotype. For chronic cardiac diseases (HCM, LMNA cardiomyopathy) requiring durability beyond 5–10 years, the single-dose constraint is a major unresolved barrier. Capsid re-engineering and extracellular vesicle shielding are proposed but unvalidated in humans. ([[sources/gene-therapy-arrhythmia-2025]])
- **Episomal dilution vs. re-dosing impossibility in paediatrics:** Childhood-administered AAV therapy will be progressively diluted as cardiomyocytes expand, yet pre-existing immunity prevents re-treatment. This creates a therapeutic catch-22 specific to paediatric channelopathies. ([[sources/gene-therapy-arrhythmia-2025]])
- **Publication bias inflates preclinical effect sizes:** No study in the 2024 systematic review reported failure. The OR 0.06 for combined VA inducibility almost certainly overestimates clinical translation readiness. This makes it difficult to identify which of the 22 targets are genuinely promising versus artefactually positive. ([[sources/aav-gene-therapy-arrhythmia-hr-2024]], rating: medium)
- **Editing efficiency threshold discrepancy — 20% vs. >70%:** Base editing of SCN5A p.T1307M at 20% efficiency prevented fatal LQT3 arrhythmias (Qi 2024), conflicting with the >70% structural correction threshold in DMD and ARVC. The most likely explanation is disease-specific: electrophysiological rescue is a population-level emergent property (electrotonic coupling spreads benefit to neighbouring unedited cells), whereas structural repair requires per-cell correction. This distinction has direct implications for which diseases are tractable with lower editing efficiency. ([[sources/aav-gene-therapy-arrhythmia-hr-2024]], [[sources/gene-editing-cv-tcm-2025]])

## Connections
- Related to [[concepts/SupRep-Therapy]]
- Related to [[concepts/Gene-Silencing-Therapy]]
- Related to [[concepts/CRISPR-Cas9-in-Channelopathies]]
- Related to [[concepts/Gene-Editing-Risk-Benefit-Framework]]
- Related to [[concepts/Epigenetics-Cardiac-Arrhythmia]]
- Related to [[entities/CPVT]]
- Related to [[entities/Long-QT-Syndrome]]
- Related to [[entities/Brugada-Syndrome]]
- Related to [[entities/ARVC]]
- Related to [[entities/RYR2]]
- Related to [[entities/SCN5A]]

## Sources
- [[sources/gene-therapy-arrhythmia-2025]]
- [[sources/gene-editing-cv-tcm-2025]]
- [[sources/aav-gene-therapy-arrhythmia-hr-2024]]
