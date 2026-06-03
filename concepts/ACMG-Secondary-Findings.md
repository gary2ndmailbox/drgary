---
dg-publish: true
title: "ACMG Secondary Findings"
tags: [actionable-genotypes, ACMG-secondary-findings, genetics, population-genomics, genetic-testing]
source_count: 2
last_updated: 2026-05-17
---

# ACMG Secondary Findings

## Definition
ACMG Secondary Findings (SF) refers to the American College of Medical Genetics and Genomics policy requiring reporting of pathogenic (P) or likely pathogenic (LP) variants in a curated gene list when these variants are identified incidentally during clinical exome or genome sequencing performed for a different diagnostic purpose. The gene list — currently v3.2 (June 2023) — contains 73 genes considered "medically actionable" because: (1) the associated disease is highly penetrant, (2) preventive or therapeutic interventions are established and effective, and (3) early detection before symptom onset provides clinical benefit. Genes are grouped into four disease categories: cardiovascular, cancer, metabolic, and miscellaneous.

## Key Concepts

### ACMG SF v3.0 Gene List Structure
- 73 genes at v3.0 (2021); updated annually: v3.1 (2022), v3.2 (June 2023), and subsequent versions
- **Cardiovascular group:** Cardiomyopathies (MYBPC3, MYH7, TNNT2, TNNI3, TPM1, MYL3, ACTC1, MYL2, PRKAG2, GLA, TTR, LMNA, DSP, DSC2, DSG2, JUP, PKP2, TMEM43, RBM20); inherited arrhythmias (KCNQ1, KCNH2, SCN5A, RYR2, CASQ2); aortic disease (FBN1, TGFBR1, TGFBR2, SMAD3, ACTA2, MYH11, COL3A1); FH (LDLR, APOB, PCSK9)
- **Cancer group:** BRCA1, BRCA2, PALB2, MLH1, MSH2, MSH6, PMS2, EPCAM, APC, MUTYH, RET, VHL, TP53, STK11, CDH1, PTEN, MEN1, NF2, SDHB, SDHC, SDHD, and others
- **Metabolic group:** ACADM, LDHA and others
- **Miscellaneous group:** HFE, OTC, ATP7B and others
- 42 of 78 ACMG-listed genes (54%) relate to CVD ([[sources/incident-gene-aha-2023]] — high)

### Population Prevalence of Actionable Genotypes
- **4.0% of Icelanders** (1 in 25; n=57,933 WGS) carry ≥1 actionable genotype by manual curation — **consistent across populations:** UK Biobank 2.0%, Qatar 2.3%, US 2.8% (using automated narrow criteria on comparable gene lists) ([[sources/genotype-lifespan-nejm-2023]] — high)
- Using automated narrow criteria alone: 2.9% — manual curation identifies ~38% additional carriers by reclassifying ClinVar VUSs using population-level disease associations and frequency data
- Actionable genotypes in two genes simultaneously: 42/2306 (1.8%) of Icelandic carriers
- The BRCA2 p.Asn257LysfsTer17 Icelandic founder variant was the single most common actionable genotype (421 carriers, 18% of all carriers) — illustrating how founder effects elevate local prevalence

### Lifespan Impact by Disease Group
Kaplan–Meier and Cox proportional-hazards survival analyses (n=57,933; Icelandic Death Registry): ([[sources/genotype-lifespan-nejm-2023]] — high)

| Group | Carrier Median Survival | Noncarrier Median Survival | Key Drivers |
|---|---|---|---|
| All actionable genotypes combined | 86 yr (95% CI 85–87) | 87 yr | Cancer > CV |
| Cancer gene group | 84 yr (95% CI 82–85) | 87 yr (−3 yr) | BRCA2 (−7.1 yr women −9.3, men −4.6), BRCA1, PALB2, MSH6 |
| Cardiovascular gene group | No group-level difference | — | Only LDLR (−6.47 yr) and MYBPC3 (−2.18 yr) individually |
| Miscellaneous group | No difference | — | — |
| Metabolic group | No difference | — | HFE: morbidity not mortality |

- Early death (10th percentile): 69 years for all carriers vs 73 years for noncarriers (4 years); cancer group 65 vs 73 years (8 years)
- Cardiovascular gene group: only 25% of CV gene carriers carry the two variants (LDLR, MYBPC3) with individual lifespan signals — the remaining 75% show no survival difference

### Cause-of-Death Registry Findings
Seven genes showed evidence of association between the actionable genotype and the relevant disease listed as a cause, direct cause, or contributing factor on death certificates (Icelandic Death Registry): ([[sources/genotype-lifespan-nejm-2023]] — high)
- **Cancer:** BRCA2 (22% vs 4% related-cancer death; OR 6.82, 95% CI 4.01–11.62), BRCA1, PALB2, MSH6
- **Cardiovascular:** TGFBR2, KCNQ1
- **Miscellaneous:** HFE
- **MYBPC3 cause-of-death nuance:** cardiomyopathy on death certificate in 10.4% of MYBPC3 carriers vs 0.8% noncarriers (OR 14.04; 95% CI 5.44–36.23); however, the composite of all MYBPC3-associated conditions (cardiomyopathy + SCD + AF + HF) dilutes the effect (OR 1.34; NS) — confirming that cardiomyopathy is the specific mechanism, not the full composite

