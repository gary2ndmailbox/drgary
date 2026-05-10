---
dg-publish: true
title: "RYR2"
tags: [genetics, calcium-handling, channelopathies, CPVT, RYR2, ryanodine-receptor, variant-interpretation, sudden-cardiac-death]
source_count: 7
last_updated: 2026-05-09
---

# RYR2 (Ryanodine Receptor 2)

## Details
RYR2 encodes ryanodine receptor 2 (RyR2), the primary sarcoplasmic reticulum Ca²⁺ release channel in cardiomyocytes. Located on chromosome 1q42–q43, gain-of-function mutations are the predominant genetic cause of catecholaminergic polymorphic ventricular tachycardia (CPVT1), accounting for 60–70% of all CPVT cases. The same gene also produces a distinct loss-of-function phenotype — Ca²⁺ Release Deficiency Syndrome (CRDS) — with rest-triggered arrhythmias rather than exercise-triggered arrhythmias. At ~15,000 nt, RYR2 far exceeds AAV packaging capacity, making direct gene replacement infeasible with current vectors.

## Key Facts

### Gene & Channel Complex
- RyR2 is the primary SR Ca²⁺ release channel; it forms the calcium release unit together with calsequestrin-2 (CASQ2, main Ca²⁺ buffer), juntin (ASPH), and triadin (TRDN). CASQ2 mutations indirectly destabilise the RYR2-mediated release unit. ([[sources/channelopathies-jaha-2025]], rating: high)
- RYR2 mutations are typically missense variants producing autosomal dominant inheritance. ([[sources/channelopathies-jaha-2025]])
- ClinGen definitive genes for CPVT: RYR2 (~50–60% of CPVT cases), CASQ2 (~5%, autosomal recessive), TECRL, and TRDN. ([[sources/arrhythmia-genetics-mgenetik-2025]], rating: high)

### CPVT1: Pathophysiology
- **Gain-of-function mechanism:** Hyperactive RyR2 channels. During adrenergic stimulation (exercise/emotion), excessive Ca²⁺ accumulates in the SR, followed by spontaneous diastolic Ca²⁺ release → delayed afterdepolarizations (DADs) → triggered ventricular arrhythmias. ([[sources/channelopathies-jaha-2025]])
- The characteristic arrhythmia is bidirectional VT — beat-to-beat 180° QRS axis alternation — pathognomonic for CPVT. ([[sources/channelopathies-jaha-2025]])
- RYR2 is also listed among genes associated with idiopathic ventricular fibrillation (IVF), though IVF and CPVT differ in trigger (R-on-T PVCs at rest vs. exercise-induced DADs) and distinct from the DPP6 haplotype biomarker associated with IVF. ([[sources/channelopathies-jaha-2025]])

### CRDS: Loss-of-Function RYR2 Spectrum
- **Ca²⁺ Release Deficiency Syndrome (CRDS):** Caused by RYR2 *loss-of-function* variants → reduced Ca²⁺ release rather than the excessive release of CPVT1. CRDS presents with short-coupled ventricular torsades-de-pointes at rest (not exercise-induced). RYR2 exon 3 deletion has been associated with LVNC and atypical CPVT overlap. Formally established as a novel phenotypic spectrum (Steinberg et al., Europace 2023). ([[sources/arrhythmia-genetics-mgenetik-2025]])
- RYR2 thus spans a gain-of-function (CPVT) and loss-of-function (CRDS) phenotypic spectrum — analogous to SCN5A causing LQT3 (GOF) and Brugada syndrome (LOF). Functional characterisation of variant direction is clinically essential before management decisions. ([[sources/arrhythmia-genetics-mgenetik-2025]])

### Variant Landscape — Chang 2025 Database
- Systematic review of 221 publications catalogued **263 unique RYR2 protein-coding variants in 964 CPVT patients** — the largest compilation to date. 76.43% of variants reported in ≤3 patients each. ([[sources/RYR2-CPVT-CircEP-2025]], rating: very high)
- **Four historical hotspot regions** contain 77.13% of variants: Hotspot I (exons 3–15), II (44–50), III (83–90), IV (93–105). Authors propose adding exons 37 and 42 to hotspot II based on clustering data. ([[sources/RYR2-CPVT-CircEP-2025]])
- Publicly accessible web app: **markslab-cpvtdb.org** — queryable by phenotype, age of onset, and variant location with 3D structural visualisation via Mol* Viewer (cryo-EM structure PDB 7UA5). ([[sources/RYR2-CPVT-CircEP-2025]])

