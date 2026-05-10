---
dg-publish: true
title: "ClinGen Gene-Disease Validity Framework"
tags: [genetics, gene-disease-validity, clingen, variant-classification, precision-medicine]
source_count: 1
last_updated: 2026-05-09
---

# ClinGen Gene-Disease Validity Framework

## Definition
The ClinGen Gene-Disease Validity Framework is a standardized, semi-quantitative method for assessing the strength of evidence supporting a gene-disease relationship. Developed by the NIH-funded Clinical Genome Resource (ClinGen) Consortium, it is performed by disease-specific Gene Curation Expert Panels (GCEPs) and represents the international gold standard for deciding which genes should appear on clinical diagnostic panels and how results should be interpreted.

## Key Concepts

### Evidence Classification Tiers
The framework produces one of 7 classifications, in descending order of confidence:

1. **Definitive** — Overwhelming evidence: multiple independent studies in ≥2 families/unrelated probands; functional data available; >18 months of replicated evidence. Clinical use: gene should be on diagnostic panels; P/LP variants are reportable. ([[sources/clingen-summary-2026-05-09]], rating: high)

2. **Strong** — Convincing evidence from multiple studies but <18 months of replicated evidence, or lacking some functional validation. Clinical use: gene is appropriate for diagnostic panels. ([[sources/clingen-summary-2026-05-09]])

3. **Moderate** — Emerging evidence; the gene-disease relationship is plausible but requires more replication. Clinical use: panel inclusion varies by GCEP; results require careful interpretation. ([[sources/clingen-summary-2026-05-09]])

4. **Limited** — Some genetic or functional evidence, but insufficient for confident causal claim; typically <3 unrelated probands or no functional data. Clinical use: classification as VUS recommended rather than P/LP. ([[sources/clingen-summary-2026-05-09]])

5. **Disputed** — Existing evidence raises doubt about a previously proposed gene-disease relationship; prior publications may have used insufficient methodology. Clinical use: gene should NOT be on routine panels; P/LP interpretation would be misleading. ([[sources/clingen-summary-2026-05-09]])

6. **Refuting** — Multiple lines of evidence actively refute causation. Clinical use: gene should be removed from panels. ([[sources/clingen-summary-2026-05-09]])

7. **No known disease relationship** — Insufficient evidence to suggest any association. ([[sources/clingen-summary-2026-05-09]])

### Why This Matters Clinically
- Variants in genes with only "Limited" or weaker evidence should be classified as **Variants of Unknown Significance (VUS)**, not pathogenic or likely pathogenic — even if the variant appears biologically plausible.
- Genes with "Disputed" or lower classification are often included in older multi-gene panels; their results are frequently over-interpreted, leading to misdiagnosis and inappropriate management.
- ClinGen classifications update over time as evidence accumulates; a gene reclassification can change the clinical management of patients and families currently labeled "gene-positive." See [[concepts/Variant-Reclassification]].
- >36% reclassification rate in cardiovascular genetics panels, predominantly downgrading — clinicians must check for updated classifications.

### Cardiovascular GCEPs
Disease-specific expert panels in cardiovascular medicine:
- **Hereditary Cardiovascular Disease GCEP** — HCM, BrS, LQTS, SQTS, CPVT, ARVC, channelopathies
- **Dilated Cardiomyopathy GCEP** — DCM-specific gene curation
- **Hypertrophic Cardiomyopathy GCEP** — HCM-specific
- **Arrhythmogenic Right Ventricular Cardiomyopathy GCEP** — ARVC desmosomal genes
- **Long QT Syndrome GCEP** — ion channel genes
- **Catecholaminergic Polymorphic Ventricular Tachycardia GCEP** — RYR2/CASQ2 family
- **Pulmonary Hypertension GCEP** — BMPR2/CAV1 family

### Key Cardiovascular Findings (2026-05-09 Report)
**Genes with ClinGen Definitive or Strong evidence — selected cardiovascular highlights:**
- HCM: MYBPC3, MYH7, TNNI3, TNNC1, TPM1, FHOD3, CSRP3 (semidominant), ALPK3 (AR definitive/AD strong), ACTC1
- DCM: TTN, LMNA, MYH7, SCN5A, DES, FLNC, BAG3, RBM20, TNNC1, TNNT2, TNNI3, VCL, CAMK2D
- ARVC: PKP2, DSG2, DSC2, TMEM43, DSP (ACM + wooly hair)
- LQTS: KCNQ1, KCNH2, CALM1, CALM2, CALM3 (definitive); TRDN (strong)
- CPVT: RYR2, CASQ2 (AR), TECRL, TRDN (all definitive)
- BrS: SCN5A (via broad "SCN5A-related cardiac rhythm disorder" designation)
- PAH: BMPR2, CAV1, ATP13A3, EIF2AK4

**Genes with ClinGen Disputed or Refuting evidence — clinically important:**
- BrS claimed genes (disputed): KCNH2, CACNA1C, CACNB2, ABCC9, SCN10A, HCN4, SCN1B, SCN2B, PKP2
- BrS claimed genes (refuting): TRPM4, SCN3B
- HCM claimed genes (disputed): CALR3, MYH6, CASQ2, DSP (for HCM), VCL, KCNQ1, ANKRD1
- ARVC claimed genes (no known relationship): TNNC1, TNNI3, TNNT2, TPM1
- ARVC claimed genes (refuting): RYR2
- CPVT claimed genes (disputed): PKP2, KCNJ2
- LQTS claimed genes (disputed): SCN4B
- DCM claimed genes (disputed): PKP2

## Contradictions / Open Questions
- **Panel legacy problem:** Many commercial panels were built before ClinGen curations and still include genes now classified as "Disputed" or "Limited." Positive results for these genes generate anxiety, further testing, and in some cases inappropriate ICD implantation — without evidence of actual risk. ([[sources/clingen-summary-2026-05-09]])
- **Disputed ≠ definitely non-causal:** A "Disputed" classification means current evidence is insufficient to support prior claims, not that the gene is definitively unrelated. Some currently disputed genes may be reclassified as evidence grows (e.g., new large cohort studies, functional data). Clinicians should not dismiss all variants in disputed genes; context matters. ([[sources/clingen-summary-2026-05-09]])
- **Classification lag:** ClinGen curations may lag behind published literature by years for rapidly evolving genes. The 2026-05-09 report reflects the latest available curations but may not capture the most recent publications. ([[sources/clingen-summary-2026-05-09]])

## Connections
- Related to [[concepts/Variant-Reclassification]]
- Related to [[concepts/Cardiogenetic-Centers]]
- Related to [[concepts/Genetic-Testing-in-Cardiomyopathy]]
- Related to [[concepts/Genetic-Testing-in-AF]]
- Related to [[sources/arrhythmia-genetics-mgenetik-2025]]
- Related to [[entities/HCM]]
- Related to [[entities/DCM]]
- Related to [[entities/ARVC]]
- Related to [[entities/Brugada-Syndrome]]
- Related to [[entities/CPVT]]
- Related to [[entities/Long-QT-Syndrome]]
- Related to [[entities/Pulmonary-Hypertension]]

## Sources
- [[sources/genetic-test-aha-2020]]
- [[sources/clingen-summary-2026-05-09]]