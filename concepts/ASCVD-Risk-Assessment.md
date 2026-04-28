---
dg-publish: true
title: "ASCVD Risk Assessment"
tags: [ASCVD, primary-prevention, risk-stratification, dyslipidemia, guidelines]
source_count: 3
last_updated: 2026-04-25
---

# ASCVD Risk Assessment

## Definition
ASCVD (atherosclerotic cardiovascular disease) risk assessment quantifies an individual's probability of experiencing a hard ASCVD event (fatal/nonfatal stroke, nonfatal MI, or CHD death). Accurate risk estimation is the cornerstone of shared decision-making for lipid-lowering therapy in primary prevention. The 2026 ACC/AHA guideline mandates adoption of the AHA PREVENT-ASCVD equations, replacing the older Pooled Cohort Equations (PCE) that substantially overestimated risk.

## Key Concepts

### PREVENT-ASCVD Equations — Overview
- Derived in ~3.3 million contemporary US adults; validated in separate ~3.3 million — far larger and more contemporary than PCE (~25,000 subjects, older cohorts) [[sources/lipid-aha-2026]] (very high)
- Age range: 30–79 years
- Variables (base model): age, sex, systolic BP, total cholesterol, HDL-C, diabetes, tobacco use, eGFR, statin use, antihypertensive medication use
- Optional enhanced inputs: HbA1c (glycaemic status), urine albumin-to-creatinine ratio (proteinuria/CKD), zip code (social deprivation index)
- **Race/ethnicity is NOT included** — did not add predictive value in derivation
- Outputs: 10-year and 30-year estimates for hard ASCVD, heart failure, and total CVD
- Risk estimates are **40–50% lower** than PCE for the same risk profile; PCE was substantially over-calibrated

### Risk Categories (PREVENT vs PCE Crosswalk)
| Risk Group | PREVENT-ASCVD (New) | PCE (Old) |
|---|---|---|
| Low | <3% | <5% |
| Borderline | 3% to <5% | 5% to <7.5% |
| Intermediate | 5% to <10% | 7.5% to <20% |
| High | ≥10% | ≥20% |

- These thresholds were re-examined empirically: net benefit for moderate-intensity statin emerges at ~3% 10-year event rate; net benefit for high-intensity statin at ~7% (Figure 4 in guideline) [[sources/lipid-aha-2026]] (very high)
- Number needed to treat to prevent 1 ASCVD event = number needed to cause 1 new case of diabetes at 3% 10-year risk for moderate-intensity statin

### CPR Framework — Practical Risk Assessment
A structured three-step approach for primary prevention decision-making [[sources/lipid-aha-2026]] (very high):

1. **C — Calculate** 10-year (and if appropriate, 30-year) ASCVD risk using PREVENT-ASCVD equations
2. **P — Personalize** estimated risk by considering risk enhancers not captured in PREVENT (see below)
3. **R — Reclassify** with selective use of CAC scoring (and Reassess treatment recommendations)

### Risk Enhancers (Personalise Step)
Factors that increase risk beyond PREVENT estimate, especially relevant at borderline risk [[sources/lipid-aha-2026]] (very high):
- Family history of premature ASCVD (men <55 y, women <65 y)
- Higher-risk ancestry (South Asian, Filipino)
- Chronic inflammatory diseases (SLE, RA, advanced psoriasis)
- Lp(a) ≥125 nmol/L (50 mg/dL) — see [[concepts/Lipoprotein-a]]
- hsCRP ≥2 mg/L on >1 occasion; if ≥2 mg/L × 2 without identifiable cause → high-intensity statin useful even at borderline risk (JUPITER trial: 44% RRR in MACE)
- TG persistently ≥175 mg/dL (nonfasting) or ≥150 mg/dL (fasting)
- CKM syndrome (metabolic dysfunction, CKD, obesity, diabetes)
- LDL-C persistently 160–189 mg/dL or non-HDL-C ≥190–219 mg/dL
- **Reproductive risk markers**: early menopause (<45 y), premature menopause (<40 y), adverse pregnancy outcomes (preeclampsia, gestational hypertension, gestational diabetes, preterm delivery, small-for-gestational-age, recurrent pregnancy loss)