### Domain Architecture & Age of Onset
- Age of onset differs significantly by RyR2 structural domain (median, IQR): ([[sources/RYR2-CPVT-CircEP-2025]])
  - **Core solenoid (CSol):** 8 years (IQR 6–14, P=0.001 vs other domains). CSol is a signal transduction hub connecting regulatory cytoplasmic domains to the transmembrane pore — mutations here cause the earliest onset.
  - **CSol(exEF-hand) subdomain:** 8 years (IQR 6–13, P<0.001 vs other subdomains) — lowest median among all subdomains.
  - **Channel pore subdomain:** 8 years (P=0.019 vs other subdomains) — direct intrinsic pore function role.
  - **N-terminal domain (NTD):** 12 years (IQR 9–16, P=0.006 vs other domains) — furthest hotspot from the pore, less direct allosteric influence, later onset.
  - **EF-hand subdomain:** 28 years (P=0.187, NS) — minor role in channel opening; primary role in Ca²⁺ release termination.

### Structural Mechanisms of Exemplar Variants
- **p.G357S** — glycine stabilises a β-turn secondary structure in NTD-B; substitution disrupts the NTD-B–CSol interaction. ([[sources/RYR2-CPVT-CircEP-2025]])
- **p.R420Q vs p.R420W** — both disrupt an interaction network centred on R420 between the N-terminal solenoid and NTD-B. Q420 induces larger conformational changes than W420, correlating with significantly earlier onset (10y vs 18.5y, P=0.012). The same residue, different substitute → meaningfully different phenotypes. ([[sources/RYR2-CPVT-CircEP-2025]])
- **p.S2246L** — large hydrophobic leucine replaces small polar serine, introducing steric impediments that increase domain flexibility. ([[sources/RYR2-CPVT-CircEP-2025]])
- All three mechanisms converge on loss of inter-domain interactions and increased channel flexibility → leaky channels confirmed by single-channel Ca²⁺ imaging and knock-in mouse models. ([[sources/RYR2-CPVT-CircEP-2025]])

### Variant-Specific Treatment Response
- β-blocker effectiveness varies significantly by variant: p.G2337V 10/11 effective vs p.R420W 5/17 (P=0.031) and p.C2277R 2/8 (P=0.047). ([[sources/RYR2-CPVT-CircEP-2025]])
- Flecainide addition (post-2013 data): p.S2246L 3/4, p.R420W 7/9, p.C2277R 6/8 vs p.G357S 0/91 and p.G2337V 0/21 — suggesting flecainide is ineffective for some variants. ([[sources/RYR2-CPVT-CircEP-2025]])
- ICD implantation rates also differ: p.S2246L 7/9, p.R420Q 13/24 vs p.G357S 1/94. ([[sources/RYR2-CPVT-CircEP-2025]])
- At the same residue, p.R420W required significantly more flecainide and beta-blocker combinations than p.R420Q (P=0.008). ([[sources/RYR2-CPVT-CircEP-2025]])
- These data support variant-specific personalised therapy rather than uniform CPVT treatment protocols, though individual sample sizes remain small. ([[sources/RYR2-CPVT-CircEP-2025]])

### Management
- **Beta-blockers:** First-line; non-selective agents (nadolol, propranolol) preferred. Efficacy varies by variant (see above). ([[sources/channelopathies-jaha-2025]])
- **Flecainide:** Adjunct therapy; class IC agent added when beta-blockers alone are insufficient (~30% of patients). Preclinical mechanism: open-state blockade of RyR2 Ca2+ release channels (Hilliard 2010) reduces spark Ca2+ mass without causing compensatory SR Ca2+ loading, preventing diastolic Ca2+ waves that drive DAD-triggered arrhythmias. Whether clinical efficacy is primarily via this RyR2 mechanism or via Na+ channel blockade remains unresolved (see Contradictions). Variant-specific response: effective in p.R420W, p.S2246L, p.C2277R; appears ineffective in p.G357S and p.G2337V in registry data. ([[sources/RYR2-CPVT-CircEP-2025]], rating: very high; [[sources/channelopathies-jaha-2025]], rating: high; [[sources/flecainide-af-europace-2011]], rating: medium)
- **ICD:** Indicated after resuscitated cardiac arrest or breakthrough arrhythmia on maximally tolerated therapy. Implantation rate varies substantially by variant. ([[sources/RYR2-CPVT-CircEP-2025]])
- **Left cardiac sympathetic denervation (LCSD):** Option for patients with breakthrough events on medical therapy or who decline ICD. ([[sources/channelopathies-jaha-2025]])
- See [[entities/CPVT]] for full management algorithm including epinephrine provocation testing and exercise stress testing protocol.

