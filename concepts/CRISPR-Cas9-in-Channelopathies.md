---
dg-publish: true
title: "CRISPR-Cas9 in Channelopathies"
tags: [gene-therapy, channelopathies, precision-medicine, genetics, gene-editing]
source_count: 4
last_updated: 2026-05-23
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
- **Prime editing:** A third-generation approach enabling precise sequence changes without DNA double-strand breaks and without being restricted to specific base conversions (unlike base editing). Promising for correcting point mutations causing inherited cardiac conditions; requires optimised delivery systems. ([[sources/gene-editing-cv-tcm-2025]] — medium)
- **Disease applications beyond channelopathies — gene editing in cardiomyopathies:**
  - *HCM (MYBPC3):* Ma et al. 2017 — CRISPR-Cas9 corrected heterozygous MYBPC3 4 bp deletion in human preimplantation embryos at high efficiency; preferential HDR repair using wild-type oocyte allele as template; requires further reproducibility before clinical use. ([[sources/gene-editing-cv-tcm-2025]])
  - *Calmodulinopathy-LQTS (CALM2):* Limpitikul et al. 2017 — CRISPRi selectively suppresses mutant CALM2 gene sparing wild-type; normalised APD and Ca²⁺/CaM-dependent L-type Ca²⁺ channel inactivation in iPSC-derived CMs; potential mutation-agnostic approach. ([[sources/gene-editing-cv-tcm-2025]])
  - *DMD cardiomyopathy (Dystrophin):* Refaey et al. 2017 — AAV-SaCas9 excises mutant exon 23; 40% dystrophin restoration in cardiac muscle; improved fibre architecture and contractility. ([[sources/gene-editing-cv-tcm-2025]])
  - *PRKAG2 cardiac syndrome:* AAV9-CRISPR/Cas9-sgRNA single postnatal injection restored cardiac function in mice; CRISPR correction in iPSC-CMs normalised arrhythmic behaviour — paradigm case for gene editing over standard ablation. ([[sources/gene-editing-cv-tcm-2025]]; see [[entities/PRKAG2-Cardiac-Syndrome]])
- **Mosaicism threshold:** In in vivo cardiac gene editing, >70% phenotypic correction is required to achieve restoration of cardiac function in mouse models. Heterogeneous editing (regions of corrected and uncorrected myocardium) carries risks of arrhythmia from electrophysiological heterogeneity, compensatory fibrosis, and neoantigen immunogenicity. ([[sources/gene-editing-cv-tcm-2025]])
- **Risk-benefit framework:** Gene editing is clinically appropriate when existing standard therapy is insufficient for the disease burden (e.g., PRKAG2 syndrome, HoFH, TTR amyloidosis, CPVT) and inappropriate when effective alternatives exist (e.g., isolated WPW — ablation 90–95% success). See [[concepts/Gene-Editing-Risk-Benefit-Framework]]. ([[sources/gene-editing-cv-tcm-2025]])
- **First in-human CRISPR-Cas9 in ATTR-CM — Phase 1 clinical translation (Fontana et al. NEJM 2024):** Nexiguran ziclumeran (nex-z/NTLA-2001) uses a hepatotropic LNP (not AAV) to deliver single-guide RNA + Cas9 mRNA to hepatocytes, permanently knocking out the TTR gene via NHEJ in 36 patients with ATTR-CM. Mean serum TTR reduction −89% at 28 days, −90% at 12 months, sustained through 24 months — demonstrating that LNP-delivered CRISPR can achieve durable, deep in vivo gene knockout in humans with a single infusion. LNP delivery has distinct practical advantages over AAV: no pre-existing immunity exclusion, no viral genome, rapid clearance. The permanent nature of the edit distinguishes nex-z from RNAi (vutrisiran/patisiran), which require repeat dosing. **MAGNITUDE Phase 3 trial paused Oct 2025 due to rare severe hepatotoxicity, including one death from liver failure** — a signal not anticipated from Phase 1 data. See [[entities/Nexiguran-Ziclumeran]]. ([[sources/nexz-crispr-attrcm-nejm-2024]] — high; [[sources/gene-editing-acc-2026]] — very high)
- **2026 ACC statement — GET delivery platform framework:** The ACC 2026 scientific statement codifies the strategic rule: LNP for hepatic targets (ATTR-CM, lipid disorders), AAV for cardiac targets. Only disorders where pathogenic protein is hepatically produced are tractable with current LNP-GET; LNP has advantages of re-dosability and lower immunogenicity vs. AAV. LNP modifications are in development to target non-liver tissues. ([[sources/gene-editing-acc-2026]] — very high)
- **DMD clinical fatality — AAV-CRISPR innate immune response:** A 27-year-old patient with advanced DMD died 8 days after AAV-based CRISPR epigenome editing therapy due to innate immune response to the AAV vector, aggravated by baseline poor health. The first two boys treated with AAV-CRISPR-Cas12 in clinical trial showed minimal evidence of long-term dystrophin rescue. These results highlight the challenge of AAV-based GET for myocardial/vascular diseases and support development of non-viral delivery methods. ([[sources/gene-editing-acc-2026]] — very high)
- **Lipid disorder GET — PCSK9/ANGPTL3/LPA targets (clinical trials):** PCSK9 base editing (VERVE-102/Heart-2, GalNAc-LNP; NEJM 2026; n=35): highest dose 1.0 mg/kg → mean PCSK9 −88%, LDL-C −62% (absolute −78 mg/dL), stable to ≥18 months; no thrombocytopenia; no DLTs; ANGPTL3 editing (CTX310, CRISPR Therapeutics): LDL-C −49% + TG −55% at highest dose; LPA gene editing (CTX320/VERVE-301) in development; APOC3 base editing for familial chylomicronemia initiated. All use LNP/GalNAc delivery targeting hepatocytes. See [[concepts/Lipid-Gene-Therapy]]. ([[sources/verve102-pcsk9-nejm-2026]] — high; [[sources/gene-editing-acc-2026]] — very high)

