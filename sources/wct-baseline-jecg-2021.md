---
dg-publish: true
title: "Conceptual and Literature Basis for Wide Complex Tachycardia and Baseline ECG Comparison"
date_ingested: 2026-05-22
source_type: review article
Citation: "Evenson CM, Kashou AH, LoCoco S, DeSimone CV, Deshmukh AJ, Cuculich PS, Noseworthy PA, May AM. Conceptual and literature basis for wide complex tachycardia and baseline ECG comparison. J Electrocardiol. 2021;65:50–54."
DOI: "https://doi.org/10.1016/j.jelectrocard.2021.01.007"
tags: [wide-complex-tachycardia, ventricular-tachycardia, ECG-algorithm, automated-ECG-interpretation, baseline-ECG-comparison]
rating: low
raw_path: raw/WCT-JECG-2021.md
---

# Conceptual and Literature Basis for Wide Complex Tachycardia and Baseline ECG Comparison

## Authors, Journal, Affiliations, Type, DOI
- Evenson CM, Kashou AH, LoCoco S, DeSimone CV, Deshmukh AJ, Cuculich PS, Noseworthy PA, May AM
- Journal of Electrocardiology, 2021;65:50–54
- Department of Medicine/Cardiovascular Diseases, Washington University School of Medicine, St. Louis, MO; Mayo Clinic, Rochester, MN
- Short review / correspondence
- DOI: 10.1016/j.jelectrocard.2021.01.007
- No conflicts of interest declared

## Overview
A focused 2021 correspondence from the May/Kashou/DeSimone group articulating the theoretical and historical basis for comparing the WCT ECG to the patient's baseline ECG as a differentiation strategy. SWCT is constrained to His-Purkinje-mediated ventricular activation patterns, producing a limited variety of QRS/T-wave morphologies that often resemble the baseline ECG; VT has "electrical freedom" and routinely produces markedly different depolarisation and repolarisation patterns. The paper reviews the historical literature (Sandler 1965 → Dongas 1985 → Griffith 1991 → Pachón 2019) and introduces the WCT Formula II as the third automated baseline-comparison method.

## Keywords
ECG, electrocardiogram, supraventricular tachycardia, wide complex tachycardia, ventricular tachycardia

## Key Takeaways

### Conceptual Framework: Electrical Constraint vs Electrical Freedom
- **SWCT:** Ventricular activation constrained by the His-Purkinje network → limited variety of QRS/T-wave patterns; functional aberrancy (new BBB) changes QRS configuration vs baseline but remains within His-Purkinje-permitted patterns; **exception: SWCT with preexisting aberrancy** often produces near-identical QRS morphology to the baseline ECG
- **VT:** Originates from any ventricular region; wavefront propagation multidimensional and unconstrained → routinely produces QRS/T-wave patterns markedly different from baseline; **exceptions: fascicular VT and bundle branch re-entry** — the only VT varieties that may closely resemble the baseline ECG

### Historical Literature Basis for Baseline ECG Comparison
- **Sandler & Marriott (1965):** Compared initial QRS activation vector of wide complex beats (RBBB morphology) to baseline — 44% of SVT aberrant beats shared the same initial vector as baseline vs only 4% of PVCs; conclusion: identical initial vector to baseline sinus rhythm implies unchanged ventricular septal activation → aberrancy
- **Dongas et al. (1985):** WCTs with unchanged QRS morphology at V1/II/III vs preexisting BBB in sinus → almost invariably SWCT; different QRS morphology → usually VT; SWCT QRS axis ≈ baseline axis; VT QRS axis significantly different from baseline; more extensive QRS duration changes in VT
- **Griffith et al. (1991):** QRS axis change ≥40° from baseline was the third strongest independent VT predictor (after MI history and aVF QRS configuration); 83% of VT patients had ≥40° axis shift vs only 36% of SWCT patients

### Pachón et al. (2019) — Baseline-Comparison Criteria
Four of the seven Pachón algorithm criteria explicitly capitalise on WCT–baseline ECG comparison:
1. **Sudden QRS normalisation in patients with baseline AF** — 11% sensitive, **100% specific** for VT
2. **QRS duration narrower during WCT than baseline rhythm** — 10% sensitive, **99% specific** for VT
3. **Discordant BBB pattern in patients with baseline BBB** — 15% sensitive, **99% specific** for VT
4. **WCT QRS morphology identical to baseline ECG** — 37% sensitive, **99% specific** for SWCT

All four criteria are individually low sensitivity but near-perfect specificity — useful as rule-in criteria when present.

### Automated Methods: Performance Data
Three automated methods from the same group, all using logistic regression on computerised ECG measurements between paired WCT and baseline ECGs:

| Method | Year | Key Variables | AUC |
|---|---|---|---|
| WCT Formula | 2019 (May et al.) | Frontal & horizontal percent amplitude change (PAC) | **0.97** |
| VT Prediction Model | 2020 (May et al.) | QRS duration change, QRS axis change, T-wave axis change | **0.90** |
| WCT Formula II | 2020 (Kashou et al.) | Frontal & horizontal percent time-voltage area change (PTVAC) | **0.96** |

- VT demonstrates far greater frontal PTVAC than SWCT: **226.5% vs 53.6%** (p<0.001) — WCT Formula II derivation data
- VT demonstrates greater T-wave axis change than SWCT: **92° vs 41°** (p<0.001) — VT Prediction Model derivation data
- **All three require a paired baseline ECG** (recorded before or after the WCT event); not applicable when no prior ECG is available

## Limitations of the Document
- Short correspondence (5 pages), no new primary data — a conceptual and literature review only
- All three automated methods reviewed are by the same author group (May, Kashou, DeSimone, Deshmukh); no independent replication reported
- No head-to-head comparison with traditional manual algorithms reported
- Performance figures are from derivation datasets only; external validation not reviewed in this paper
- Extremely narrow scope (baseline comparison only); does not address most WCT differentiation scenarios

## Key Concepts Mentioned
- [[concepts/wide-complex-tachycardia]] — primary subject; baseline comparison framework, Pachón criteria details, WCT Formula II
- [[concepts/Fascicular-Ventricular-Tachycardia]] — exception: closely resembles baseline ECG (limits all algorithms including baseline comparison)

## Key Entities Mentioned
- None specific

## Wiki Pages Updated
- `wiki/sources/wct-baseline-jecg-2021.md` — created
- `wiki/concepts/wide-complex-tachycardia.md` — added: SWCT electrical constraint vs VT electrical freedom conceptual framework; Pachón 4 baseline-comparison criteria with specificity data; WCT Formula II (AUC 0.96); AUC data for all three automated methods; Sandler/Dongas/Griffith baseline-comparison data
- `wiki/sourceindex.md` — updated
- `wiki/wikiindex.md` — updated
