---
dg-publish: true
title: "Mitochondrial Genetics in Cardiovascular Health and Disease: A Scientific Statement From the American Heart Association"
date_ingested: 2026-04-25
source_type: consensus
Citation: "Fetterman JL, Chinnery PF, McClellan R, Wallace DC, Suomalainen A, Ojala T, Lewis SC, Ballinger SW; on behalf of the American Heart Association. Mitochondrial genetics in cardiovascular health and disease: a scientific statement from the American Heart Association. Circulation. 2026;153:e42–e68."
DOI: "https://doi.org/10.1161/CIR.0000000000001393"
tags: [mitochondrial-genetics, cardiomyopathy, arrhythmia, genetic-testing, cardiovascular-disease]
rating: very high
raw_path: raw/Mitochrondrial-CV-AHA-2025.md
---

# Mitochondrial Genetics in Cardiovascular Health and Disease: A Scientific Statement From the American Heart Association

## Authors, Journal, Affiliations, Type, DOI
- Jessica L. Fetterman PhD FAHA (Chair), Patrick F. Chinnery MBBS PhD (Vice Chair), Rebecca McClellan MGC CGC, Douglas C. Wallace PhD, Anu Suomalainen MD PhD, Tiina Ojala MD PhD, Samantha C. Lewis PhD, Scott W. Ballinger PhD
- *Circulation* 2026;153:e42–e68
- On behalf of the AHA Council on Genomic and Precision Medicine; Council on Cardiopulmonary, Critical Care, Perioperative and Resuscitation; Council on Cardiovascular and Stroke Nursing; and Council on Peripheral Vascular Disease
- AHA Scientific Statement (approved August 13, 2025; published February 3, 2026)
- DOI: 10.1161/CIR.0000000000001393

## Overview
This AHA Scientific Statement comprehensively reviews the role of mitochondrial DNA (mtDNA) genetic variation in cardiovascular health and disease. It covers best practices for NGS-based mtDNA variant identification, the cardiovascular manifestations of rare mitochondrial syndromes (~30% cardiac involvement; CVD is the leading cause of adult death), population-level evidence linking mtDNA variants and haplogroups to common CVD risk factors, animal and cell models, emerging gene-editing technologies, and the inflammatory mechanisms linking mitochondrial dysfunction to cardiovascular pathobiology. The statement identifies substantial knowledge gaps and calls for larger ancestrally diverse genomic datasets, improved mtDNA editing tools, and better mechanistic models.

## Keywords
AHA Scientific Statements; cardiovascular diseases; DNA, mitochondrial; genes, mitochondrial; mitochondria

## Key Takeaways

### Mitochondrial Genetics Basics
- The heart consumes 6 g of ATP/day, predominantly from OXPHOS; OXPHOS complex I, III, IV, V core subunits are encoded by the 16.6 kb circular mtDNA
- Each cell contains hundreds to thousands of mtDNA copies; variants may be **homoplasmic** (all copies identical, VAF 100%) or **heteroplasmic** (different copies carry different variants at varying VAFs)
- Heteroplasmy is dynamic: increases with advancing age, is affected by environmental exposures (smoking, alcohol), and may be maternally transmitted with random segregation
- A pathogenic variant must reach a cell-specific **biochemical threshold** VAF before OXPHOS function is impaired, and a higher **phenotypic threshold** before disease manifests; thresholds are largely unknown except for tRNA variants (typically >60% VAF)
- **Nuclear mtDNA segments (NuMTs)** — fragments of mtDNA inserted into the nuclear genome — are a major source of false-positive heteroplasmic variant calls in NGS datasets

### Best Practices for mtDNA NGS
- WGS at standard 30× nuclear depth provides >500–1000× mtDNA depth, adequate for heteroplasmic variant detection at VAF ≥3–10%; WES often insufficient mtDNA depth
- Long-read WGS enables phasing (variants on same mtDNA molecule) and superior structural variant detection
- Bioinformatic pipeline must: (1) circularize mtDNA reference at alignment, (2) filter NuMT-derived reads, (3) construct a sample-specific consensus reference, (4) apply rigorous QC (depth ≥400–500×, quality scores ≥30, haplogroup contamination check)
- Revised Cambridge Reference Sequence (rCRS) introduces European ancestry bias; sample-specific consensus reference preferred
- WGS (or WES) recommended as first-line testing for suspected mitochondrial disease, not targeted panels — most cardiomyopathy/arrhythmia panels do not include mitochondrial genes

