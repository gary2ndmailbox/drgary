---
dg-publish: true
title: "Rare and Common Genetic Variation Underlying Atrial Fibrillation Risk"
date_ingested: 2026-04-13
source_type: original article
Citation: "Vad OB, Monfort LM, Paludan-Müller C, et al. Rare and Common Genetic Variation Underlying Atrial Fibrillation Risk. JAMA Cardiol. 2024;9(8):732-740."
DOI: "https://doi.org/10.1001/jamacardio.2024.1528"
tags: [atrial-fibrillation, genetics, polygenic-risk-score, cardiomyopathy, early-onset-atrial-fibrillation]
rating: high
raw_path: raw/Biobank-AF-JAMA-2024.md

---

# Rare and Common Genetic Variation Underlying Atrial Fibrillation Risk

## Authors, Journal, Affiliations, Type, DOI
- **Authors:** Oliver B. Vad, Laia M. Monfort, Christian Paludan-Müller, et al.; for the Geisinger MyCode Community Health Initiative and Regeneron Genetics Center Research Team
- **Journal:** JAMA Cardiology 2024;9(8):732–740
- **Affiliations:** Department of Cardiology, Copenhagen University Hospital – Rigshospitalet; Department of Biomedical Sciences, University of Copenhagen; Regeneron Genetics Center, Tarrytown, New York
- **Type:** Genetic association and nested case-control study (observational)
- **DOI:** https://doi.org/10.1001/jamacardio.2024.1528

## Overview
Using whole-exome sequencing of 403,990 UK Biobank participants, this study identified rare predicted loss-of-function (pLOF) variants in 6 genes (TTN, RPL3L, PKP2, CTNNA3, KDM5B, C10orf71) significantly associated with AF, with 5 of 6 replicated in an external cohort of >160,000 individuals. The key finding is a multiplicative interaction between rare pLOF variants and a polygenic risk score (PRS): together they confer an OR of 7.08 for AF. Carriers with a top-quintile PRS face a 10-year absolute AF risk of 24% (males >60 years). Critically, pLOF variants — predominantly driven by TTN — are associated with a 3× increased risk of cardiomyopathy both before and after AF diagnosis, supporting the concept that AF may be the first clinical manifestation of an underlying cardiomyopathy in genetically predisposed individuals.

## Keywords
Atrial fibrillation · Rare variants · Predicted loss-of-function · Whole-exome sequencing · Polygenic risk score · Cardiomyopathy · Heart failure · TTN · PKP2 · UK Biobank · Gene-based burden test

## Key Takeaways

### Study Design and Population
- **UK Biobank whole-exome sequencing:** 403,990 individuals (54.1% female; median age 58 years; European ancestry); median follow-up 13.3 years (end July 2022).
- **Case definition:** 31,124 individuals with AF (6,677 prevalent at inclusion + 24,447 incident AF during follow-up).
- **Gene-based burden test:** Rare pLOF variants (MAF <1%) collapsed across 17,979 genes; significance threshold P <2.77 × 10⁻⁶ (correction for ~18,000 genes). Firth logistic regression adjusted for age, sex, and 10 principal components.
- **External replication cohort:** 17,910 individuals with AF and 149,348 controls.

### Gene-Based pLOF Associations with AF (Table 2)
Six genes reached exome-wide significance for pLOF variants and AF:

| Gene | Protein | OR (95% CI) | P value | Replicated? |
|------|---------|-------------|---------|-------------|
| TTN (PSI90) | Titin (constitutively expressed cardiac exons, spliced-in >90%) | 3.85 (3.25–4.55) | 1.09 × 10⁻⁵⁵ | Yes |
| TTN (N2BA-N2B) | Titin (cardiac isoforms) | 2.17 (1.93–2.43) | 2.07 × 10⁻⁴⁰ | Yes |
| TTN (all) | Titin | 1.77 (1.60–1.95) | 3.38 × 10⁻³⁰ | Yes |
| RPL3L | Ribosomal protein L3-like | 1.56 (1.38–1.77) | 1.69 × 10⁻¹² | Yes |
| PKP2 | Plakophilin-2 | 2.12 (1.60–2.82) | 2.21 × 10⁻⁷ | Yes |
| CTNNA3 | Catenin α3 | 2.79 (1.88–4.14) | 3.74 × 10⁻⁷ | Yes |
| C10orf71 | Cardiac-enriched FHL2-interacting protein (CEFIP) | 2.40 (1.69–3.39) | 7.83 × 10⁻⁷ | **No** |
| KDM5B | Lysine demethylase 5B | 2.70 (1.80–4.06) | 1.76 × 10⁻⁶ | Yes |