### CAC Scoring — Reclassification Step
Coronary artery calcium (CAC) scoring by non-contrast cardiac CT is the primary reclassification tool [[sources/lipid-aha-2026]] (very high):

**When to use CAC:**
- Adults at intermediate risk (5–<10%) or select borderline-risk adults (3–<5%) when LLT decision remains uncertain (COR 1)
- Adults at intermediate or high risk when intensity of LLT is uncertain (COR 2a)

**Interpreting CAC results:**
| CAC Score | Interpretation | Action |
|---|---|---|
| 0 AU | Very low coronary atherosclerosis burden | Defer LLT, reassess with repeat CAC in 3–7 y (unless DM, active smoking, FH, LDL-C ≥190 mg/dL) |
| 1–99 AU, <75th percentile | Mild subclinical atherosclerosis | Moderate-intensity statin; LDL-C <100 mg/dL |
| 100–299 AU or ≥75th percentile | Moderate subclinical atherosclerosis | Statin (first-line); LDL-C <70 mg/dL |
| 300–999 AU | Significant subclinical atherosclerosis | Statin; LDL-C <70 mg/dL; consider intensification to <55 mg/dL |
| ≥1000 AU | Severe subclinical atherosclerosis (near-ASCVD equivalent) | LDL-C <55 mg/dL; non-HDL-C <85 mg/dL |

- Both absolute CAC score AND age-sex-race standardised percentile have prognostic importance
- Incidental CAC on non-cardiac CT (by visual estimate or validated AI algorithm) should inform LLT decisions (COR 1)

### 30-Year Risk and Young Adults
- 10-year risk estimation is less useful for younger adults due to long latency between risk factor exposure and ASCVD events
- 30-year risk estimates (available from PREVENT) can guide discussion in adults 30–59 y at low 10-year risk
- Low 10-year risk + LDL-C 160–189 mg/dL OR 30-year risk ≥10% → moderate-intensity statin reasonable (COR 2a)

### Polygenic Risk Scores (PRS)
- CAD polygenic risk scores (PRS) can improve risk prediction beyond clinical factors, particularly in adults <55 y [[sources/lipid-aha-2026]] (very high)
- High CAD PRS is enriched in those with family history of premature CAD; effects additive
- Post hoc RCT analyses: high PRS associated with greater relative and absolute benefit from LLT
- Not yet standardised for routine clinical use; different PRS may yield different estimates
- Included in risk enhancers if measured; not a stand-alone clinical recommendation yet

### DTC-GT PRS — Distinct Limitations from Clinical PRS
- **No DTC PRS product has achieved FDA clearance or approval** — clinical validation is absent for all commercially available DTC cardiovascular PRS products ([[sources/consumer-genetictest-aha-2025]] — high)
- Array-based genotyping (used in most DTC products) may not adequately capture allele diversity in the target population; low-coverage WGS may partially address this but requires adequate imputation panel representation
- **DTC PRS construction is opaque** — limited public benchmarking makes cross-product comparison and result interpretation difficult; clinicians should not interpret DTC PRS results using the same framework as physician-ordered clinical PRS
- **Ancestry integration is highly variable** — PRS performance depends substantially on the population in which it was trained; non-European ancestry populations are substantially underrepresented in GWAS training datasets; DTC PRS results may be unreliable or systematically biased for these groups
- An integrated risk score incorporating clinical risk factors alongside genetics is the desired standard — a DTC PRS alone does not account for medication use, comorbidities, or lifestyle factors ([[sources/consumer-genetictest-aha-2025]] — high)
- For DTC-GT PRS clinical context, see [[concepts/DTC-Genetic-Testing]]

### Limitations of Risk Assessment
- PREVENT derived in US adults 30–79 y; generalizability to non-US populations uncertain
- Population-level probability estimates applied to individuals — inherent uncertainty
- HeFH: standard PREVENT equations should NOT be used (COR 3: Harm) — risk is substantially underestimated
- Competing non-ASCVD mortality (especially elderly) affects net benefit estimation

