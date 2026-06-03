---
dg-publish: true
title: "Cardiac glycosides in patients with heart failure and reduced ejection fraction: a systematic review and meta-analysis"
date_ingested: 2026-05-22
source_type: review article
Citation: "Wang D, Xu X, Lu J, Gao J, Li Y, Pan G and Peng W (2026) Cardiac glycosides in patients with heart failure and reduced ejection fraction: a systematic review and meta-analysis. Front. Cardiovasc. Med. 13:1746467."
DOI: "https://doi.org/10.3389/fcvm.2026.1746467"
tags: [cardiac-glycosides, heart-failure, HFrEF, digoxin, meta-analysis]
rating: medium
raw_path: raw/Cardiac-glycosides-HFrEF-FCVM-2026.md
---

# Cardiac Glycosides in HFrEF: A Systematic Review and Meta-Analysis

## Authors, Journal, Affiliations, Type, DOI
- Dayang Wang, Xiaoqing Xu, Jingyao Lu, Jiayi Gao, Yingyu Li, Guozhong Pan, Wenhua Peng
- Frontiers in Cardiovascular Medicine (2026; 13:1746467)
- Dongzhimen Hospital, Beijing University of Chinese Medicine; Beijing Hepingli Hospital
- Type: Systematic review and meta-analysis (PRISMA 2020); pre-registered PROSPERO CRD420251142262
- DOI: https://doi.org/10.3389/fcvm.2026.1746467

## Overview
This 2026 systematic review and meta-analysis pooled 6 RCTs (n=8,488 patients) evaluating cardiac glycosides (predominantly digoxin; one digitoxin trial) versus placebo on top of GDMT in HFrEF. The primary finding is that cardiac glycosides reduce HF hospitalization (HR=0.79) but do not reduce all-cause mortality (HR=0.98). An exploratory network meta-analysis found no significant advantage of digitoxin over digoxin for either mortality or hospitalization. The DIGIT-HF trial (2025) — the sole RCT conducted within contemporary GDMT — dominates the modern evidence base but was underpowered to detect individual component benefits.

## Keywords
Cardiac glycosides, digitoxin, digoxin, heart failure and reduced ejection fraction, meta-analysis, prognosis

## Key Takeaways

### Introduction
- Cardiac glycosides enhance myocardial contractility by inhibiting Na⁺/K⁺-ATPase → increases intracellular calcium in cardiomyocytes and sarcoplasmic reticulum; also reduces heart rate via indirect sympathetic tone suppression
- The DIG trial (1997) established no mortality benefit with digoxin; current guidelines classify glycosides as symptom-modifying, not prognosis-modifying
- Digitoxin has distinct pharmacokinetics from digoxin: lipophilic → higher intestinal absorption, stronger serum protein binding, predominantly hepatic clearance (not renal) → more stable plasma concentrations especially in renal impairment
- The DIGIT-HF trial (2025) showed digitoxin reduced the composite of all-cause mortality and HF rehospitalization in HFrEF on contemporary GDMT, challenging the conventional position

### Methods
- Databases: PubMed, EMBASE, Cochrane Library, Web of Science; up to September 12, 2025
- Inclusion: RCTs only; HFrEF population; cardiac glycoside + GDMT vs placebo + GDMT; all-cause mortality or HF rehospitalization reported
- Quality: RoB-2 tool; all 6 trials classified as "low risk of bias"
- Statistical: random-effects model; pooled HR; I² heterogeneity; network meta-analysis (mvmeta/network packages in STATA 17) for indirect digoxin vs digitoxin comparison
- Publication bias: funnel plots + Egger's test (p=0.204 — no significant bias)

### Results

#### Study characteristics
- 6 RCTs included from 1,181 identified studies (after removing duplicates and applying eligibility criteria)
- Total 8,488 patients; follow-up ranged 6 months to 4 years
- 5 trials evaluated digoxin; 1 trial (DIGIT-HF) evaluated digitoxin
- Key trials:
  - DIG trial (1997): n=6,800; digoxin; 37-month follow-up; United States/Canada
  - DIGIT-HF (2025): n=1,212; digitoxin; 48-month follow-up; Austria/Germany/Serbia; ARNi 39.5%, SGLT2i 19.3%
  - Smaller trials: Captopril-Dig Group 1988 (n=196), DIBianco 1989 (n=111), Blackwood 1990 (n=61), DIMT 1993 (n=108)
