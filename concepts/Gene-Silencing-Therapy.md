---
dg-publish: true
title: "Gene Silencing Therapy"
tags: [gene-therapy, channelopathies, RNA-interference, precision-medicine]
source_count: 1
last_updated: 2026-04-11
---

# Gene Silencing Therapy

## Definition
Gene silencing therapy (GST) is a class of gene therapy that attenuates expression of a target gene at the RNA level without altering the underlying DNA sequence. It is primarily used to counteract gain-of-function or dominant-negative mutations. Key modalities include antisense oligonucleotides (ASOs), RNA interference (RNAi via siRNA/shRNA), and CRISPR interference (CRISPRi).

## Key Concepts
- **Antisense oligonucleotides (ASOs):** Single-stranded DNA or RNA sequences that bind complementary mRNA, promoting RNase H-mediated degradation or blocking translation. Deliverable without viral vectors. ([[sources/gene-therapy-arrhythmia-2025]])
- **Small interfering RNA (siRNA):** Double-stranded RNA incorporated into the RISC complex that cleaves complementary target mRNA. Used to silence mutant CASQ2-R33Q in CPVT: siRNA reduced mutant mRNA/protein by ~60% and prevented arrhythmias after 3 injections every 2 weeks (Bongianino 2017). ([[sources/gene-therapy-arrhythmia-2025]])
- **Short hairpin RNA (shRNA):** Viral-vector-encoded siRNA precursor enabling stable, long-term gene silencing. Core component of SupRep therapy — shRNA silences both WT and mutant endogenous transcripts, paired with shRNA-immune replacement cDNA. ([[sources/gene-therapy-arrhythmia-2025]])
- **CRISPRi:** Uses a catalytically inactive Cas9 (dCas9) with a guide RNA to block transcription without cleaving DNA. Emerging tool for cardiac gene silencing. ([[sources/gene-therapy-arrhythmia-2025]])
- **Allele-specific silencing:** Targets only the pathogenic allele by exploiting SNPs near the mutation site. Applied to RYR2 in CPVT1 — suppressed arrhythmias and restored junctional SR ultrastructure (Bongianino 2017). Limitation: variant-specific constructs needed for each mutation, impractical in highly heterogeneous diseases. ([[sources/gene-therapy-arrhythmia-2025]])
- **Dominant-negative gene transfer** (a form of GST): Delivery of a non-functional dominant-negative protein that outcompetes the endogenous channel. Examples in AF: dominant-negative KCNH2-G628S prolonged atrial APD and reduced AF inducibility in porcine models. ([[sources/gene-therapy-arrhythmia-2025]])
- GST is combined with replacement cDNA in SupRep therapy to achieve mutation-agnostic treatment of heterozygous channelopathies. ([[sources/gene-therapy-arrhythmia-2025]])

## Contradictions / Open Questions
- **Durability of siRNA vs. shRNA:** siRNA-mediated silencing (e.g., allele-specific siRNA for CASQ2-R33Q in CPVT) required 3 injections every 2 weeks to maintain effect in mice — it is not a single-dose durable therapy. shRNA delivered via AAV provides stable long-term silencing but inherits all AAV re-dosing and immune limitations. No head-to-head durability comparison exists, and neither approach has human data. ([[sources/gene-therapy-arrhythmia-2025]])
- **Dominant-negative KCNH2 for AF — transient adenoviral expression:** Adenoviral delivery of KCNH2-G628S prolonged atrial APD and reduced AF inducibility in porcine models, but the effect was lost by day 21 when transgene expression was lost. Without a durable vector, this approach cannot transition to clinical use for a chronic disease like AF. The discrepancy between biological proof-of-concept and translational practicality is unresolved. ([[sources/gene-therapy-arrhythmia-2025]])

## Connections
- Related to [[concepts/SupRep-Therapy]]
- Related to [[concepts/AAV-Gene-Delivery]]
- Related to [[concepts/CRISPR-Cas9-in-Channelopathies]]
- Related to [[entities/CPVT]]
- Related to [[entities/Long-QT-Syndrome]]
- Related to [[entities/Atrial-Fibrillation]]
- Related to [[entities/RYR2]]
- Related to [[entities/KCNH2]]