### Variant Reclassification Using Population Data
- Manual curation using a local genotypic and phenotypic database outperforms automated ClinVar approaches
- Example: BRCA1 c.4096+3A→G — classified as VUS in ClinVar; found in 1/500 Icelanders (founder effect); associated with breast cancer (OR 3.13; 95% CI 1.90–5.16) and ovarian cancer (OR 8.49; 95% CI 3.99–18.10); RNA sequencing in 42 heterozygotes confirms exon 10 omission (−1.45 SD); reclassified as pathogenic ([[sources/genotype-lifespan-nejm-2023]] — high)
- This reclassification framework illustrates how population-scale WGS enables evidence generation for ClinVar variant classification that individual clinical laboratories cannot achieve

### Candidate Genes for Future ACMG List Inclusion
Ten genotypes in 10 genes from Iceland identified as potential additions: ([[sources/genotype-lifespan-nejm-2023]] — high)
- **MYL4** — early-onset familial AF; associated with shorter lifespan
- **PKD1, PKD2** — ADPKD; associated with shorter lifespan
- **APRT** — renal stones/failure; associated with shorter lifespan
- **F5** (Factor V Leiden, homozygous only) — VTE lifetime risk >80%; OR 7.61 for VTE; −4.47 years lifespan
- **F2** (homozygous c.*97G→A) — VTE; OR 11.92 for VTE; 5 homozygotes identified
- Heterozygous F5 Leiden and F2 not proposed (10% lifetime VTE risk — insufficient actionability threshold)

### Reporting Policy Context
- ACMG SF reporting applies ONLY when clinical ES/GS is performed for diagnostic purposes — NOT for research biobanks, DTC testing, or clinical trials ([[sources/incident-gene-aha-2023]] — high)
- Several large biobank programs (UK Biobank n=500,000) do not have return-of-results mechanisms — this study and others highlight the public health argument for establishing such mechanisms
- deCODE Genetics established a web interface allowing participants to request BRCA2 p.Asn257LysfsTer17 status: 450 positive results reported from 39,267 requests

## Contradictions / Open Questions
- **Manual curation gap vs clinical practice:** Manual curation identifies 38% more actionable genotype carriers than automated criteria, but most clinical and research labs use automated criteria. Thousands of carriers go unidentified in large-scale programs. ([[sources/genotype-lifespan-nejm-2023]] — high)
- **Cardiovascular group lifespan paradox:** Most ACMG cardiovascular gene carriers (75%) show no individual survival signal despite carrying "actionable" genotypes. If the rationale for ACMG reporting is lifespan benefit from intervention, this raises the question of whether all 73 genes truly meet the actionability threshold — particularly for CV genes where penetrance is highly variable. ([[sources/genotype-lifespan-nejm-2023]] — high; [[sources/incident-gene-aha-2023]] — high)
- **Treatment attenuation of mortality signal:** The absence of a mortality signal for most CV gene groups may reflect successful treatment (e.g., LDLR/FH on statins, HCM patients on beta-blockers, ICD recipients), making it difficult to estimate untreated lifespan impact from population data that includes treated individuals.
- **Generalizability — Icelandic founder effects:** Variant frequencies in Iceland are shaped by founder effects not present in other populations; the 4% actionable genotype prevalence may differ meaningfully in diverse-ancestry populations. Non-European ancestry populations have higher VUS rates and different founder variants, making direct extrapolation uncertain. ([[sources/genotype-lifespan-nejm-2023]] — high; [[sources/incident-gene-aha-2023]] — high)
- **Survival bias (bidirectional):** Participants with the most severe genotype-mediated disease or earliest deaths are the least likely to enroll in research studies — meaning both survival and lifespan-reduction estimates are attenuated in this data.

## Connections
- Related to [[concepts/Incidental-Cardiovascular-Variants]] — ACMG SF is the most used incidental variant reporting framework
- Related to [[concepts/Variant-Reclassification]] — population-scale data enables reclassification beyond ClinVar automated methods
- Related to [[concepts/Genetic-Testing-in-Cardiomyopathy]] — MYBPC3, MYH7, and other HCM/DCM/ARVC genes are in the ACMG SF list
- Related to [[concepts/Cascade-Family-Screening]] — ACMG SF LP/P variants trigger cascade testing
- Related to [[concepts/Cardiogenetic-Centers]] — multidisciplinary expertise needed for ACMG SF result management
- Related to [[entities/MYBPC3]] — HCM gene; −2.18 years lifespan; 10.4% cardiomyopathy death
- Related to [[entities/KCNQ1]] — LQTS gene; cause-of-death association in Iceland registry
- Related to [[concepts/Familial-Hypercholesterolemia]] — LDLR; −6.47 years lifespan; only FH is CDC Tier 1 CVD gene
- Related to [[entities/MYL4]] — familial AF gene; proposed for ACMG list expansion

## Sources
- [[sources/genotype-lifespan-nejm-2023]]
- [[sources/incident-gene-aha-2023]]
