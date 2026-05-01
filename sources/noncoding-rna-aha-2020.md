---
dg-publish: true
title: "Noncoding RNAs in Cardiovascular Disease: Current Knowledge, Tools and Technologies for Investigation, and Future Directions"
date_ingested: 2026-04-29
source_type: review article
Citation: "Das S, Shah R, Dimmeler S, et al.; on behalf of the American Heart Association. Noncoding RNAs in cardiovascular disease: current knowledge, tools and technologies for investigation, and future directions. Circ Genom Precis Med. 2020;13:e000062."
DOI: "https://doi.org/10.1161/HCG.0000000000000062"
tags: [noncoding-RNA, microRNA, lncRNA, RNA-therapeutics, extracellular-RNA]
rating: high
raw_path: raw/Noncoding-RNA-AHA-2020.md
---

# Noncoding RNAs in Cardiovascular Disease

## Authors, Journal, Affiliations, Type, DOI
- **Authors:** Saumya Das (Chair), Ravi Shah (Co-chair), Stefanie Dimmeler, Jane E. Freedman, Christopher Holley, Jin-Moo Lee, Kathryn Moore, Kiran Musunuru, Da-Zhi Wang, Junjie Xiao, Ke-Jie Yin; on behalf of AHA Council on Genomic and Precision Medicine
- **Journal:** Circulation: Genomic and Precision Medicine
- **Date:** August 2020
- **Type:** AHA Scientific Statement (systematic review + expert consensus)
- **DOI:** 10.1161/HCG.0000000000000062

## Overview
This AHA Scientific Statement provides a comprehensive synthesis of all major noncoding RNA (ncRNA) classes and their roles in cardiovascular disease as of 2018. It covers miRNAs, snoRNAs, Y-RNAs, tRNA-derived fragments, long noncoding RNAs (lncRNAs), circular RNAs (circRNAs), and extracellular RNAs (exRNAs), alongside computational tools and experimental methodologies for studying each class. Key translational highlights include the clinical-stage siRNA inclisiran (PCSK9-targeting), anti-miR approaches to cardiac remodeling, and exRNAs as circulating biomarkers. The authors emphasise that methodological heterogeneity and annotation gaps remain major barriers to clinical translation, and that network-level approaches (rather than single-RNA studies) are needed to understand complex RNA–RNA interactions in disease.

## Keywords
AHA Scientific Statements, cardiovascular diseases, microRNAs, RNA long noncoding, RNA small nucleolar, RNA untranslated

## Key Takeaways

### Computational Tools and Databases
- RNA-seq provides unprecedented transcriptome depth but creates annotation challenges; short reads (≤200 bp) map to sncRNA; longer reads to mRNA and lncRNAs
- Key databases: miRbase (miRNAs), gtRNAdb (tRNAs), piRNABank, GENCODE, UCSC for snoRNA/snRNA; frequent version updates complicate reproducibility
- RNA-binding protein databases (ATtRACT, RBPDB) enable search for protein–RNA interactions
- Multi-omics integration (genomics + transcriptomics + proteomics) is possible but challenged by heterogeneous experimental approaches; longitudinal personal omics pioneered in single individuals

### Small Noncoding RNAs: MicroRNAs (miRNA)
- miRNAs are 17–22 nt ncRNAs that decrease target gene expression by altering mRNA stability or translation via the RISC complex
- Biogenesis: pri-miRNA (RNA Pol II) → pre-miRNA (~70 nt, Microprocessor) → cytoplasm export → Dicer cleavage → ~22 nt mature miRNA incorporated into RISC
- One miRNA can target hundreds of genes; one gene can be targeted by multiple miRNAs — supports key regulatory roles in cardiac development, physiology, and disease
- Therapeutic modulation: anti-miRs, antagomiRs (cholesterol-conjugated), LNA-anti-miRs; catheter-based intracoronary delivery enhances cardiac targeting; major challenges are organ-specific delivery and off-target effects

### Small Noncoding RNAs: snoRNAs
- snoRNAs (60–200 nt) reside in the nucleolus and primarily guide rRNA/snRNA modifications; >200 well-defined snoRNAs with hundreds more predicted
- Box C/D snoRNAs (SNORDs) guide 2'-O-methylation; Box H/ACA snoRNAs (SNORAs) guide pseudouridylation
- Cardiometabolic: _Rpl13a_ locus snoRNAs regulate oxidative stress and diabetes; _Snord32A_ targets peroxidasin mRNA to alter cardiac reactive oxygen species; _Snora73_ regulates cholesterol homeostasis via _Hummr_
- Stroke/CHD: 6 miRNAs and 1 snoRNA (SNO1402) associated with prevalent stroke in FHS (n=2763); no clear functional connection established
- Congenital HD: lower snoRNA expression in tetralogy of Fallot; zebrafish knockdown of _Snord94/Scarna1_ → abnormal cardiac development

