---
dg-publish: true
title: "Polygenic Risk Score"
tags: [polygenic-risk-score, long-qt-syndrome, cardiac-repolarization, genetics, precision-medicine, cardiomyopathy, GWAS, inherited-arrhythmias]
source_count: 4
last_updated: 2026-05-07
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

### GWAS-Derived Single-Variant Modifiers vs. Multi-SNP PRS
- A **61-SNP GWAS-derived QT risk score** (Strauss et al.) was prospectively validated in a randomised double-blind crossover trial of 3 QT-prolonging drugs, where it correlated with drug-induced QTc prolongation. Schwartz et al. propose applying this score to LQTS mutation carriers as the next step toward individual-level modifier gene risk stratification. ([[sources/modifier-genes-scd-ehj-2018]], rating: high)
- Single GWAS-derived variants (e.g., NOS1AP, KCNH2-K897T) function as individual modifier alleles, distinct from multi-SNP PRS in methodology but overlapping in clinical intent: refining arrhythmic risk beyond the primary Mendelian mutation. NOS1AP variants explain only part of the polygenic modifier contribution; the multi-SNP QT-PRS captures the aggregate effect of common variants. See [[entities/NOS1AP]] and [[concepts/Modifier-Genes]]. ([[sources/modifier-genes-scd-ehj-2018]])

### PRS in ASCVD and Other CVD
- PRS has been validated for ASCVD risk stratification in the general population; genome-wide PRS for CAD has shown performance beyond traditional risk scores. See [[concepts/ASCVD-Risk-Assessment]] for the ACC/AHA PRS-in-ASCVD context. ([[sources/consumer-genetictest-aha-2025]])
- DTC genetic testing companies offer PRS-based CVD risk reports; regulatory and clinical validity concerns exist (SNP chip coverage, ancestry mismatch, lack of integration with clinical risk factors). See [[concepts/DTC-Genetic-Testing]]. ([[sources/consumer-genetictest-aha-2025]])

### PRS in Hypertrophic Cardiomyopathy
- **Zheng 2025 HCM PRS — OR 2.34/SD:** Multi-ancestry HCM GWAS-derived PRS yields **OR 2.34 per SD increase** for HCM case status; performance is equivalent to rare sarcomeric variant carrier status for predicting phenotypic expressivity. ([[sources/gwas-arrhythmias-cmp-genes-2025]], rating: high)
- HCM PRS operates independently of sarcomeric variant status: individuals without identifiable pathogenic rare variants can still carry a high PRS that meaningfully elevates HCM risk — challenging the dichotomy between "genotype-positive" and "genotype-negative" HCM. ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- HCM PRS predicts adverse outcomes including death and clinical progression, suggesting independent prognostic value beyond the HCM Risk-SCD model. ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- Novel GWAS-identified HCM loci beyond sarcomere genes: FHOD3 (actin filament formation), ALPK3 (alpha-kinase/transcription), PLN (phospholamban/calcium handling), ACTN2 (alpha-actinin-2), CSRP3 (cardiac LIM protein). See [[entities/HCM]] and [[concepts/GWAS-Cardiac-Genetics]]. ([[sources/gwas-arrhythmias-cmp-genes-2025]])

### PRS in Dilated Cardiomyopathy and Inverse HCM-DCM Loci
- **Jurgens 2024 DCM PRS — multi-ancestry validation:** Multi-ancestry GWAS + MTAG-derived PRS validated in three populations: **OR 1.73 (European)**, **1.61 (African)**, and **1.34 (Admixed-American)** per SD increase. This is the most ancestry-diverse cardiac PRS validation for any cardiomyopathy to date. ([[sources/gwas-arrhythmias-cmp-genes-2025]], rating: high)
- **Inverse HCM-DCM risk loci (Tadros et al.):** Several GWAS loci at MYBPC3, ALPK3, and FHOD3 show *opposing* effect directions for HCM vs. DCM — the same SNP allele that increases HCM susceptibility decreases DCM susceptibility, and vice versa. This biologically confirms the sarcomere stiffness (HCM) vs. sarcomere insufficiency (DCM) axis at the common variant level. Therapeutic implication: **mavacamten** (reduces myosin cross-bridge engagement; HCM) and **omecamtiv mecarbil** (increases myosin cross-bridge formation; DCM) target opposing ends of the same contractility axis. ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- **BAG3 p.C151R:** Common low-frequency variant in BAG3 associated with DCM risk; effect size is larger than typical GWAS SNPs and sits at the intermediate boundary between common and rare variant spectra — acts as a modifier in addition to rare TTN/LMNA variants. ([[sources/gwas-arrhythmias-cmp-genes-2025]])

