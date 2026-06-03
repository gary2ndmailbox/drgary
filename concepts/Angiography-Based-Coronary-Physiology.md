---
dg-publish: true
title: "Angiography-Based Coronary Physiology"
tags: [angiography-based-physiology, fractional-flow-reserve, coronary-physiology, intermediate-coronary-lesions, pci-guidance]
source_count: 1
last_updated: 2026-05-20
---

# Angiography-Based Coronary Physiology

## Definition
Angiography-based coronary physiological indices derive a functional assessment of coronary stenosis severity (analogous to fractional flow reserve) directly from coronary angiographic images, using 3D quantitative coronary angiography (QCA) and computational fluid dynamics models, without requiring a pressure wire or pharmacologic hyperemia. The key example validated in randomized trials is vessel fractional flow reserve (vFFR). These tools aim to make physiological guidance universally accessible, shorten procedures, and eliminate wire-related and adenosine-related complications.

## Key Concepts

### How vFFR Works
- vFFR (Pie Medical Imaging) reconstructs coronary geometry in three dimensions from two angiographic projections acquired ≥30° apart, after intracoronary nitrate administration
- Aortic-root pressure is measured invasively via the guiding catheter tip (not eliminated — only the intracoronary wire is removed)
- Blood flow behaviour is modelled using physical laws: viscous resistance and separation loss effects (Gould and Kirkeeide formulations from the 1980s)
- Output: a single vFFR value analogous to wire-measured FFR; ≤0.80 = hemodynamically significant, >0.80 = defer revascularization
- Requires local analyst certification; performed directly at the cath lab workstation

### Diagnostic Accuracy vs Pressure-Wire FFR
- Prospective multicenter validation studies (FAST 2020, FAST II 2022, FAST EXTEND 2021) demonstrated diagnostic accuracy of vFFR comparable to pressure-wire FFR for identifying hemodynamically significant stenoses ([[sources/vffr-fastiii-nejm-2026]], rating: very high)
- Other angiography-based indices include quantitative flow ratio (QFR), AngioFFR, and caFFR — each use different computational approaches and validation datasets

### FAST III — First Head-to-Head RCT: vFFR vs Wire FFR
- **Design:** 2,235 patients with intermediate coronary-artery lesions (30–80% stenosis); chronic or acute coronary syndrome; 37 European centers; 1:1 vFFR vs FFR revascularization guidance; 1-year follow-up ([[sources/vffr-fastiii-nejm-2026]], rating: very high)
- **Primary endpoint (death/MI/revascularization at 1 year):** 7.5% (vFFR) vs 7.5% (FFR); risk difference −0.02 pp (95% CI −2.25 to 2.21); **P=0.004 for noninferiority** — vFFR noninferior to FFR
- **Study-vessel failure:** 4.0% vs 4.6% (NS)
- **Death:** 2.2% vs 2.3% (NS); **MI:** 2.9% vs 2.4% (NS); **Any revascularization:** 4.2% vs 4.2%
- **Quality of life (SAQ score at 1 year):** 87.3 vs 86.8 — equivalent

### Key Discordance: vFFR Detects More Functionally Significant Lesions
- Functionally significant lesions (≤0.80): **40.9% (vFFR) vs 31.3% (FFR)** — a 9 percentage point gap ([[sources/vffr-fastiii-nejm-2026]], rating: very high)
- This resulted in **more revascularizations with vFFR (45.0% vs 36.0%)** despite equivalent outcomes
- Mechanistic explanation: angiography-based tools assume flow based on vessel geometry (reference diameter) rather than measuring actual hyperemic flow; true microvascular resistance, demand, and patient-specific hyperemia response are unaccounted for → computed pressure gradient exceeds true gradient → lower vFFR value → higher lesion detection rate
- Longer or tapered lesions may be further overestimated due to accumulated resistance across diffuse disease
- This vFFR-FFR discordance is a class effect — parallel findings in FAVOR III Europe (QFR vs FFR) showed QFR also detected more lesions, albeit with different clinical outcome implications

