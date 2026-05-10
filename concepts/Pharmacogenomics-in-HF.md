---
dg-publish: true
title: "Pharmacogenomics in Heart Failure"
tags: [pharmacogenomics, heart-failure, precision-medicine, beta-blockers, CYP450]
source_count: 1
last_updated: 2026-04-29
---

# Pharmacogenomics in Heart Failure

## Definition
Pharmacogenomics in HF evaluates how inherited genetic variation influences drug response — encompassing both pharmacokinetics (drug absorption, transport, metabolism, excretion) and pharmacodynamics (drug-target interactions). The goal is to identify patient subgroups who derive greater benefit, no benefit, or potential harm from standard HF therapies, enabling genotype-guided drug selection and dosing.

## Key Concepts

### Beta-Blocker Pharmacogenomics

#### ADRB1 (β1-Adrenergic Receptor) — Arg389Gly Variant
- **Mechanism:** Arg389Gly substitution in the intracytoplasmic carboxy terminus of the β1-adrenergic receptor alters stimulatory G-protein coupling activity. Arg389 receptor has greater G-protein coupling than Gly389.
- **BEST Trial finding:** Patients with HFrEF homozygous for ADRB1 Arg389 had a **38% reduction in mortality** with bucindolol therapy vs. no significant benefit in Gly389 carriers. ([[sources/HF-Precision-Medicine-AHA-2019]], rating: high)
- **Limitation:** This association has not been replicated in studies with other beta-blockers. Clinical implementation requires replication and an appropriately powered prospective trial. ([[sources/HF-Precision-Medicine-AHA-2019]], rating: high)

#### GRK5 (G-Protein Receptor Kinase 5) — Leu41 Variant
- **Mechanism:** GRK5 desensitises cardiac β-adrenergic receptors; the Leu41 variant causes greater receptor desensitisation in vitro than the wild-type Gln41 — effectively providing an intrinsic "pharmacological beta-blockade."
- **Clinical implication:** In a 2,460-patient HF cohort, GRK5 Leu41 allele carriers showed no mortality benefit from beta-blocker therapy, consistent with pre-existing receptor desensitisation. ([[sources/HF-Precision-Medicine-AHA-2019]], rating: high)
- **Racial pharmacogenomics:** GRK5 Leu41 allele frequency is **10-fold higher** in Black patients (0.23) vs. white patients (0.02) — a major source of observed racial differences in beta-blocker efficacy that is genetically rather than racially determined. ([[sources/HF-Precision-Medicine-AHA-2019]], rating: high)

#### GNB3 (G-Protein β-3 Subunit) — Thr825/Cys825 Variant
- **A-HeFT Trial (African American Heart Failure):** GNB3 Thr825 homozygotes had significantly greater event-free survival with fixed-dose hydralazine/isosorbide dinitrate (H-ISDN) therapy vs. GNB3 Cys825 variant carriers. ([[sources/HF-Precision-Medicine-AHA-2019]], rating: high)
- H-ISDN is guideline-recommended (AHA COR 1A) for self-identified Black patients with HFrEF; GNB3 genotyping may further refine which patients derive the greatest benefit. Prospective replication study ongoing (GRAFFITI trial). ([[sources/HF-Precision-Medicine-AHA-2019]], rating: high)

---

### CYP450 Enzyme Pharmacogenomics

#### CYP2D6 — Metoprolol and Carvedilol Metabolism
- CYP2D6 metaboliser phenotypes: **Poor (PM)**, **Intermediate (IM)**, **Extensive (EM)**, **Ultrarapid (UM)** — determined by loss-of-function or gain-of-function alleles or gene duplication.
- **Rotterdam Study:** Metoprolol-treated PMs had heart rates 8.5 bpm lower and BP 5 mmHg lower vs. EMs at equivalent doses; **4-fold increased bradycardia risk** in PMs. ([[sources/HF-Precision-Medicine-AHA-2019]], rating: high)
- **Royal Dutch Pharmacists Association recommendations:**
  - PMs and IMs: switch to bisoprolol (non-CYP2D6 substrate) OR reduce metoprolol dose by 50–75%
  - Ultrarapid metabolisers: switch to alternative OR increase metoprolol dose up to 250% of typical
- Note: US FDA drug labelling for metoprolol only cautions about interactions, does not reflect dose adjustment recommendations. ([[sources/HF-Precision-Medicine-AHA-2019]], rating: high)

#### CYP3A5 — Tacrolimus Post-Heart Transplant
- Tacrolimus (most common post-heart transplant immunosuppressant) is primarily metabolised by CYP3A5; EMs/IMs achieve lower dose-adjusted troughs and have significantly increased rejection risk with standard dosing (OR 1.32; P=0.04 meta-analysis). ([[sources/HF-Precision-Medicine-AHA-2019]], rating: high)
- **Clinical Pharmacogenetics Implementation Consortium (CPIC) recommendation:** EMs or IMs of CYP3A5 should receive **1.5–2× higher initial tacrolimus dose** to achieve therapeutic concentrations rapidly. Supported by an RCT demonstrating significantly more patients achieving target range at day 3 with genotype-based dosing. ([[sources/HF-Precision-Medicine-AHA-2019]], rating: high)

---

### Clinical Implementation Strategy
- **Preemptive genotyping:** Genetic testing performed before drug prescription; results embedded in EHR and triggered at the point of drug ordering with decision support for dose adjustment or drug selection — avoids time-lag limitation of reactive testing. ([[sources/HF-Precision-Medicine-AHA-2019]], rating: high)
- Large academic medical centres are implementing CLIA-approved pharmacogenomic panels (multi-pharmacogene panels) into clinical workflows. ([[sources/HF-Precision-Medicine-AHA-2019]], rating: high)

---

## Contradictions / Open Questions
- **ADRB1 Arg389Gly not replicated beyond bucindolol:** The only significant pharmacogenomic-mortality association for beta-blockers is specific to bucindolol in the BEST trial; has not been replicated with carvedilol, metoprolol, or bisoprolol — limiting clinical generalisation. ([[sources/HF-Precision-Medicine-AHA-2019]], rating: high)
- **GRK5 Leu41 and clinical practice:** If Black patients with HFrEF have intrinsic GRK5-mediated receptor desensitisation equivalent to beta-blockade, does standard beta-blocker therapy produce the same mortality benefit? This has not been resolved in a prospective genotype-stratified trial. ([[sources/HF-Precision-Medicine-AHA-2019]], rating: high)
- **General pharmacogenomics barriers:** Lack of robust statistical associations, absent replication cohorts, small sample sizes, rare adverse drug events difficult to power for, and population stratification challenges. Most pharmacogenomic discoveries in HF remain research findings, not clinical practice standards. ([[sources/HF-Precision-Medicine-AHA-2019]], rating: high)

## Connections
- Related to [[entities/Heart-Failure]]
- Related to [[concepts/Gut-Microbiome-in-HF]]
- Related to [[sources/HF-Precision-Medicine-AHA-2019]]
- Related to [[sources/consumer-genetictest-aha-2025]]

## Sources
- [[sources/HF-Precision-Medicine-AHA-2019]]
- [[sources/consumer-genetictest-aha-2025]]