### ESC 2025: SCORE2/SCORE2-OP Framework
- **SCORE2** (age <70 y) and **SCORE2-OP** (age ≥70 y) replace the original SCORE algorithm: COR I B [[sources/lipid-esc-2025]] (very high)
- Key advantages over SCORE: uses non-HDL-C (not total cholesterol); estimates fatal + non-fatal events; valid to age 89
- SCORE2/SCORE2-OP thresholds are approximately double SCORE thresholds (total CVD events ~2–3× fatal CVD events)
- **ESC 2025 Risk Categories:**

| Category | SCORE2/SCORE2-OP |
|---|---|
| Very high | ≥20% (or documented ASCVD, DM+TOD, severe CKD, FH+ASCVD) |
| High | 10–<20% (or FH, markedly elevated single RF, DM without TOD, moderate CKD) |
| Moderate | 2–<10% (or young DM) |
| Low | <2% |

- ESC 2025 LDL-C targets (unchanged from 2019): very high risk <1.4 mmol/L (<55 mg/dL) + ≥50% reduction; high risk <1.8 mmol/L (<70 mg/dL); moderate risk <2.6 mmol/L (<100 mg/dL); low risk <3.0 mmol/L (<116 mg/dL)
- **CAC as risk modifier** (new ESC 2025 COR IIa B): subclinical coronary atherosclerosis by imaging or elevated CAC score should be considered as risk modifier at moderate risk or around treatment thresholds [[sources/lipid-esc-2025]] (very high)
- SCORE2/SCORE2-OP should NOT be used in patients with existing ASCVD or those on lipid-lowering therapy

## Contradictions / Open Questions
- Whether PREVENT-ASCVD equations will be validated in all major non-US ethnic populations before widespread global adoption — race not in the model but ancestry-specific calibration may still be needed
- Optimal integration of PRS into clinical workflows: methodological heterogeneity across PRS scores; a "low PRS" from one score does not guarantee low genetic risk
- Serial CAC testing as a surrogate for treatment response — not yet validated as ASCVD outcome surrogate
- **ESC SCORE2 vs ACC/AHA PREVENT — different risk category thresholds:** ESC defines high risk at SCORE2 ≥10% (fatal+non-fatal 10-year); ACC/AHA defines high risk at PREVENT ≥10% (hard ASCVD 10-year including HF). Thresholds appear similar but equations are not interchangeable: populations, endpoints, and calibration differ. Applying one in a population calibrated for the other may misclassify risk [[sources/lipid-aha-2026]] [[sources/lipid-esc-2025]] (both very high)
- **PREVENT dual-use — lipid vs. hypertension guideline thresholds differ:** The 2026 ACC/AHA lipid guideline uses PREVENT-ASCVD with a ≥10% threshold for initiating high-intensity statin. The 2025 AHA HT guideline uses PREVENT total CVD with a ≥7.5% threshold for initiating antihypertensives at SBP ≥130 mmHg. The same PREVENT tool generates both ASCVD and total CVD outputs — clinicians must use the correct output for each decision context. A patient at 8% total CVD risk may qualify for antihypertensive initiation but not yet for statin intensification. ([[sources/HT-AHA-2025]], rating: very high)
- **ESC vs ACC/AHA treatment initiation thresholds differ substantially** for moderate-risk primary prevention: ESC recommends pharmacological LLT consideration at LDL-C ≥2.6 mmol/L (100 mg/dL) in moderate risk (COR IIa A); ACC/AHA defines intermediate risk at PREVENT 5–<10% with LDL-C ≥70 mg/dL. Practical implications for who gets treated vary across guidelines

## Connections
- Related to [[concepts/Dyslipidemia-Management]] — risk score drives all treatment threshold and intensity decisions
- Related to [[concepts/Lipoprotein-a]] — Lp(a) is a key risk enhancer not captured by PREVENT or SCORE2 equations
- Related to [[concepts/Familial-Hypercholesterolemia]] — PREVENT equations explicitly contraindicated in HeFH; SCORE2/SCORE2-OP similarly not validated in FH
- Related to [[entities/Hypertension]] — 2025 AHA HT guideline adopts PREVENT at ≥7.5% threshold for medication initiation at SBP ≥130 mmHg
- Related to [[concepts/DTC-Genetic-Testing]] — DTC PRS products have no FDA clearance; population-ancestry bias; not interchangeable with physician-ordered clinical PRS
