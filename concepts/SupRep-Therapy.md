---
dg-publish: true
title: "Suppression-and-Replacement (SupRep) Therapy"
tags: [gene-therapy, channelopathies, LQTS, precision-medicine]
source_count: 1
last_updated: 2026-04-11
---

# Suppression-and-Replacement (SupRep) Therapy

## Definition
Suppression-and-replacement (SupRep) therapy is a hybrid gene therapy strategy that simultaneously silences endogenous gene expression (via shRNA targeting both wild-type and mutant transcripts) while reintroducing a functional, knockdown-resistant wild-type transgene. It addresses the limitations of allele-specific targeting in diseases with extreme mutational heterogeneity.

## Key Concepts
- **Why SupRep is needed:** In LQTS caused by KCNQ1 or KCNH2 mutations, hundreds of rare disease-causing variants exist with no single predominant mutation. Allele-specific RNAi must be redesigned for each variant, making it clinically impractical. SupRep is mutation-agnostic. ([[sources/gene-therapy-arrhythmia-2025]])
- **Mechanism:** shRNA suppresses endogenous transcripts (both wild-type and mutant); a shRNA-immune engineered cDNA restores protein function. Both components are typically co-delivered via AAV9. ([[sources/gene-therapy-arrhythmia-2025]])
- **LQT1 (KCNQ1) results:** AAV9-SupRep normalized QTi and APD90 in transgenic LQT1 rabbits; restored physiological β-adrenergic QT shortening; reduced QT dispersion. No inflammation or adverse events (Bains 2024; Dotzler 2023). ([[sources/gene-therapy-arrhythmia-2025]])
- **LQT2 (KCNH2) results:** AAV9-SupRep normalized QTc (470 → 414 ms in rabbits); suppressed early afterdepolarizations and TdP inducibility (Bains 2023). ([[sources/gene-therapy-arrhythmia-2025]])
- **SQTS1 (gain-of-function KCNH2 N588K):** shRNA-only silencing (no replacement needed for gain-of-function) prolonged QTc from 283 to 333 ms; reduced TdP inducibility (5/7 → 1/8 animals). ([[sources/gene-therapy-arrhythmia-2025]])
- **SupRep has also been applied to:** hiPSC-CM models of LQT2, SQTS1, and calmodulin-associated LQTS — demonstrating versatility across multiple channelopathy genotypes. ([[sources/gene-therapy-arrhythmia-2025]])
- **Critical dosing balance:** Excess suppression without adequate replacement worsens the LQTS phenotype; excess replacement without suppression risks inducing a short QT phenotype. Iterative dose escalation and in silico modeling required. ([[sources/gene-therapy-arrhythmia-2025]])
- **Broader applicability:** The modular, scalable approach holds potential for any monogenic cardiovascular disorder characterized by dominant-negative pathophysiology. ([[sources/gene-therapy-arrhythmia-2025]])

## Contradictions / Open Questions
- **Critical dosing balance — therapeutic window undefined in humans:** Excess shRNA suppression without adequate replacement worsens the LQTS phenotype (insufficient IKs/IKr); excess replacement without suppression risks inducing a short QT phenotype. This balance has been demonstrated in animal models but the therapeutic window has never been established in humans. Phase I dose-escalation trials will need to define safe ratios before broader clinical use. ([[sources/gene-therapy-arrhythmia-2025]])
- **SupRep for SQTS1 — silencing only, no replacement:** For SQTS1 (gain-of-function KCNH2), shRNA silencing alone (without replacement) is the therapeutic goal. But excessive silencing of KCNH2 in a patient whose baseline QTc is already short risks inducing LQT2. The optimal silencing dose is even more tightly constrained in this context. ([[sources/gene-therapy-arrhythmia-2025]])
- **AAV delivery limitations apply:** SupRep is co-delivered via AAV9. All AAV constraints (pre-existing immunity, re-dosing restrictions, episomal dilution in pediatric patients, liver off-target) apply to SupRep. The durability of the shRNA+cDNA combination in human cardiomyocytes over decades is untested. ([[sources/gene-therapy-arrhythmia-2025]])

## Connections
- Related to [[concepts/AAV-Gene-Delivery]]
- Related to [[concepts/Gene-Silencing-Therapy]]
- Related to [[concepts/iPSC-Derived-Cardiomyocytes]]
- Related to [[entities/Long-QT-Syndrome]]
- Related to [[entities/Short-QT-Syndrome]]
- Related to [[entities/KCNQ1]]
- Related to [[entities/KCNH2]]