### Mitochondrial Diseases — Cardiac Manifestations
- ~30% of patients with genetically confirmed mitochondrial disorders have cardiovascular involvement; CVD is the **leading cause of death** in adults with mitochondrial disorders
- Cardiomyopathy and ECG abnormalities present in 29–40% and 39–68% of patients respectively; pediatric survival with cardiac involvement is only 18%
- **HCM is the most common cardiomyopathy phenotype** (may present antenatally); obstructive HCM is rare; HCM may progress to systolic dysfunction and DCM; RCM is rare
- **Key mtDNA syndromes with cardiac manifestations:**
  - *MELAS* (m.3243A>G in MT-TL1): HCM most common, also DCM, RCM, hypertrabeculation, WPW, SCD — heteroplasmy 50–80% for MELAS presentation
  - *MIDD* (m.3243A>G at lower VAF 10–40%): HCM, DCM, WPW, AF, sinoatrial node dysfunction
  - *MERRF* (m.8344A>G in MT-TK): DCM, HCM, WPW, SVT, RBBB
  - *Kearns-Sayre syndrome* (large sporadic mtDNA deletion): cardiac manifestations in up to 50%; SCD in up to 20% from complete heart block; DCM, LBBB/RBBB, torsades de pointes
  - *LHON* (m.11778G>A, m.3460G>A, m.14484T>C): HCM, WPW, VT, SCD; mortality doubled vs general population
  - *Leigh syndrome* (>100 genes, mtDNA and nuclear): HCM most common; also DCM, WPW
  - *Pearson syndrome* (large mtDNA deletion): LVH, LQT, conduction abnormalities
- **Key nuclear-encoded mitochondrial diseases with cardiac manifestations (selected):**
  - *Barth syndrome* (TAFAZZIN, X-linked): DCM, hypertrabeculation, LQT, WPW; 70% survival, mean life expectancy 40 y
  - *DCMA syndrome* (DNAJC19, AR): DCM, LQT; most deaths by 15 months
  - *Friedreich ataxia* (FXN triplet repeat, AR): HCM, DCM, HF, AF; mean life expectancy 40 y
  - *PPA2* variants (AR): SCD and VF triggered by even minimal alcohol consumption at any age — alcohol abstinence mandatory counselling
  - *Leigh syndrome complex I/IV deficiency*: HCM most common
- Patients with MERRF, MELAS, or MIDD should be screened with cardiac evaluation (ECG, echo or CMR) every 3–5 years even without cardiac symptoms

### Clinical Care and Management
- Coordinated multidisciplinary care: neurology, cardiology, arrhythmia management, pulmonology, genetics
- Cardiac evaluation at diagnosis and periodically: physical exam, ECG, ambulatory ECG, echocardiography or CMR
- CMR underused in mitochondrial disease but provides detailed tissue characterization for differential diagnosis
- Conventional treatments: HF therapy, pacing, CRT, ICD, heart transplantation (rare cases)
- No randomized trial evidence supports targeted mitochondrial interventions over conventional symptom-based treatment

### mtDNA Variation and Common CVD
- Population-level studies have primarily assessed haplogroups or select variants; global mtDNA variation study is limited
- Mitochondrial haplogroups associated with hypertension, cardiomyopathies, atherosclerosis, MI, ischemic stroke, cardiac transplant complications, aortic aneurysm, and AF — though with contradictory reports
- Higher levels of heteroplasmic variants in circulating blood cells are associated with advancing age and CVD
- The **common 4.977-kb deletion** (m.4977DEL) is independently predictive of major adverse cardiovascular events (MACE) and all-cause mortality in patients with coronary artery disease
- m.3243A>G at higher levels in the general population associates with higher pulse wave velocity, fasting insulin, and all-cause/stroke mortality
- tRNA heteroplasmic variants correlated with carotid intima-media thickness and coronary heart disease; directionality of association varies (some variants positively, some negatively correlated)
- Cigarette smoke increases mtDNA damage, lowers mtDNA copy number, and alters heteroplasmy to promote pathogenic variant penetrance

### Models for Studying mtDNA
- **Mouse models:** Xenomitochondrial, conplastic, and mitochondrial-nuclear exchange models used; heteroplasmy >10% linked to pulmonary hypertension, right-sided HF, and reduced lifespan; MT-TA m.5024C>T model shows mild progressive cardiomyopathy partially rescued by TFAM overexpression
- **Invertebrate models:** *Drosophila* (has heart tube) and *C. elegans* (basic mtDNA biology) useful for tractable genetics
- **Cybrids:** Cancer cell lines depleted of mtDNA then fused with patient platelets/cytoplasm; VAF >60% needed for OXPHOS impairment with m.3243A>G; cytoplasmic heteroplasmy levels affect epigenetic state via metabolite availability
- **iPSC-derived cardiomyocytes:** Reprogramming mimics the mtDNA bottleneck; most heteroplasmic variants persist in iPSCs and derived cardiomyocytes; sequencing must confirm genotype at each step; some pathogenic variants interfere with cardiomyocyte differentiation
- **mtDNA gene editing:** TALE/zinc-finger-targeted deaminases can shift heteroplasmy but have off-target effects (bystander mutations); CRISPR-Cas9 cannot be delivered to mitochondrial matrix (no guide RNA transport); targeted point variant introduction remains a challenge

