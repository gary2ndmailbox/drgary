---
dg-publish: true
title: "Long Noncoding RNA in CVD"
tags: [lncRNA, noncoding-RNA, cardiac-hypertrophy, atherosclerosis, RNA-therapeutics]
source_count: 1
last_updated: 2026-04-29
---

# Long Noncoding RNA in CVD

## Definition
Long noncoding RNAs (lncRNAs) are RNA transcripts >200 nt that share many features of mRNAs (transcribed by RNA Pol II, 5'-capped, polyadenylated, spliced) but are not translated into protein. The human genome may contain >30,000 lncRNAs, with expression typically lower and less conserved than mRNAs. ([[sources/noncoding-rna-aha-2020]] — high)

## Key Concepts

### Classification
- **By genomic location:** lincRNA (intergenic), intronic, eRNA (enhancer RNA), AS-lncRNA (antisense) ([[sources/noncoding-rna-aha-2020]] — high)
- **By function:** guides (direct chromatin modifiers to DNA), scaffolds (tether protein complexes), decoys (bind proteins/miRNAs to block targets), ceRNAs (competing endogenous RNAs — sponge miRNAs)
- **cis vs. trans:** cis-acting lncRNAs regulate nearby genes; trans-acting lncRNAs function at distal loci; many lncRNAs are multifunctional and defy single classification
- HUGO nomenclature (2014): function-based names; antisense = suffix _AS_; intronic = _IT_; intergenic = _LINC_ prefix

### CVD Risk Loci lncRNAs
- **ANRIL** (antisense ncRNA in the INK4 locus at 9p21): scaffold regulating CDKN2a/B expression; certain variants circularise and take on atherogenic function; ANRIL variants correlate with stroke risk (9p21.3 locus). ([[sources/noncoding-rna-aha-2020]] — high)
- **MIAT** (myocardial infarction–associated transcript): variant associated with MI risk; higher expression → poor prognosis in ischemic stroke (independent prognostic marker for functional outcome and death); ceRNA binding miR-150-5p to regulate endothelial function. ([[sources/noncoding-rna-aha-2020]] — high)
- **H19**: variant increases IGF2 expression and CAD risk; stabilises SREBP-1c (hepatic lipogenesis); ceRNA binding let-7 to inhibit muscle differentiation; regulates aortic aneurysm and endothelial cell aging. ([[sources/noncoding-rna-aha-2020]] — high)

### Lipid and Cardiometabolic Roles
- **MALAT1:** stabilises SREBP-1c (lipogenesis); regulates angiogenesis; contributes to diabetic retinopathy and atherosclerosis; may protect against ischemic stroke by inhibiting proapoptotic proteins and proinflammatory cytokines. ([[sources/noncoding-rna-aha-2020]] — high)
- **LeXis** (liver-expressed LXR-induced): LXR induces; reduces cholesterol synthesis by blocking RNA Pol II recruitment to _Srebf2_ and its targets. ([[sources/noncoding-rna-aha-2020]] — high)
- **MeXis** (macrophage-expressed LXR-induced): LXR induces; acts in cis to promote ABCA1 cholesterol efflux by guiding helicase DDX17 to the _Abca1_ promoter. ([[sources/noncoding-rna-aha-2020]] — high)
- **APOA1-AS / APOA4-AS**: antisense lncRNAs in the apolipoprotein gene cluster; APOA1-AS represses _APOA1_ via PRC2-mediated chromatin silencing; APOA4-AS stabilises _APOA4_ mRNA via HuR binding. ([[sources/noncoding-rna-aha-2020]] — high)
- **CHROME** (macrophage): ceRNA binding miR-27b, -33a, -33b, -128 to regulate cholesterol efflux and HDL formation. ([[sources/noncoding-rna-aha-2020]] — high)

### Vascular Biology
- PUNISHER (AGAP2-AS1), MEG3, GATA6-AS: regulate vessel formation/angiogenesis. ([[sources/noncoding-rna-aha-2020]] — high)
- LincRNA-p21: restricts smooth muscle cell proliferation; downregulated in mouse and human atherosclerosis

### Cardiac Hypertrophy and Heart Failure
- **Mhrt/MHRT:** cardiac-specific; expressed in adult heart; regulates _Myh6_, _Myh7_, osteopontin via Brg1 chromatin remodeling factor; repressed during pressure overload–induced hypertrophy; restoring expression is cardioprotective in mice; MHRT levels proposed as HF biomarker. ([[sources/noncoding-rna-aha-2020]] — high)
- **Chast:** upregulated in pressure overload hypertrophy in mice and humans; impedes cardiomyocyte autophagy by negatively regulating Plekhm1; silencing attenuates pathological remodeling. ([[sources/noncoding-rna-aha-2020]] — high)
- **Chaer:** interacts with catalytic subunit of PRC2 to alter epigenetic reprogramming at hypertrophy gene promoters; silencing attenuates pathological remodeling and dysfunction. ([[sources/noncoding-rna-aha-2020]] — high)
- Both Chast and Chaer act via different mechanisms but silencing either is sufficient for cardioprotection — suggests multiple independent lncRNA pathways regulate hypertrophic remodeling

### Stroke
- Broadly dysregulated lncRNA expression in ischemic stroke whole blood (vs. control); some differentially expressed lncRNAs in proximity to stroke-risk genes. ([[sources/noncoding-rna-aha-2020]] — high)
- Most highly upregulated after oxygen-glucose deprivation in brain microvascular endothelium: Snhg12, Malat1, lnc-OGD 1006
- Malat1 may protect against ischemic injury by inhibiting proapoptotic proteins and proinflammatory cytokines
- Proposed lncRNA mechanisms in ischemic brain injury: epigenetic transcriptional regulation, miRNA modulation, translational repression

### Investigational Tools
- **Expression profiling:** RNA-seq (require sufficient depth for low-abundance lncRNAs); cap-assisted gene expression sequencing; global run-on sequencing for nascent transcription. ([[sources/noncoding-rna-aha-2020]] — high)
- **Loss-of-function:** ASOs/Gapmers (no genomic engineering; limited by secondary structure); CRISPRi (catalytically inactive Cas9); CRISPR/Cas9 deletion (requires large genomic deletion — often >1 kb); early poly(A) insertion to halt transcription
- **Gain-of-function:** ectopic expression (not amenable for cis-acting lncRNAs); CRISPRa
- **Interactome:** ChIRP (chromatin isolation by RNA purification) + mass spec/RNA-seq/DNA-seq; RNA antisense purification; CLIP (cross-linking immunoprecipitation)
- **Localisation:** single-molecule RNA-FISH; digital droplet PCR for copy number
- Nuclear lncRNAs may be resistant to siRNA/shRNA approaches; cis-acting lncRNAs cannot be studied by ectopic overexpression — complementary approaches essential

### ceRNA Validation Requirements
For a valid lncRNA ceRNA claim, evidence required: (1) coprecipitation of lncRNA-miRNA; (2) miRNA target derepression upon lncRNA deletion/depletion; (3) loss of sponging activity upon mutation of miRNA binding sites. ([[sources/noncoding-rna-aha-2020]] — high)

## Contradictions / Open Questions
- **ceRNA stoichiometry controversy:** A functional ceRNA requires the lncRNA to be present at sufficient copy numbers to compete with miRNA targets. Most reports do not formally validate stoichiometry — many putative ceRNA claims are likely not physiologically relevant. ([[sources/noncoding-rna-aha-2020]] — high)
- **Micropeptide boundary:** Up to 20% of lncRNAs in the human heart encode micropeptides — several established lncRNAs (DANCR, TUG1, JPX, myheart, UPPERHAND) have now been shown to also code for microproteins, blurring the functional definition. ([[sources/noncoding-rna-aha-2020]] — high)
- **lncRNA delivery challenge:** Large RNA size makes lncRNA delivery via AAV or lipid nanoparticles extremely difficult; no clinical-stage lncRNA therapeutic exists. This stands in contrast to siRNA/ASO therapeutics that are now FDA-approved. ([[sources/noncoding-rna-aha-2020]] — high)

## Connections
- Related to [[concepts/Noncoding-RNA-in-CVD]]
- Related to [[concepts/Gene-Silencing-Therapy]]
- Related to [[concepts/AAV-Gene-Delivery]]
- Related to [[entities/HCM]] — Mhrt/MHRT in pressure overload hypertrophy
- Related to [[entities/Heart-Failure]] — Mhrt, Chast, Chaer in cardiac remodeling
- Related to [[entities/Atrial-Fibrillation]] — ANRIL 9p21 locus
- Related to [[concepts/Lipoprotein-a]] — CHROME, LeXis, MeXis in cholesterol regulation