- Associated genes were predominantly expressed in cardiomyocytes; KDM5B was the exception (expressed across all cell types). C10orf71 was almost exclusively expressed in muscle tissue.
- Secondary missense variant analysis replicated one association: UBE4B (OR 1.22; P = 5.90 × 10⁻⁷) — predominantly driven by a single missense variant.
- TTN PSI90 (constitutively expressed cardiac exons) had the strongest association — restricting analysis to functionally expressed exons greatly increases signal.

### Novel Gene Mechanisms
- **CTNNA3 (catenin α3):** Cytoskeletal protein interacting with cardiomyocyte desmosomes; putatively associated with ARVC and familial AF. Confirms a role for desmosome-associated cytoskeletal proteins in AF beyond classical ARVC genes.
- **KDM5B (lysine demethylase 5B):** Not previously associated with arrhythmias. Encodes a histone H3K4 demethylase thought to play a role in **cardiac fibrosis** — a common substrate for re-entry arrhythmias. Novel mechanism: epigenetic regulation of arrhythmia substrate.
- **RPL3L (ribosomal protein L3-like):** Involved in ribosomal function and muscle growth. The association was primarily driven by a single splice-donor variant previously reported in an AF GWAS, providing mechanistic annotation.
- **C10orf71 (CEFIP):** Located at a locus near a known AF GWAS signal; protein may locate to sarcomere Z-discs and regulate cardiomyocyte hypertrophy. **Association did not replicate** — uncertain causal role.

### Combined PRS + pLOF Risk: Multiplicative Interaction
- **PRS alone:** 1-SD increase in AF PRS → OR 1.53 (95% CI 1.51–1.55); AUC 0.76 (reference model without PRS: AUC 0.74).
- **PRS alone in pLOF carriers:** OR per SD 1.69 (vs. 1.53 in non-carriers) — suggests rare variant carriers are also more sensitive to polygenic risk.
- **Top quintile PRS + pLOF variant: OR 7.08** (95% CI 6.03–8.28) for AF — dose-response increase across all 10 PRS × carrier strata.
- **Incident AF hazard ratio (top PRS quintile + pLOF):** HR 4.78 (95% CI 4.06–5.63) vs. non-carriers with low PRS.
- **Cumulative absolute risk by age 80:** 28.6% in top PRS + pLOF carriers vs. 12.1% (mid PRS, non-carrier) and 8.1% (low PRS, non-carrier).

### 10-Year Absolute Risk of AF (Figure 2)
- **Highest risk group (males >60 years, top PRS quintile, pLOF carrier): 24%**; equivalent female group: 16%.
- Males >60 years, top PRS quintile, non-carrier: 21%.
- Modifiable risk factors compound polygenic + rare variant risk: BMI ≥30 + hypertension + top PRS: comparable absolute risk to pLOF carriers.
- Males <60 years with top PRS + pLOF: 10%; equivalent females: 5%.

### Genetic Predisposition and Risk of Cardiomyopathy / Heart Failure
All analyses used cause-specific Cox regression with AF, HF, and cardiomyopathy as competing events:

**Full cohort (without AF at baseline; n = 395,528):**
- pLOF variants (all 5 replicated genes) → incident AF: HR 1.85 (1.69–2.02)
- pLOF variants → incident **cardiomyopathy: HR 3.13** (2.24–4.36; P <0.001)
- pLOF variants → incident HF: HR 1.51 (1.26–1.82)
- **When TTN excluded:** CM HR drops to 1.39 (0.80–2.40, non-significant); HF HR drops to 1.01 (non-significant) — TTN drives almost all the CM/HF association.
- AF PRS per SD: associated with AF (HR 1.45) but **not** with cardiomyopathy (HR 0.99) or HF (HR 1.02) — common polygenic variation is arrhythmia-specific, not cardiomyopathy-specific.

**In individuals with AF (n = 21,154; no prior HF/CM):**
- pLOF variants → incident **cardiomyopathy post-AF: HR 2.98** (1.89–4.69; P <0.001)
- When TTN excluded: HR 1.01 (non-significant) — again TTN-driven.
- AF PRS: not associated with cardiomyopathy or HF after AF.

**Interpretation:** For pLOF variant carriers (especially TTNtv), AF may be the first disease manifestation preceding more severe cardiomyopathy. The common genetic AF PRS does not carry this cardiomyopathy risk — supporting fundamentally different biological pathways for rare vs. common genetic AF risk.

### Clinical Implications
- Rare pLOF variants with large effect sizes may justify genetic testing in specific high-risk groups (early-onset AF, family history, coexisting CM features).
- Prior data (Yoneda 2021, 2022) showed higher rare variant rates and increased mortality in younger patients — consistent with findings from this general population cohort.
- Aligns with **AHA/ACC 2023** recommendation (Class IIb): genetic testing/CM surveillance may be reasonable in AF onset <45 years.
- Integration of PRS + rare pLOF variant status could enable population-level risk stratification as WES becomes cheaper and more accessible.

## Limitations of the document
- **European ancestry only:** Results may not be generalizable to other ethnicities; population stratification corrections applied but residual confounding possible.
- **Strict significance threshold** (P <2.77 × 10⁻⁶) may have limited power to detect additional AF-associated genes.
- **Observational design:** Gene-based associations cannot be assumed causal without functional validation. Confounding by indication and residual confounding possible.
- **C10orf71 did not replicate** externally; causal role uncertain.
- **UK Biobank healthy volunteer bias:** Enrolled individuals are healthier on average than the general UK population — absolute risk estimates may be conservative.
- **Age at inclusion 40–69:** Not a dedicated early-onset AF cohort; the youngest patients are included but the study is not powered to characterize very early-onset AF (<30 years) specifically.

## Key Concepts Mentioned
- [[concepts/Early-Onset-Atrial-Fibrillation]] — pLOF variants provide population-level corroboration of cardiomyopathy gene involvement in AF
- [[concepts/Genetic-Testing-in-AF]] — combined PRS + rare variant model; clinical case for genetic testing
- [[concepts/Arrhythmogenic-Cardiomyopathy]] — CTNNA3 and PKP2 link AF to desmosomal disease

## Key Entities Mentioned
- [[entities/TTN]] — strongest and most prevalent pLOF AF association; drives all cardiomyopathy/HF signal
- [[entities/PKP2]] — pLOF OR 2.12 for AF; replicated; corroborates GWAS locus; desmosomal pathway
- [[entities/Atrial-Fibrillation]] — primary outcome; PRS + pLOF multiplicative model
- [[entities/DCM]] — CTNNA3 and TTN overlap with cardiomyopathy gene landscape

## Wiki Pages Updated
- Created: wiki/sources/Biobank-AF-JAMA-2024.md
- Updated: wiki/entities/TTN.md (population-level pLOF AF evidence; CM/HF risk driven by TTNtv)
- Updated: wiki/entities/PKP2.md (population-level pLOF AF association OR 2.12; replicated)
- Updated: wiki/concepts/Genetic-Testing-in-AF.md (PRS + pLOF combined model; OR 7.08; 10-year absolute risk data)
- Updated: wiki/concepts/Early-Onset-Atrial-Fibrillation.md (UK Biobank population-level pLOF data)
- Updated: wiki/wikiindex.md
- Updated: log.md