## Contradictions / Open Questions
- **Allele-specific targeting vs. mutation heterogeneity:** CRISPR/Cas9-based correction requires a guide RNA designed for a specific mutation. In diseases with extreme mutational heterogeneity (RYR2: >150 variants; KCNQ1/KCNH2: hundreds of variants), individual correction constructs must be redesigned for each patient — clinically impractical. SupRep's mutation-agnostic approach was developed precisely to overcome this; CRISPR remains allele-specific unless targeting conserved non-coding regulatory elements or shared pathway nodes. ([[sources/gene-therapy-arrhythmia-2025]])
- **Off-target editing — long-term cancer risk unproven but theoretically present:** The Pan 2023 in-vivo RYR2 CRISPR study reported no off-target edits by sequencing; however, comprehensive genome-wide off-target analysis in cardiomyocytes is technically limited. The ACC 2026 statement notes that off-target editing causing malignancy has not been reported in humans but may take many years to manifest — FDA mandates 15-year minimum post-treatment follow-up. ([[sources/gene-therapy-arrhythmia-2025]], [[sources/gene-editing-acc-2026]])
- **Base editing vs. CRISPR cleavage — different risk profiles:** Base editing (ABE8e for LQT3) avoids DNA double-strand breaks and off-target indels, but is limited to specific substitution types (A→G with ABE). CRISPR/Cas9 cleavage addresses a broader range of mutations but carries higher DSB-related risk. Neither approach is validated in humans; no direct comparison exists for cardiac applications. ([[sources/gene-therapy-arrhythmia-2025]])
- **MAGNITUDE Phase 3 hepatotoxicity — Phase 1 did not predict Phase 3 signal:** Nexiguran ziclumeran Phase 1 (n=36) showed manageable safety (5 infusion reactions, 2 transient AST elevations). The MAGNITUDE Phase 3 pause in Oct 2025 for severe hepatotoxicity including one death demonstrates that Phase 1 safety data may be insufficient to predict rare serious events in larger populations — with implications for how all cardiovascular GET trials are designed and monitored. ([[sources/gene-editing-acc-2026]] — very high)

## Connections
- Related to [[concepts/iPSC-Derived-Cardiomyocytes]]
- Related to [[concepts/Ion-Channel-Mutations]]
- Related to [[concepts/Gene-Editing-Risk-Benefit-Framework]]
- Related to [[concepts/AAV-Gene-Delivery]]
- Related to [[entities/CPVT]]
- Related to [[entities/Long-QT-Syndrome]]
- Related to [[entities/RYR2]]
- Related to [[entities/PRKAG2-Cardiac-Syndrome]]
- Related to [[entities/HCM]]
- Related to [[entities/Nexiguran-Ziclumeran]] — first clinical application of LNP-delivered CRISPR-Cas9 in ATTR-CM
- Related to [[entities/ATTR-Amyloidosis]] — ATTR-CM as the first disease to reach clinical-stage CRISPR-Cas9 in vivo gene editing with LNP delivery; MAGNITUDE Phase 3 pause
- Related to [[concepts/Lipid-Gene-Therapy]] — PCSK9/ANGPTL3/LPA base editing clinical trials

## Sources
- [[sources/channelopathies-jaha-2025]]
- [[sources/gene-editing-acc-2026]]
- [[sources/gene-editing-cv-tcm-2025]]
- [[sources/gene-therapy-arrhythmia-2025]]
- [[sources/nexz-crispr-attrcm-nejm-2024]]
- [[sources/verve102-pcsk9-nejm-2026]] — VERVE-102 Heart-2 Phase 1 NEJM 2026; GalNAc-LNP adenine base editing of PCSK9; full safety and dose-response data