- Mean age 56.8–65.9 years; LVEF <30–45% across studies

#### Primary outcome: All-cause mortality
- **HR = 0.98 (95% CI 0.92–1.04)** — no significant difference vs placebo
- Result robust on leave-one-out sensitivity analysis across all 6 trials

#### Secondary outcome: HF hospitalization
- **HR = 0.79 (95% CI 0.67–0.94)** — significant reduction vs placebo
- Sensitivity analysis: result sensitive to exclusion of DIG trial (HR shifts to 0.71 [0.44–1.15] when DIG removed, crossing the null)

#### Indirect comparison: digitoxin vs digoxin
- All-cause mortality: HR = 0.93 (95% CI 0.77–1.13) — NS
- HF hospitalization: HR = 1.35 (95% CI 0.70–2.60) — NS
- Indirect comparison methodology limited by 30-year GDMT evolution gap between DIG (1997) and DIGIT-HF (2025)

### Discussion
- Pooled results consistent with DIG trial conclusions: glycosides reduce HF hospitalization but not mortality
- DIGIT-HF contributed unique context: only trial in contemporary GDMT with therapeutic drug monitoring (TDM) — TDM may explain more pronounced benefits in that trial versus older studies
- Digitoxin's pharmacokinetic advantages (hepatic clearance, higher bioavailability) did not translate to clinical superiority in indirect comparison; limited by single digitoxin trial with only 613 patients
- GDMT evolution (ARNi, SGLT2i, vericiguat, ICD/CRT device therapy) between 1997 and 2025 lowered annual HF mortality from 33.4 to 23.8 per 100,000 (Swedish National Patient Register), potentially attenuating absolute benefit of glycosides
- Ongoing DECISION trial (low-dose digoxin in HFrEF, contemporary GDMT) will provide additional evidence for direct digoxin comparison
- Current 2022 AHA/ACC/HFSA guidelines: digoxin COR IIb in symptomatic HFrEF despite GDMT (or GDMT intolerance) — to decrease HF hospitalizations
- Vamos 2015 meta-analysis suggested increased mortality with digoxin, but that study included observational data; RCT-only analyses (Ziff 2015; this study) show no mortality signal

## Limitations of the document
- Study-level (not patient-level) meta-analysis; unable to perform subgroup analyses for specific HFrEF populations
- All five digoxin trials are dated (1988–1997); conducted before ARNi, SGLT2i, CRT, ICD became standard
- Wide range of follow-up durations (6 months–4 years) introduces temporal bias
- Only one digitoxin trial (DIGIT-HF, n=1,212 with 613 in digitoxin arm) — indirect comparison underpowered
- No head-to-head RCTs between digoxin and digitoxin exist
- GDMT evolution across trials makes indirect comparison unreliable
- HF hospitalization result sensitive to DIG trial exclusion (loses significance without it)
- Frontiers in Cardiovascular Medicine is a lower-tier journal; no independent replication yet

## Key Concepts Mentioned
- [[concepts/Cardiac-Glycosides-in-HFrEF]] — primary concept page for this topic
- [[concepts/Iron-Deficiency-in-HF]] — context for GDMT landscape in HFrEF
- [[concepts/Cardiac-Resynchronization-Therapy]] — device therapy evolution context
- [[concepts/Pharmacogenomics-in-HF]] — GDMT framework

## Key Entities Mentioned
- DIG trial (1997) — landmark digoxin RCT; dominant contributor to all-cause mortality pooled result
- DIGIT-HF trial (2025) — see [[sources/digitoxin-hfref-digithf-nejm-2025]]; only contemporary GDMT digitoxin trial
- DECISION trial — ongoing low-dose digoxin RCT in HFrEF; will enable direct digoxin comparison

## Wiki Pages Updated
- Created `wiki/sources/cardiac-glycosides-hfrEF-fcvm-2026.md`
- Created `wiki/concepts/Cardiac-Glycosides-in-HFrEF.md`
- Updated `wiki/sourceindex.md`
- Updated `wiki/wikiindex.md`
