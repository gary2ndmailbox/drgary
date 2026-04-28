---
dg-publish: true
title: "Heteroplasmy"
tags: [mitochondrial-genetics, cardiovascular-disease, genetics]
source_count: 1
last_updated: 2026-04-25
---

# Heteroplasmy

## Definition
Heteroplasmy is the coexistence of multiple, genetically distinct mitochondrial DNA (mtDNA) copies within the same cell or organism, where different copies carry different sequence variants. This contrasts with homoplasmy, where all mtDNA copies carry the same allele (variant allele frequency [VAF] = 100%). Heteroplasmic variants exist at VAFs between 0% and 100%.

## Key Concepts

### Biology of Heteroplasmy
- Each mitochondrion contains multiple mtDNA copies; each cell contains hundreds to thousands of total copies distributed across the mitochondrial network. [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- Heteroplasmic variants may be **maternally inherited** or **somatically acquired** over a lifetime. [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- Heteroplasmy is dynamic: levels can shift through **relaxed replication** (mtDNA replication not tied to cell cycle, allowing stochastic drift), cell division with random segregation into daughter cells, and cell-type-specific selective pressures. [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- In non-proliferative cells (e.g. cardiomyocytes), pathogenic heteroplasmic variants can expand over time. [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- Environmental exposures modify heteroplasmy: cigarette smoke increases mtDNA damage and deletion levels; alcohol can trigger disease in PPA2-variant carriers. [[sources/mitochondrial-cv-aha-2025]] ★★★★★

### Biochemical and Phenotypic Thresholds
- A pathogenic variant must reach a cell-type-specific **biochemical threshold** VAF before OXPHOS function is measurably impaired. [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- A higher **phenotypic threshold** must be reached before clinical disease manifests. [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- For most pathogenic variants, these thresholds are **unknown**; for tRNA-encoding genes, a VAF >60% is typically required. [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- Example: m.3243A>G (MELAS variant) — OXPHOS is intact until VAF >60%; at 30–40% VAF, mTOR/growth signalling is downregulated; at 50–90%, glycolytic upregulation and complex IV decline. [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- Heteroplasmy levels modulate clinical phenotype: same variant at 10–40% → MIDD; at 50–80% → MELAS; >90% → lethal pediatric disease. [[sources/mitochondrial-cv-aha-2025]] ★★★★★

### Age-Related Accumulation and CVD
- Heteroplasmic variant levels increase with advancing age in the general population. [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- Higher heteroplasmic variant levels in circulating blood cells are associated with CVD in humans. [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- The common 4.977-kb deletion (m.4977DEL) is elevated 10–200-fold in explanted hearts of patients with ischaemic heart disease compared to normal hearts. [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- m.4977DEL levels independently predict MACE and all-cause mortality in coronary artery disease patients; combined short leukocyte telomere length + high m.4977DEL confers highest risk. [[sources/mitochondrial-cv-aha-2025]] ★★★★★

### mtDNA Haplogroups
- Mitochondrial haplogroups are collections of related mtDNA sequences defined by homoplasmic variants reflecting prehistoric human migration patterns. [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- Haplogroups are associated with hypertension, cardiomyopathies, atherosclerosis, MI, ischaemic stroke, cardiac transplant complications, aortic aneurysm, and AF — although with contradictory reports in the literature. [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- Haplogroup can modify penetrance of pathogenic mtDNA variants. [[sources/mitochondrial-cv-aha-2025]] ★★★★★

### Detection — NGS Best Practices
- VAF threshold for defining heteroplasmy varies by sequencing method, depth, and error rates; no population consensus exists. [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- WGS typically achieves >500–1000× mtDNA depth, enabling detection at VAF ≥3–10%. [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- Nuclear mtDNA segments (NuMTs) are major sources of false-positive heteroplasmic calls and must be filtered before alignment, not just by post-hoc annotation. [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- Sample-specific consensus reference sequences improve detection of low-level heteroplasmic variants over the standard rCRS. [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- Long-read WGS enables phasing — identifying which variants reside on the same mtDNA molecule. [[sources/mitochondrial-cv-aha-2025]] ★★★★★

### Therapeutic Implications
- Gene editing strategies aim to shift heteroplasmy below the biochemical threshold by selectively degrading pathogenic mtDNA copies or enriching reference copies. [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- TALE/zinc-finger mitochondrially targeted deaminases can reduce pathogenic heteroplasmy but introduce off-target bystander variants. [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- CRISPR-Cas9 cannot currently target the mitochondrial matrix (no guide RNA transport mechanism). [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- TFAM overexpression in the m.5024C>T mouse model partially rescued cardiomyopathy without changing heteroplasmy levels, suggesting that increasing total mtDNA copy number may dilute pathogenic variant effects. [[sources/mitochondrial-cv-aha-2025]] ★★★★★

## Contradictions / Open Questions
- Causal vs. secondary vs. bystander role of heteroplasmic variants and mtDNA deletions in common CVD is not established. [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- Optimal VAF threshold for defining heteroplasmic variants in clinical NGS pipelines is not yet standardized. [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- Whether heteroplasmy levels in blood reliably reflect levels in cardiac tissue (the clinically relevant tissue) is unclear; disease-causing variants may be lost or underrepresented in circulating blood cells in adults. [[sources/mitochondrial-cv-aha-2025]] ★★★★★
- Thresholds for m.3243A>G and most other pathogenic variants vary by haplogroup, tissue sampled, and patient age — the same heteroplasmy level may cause MIDD in one patient and MELAS in another. [[sources/mitochondrial-cv-aha-2025]] ★★★★★

## Connections
- Related to [[concepts/Mitochondrial-Cardiomyopathy]] — central mechanism of disease penetrance
- Related to [[concepts/Genetic-Testing-in-Cardiomyopathy]] — NGS and WGS best practices for mtDNA variant detection
- Related to [[entities/HCM]] — mitochondrial HCM; heteroplasmy as a disease modifier
- Related to [[entities/DCM]] — mitochondrial DCM from high heteroplasmy
- Related to [[entities/Atrial-Fibrillation]] — m.3243A>G and haplogroup associations with AF
