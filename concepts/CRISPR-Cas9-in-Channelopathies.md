---
dg-publish: true
title: "CRISPR-Cas9 in Channelopathies"
tags: [gene-therapy, channelopathies, precision-medicine, genetics]
source_count: 1
last_updated: 2026-04-11
---

# CRISPR-Cas9 in Channelopathies

## Definition
CRISPR/Cas9 (Clustered Regularly Interspaced Short Palindromic Repeats and associated protein 9) is a gene-editing technology that uses a guide RNA to direct Cas9 endonuclease to a precise genomic location, inducing DNA double-strand breaks to knock out, correct, or modify target genes.

## Key Concepts
- In channelopathy research, CRISPR/Cas9 is introduced into iPSC-derived cardiomyocytes to compare properties of different ion channel variants, the same variant in different cellular contexts, and homozygous vs. heterozygous mutations — enabling fine-grained genotype-phenotype mapping. ([[sources/channelopathies-jaha-2025]])
- In CPVT, CRISPR/Cas9-mediated genome editing can be used to suppress dominant-negative or gain-of-function mutant alleles (e.g., RYR2), potentially correcting the Ca²⁺ dysregulation responsible for arrhythmias. ([[sources/channelopathies-jaha-2025]])
- CRISPR/Cas9 is complementary to CASQ2 gene reconstitution therapy in CPVT: where gene reconstitution restores a functional wild-type allele, CRISPR/Cas9 directly targets and silences the mutant allele. ([[sources/channelopathies-jaha-2025]])
- Clinical translation remains in early phases; current applications are primarily in research models (iPSC-CMs and animal models) rather than in patients. ([[sources/channelopathies-jaha-2025]])
- **First in-vivo CRISPR RYR2 repair (Pan 2023):** AAV9-SaCas9 targeting RYR2-R4496C achieved ~41% editing efficiency in cardiomyocytes; 0/7 treated vs. 7/8 untreated mice had arrhythmias during caffeine/epinephrine challenge; no off-target edits detected. ([[sources/gene-therapy-arrhythmia-2025]])
- **Base editing for LQT3 (Qi 2024):** Adenine base editor ABE8e-SpRY split across dual AAV9 corrected SCN5A-M1875T in mice; 54% efficiency; QTc and APD90 normalized; late INa reduced 66%; ~20% editing sufficient to prevent arrhythmias (source-sink electrotonic coupling buffers arrhythmia propagation). ([[sources/gene-therapy-arrhythmia-2025]])
- Allele-specific gene editing faces the same limitation as allele-specific silencing for highly heterogeneous genes (RYR2, KCNQ1, KCNH2) — each variant requires a distinct therapeutic construct. ([[sources/gene-therapy-arrhythmia-2025]])

## Contradictions / Open Questions
- **Allele-specific targeting vs. mutation heterogeneity:** CRISPR/Cas9-based correction requires a guide RNA designed for a specific mutation. In diseases with extreme mutational heterogeneity (RYR2: >150 variants; KCNQ1/KCNH2: hundreds of variants), individual correction constructs must be redesigned for each patient — clinically impractical. SupRep's mutation-agnostic approach was developed precisely to overcome this; CRISPR remains allele-specific unless targeting conserved non-coding regulatory elements or shared pathway nodes. ([[sources/gene-therapy-arrhythmia-2025]])
- **Off-target editing — long-term safety unknown:** The Pan 2023 in-vivo RYR2 CRISPR study reported no off-target edits by sequencing; however, comprehensive genome-wide off-target analysis in cardiomyocytes is technically limited, and long-term oncogenic or functional consequences in post-mitotic heart cells remain uncharacterized. This is a prerequisite for human trial approval. ([[sources/gene-therapy-arrhythmia-2025]])
- **Base editing vs. CRISPR cleavage — different risk profiles:** Base editing (ABE8e for LQT3) avoids DNA double-strand breaks and off-target indels, but is limited to specific substitution types (A→G with ABE). CRISPR/Cas9 cleavage addresses a broader range of mutations but carries higher DSB-related risk. Neither approach is validated in humans; no direct comparison exists for cardiac applications. ([[sources/gene-therapy-arrhythmia-2025]])

## Connections
- Related to [[concepts/iPSC-Derived-Cardiomyocytes]]
- Related to [[concepts/Ion-Channel-Mutations]]
- Related to [[entities/CPVT]]
- Related to [[entities/Long-QT-Syndrome]]
- Related to [[entities/RYR2]]