### RYR2 Beyond CPVT
- **HCM arrhythmogenesis:** RyR2 hyperphosphorylation at CaMKII-sensitive sites (secondary to Ca²⁺ overload from sarcomere mutations) → increased RyR2 opening probability → spontaneous SR Ca²⁺ release → EADs/DADs → ventricular arrhythmia. Confirmed in human HCM specimens and mouse models. ([[sources/HCM-VA-FCVMed-2022]], rating: high)
- **MYBPC3–RyR2 interaction:** RyR2 may interact directly with MYBPC3; sarcomere mutation or conformational change disrupts this interaction → altered intracellular Ca²⁺ homeostasis. ([[sources/HCM-VA-FCVMed-2022]])
- **RYR2-P1124L in apparent genotype-negative HCM:** This variant increases RyR2 Ca²⁺ sensitivity → arrhythmia + secondary structural cardiac remodelling in patients negative for classical HCM sarcomere genes. ([[sources/HCM-VA-FCVMed-2022]])
- **Early-onset AF:** RYR2 was among the most common VUS-bearing genes (66 VUSs) in 1,293 patients with EOAF undergoing WGS. RYR2 GOF is the primary CPVT cause; a VUS requires anticipatory genetic counselling to contextualise uncertainty without causing inappropriate clinical anxiety. ([[sources/eoaf-jama-2021]], rating: high)

### ClinGen Gene-Disease Validity — RYR2
- **CPVT (Definitive, 01/20/2021):** RYR2 gain-of-function variants have definitive gene-disease validity for CPVT — the highest ClinGen classification. This is the canonical RYR2 disease association. ([[sources/clingen-summary-2026-05-09]], rating: high; ClinGen classification date: 01/20/2021)
- **ARVC (Refuting, 07/19/2019):** ClinGen explicitly refutes RYR2 as a cause of ARVC. Early reports of RYR2 variants in ARVC patients have been re-evaluated and determined to be insufficient — the ARVC phenotype in RYR2-variant carriers likely reflects exercise-induced CPVT (which can mimic ARVC with RV stress) rather than true desmosomal/structural ARVC. Clinicians should not interpret an RYR2 variant on an ARVC panel as supporting an ARVC diagnosis. ([[sources/clingen-summary-2026-05-09]], rating: high; ClinGen classification date: 07/19/2019)
- **HCM (Limited, 12/14/2022):** ClinGen classifies RYR2 as Limited evidence for HCM — only a few case reports/small series link RYR2 to a primary HCM phenotype. Variants in RYR2 found in apparent HCM patients may reflect secondary structural remodelling from RyR2-mediated Ca²⁺ dysregulation (as with RYR2-P1124L) rather than classic sarcomere-driven HCM. ([[sources/clingen-summary-2026-05-09]], rating: high; ClinGen classification date: 12/14/2022)
- **DCM (Limited, 01/10/2025):** ClinGen classifies RYR2 as Limited evidence for DCM. Only a small number of reports link RYR2 loss-of-function to a dilated cardiomyopathy phenotype. Variants in RYR2 on DCM panels should not be classified P/LP for DCM without additional functional evidence or strong co-segregation. ([[sources/clingen-summary-2026-05-09]], rating: high; ClinGen classification date: 01/10/2025)

### Gene Therapy
- **Size constraint:** RYR2 coding sequence ~15,000 nt far exceeds standard AAV packaging capacity (~4.7 kb) — direct gene replacement is infeasible with current vectors. ([[sources/gene-therapy-arrhythmia-2025]], rating: high)
- **CRISPR-SaCas9 (AAV9):** Targeting RYR2-R4496C achieved ~41% editing efficiency in cardiomyocytes; 0/7 treated vs. 7/8 control mice had arrhythmias — first in-vivo demonstration of safe CRISPR-mediated RYR2 repair (Pan 2023). ([[sources/gene-therapy-arrhythmia-2025]])
- **Allele-specific silencing (siRNA/shRNA):** Suppressed mutant Ryr2 in mice; also restored junctional SR and T-tubular ultrastructure. ([[sources/gene-therapy-arrhythmia-2025]])
- **Pathway-targeted alternatives (bypass RYR2 size constraint):**
  - CASQ2 overexpression suppresses arrhythmias in RYR2-CPVT1
  - CaMKII inhibitory peptide (AIP) via AAV9 normalises Ca²⁺ handling
  - Modified calmodulin delivery increases RYR2 channel refractoriness
- ([[sources/gene-therapy-arrhythmia-2025]])