### Small Noncoding RNAs: Y-RNAs
- Y-RNAs (83–112 nt; 4 types in humans) form stem-loop structures; stem highly conserved; loop harbours cleavage sites generating s-RNY fragments (~20–40 nt)
- s-RNY fragments measurable in blood as cell-free ribonucleoprotein complexes and in extracellular vesicles
- Atherosclerosis: atherogenic stimuli (ox-LDL, saturated fatty acids) strongly upregulate macrophage s-RNY; mouse atherosclerosis models show elevated plasma s-RNY; patients with CAD have higher serum s-RNY than controls (confounded by multiple co-morbidities)
- MI: in CADUCEUS trial cardiosphere-derived cells (CDCs), EVs contain 18% Y-RNA fragments; EV-YF1 (5'-half of Y-RNA 4) correlates with cardiac functional improvement in mouse MI model; direct injection reduces infarct mass and cardiomyocyte apoptosis
- Hypertrophy/fibrosis: EV-YF1 attenuates hypertrophy and reduces inflammation/fibrosis markers in angiotensin II mouse model; associated with reduced IL-10 expression

### Small Noncoding RNAs: tRNA-Derived sRNAs (tsRNAs)
- tiRNAs (tRNA halves): generated by angiogenin cleavage at anticodon loop; accumulate under stress (hypoxia, heat shock, nutritional deprivation); inhibit translation, regulate apoptosis and stress granules
- tiRNAs upregulated in rat stroke model (tRNA[Val], tRNA[Gly]) and mouse hindlimb ischemia; synthetic tiRNAs inhibit endothelial proliferation/migration/tube formation — mechanism unclear
- tRNA-derived fragments (tRFs): generated by Dicer at T/D loops; some tRF-5' fragments interact with Argonaute proteins in RISC-like manner; tRFs enriched in isoproterenol-induced hypertrophic hearts; overexpression increases ANP, BNP, α-MHC and cardiomyocyte hypertrophy; tRFs can target _Timp3_ 3'-UTR
- Heavy tRNA modification interferes with reverse transcription — bacterial AlkB enzyme pre-treatment recommended for tRNA/tRF sequencing

### Long Noncoding RNAs (lncRNAs)
- lncRNAs are >200 nt transcripts sharing mRNA features (RNA Pol II, 5'-capped, polyadenylated, spliced); >30,000 predicted in human genome; lower abundance and poor conservation vs. mRNAs
- Classified by genomic location (lincRNA, intronic, eRNA, AS-lncRNA) and function (guides, scaffolds, decoys, ceRNAs)
- ceRNA function: lncRNAs sponge miRNAs, preventing their repression of mRNA targets — validation requires coprecipitation, miRNA target derepression upon lncRNA deletion, and loss of sponging after miRNA binding site mutation; ceRNA stoichiometry remains controversial
- **CVD risk loci lncRNAs:** ANRIL (9p21) — scaffold for CDKN2a/B regulation; circularised ANRIL isoforms take on atherogenic function; MIAT — variant associated with MI risk; H19 — variants increase IGF2 expression and CAD risk
- **Metabolism:** MALAT1 and H19 stabilise SREBP-1c to promote hepatic lipogenesis; LeXis (LXR-induced) reduces cholesterol synthesis; MeXis (macrophage LXR-induced) promotes ABCA1/cholesterol efflux; APOA1-AS and APOA4-AS regulate apolipoprotein expression
- **Vascular biology:** PUNISHER, MEG3, GATA6-AS regulate vessel formation; LincRNA-p21 restricts smooth muscle proliferation; MALAT1 regulates angiogenesis and contributes to diabetic retinopathy and atherosclerosis
- **Cardiac hypertrophy/HF:** _Mhrt_ — cardiac-specific; repressed in pressure-overload hypertrophy; restoration is cardioprotective; potential HF biomarker; _Chast_ — impedes cardiomyocyte autophagy by negatively regulating Plekhm1; _Chaer_ — interacts with PRC2 catalytic subunit to alter epigenetic reprogramming; silencing either attenuated pathological remodeling in mice
- **Stroke:** Multiple lncRNAs differentially expressed in ischemic stroke whole blood; MIAT expression correlates with poor prognosis; ANRIL variants correlate with stroke risk at 9p21.3; Malat1 may protect against ischemic brain injury via proapoptotic/proinflammatory inhibition
- **Tools:** RNA-seq (with sufficient depth); CRISPRi/CRISPRa for lncRNA manipulation; ASOs/Gapmers for knockdown; chromatin isolation by RNA purification (ChIRP) + mass spectrometry for interactome mapping; digital droplet PCR + RNA-FISH for copy number and localisation
- Up to 20% of lncRNAs in human heart may encode micropeptides — blurring noncoding/coding boundary

### Circular RNAs (circRNAs)
- circRNAs generated by back-splicing (3' exon end joined to upstream 5' exon end); lack poly(A) tails; detected by rRNA-depleted or ribonuclease R–enriched RNA-seq; validated by poly(A) depletion + RNase R resistance + Northern blotting
- Tools: circtools, CIRCexplorer2, CIRI2 for detection; StarBase3, CircNet, circInteractome for interaction prediction
- Biological examples: cZNF292 (endothelial angiogenic sprouting); circ_lrp4 (smooth muscle proliferation); circANRIL (atheroprotection); HRCR and circFoxo3 (cardiac hypertrophy and senescence)
- CDR1as has 63 binding sites for miR-7 — paradigmatic miRNA sponge; genetic deletion confirms in vivo function
- Detected in human blood (high stability); copy numbers are low — clinical utility as biomarkers requires larger validation studies

### Extracellular RNAs (exRNAs)
- exRNAs encompass all circulating ncRNAs (miRNA, piRNA, snoRNA, lncRNA, circRNA, tRNA fragments) carried in EVs, bound to lipoproteins, or RNA-binding proteins
- FHS exRNA atlas (n=2763): miRNA, piRNA, snoRNA, circRNA, tRNA fragments all detectable in human circulation
- Major quantification challenges: low abundance, sample handling instability, heparin interference with RNA assays, biofluid selection (whole blood vs. plasma vs. serum vs. vesicle), technical biases in RNA isolation and library construction
- Three quantification platforms: RNA-seq (unbiased but library bias), RT-PCR (a priori target selection), hybridisation-based direct quantification (limited breadth)
- CVD biomarker associations reported for: AF (miR-21, miR-150), MI (miR-208b, miR-1, miR-133), cardiometabolic disorders, cardiac arrest
- Key unmet need: tissue-specific markers for exRNA carrier subtypes — the Extracellular RNA Communication Consortium (ERCC) is addressing this

### ncRNAs in Exercise
- miRNAs dynamically regulated by exercise: upregulated — miR-21, miR-150, miR-222, miR-17-3p, miR-223; downregulated — miR-1, miR-133a, miR-208
- Proposed mechanisms: promotion of physiological cardiac hypertrophy, cardiomyocyte proliferation, angiogenesis, reduced fibrosis
- Circulating miR-222 and miR-17-3p increased after exercise training in both healthy athletes and HF patients
- lncRNAs in exercise: largely unstudied; one microarray study showed lncRNA FR030200 downregulation in aortic endothelium after exercise, cis-regulating col3a1

### RNA Therapeutics in CVD
- **siRNA (inclisiran):** Targets PCSK9 mRNA in hepatocytes; N-acetylgalactosamine conjugate for liver targeting; phase II trial showed sustained LDL-C reduction at 240 days after 2 doses; phase III trials ongoing at time of publication
- **siRNA (patisiran):** Targets transthyretin mRNA; phase III trial showed improvement in multiple clinical endpoints for ATTR amyloidosis
- **ASOs:** First-generation ASOs against PCSK9 insufficient affinity; second-generation LNA-based ASOs show promise in primates and early human studies; RNase H-mediated degradation of RNA:DNA hybrid
- **Anti-miR strategies:** Systemic administration of LNA-anti-miRs or antagomiRs achieves target miRNA knockdown in vivo; intracoronary delivery enhances cardiac targeting; phase I trials ongoing for anti-miR-92a (NCT03603431, NCT03494712); phase I trial for CDR132L (anti-miR-132) for cardiac remodeling (NCT04045405)
- **AAV-delivered miRNA overexpression:** Promising results with AAV-miR-199 in porcine MI model, but dose-dependent toxicity observed — careful dosing essential before human translation
- **Key hurdles:** Cardiac-specific delivery, RNA chemistry stability, off-target effects, pharmacokinetics/pharmacodynamics

## Limitations of the Document
- Literature review through 2018; field has evolved substantially
- Most functional data from in vitro or mouse/rat models — human translation unproven for most ncRNA classes
- exRNA biomarker studies show inconsistent associations across cohorts, biofluids, and quantification methods — lack of standardised protocols
- lncRNA annotation is species-dependent and lagging; >20% of putative lncRNAs may encode micropeptides (complicating classification)
- ceRNA sponging stoichiometry often not rigorously validated
- Single-RNA mechanistic studies dominate — complex RNA–RNA interaction networks understudied

## Key Concepts Mentioned
- [[concepts/Noncoding-RNA-in-CVD]] — umbrella concept covering all ncRNA classes
- [[concepts/Long-Noncoding-RNA]] — lncRNA classification, function, CVD roles, tools
- [[concepts/Gene-Silencing-Therapy]] — siRNA, ASO, anti-miR modalities; inclisiran and patisiran clinical data added
- [[concepts/AAV-Gene-Delivery]] — AAV-delivered miRNA overexpression in porcine MI model

## Key Entities Mentioned
- [[entities/ATTR-Amyloidosis]] — siRNA (patisiran) phase III benefit

## Wiki Pages Updated
- wiki/sources/noncoding-rna-aha-2020.md (created)
- wiki/sourceindex.md (updated)
- wiki/wikiindex.md (updated)
- wiki/concepts/Noncoding-RNA-in-CVD.md (created)
- wiki/concepts/Long-Noncoding-RNA.md (created)
- wiki/concepts/Gene-Silencing-Therapy.md (updated — inclisiran/patisiran/anti-miR clinical data)
