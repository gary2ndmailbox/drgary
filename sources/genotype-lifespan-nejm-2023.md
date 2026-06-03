---
dg-publish: true
title: "Actionable Genotypes and Their Association with Life Span in Iceland"
date_ingested: 2026-05-17
source_type: original article
Citation: "Jensson BO, Arnadottir GA, Katrinardottir H, et al. Actionable Genotypes and Their Association with Life Span in Iceland. N Engl J Med. 2023;389(19):1741-1752."
DOI: "https://doi.org/10.1056/NEJMoa2300792"
tags: [actionable-genotypes, ACMG-secondary-findings, population-genomics, lifespan, genetics]
rating: high
raw_path: raw/Genotype-Lifespan-NEJM-2023.md
---

# Actionable Genotypes and Their Association with Life Span in Iceland

## Authors, Journal, Affiliations, Type, DOI
- Brynjar O. Jensson, Gudny A. Arnadottir, Hildigunnur Katrinardottir, et al.
- Kari Stefansson, Patrick Sulem (co-corresponding)
- deCODE Genetics–Amgen; University of Iceland; Landspitali National University Hospital; Reykjavik University
- New England Journal of Medicine 2023;389:1741–52
- Original article — population-based WGS cohort with national mortality linkage
- DOI: 10.1056/NEJMoa2300792
- Funded by deCODE Genetics–Amgen

## Overview
This Icelandic population-genomics study assessed the prevalence and lifespan impact of actionable genotypes in all 73 ACMG Secondary Findings v3.0 genes in 57,933 participants who underwent whole-genome sequencing (30× depth). Manual curation of 4405 variants identified 235 actionable genotypes in 53 genes; 4% of Icelanders (1 in 25) carried at least one. Carriers had shorter median survival (86 vs 87 years), driven primarily by cancer-group genes (−3 years median survival). Among cardiovascular genes, LDLR (FH; −6.47 years) and MYBPC3 (HCM; −2.18 years) showed individual lifespan associations, and KCNQ1/TGFBR2 were linked to cause of death in the national death registry. The study also proposed 10 new candidate genes for the ACMG list and used population genetics to reclassify a BRCA1 variant of uncertain significance as pathogenic.

## Keywords
ACMG secondary findings, actionable genotypes, whole-genome sequencing, life span, survival analysis, ClinVar, deCODE, Iceland, BRCA2, MYBPC3, LDLR

## Key Takeaways

### Actionable Genotype Assessment
- Of 57,933 Icelanders with WGS, **4.0% (n=2306; 1 in 25) carried at least one actionable genotype** across 235 variants in 53 of the 73 ACMG SF v3.0 genes
- Using automated narrow criteria (as used by prior studies), only 2.9% had actionable genotypes — manual curation identifies 38% more carriers
- The Icelandic BRCA2 p.Asn257LysfsTer17 founder variant was the single most common actionable genotype (421 carriers = 18% of all carriers)
- 42 persons carried actionable genotypes in two genes simultaneously
- 67 variants (in 33 genes) were imputed to an additional 108,348 chip-genotyped Icelanders, accounting for 90% of WGS-identified actionable genotypes
- Actionable genotype prevalence in Iceland (4.0%) is consistent with Qatar (2.3%), UK (2.0%), and US (2.8%) using comparable methods and gene lists

### Genotype, Life Span, and Cause of Death
- **All actionable genotypes combined:** carriers median survival 86 years (95% CI 85–87) vs 87 years noncarriers; 10th percentile (early death) 69 vs 73 years
- **Cancer gene group:** median survival 3 years shorter (84 vs 87 years); 10th percentile 8 years shorter (65 vs 73 years); driven primarily by BRCA2 p.Asn257LysfsTer17 (−7.11 years; women −9.34, men −4.60) but persists after excluding BRCA2 carriers (−3 years)
- **Cardiovascular gene group:** no group-level median survival difference; however two individual variants showed lifespan association:
  - LDLR c.694+2T→C (FH): −6.47 years (95% CI −9.91 to −3.03)
  - MYBPC3 (variant not specified): −2.18 years (95% CI −3.44 to −0.92)
  - These two variants account for only 25% of cardiovascular gene group carriers — the majority of CV gene carriers have no survival signal
- **Miscellaneous and metabolic groups:** no group-level survival difference
- **Cause-of-death registry linkage (7 genes with ≥6 carrier deaths):**
  - Cancer: BRCA2 (22% vs 4% cancer-related death; OR 6.82), BRCA1, PALB2, MSH6
  - Cardiovascular: TGFBR2, KCNQ1 (associated with cause-of-death registry)
  - Miscellaneous: HFE
- **MYBPC3 specific cause-of-death finding:** 10.4% of MYBPC3 actionable genotype carriers had cardiomyopathy listed on the death certificate vs 0.8% of noncarriers (OR 14.04; 95% CI 5.44 to 36.23); however, combining all MYBPC3-associated conditions (cardiomyopathy, SCD, AF, HF) diluted the effect (OR 1.34; NS) — indicating that cardiomyopathy is the primary death mechanism, not the broader composite
- **Treatment effect consideration:** some CV genotypes (e.g., HFE C282Y homozygous) were not mortality-associated, possibly because phlebotomy normalises iron and is easily available; treatment may mitigate some genotype-mediated mortality