## Contradictions / Open Questions
- **CRISPR-SaCas9 41% editing efficiency — sufficient preclinically, untested in humans:** Pan 2023 demonstrated 41% cardiomyocyte editing efficiency and complete arrhythmia suppression in mice. The editing efficiency threshold for arrhythmia prevention in humans is unknown. Off-target editing safety in non-dividing human cardiomyocytes over decades has not been assessed. The mouse result establishes proof-of-concept but cannot be extrapolated to predict human therapeutic safety or efficacy. ([[sources/gene-therapy-arrhythmia-2025]])
- **Dantrolene — theoretical RYR2 relevance without human CPVT trial data:** Dantrolene inhibits RYR1 (skeletal muscle) for malignant hyperthermia and has theoretical applicability to RYR2-mediated CPVT given structural homology. However, no human CPVT trial data exist, and cardiac side effects (negative inotropy, hypotension) limit feasibility in symptomatic CPVT. ([[sources/channelopathies-jaha-2025]])
- **CRDS vs. CPVT — opposite phenotypes, same gene:** RYR2 gain-of-function (CPVT: exercise-induced DAD-triggered arrhythmias) and loss-of-function (CRDS: short-coupled rest arrhythmias) produce opposite arrhythmia triggers and likely require different treatments. As with SCN5A, functional characterisation of variant direction is essential before prescribing — yet most clinical laboratories do not routinely provide this assessment, and variant direction cannot be inferred from variant location alone. ([[sources/arrhythmia-genetics-mgenetik-2025]])
- **ClinGen refutes RYR2 in ARVC (07/19/2019) — clinical implication:** RYR2 variants found on ARVC multi-gene panels should not be used to support an ARVC diagnosis. The refuting ClinGen classification post-dates many panel designs — laboratories may still include RYR2 on ARVC panels, and variant reports may not explicitly flag the refuting status. Clinicians should verify ClinGen classification for RYR2 before attributing an ARVC phenotype to an RYR2 variant. If CPVT-mimicking ARVC is clinically suspected, exercise testing (bidirectional VT induction, not structural criteria) is the appropriate diagnostic test. ([[sources/clingen-summary-2026-05-09]], rating: high)
- **RYR2-P1124L in "genotype-negative HCM" — category blurring:** This variant causes arrhythmia and secondary structural remodelling resembling HCM in patients negative for classical sarcomere gene mutations, raising the question of whether some "genotype-negative HCM" patients actually have a calcium-channel arrhythmogenic disease — with management implications if HCM-specific risk calculators (HCM Risk-SCD) are applied to this group. ([[sources/HCM-VA-FCVMed-2022]])
- **Variant-specific treatment response — biological plausibility vs. small sample sizes:** Chang 2025 demonstrates statistically significant differences in beta-blocker efficacy, flecainide usage, and ICD implantation across specific RYR2 variants. However, individual variant sample sizes range from 4–91 patients per variant, and flecainide comparisons include as few as 4 patients per group. The data strongly suggest variant-specific treatment responses exist, but are insufficient to drive clinical guidelines — a tension between compelling biological plausibility and inadequate statistical power. ([[sources/RYR2-CPVT-CircEP-2025]])

## Connections
- Related to [[entities/CPVT]]
- Related to [[concepts/Ion-Channel-Mutations]]
- Related to [[concepts/Bidirectional-Ventricular-Tachycardia]]
- Related to [[concepts/CRISPR-Cas9-in-Channelopathies]]
- Related to [[concepts/Calcium-Homeostasis-in-HCM]]
- Related to [[concepts/Early-Onset-Atrial-Fibrillation]]
- Related to [[entities/Idiopathic-Ventricular-Fibrillation]]
- Related to [[entities/HCM]]
- Related to [[entities/MYBPC3]]
- Related to [[sources/RYR2-CPVT-CircEP-2025]]
- Related to [[sources/channelopathies-jaha-2025]]
- Related to [[sources/arrhythmia-genetics-mgenetik-2025]]
- Related to [[sources/gene-therapy-arrhythmia-2025]]
- Related to [[sources/eoaf-jama-2021]]
- Related to [[sources/HCM-VA-FCVMed-2022]]
- Related to [[entities/Flecainide]]
- Related to [[sources/flecainide-af-europace-2011]]
- Related to [[concepts/ClinGen-Gene-Disease-Validity]]
- Related to [[sources/clingen-summary-2026-05-09]]

## Sources
- [[sources/HCM-VA-FCVMed-2022]]
- [[sources/RYR2-CPVT-CircEP-2025]]
- [[sources/arrhythmia-genetics-mgenetik-2025]]
- [[sources/channelopathies-jaha-2025]]
- [[sources/clingen-summary-2026-05-09]]
- [[sources/eoaf-jama-2021]]
- [[sources/flecainide-af-europace-2011]]
- [[sources/gene-therapy-arrhythmia-2025]]