### PRS in Brugada Syndrome
- **Ishikawa 2024 BrS PRS — OR 2.12/SD:** BrS GWAS-derived PRS predicts spontaneous type 1 Brugada ECG pattern and a positive sodium channel blocker provocation test with **OR 2.12 per SD**. Critically, the same PRS does **NOT predict lethal arrhythmic events** (VF/SCD) — a clinically important dissociation between polygenic susceptibility to the ECG phenotype and arrhythmic risk. ([[sources/gwas-arrhythmias-cmp-genes-2025]], rating: high)
- 21 independent GWAS loci spanning 12 chromosomal regions; novel validated loci include **HEY2** (cardiac transcription factor) and **MAPRE2** (microtubule-end-binding protein implicated in myofilament organisation). ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- European-ancestry BrS PRS achieves similar predictive performance in Japanese BrS patients — notable because most cardiac GWAS-derived PRS lose accuracy across ancestry boundaries. ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- See [[entities/Brugada-Syndrome]] and [[concepts/GWAS-Cardiac-Genetics]]. ([[sources/gwas-arrhythmias-cmp-genes-2025]])

### PRS for Drug-Induced Long QT (diLQT)
- **Simon 2024 diLQT PRS — OR 1.34/SD, 30% variance explained:** A GWAS-based QT PRS explains approximately **30% of variance** in QTc prolongation during drug exposure, with **OR 1.34 per SD** for diLQT case status. Confirms that common variant architecture is a major determinant of QT-prolonging drug response beyond baseline QTc. ([[sources/gwas-arrhythmias-cmp-genes-2025]], rating: high)
- **Nauffal 2022:** Individuals in the top decile of QT-PRS have QTc approximately **8.7 ms longer** than the population mean — a magnitude comparable to the QTc effect of some monogenic LQTS variants. ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- Approximately **75% of individuals with markedly prolonged QTc** lack both a high PRS score AND an identifiable rare pathogenic variant — highlighting the dominant role of non-genetic/environmental factors (drugs, electrolyte disturbances, autonomic tone) even among patients presenting with "unexplained" QTc prolongation. ([[sources/gwas-arrhythmias-cmp-genes-2025]])
- **NOS1AP mechanistic confirmation:** NOS1AP variants (the most-replicated LQTS modifier discovered through QT-GWAS) were mechanistically validated in hiPSC-derived cardiomyocytes and mouse models via regulation of NOS1 (neuronal nitric oxide synthase) activity on cardiac repolarizing currents — confirming a biological pathway for the GWAS association. ([[sources/gwas-arrhythmias-cmp-genes-2025]])

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
- Related to [[concepts/Modifier-Genes]]
- Related to [[entities/NOS1AP]]
- Related to [[entities/HCM]]
- Related to [[entities/DCM]]
- Related to [[entities/Brugada-Syndrome]]
- Related to [[concepts/GWAS-Cardiac-Genetics]]
- Related to [[sources/modifier-genes-scd-ehj-2018]]
- Related to [[sources/gwas-arrhythmias-cmp-genes-2025]]

## Sources
- [[sources/consumer-genetictest-aha-2025]]
- [[sources/gwas-arrhythmias-cmp-genes-2025]]
- [[sources/modifier-genes-scd-ehj-2018]]
- [[sources/repolarisation-jaccep-2023]]
