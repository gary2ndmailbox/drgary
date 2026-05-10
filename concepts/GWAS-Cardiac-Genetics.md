---
dg-publish: true
title: "GWAS in Cardiac Genetics"
tags: [GWAS, polygenic-risk-score, cardiomyopathy, inherited-arrhythmias, genetics]
source_count: 1
last_updated: 2026-05-07
---

# GWAS in Cardiac Genetics

## Definition
Genome-wide association studies (GWAS) systematically test hundreds of thousands to millions of common SNPs (minor allele frequency >1%) across the genome for association with a disease trait, without prior biological hypothesis. In cardiac genetics, GWAS has shifted understanding of traditionally "Mendelian" diseases (HCM, DCM, BrS, LQTS) toward a spectrum model in which common polygenic variants contribute alongside — and sometimes independently of — rare pathogenic variants.

## Key Concepts

### GWAS Methodology in Rare Cardiac Diseases
- **Design:** Large case-control cohorts (thousands to tens of thousands) genotyped on SNP arrays; imputation expands coverage to 10–15 million SNPs. Statistical threshold for genome-wide significance: p < 5×10⁻⁸ (Bonferroni correction for ~1 million independent tests). ([[sources/gwas-arrhythmias-cmp-genes-2025]], rating: high)
- **Fine-mapping and colocalization:** Once a GWAS locus is identified, fine-mapping narrows the credible set of causal SNPs; colocalization with eQTL data identifies the gene through which the variant acts (e.g., MAPRE2 in BrS, NOS1AP in QT). ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- **Polygenic Risk Score (PRS) construction:** Effect sizes (log-OR or beta) from GWAS for each SNP are summed as a weighted score across individuals. PRS performance is reported as AUC (discrimination), C-statistic, or OR per SD increase in the continuous score. See [[concepts/Polygenic-Risk-Score]] for full methodology. ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- **Multi-trait analysis (MTAG):** Combines GWAS summary statistics across related traits (e.g., multiple QT-related phenotypes or multi-ancestry DCM cohorts) to increase power — used in Jurgens 2024 DCM PRS. ([[sources/gwas-arrhythmias-cmp-genes-2025]])

### Paradigm Shift: Mendelian Diseases Have Polygenic Architecture
- HCM, DCM, BrS, and LQTS were historically modelled as monogenic diseases with high-penetrance rare variants as causative. GWAS has established that common variants contribute substantially to susceptibility and expressivity in all four conditions — challenging the binary genotype-positive/genotype-negative clinical framework. ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- In BrS, SCN5A is causative in only ~20% of patients; 21 independent GWAS loci explain the majority of remaining familial clustering. In LQTS, common SNPs explain ~15% of susceptibility variance. In HCM and DCM, PRS predicts case status with OR 2.34 and 1.73 per SD, respectively. ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- Clinical implication: genotype-negative patients are not necessarily "non-genetic" — they may carry a high polygenic burden without a single dominant rare variant. ([[sources/gwas-arrhythmias-cmp-genes-2025]])

### Inverse HCM-DCM Loci — Shared Contractility Axis
- **Tadros et al.** identified GWAS loci at MYBPC3, ALPK3, and FHOD3 where opposing SNP alleles increase HCM susceptibility on one side and DCM susceptibility on the other. This is genetic confirmation of the sarcomere hypercontractility (HCM) vs. hypocontractility (DCM) axis at the common variant level. ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- **Therapeutic implication:** Mavacamten (reduces myosin cross-bridge engagement; approved for obstructive HCM) and omecamtiv mecarbil (increases myosin cross-bridge formation; in development for DCM) target pharmacologically opposing ends of this same biological axis. ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- The inverse loci biology also raises the theoretical concern that drugs shifting sarcomere activity in one direction could unmask susceptibility to the opposing cardiomyopathy phenotype — not yet demonstrated clinically but a mechanistic consideration. ([[sources/gwas-arrhythmias-cmp-genes-2025]])