### Practical Advantages Over Wire-Based FFR
- No intracoronary wire needed → eliminates wire-related complications (dissection, perforation, spasm, wire bias artefact)
- No pharmacologic hyperemia → eliminates adenosine-related effects (AV block, bronchospasm, discomfort, cost)
- **Procedure time shorter by ~5 minutes** (55.8 vs 60.9 min; diff −5.13 min; 95% CI −8.55 to −1.71) ([[sources/vffr-fastiii-nejm-2026]], rating: very high)
- **Fewer intraprocedural complications at time of physiological assessment: 3.7% vs 6.0%** ([[sources/vffr-fastiii-nejm-2026]], rating: very high)
- Enables retrospective physiological analysis of angiographic images already acquired

### Context: Where Does vFFR Fit Relative to Other Physiology Tools?
- **FFR (wire + adenosine):** Gold standard; highest evidence base; requires additional equipment; adenosine complications
- **iFR (wire, no adenosine):** Validated equivalent to FFR in stable CAD; ≤0.89 threshold; also wire-based but no adenosine; STEMI false-positive risk (~11%)
- **vFFR (no wire, no adenosine):** Now validated noninferior to FFR in a large RCT for clinical outcomes; higher lesion detection rate; shorter procedure; lower complication rate
- **QFR (no wire, no adenosine):** Class IB recommendation (ESC 2024 CCS guidelines) after FAVOR III China (superior to angiography); FAVOR III Europe showed higher MACE than FFR-guided revascularization (different result from FAST III)
- The divergence between FAVOR III Europe (QFR vs FFR) and FAST III (vFFR vs FFR) highlights that not all angiography-based indices are equivalent

### FAVOR III Europe vs FAST III — Why Divergent Results?
- **FAVOR III Europe (Lancet 2024; n=2,000):** QFR-guided revascularization showed **higher MACE** than FFR-guided revascularization — QFR performed **worse** than FFR
- **FAST III (NEJM 2026; n=2,235):** vFFR-guided revascularization showed **equivalent MACE** to FFR-guided revascularization — vFFR **noninferior** to FFR
- Both trials used the same ≤0.80 threshold; the difference in outcome may reflect computational methodology differences between QFR and vFFR, or differences in patient populations and center characteristics
- The exact mechanism of QFR inferiority vs FFR in Europe remains unexplained; vFFR may have a more accurate flow model

## Contradictions / Open Questions
- **Higher revascularization rate with vFFR without better outcomes:** vFFR drove 9 pp more revascularizations (45% vs 36%) with identical outcomes. Does this indicate that vFFR better identifies prognostically relevant lesions (revascularization beneficial but not captured in 1-year composite), or that vFFR over-detects, adding stents without benefit? A prespecified cost-effectiveness analysis is planned ([[sources/vffr-fastiii-nejm-2026]], rating: very high)
- **vFFR in ACS:** Only 18.7% of FAST III patients had ACS; vFFR reliability in ACS is less established (increased microvascular dysfunction post-ACS may further magnify vFFR-FFR discordance)
- **Long-term outcomes unknown:** The higher stent burden with vFFR (more lesions treated) may affect long-term stent thrombosis, restenosis, and repeat revascularization beyond 1 year
- **QFR vs vFFR discordance:** FAVOR III Europe (QFR) and FAST III (vFFR) give different answers. Which angiography-based index is superior remains unresolved and is not directly tested
- **Generalizability beyond high-volume European centers:** vFFR requires specific training, certification, and accurate angiographic acquisition technique; adoption in lower-volume centers may yield different results

## Connections
- Related to [[concepts/Fractional-Flow-Reserve]] — wire-based gold standard comparator; ≤0.80 threshold shared
- Related to [[concepts/Instantaneous-Wave-Free-Ratio]] — wire-based resting alternative to FFR; no adenosine
- Related to [[concepts/Multivessel-PCI-STEMI-Timing]] — physiological guidance of nonculprit lesions in ACS context
- Related to [[concepts/NSTEMI-Elderly-Invasive-Strategy]] — invasive physiology guidance in ACS populations

## Sources
- [[sources/vffr-fastiii-nejm-2026]]
