---
dg-publish: true
title: "Polygenic Risk Score"
tags: [polygenic-risk-score, long-qt-syndrome, cardiac-repolarization, genetics, precision-medicine]
source_count: 2
last_updated: 2026-04-30
---

# Polygenic Risk Score (PRS)

## Definition
A polygenic risk score (PRS) is an aggregate genetic risk estimate derived by summing the effects of multiple common single nucleotide polymorphisms (SNPs) across the genome, each weighted by their per-allele effect size from a genome-wide association study (GWAS). In cardiovascular genetics, PRS are being developed to capture the cumulative contribution of common variants to complex traits such as QT interval duration and susceptibility to channelopathies.

## Key Concepts

### PRS for QT Interval in the General Population
- The QT interval has **25–50% heritability** in the general population. ([[sources/repolarisation-jaccep-2023]], rating: high)
- 2022 multiancestry GWAS (n=252,977) identified 176 independent QT-SNPs; individual common variants each contribute <1–2 ms to QT duration. ([[sources/repolarisation-jaccep-2023]])
- "QT-SNPs" are distributed across loci near known LQTS ion channel genes (KCNQ1, KCNH2, SCN5A, KCNE1, KCNJ2) and at many novel loci. PRS derived from these SNPs are being applied to predict LQTS susceptibility and disease modulation. ([[sources/repolarisation-jaccep-2023]])
- PRS also developed for **Tpeak-to-T-end interval** — some loci are specific to TpTe and do not overlap with QTc loci, suggesting partially distinct genetic control of repolarization heterogeneity. ([[sources/repolarisation-jaccep-2023]])

### PRS in Congenital LQTS — Susceptibility
- Lahrouchi et al. (2020) case-control GWAS (1,656 LQTS patients vs. 9,890 controls): QT-SNP-based PRS was significantly higher in LQTS cases vs. controls. Common SNPs explain **~15% of variance** in LQTS susceptibility — unequivocal evidence for a polygenic contribution to a classically Mendelian disease. ([[sources/repolarisation-jaccep-2023]])
- **Genotype-negative LQTS patients had a higher PRS than genotype-positive patients** — suggesting a more complex, non-Mendelian genetic architecture in the genotype-negative group, where common variants (in aggregate) substitute for a single high-penetrance rare variant in producing the LQTS phenotype. ([[sources/repolarisation-jaccep-2023]])
- Strong genome-wide genetic correlation between general population QTc and LQTS susceptibility — confirming a shared biology between QT interval regulation and congenital LQTS. ([[sources/repolarisation-jaccep-2023]])

### PRS in LQTS — Disease Severity Modulation
- **Kolder et al. (2015):** PRS from 22 QT-SNPs was associated with QTc duration in LQT2 patients. Patients in the highest PRS quartile may have a higher arrhythmia risk vs. the lowest quartile. ([[sources/repolarisation-jaccep-2023]])
- **Turkowski et al. (2020):** PRS from 61 SNPs was higher in LQTS probands with QTc ≥480 ms vs. <480 ms; PRS was higher in probands than in genotype-positive family members — supporting the role of common variants in modulating expressivity/severity independent of the Mendelian variant. ([[sources/repolarisation-jaccep-2023]])
- No significant association between PRS and cardiac events was detected in the Turkowski study, and the Lahrouchi et al. study could not detect PRS-QTc correlation due to low QTc variability in their proband-dominated cohort. ([[sources/repolarisation-jaccep-2023]])

### PRS in Drug-Induced QT Prolongation and TdP
- A PRS comprising 60 QT-SNPs was a **significant predictor of drug-induced TdP** in a case-control study (216 TdP vs. 771 controls). ([[sources/repolarisation-jaccep-2023]])
- The same PRS explained a substantial proportion of QTc response to three QTc-prolonging drugs (dofetilide, quinidine, ranolazine) in healthy individuals — demonstrating PRS utility as a pharmacogenomic predictor. ([[sources/repolarisation-jaccep-2023]])
- Individual QT-SNPs (NOS1AP, KCNQ1, KCNE1) have been shown to modulate QTc and arrhythmia risk in LQTS patients and drug-induced TdP cohorts. ([[sources/repolarisation-jaccep-2023]])

### PRS in ASCVD and Other CVD
- PRS has been validated for ASCVD risk stratification in the general population; genome-wide PRS for CAD has shown performance beyond traditional risk scores. See [[concepts/ASCVD-Risk-Assessment]] for the ACC/AHA PRS-in-ASCVD context. ([[sources/consumer-genetictest-aha-2025]])
- DTC genetic testing companies offer PRS-based CVD risk reports; regulatory and clinical validity concerns exist (SNP chip coverage, ancestry mismatch, lack of integration with clinical risk factors). See [[concepts/DTC-Genetic-Testing]]. ([[sources/consumer-genetictest-aha-2025]])

## Contradictions / Open Questions
- **PRS for LQTS — clinical utility not yet established:** Three PRS studies in LQTS (Lahrouchi, Kolder, Turkowski) give inconsistent results regarding QTc modulation and event prediction. Larger, well-characterised cohorts of probands and their gene-positive relatives are needed before PRS can inform clinical management. ([[sources/repolarisation-jaccep-2023]])
- **Genotype-negative LQTS — PRS as a diagnostic tool?** The finding that genotype-negative LQTS patients have higher PRS than genotype-positive patients suggests that PRS could eventually serve as a diagnostic adjunct for this group. However, no threshold PRS for LQTS diagnosis exists, and the sensitivity/specificity have not been established. ([[sources/repolarisation-jaccep-2023]])
- **SQTS — PRS entirely unstudied:** The authors note that modulatory variants (common or low-frequency) in SQTS have not been investigated. By analogy with LQTS, PRS from QTc-shortening variants would be expected to modulate SQTS susceptibility and severity — but this awaits investigation. ([[sources/repolarisation-jaccep-2023]])
- **Ancestry bias:** GWAS-derived QT-SNPs are predominantly identified in European-ancestry populations. PRS derived from these studies have reduced predictive validity in non-European populations. Ancestry-specific GWAS and multi-ancestry PRS are underway but not yet clinically validated. ([[sources/repolarisation-jaccep-2023]])
- **Common variant PRS vs. Mendelian variants — integration framework:** How to combine PRS (polygenic risk) with single high-impact Mendelian variants (e.g., KCNQ1 pore mutation) for individual risk estimation in LQTS is not established. A spectrum model is proposed (Figure 3 in source) but lacks a validated clinical algorithm. ([[sources/repolarisation-jaccep-2023]])

## Connections
- Related to [[concepts/Cardiac-Repolarization]]
- Related to [[entities/Long-QT-Syndrome]]
- Related to [[entities/Short-QT-Syndrome]]
- Related to [[concepts/Drug-Induced-Arrhythmia]]
- Related to [[concepts/Ion-Channel-Mutations]]
- Related to [[concepts/Variant-Reclassification]]
- Related to [[concepts/ASCVD-Risk-Assessment]]
- Related to [[concepts/DTC-Genetic-Testing]]
- Related to [[concepts/Genetic-Testing-in-Cardiomyopathy]]