### Mechanisms of Mitochondrial Genetics in CVD
- **Transcriptional/translational:** PGC-1α/β and nuclear respiratory factors coordinate biogenesis across both genomes; downregulated mitochondrial biogenesis (including aminoacyl-tRNA synthetases, mitoribosome assembly factors) is a feature of DCM; deleterious tRNA variants and nuclear-encoded tRNA synthetase variants cause maternally inherited cardiomyopathy
- **Metabolic consequences:** Altered OXPHOS affects amino acid, fatty acid, cholesterol, purine, and porphyrin biosynthesis; mitochondrial metabolites (acetyl-CoA, α-ketoglutarate, succinate, NAD+) regulate epigenetic gene expression; mitochondrial calcium uniporter and Na+/Ca2+ exchanger dysregulation linked to HF, hypertrophy, and ischaemia-reperfusion injury
- **Inflammation:** Released mtDNA acts as damage-associated molecular pattern (DAMP); activates TLR9 → NF-κB and proinflammatory cytokines; cGAS-STING → type I interferon response; NLRP3 and AIM2 inflammasome activation → IL-1β and cell death; cGAS-STING activated by cigarette smoke-induced mtDNA damage; TLR9 expressed in cardiomyocytes and endothelial cells (not only immune cells)

### Future Directions and Gaps
- Need larger ancestrally diverse population genomics datasets (current datasets predominantly European)
- Need better understanding of mtDNA homeostasis in native tissue; interindividual vs. intraindividual mtDNA copy number variation
- Role of mitokines (GDF15, FGF-21) released from skeletal muscle on the heart largely unstudied
- Machine learning and large-scale omics could improve patient classification and therapeutic response prediction
- New NGS, iPSC, and gene editing tools are creating unprecedented opportunities to study mitochondrial genetics in cardiovascular disease

## Limitations of the Document
- Most cited population studies have small sample sizes (<1000 individuals), limited ancestral diversity, and assess only a handful of mtDNA variants rather than global variation
- Many studies do not adjust for key confounders (age, smoking); multiple testing corrections often absent; external validation lacking
- Causal inference is limited — it is unclear whether mtDNA deletions and variants are causal, secondary, or bystanders in CVD
- iPSC-derived cardiomyocytes remain immature and may not fully recapitulate adult cardiac biology
- No RCT evidence supports targeted mitochondrial therapies over conventional treatments
- The biochemical threshold VAF for most pathogenic variants outside tRNA genes is unknown

## Key Concepts Mentioned
- [[concepts/Mitochondrial-Cardiomyopathy]] — primary concept page for cardiac manifestations of mitochondrial disease
- [[concepts/Heteroplasmy]] — dynamic mtDNA variant state; biochemical threshold; age-related accumulation; CVD association
- [[concepts/Genetic-Testing-in-Cardiomyopathy]] — WGS recommended over panels for suspected mitochondrial disease

## Key Entities Mentioned
- [[entities/HCM]] — most common cardiomyopathy phenotype in mitochondrial disease
- [[entities/DCM]] — secondary to HCM or primary in mitochondrial disease; DNAJC19, TWNK, MGME1 causes
- [[entities/Long-QT-Syndrome]] — LQT in multiple mitochondrial syndromes (Kearns-Sayre, Barth, Leigh, Pearson)
- [[entities/Atrial-Fibrillation]] — MIDD (m.3243A>G) causes AF; mitochondrial haplogroups associated with AF
- [[entities/Heart-Failure]] — leading cause of death in mitochondrial disorders; HF therapies appropriate
- [[entities/Pulmonary-Hypertension]] — pulmonary hypertension and right-sided HF in heteroplasmic mouse models

## Wiki Pages Updated
- `wiki/sources/mitochondrial-cv-aha-2025.md` — created (this file)
- `wiki/sourceindex.md` — source entry added
- `wiki/wikiindex.md` — new concept entries added
- `wiki/concepts/Mitochondrial-Cardiomyopathy.md` — created
- `wiki/concepts/Heteroplasmy.md` — created
- `wiki/entities/HCM.md` — updated with mitochondrial HCM section
- `wiki/entities/DCM.md` — updated with mitochondrial DCM causes
- `wiki/concepts/Genetic-Testing-in-Cardiomyopathy.md` — updated with mtDNA testing guidance