### Variant Classification in Large-Scale Study
- Five examples illustrate the utility of local population-level genotype and phenotype data for reclassification:
  - **BRCA1 c.4096+3A→G (splice-site):** Classified as VUS in ClinVar; 1 in 500 Icelanders carry it (vs 1/132,000 in UK Biobank — consistent with founder effect); associated with breast cancer (OR 3.13) and ovarian cancer (OR 8.49); RNA sequencing in 42 heterozygotes confirms omission of BRCA1 exon 10 (−1.45 SD effect); reclassified as pathogenic in this study
  - **PCSK9, MSH6, KCNQ1, DSG2** also illustrated as examples of reclassification using local frequency and disease association data
- Manual curation using a local database outperforms automated ClinVar-based approaches: identifies more true actionable variants and reclassifies VUSs where local frequency + disease association data is available

### Expanding the List of Actionable Genes
- 10 genotypes in 10 genes identified as candidates for ACMG list inclusion — each associated with diseases for which therapeutic interventions are available:
  - **MYL4** — early-onset familial atrial fibrillation (frameshift deletion); associated with shorter lifespan
  - **PKD1, PKD2** — autosomal dominant polycystic kidney disease; associated with shorter lifespan
  - **APRT** — adenine phosphoribosyltransferase deficiency (renal stones/failure); associated with shorter lifespan
  - **F5** (Factor V Leiden, homozygous) — VTE risk >80% lifetime (homozygous); OR 7.61 for VTE; −4.47 years lifespan
  - **F2** (Factor II 3'-UTR variant c.*97G→A, homozygous) — VTE; OR 11.92 for VTE
  - F5 Leiden heterozygous (10% lifetime VTE risk) and F2 heterozygous not included — only homozygous state considered actionable
  - These findings advocate for a clinically informed, population-data-driven approach to ACMG list expansion

## Limitations of the Document
- **Icelandic founder effect:** Specific variant frequencies (especially BRCA2 p.Asn257LysfsTer17) are not representative of other populations; findings may not generalise to non-European or non-founder ancestries
- **Survival bias (bidirectional):** Persons who die prematurely are less likely to participate in research — survival rate overestimated overall. Conversely, carriers with severe disease are also under-enrolled — reduction in survival among carriers likely underestimated
- **Cross-sectional cohort design:** Survival analysis is observational; treatment effects (e.g., BRCA surveillance, statin use, ICD) are not adjustable — some survival advantage from treatment may already be baked in
- **ACMG SF v3.0 used:** Published in 2021; v3.2 (June 2023) and v3.3 have since been released with additional genes
- **Narrow vs manual curation gap:** The 38% increase in carriers from manual curation represents unverified pathogenicity in clinical settings — not all manual curated variants would pass ACMG/AMP variant classification criteria at other centres
- **Confidence intervals not adjusted for multiplicity:** Authors explicitly state CIs for individual variant tests cannot be interpreted as hypothesis tests; exploratory in nature for individual variant associations

## Key Concepts Mentioned
- [[concepts/ACMG-Secondary-Findings]] — 73-gene list framework; prevalence; lifespan impact by disease group
- [[concepts/Incidental-Cardiovascular-Variants]] — population-level prevalence data; lifespan context
- [[concepts/Variant-Reclassification]] — manual curation identifies 38% more actionable genotypes; VUS reclassification using local population data (BRCA1 example)
- [[concepts/Genetic-Testing-in-Cardiomyopathy]] — MYBPC3 as key cardiovascular actionable gene; lifespan and cause-of-death data

## Key Entities Mentioned
- [[entities/MYBPC3]] — 10.4% cardiomyopathy-related death (OR 14.04); −2.18 years lifespan; Icelandic founder mutation; cardiomyopathy as primary (not composite) death mechanism
- [[entities/KCNQ1]] — listed as cause-of-death associated gene in Icelandic Death Registry analysis
- [[concepts/Familial-Hypercholesterolemia]] — LDLR actionable variant (c.694+2T→C): −6.47 years lifespan; only 1 of 7 CDC Tier 1 genes associated with CV mortality that is a non-cancer gene
- [[entities/MYL4]] — early-onset familial AF gene; proposed for ACMG list; shorter lifespan in carriers

## Wiki Pages Updated
- Created: `wiki/sources/genotype-lifespan-nejm-2023.md`
- Created: `wiki/concepts/ACMG-Secondary-Findings.md`
- Updated: `wiki/entities/MYBPC3.md` — added Iceland lifespan and cause-of-death data
- Updated: `wiki/entities/KCNQ1.md` — added mortality association (cause of death, Iceland registry)
- Updated: `wiki/concepts/Incidental-Cardiovascular-Variants.md` — added population prevalence and lifespan context
- Updated: `wiki/concepts/Familial-Hypercholesterolemia.md` — added LDLR actionable genotype lifespan data