### Novel Loci Beyond Classic Disease Genes
- **HCM:** Novel GWAS loci outside sarcomere genes include FHOD3 (actin filament formation), ALPK3 (alpha-kinase/transcription), PLN (phospholamban/calcium handling), ACTN2, CSRP3. These implicate calcium handling and cytoskeletal assembly as polygenic contributors to HCM beyond myosin/actin direct variants. ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- **DCM:** BAG3 p.C151R is a common low-frequency variant with an intermediate effect size — sitting between the typical GWAS SNP and classical rare pathogenic variant spectra. BAG3 is already known as a rare-variant DCM gene (BAG3 haploinsufficiency → Z-disc proteostasis disruption). ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- **BrS:** HEY2 (cardiac transcription factor regulating RVOT development) and MAPRE2 (microtubule-end-binding protein involved in myofilament organisation) are novel BrS loci validated beyond SCN5A — identifying structural and developmental pathways in BrS beyond ion channel biology. ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- **LQTS/QT interval:** NOS1AP is the most validated QT-modifier locus; mechanistically confirmed via NOS1 activity regulation in hiPSC-CMs and mouse models. 176 independent QT-SNPs identified in a 2022 multiancestry GWAS (n=252,977). ([[sources/gwas-arrhythmias-cmp-genes-2025]])

### Ancestry Limitation and Multi-Ancestry PRS
- The majority of cardiac GWAS have been conducted in European-ancestry cohorts. GWAS-derived PRS systematically lose predictive accuracy in non-European populations due to LD structure differences and allele frequency divergence. ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- Notable exceptions where multi-ancestry validation has been achieved: DCM PRS (Jurgens 2024) performs across European (OR 1.73), African (OR 1.61), and Admixed-American (OR 1.34) cohorts. BrS PRS (Ishikawa 2024) shows similar performance in European and Japanese populations. ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- HCM and LQTS PRS remain predominantly European-ancestry validated; clinical application in non-European patients should be approached with caution. ([[sources/gwas-arrhythmias-cmp-genes-2025]])

### PRS as Complement to Rare Variant Testing
- PRS and rare variant testing are complementary, not mutually exclusive, risk stratification tools. A high PRS in a genotype-negative patient provides risk information that rare variant testing cannot; a pathogenic rare variant confers risk independent of PRS. ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- In HCM and DCM, PRS predicts adverse outcomes (death, clinical progression, hospitalization) independent of rare variant status — supporting the use of PRS in disease monitoring, not only diagnosis. ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- In LQTS, 75% of individuals with marked QTc prolongation lack both a high PRS and a rare pathogenic variant — confirming that environmental factors (drugs, electrolytes, autonomic) dominate even "unexplained" QTc prolongation. ([[sources/gwas-arrhythmias-cmp-genes-2025]])

## Contradictions / Open Questions
- **PRS predicts ECG phenotype, not arrhythmic events, in BrS:** The BrS PRS (Ishikawa 2024) predicts spontaneous type 1 ECG and positive SCB provocation test but NOT VF or SCD. This fundamental dissociation means GWAS can explain why most BrS is "genotype-negative" but cannot resolve who needs an ICD — which remains the most clinically urgent question. ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- **Polygenic threshold for clinical action undefined:** Unlike rare pathogenic variants, there are no consensus thresholds for PRS score values that should trigger clinical intervention (ICD, prophylactic therapy, more intensive surveillance) in any inherited cardiac condition. The OR per SD metric is informative at the population level but not actionable for individual patients without prospective clinical trial validation. ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- **PRS integration with monogenic architecture — no validated algorithm:** How to combine a patient's PRS (polygenic risk) with their rare variant carrier status into a single risk estimate for clinical decision-making has not been validated in any inherited cardiac condition. The spectrum model is proposed but lacks a clinical algorithm. ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- **Sample size gap for rare cardiac diseases:** Achieving genome-wide significance in rare diseases (HCM prevalence ~0.2%, BrS ~0.05%) requires extremely large case cohorts that are difficult to assemble. Published HCM and BrS GWAS have been substantially underpowered compared to common disease GWAS (CAD, AF); many true loci remain undetected. ([[sources/gwas-arrhythmias-cmp-genes-2025]])

## Connections
- Related to [[concepts/Polygenic-Risk-Score]]
- Related to [[entities/HCM]]
- Related to [[entities/DCM]]
- Related to [[entities/Brugada-Syndrome]]
- Related to [[entities/Long-QT-Syndrome]]
- Related to [[entities/NOS1AP]]
- Related to [[concepts/Ion-Channel-Mutations]]
- Related to [[concepts/Genetic-Testing-in-Cardiomyopathy]]
- Related to [[concepts/CRISPR-Cas9-in-Channelopathies]]

## Sources
- [[sources/gwas-arrhythmias-cmp-genes-2025]]
