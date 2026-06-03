---
dg-publish: true
title: "Pulmonary Artery Pulsatility Index"
tags: [cardiogenic-shock, hemodynamic-monitoring, right-ventricular-failure, mechanical-circulatory-support, pulmonary-artery-catheter, pulmonary-arterial-capacitance]
source_count: 2
last_updated: 2026-05-25
---

# Pulmonary Artery Pulsatility Index (PAPi)

## Definition
A hemodynamic index derived from right heart catheterization reflecting the interaction between RV stroke volume, pulmonary arterial capacitance (PAC), and right atrial pressure. Used to assess right heart function severity and guide clinical decision-making in advanced HF, cardiogenic shock, and LVAD management. PAPi is **not a direct measure of RV function** — it is a composite index shaped by multiple hemodynamic determinants.

**Formula**: PAPi = (PASP − PADP) / RAP = pulmonary artery pulse pressure / right atrial pressure

## Key Concepts

### Physiological Basis
The formula was originally developed for RV infarction/shock to assess RV function without requiring estimated stroke volume or cardiac output — avoiding the need for thermodilution or echocardiographic windows [[sources/papi-ejhf-2020]] (high).

**Core equation** (derived by rearranging PAC = SV/PAPP):
> **PAPP = RV stroke volume / PAC**

Therefore PAPi varies with:
- **RV stroke volume** ↑ → PAPP ↑ → PAPi ↑
- **PAC** ↓ → PAPP ↑ → PAPi ↑ (steeper SV–PAPP slope at lower PAC)
- **RAP** ↑ → PAPi ↓
- **PAWP** ↑ → disproportionately reduces PAC (shifts PVR–PAC hyperbola leftward) → PAPP ↑ → PAPi ↑ even at constant PVR/RAP/SV [[sources/papi-ejhf-2020]] (high)

### Pulmonary Arterial Capacitance (PAC) — Key Mediator
- Normal PAC ≈ ≥4 mL/mmHg; advanced HF: ~2.5 mL/mmHg; severe LHD-related PH: ~1.3 mL/mmHg
- PAC has a hyperbolic inverse relationship with PVR; their product (RC time constant) is relatively stable across conditions
- **Exception**: elevated PAWP disproportionately reduces PAC relative to PVR, causing the PVR–PAC curve to shift downward and leftward — PAWP is therefore an independent modifier of PAPi [[sources/papi-ejhf-2020]] (high)
- At very high PVR, reducing PVR yields minimal PAC gain (right plateau of hyperbola) — limiting PAPi response to pulmonary vasodilators in severe PH

### RAP Determinants
- RAP is set by the intersection of cardiac function and venous return curves
- Volume loading in poor RV function → RAP ↑ without stroke volume increase → PAPi falls [[sources/papi-ejhf-2020]] (high)
- Venoconstriction → reduced venous return slope → lower RAP and CO even with unchanged cardiac function

### The Fundamental Limitation: Non-Unique PAPi Values
The same PAPi value can reflect entirely different hemodynamic states. Example [[sources/papi-ejhf-2020]] (high):
- Patient A: PAC 5 mL/mmHg, SV 50 mL, RAP 5 mmHg → PAPi ≈ 2.0
- Patient B: PAC 1.5 mL/mmHg, SV 40 mL, RAP 14 mmHg → PAPi ≈ 2.0

**In homogeneous populations** (similar PAC and PAWP), the SV/RAP ratio dominates PAPi → PAPi approximates a proxy for the **Frank-Starling relationship** [[sources/papi-ejhf-2020]] (high).

### Clinical Cutoffs (Population-Specific; Not Interchangeable)
Thresholds are context-specific and derived from studies with significant selection bias; cross-population application is invalid [[sources/papi-ejhf-2020]] (high); [[sources/mcs-jic-2023]] (high):
- **≤0.9**: RV failure in acute RV/inferior MI — 100% sensitivity, 98% specificity for in-hospital mortality/RV support (Korabathina 2012, n=84)
- **<1.85**: predicts post-LVAD RV failure — 94% sensitivity, 81% specificity; outperforms RA:PAWP, RVSWI, RAP (Morine 2016, n=132)
- **<3.65**: advanced HF (ESCAPE trial, n=190) — 83% sensitivity, 31% specificity, 71% PPV for 6-month death/hospitalization
- **<3.7**: lowest quartile in PAH — 1-year survival 51% vs 75% in higher quartiles (Mazimba 2019, n=272)
- **≥1.0**: required for VA-ECMO decannulation in ECPELLA weaning protocol [[sources/mcs-jic-2023]] (high)

### Application in ECPELLA Weaning
- Step 2 of the three-step ECPELLA weaning protocol governs VA-ECMO decannulation:
  - RA pressure <15 mmHg AND PAPi ≥1.0
  - Minimum VA-ECMO flow 1–1.5 L/min before decannulation trial
  - If PAPi <1.0: do not proceed; investigate RV failure, consider RV-targeted therapy
- VA-ECMO preload caveat: retrograde aortic flow augments venous return → artificially elevates RAP denominator → may lower PAPi even with adequate RV function [[sources/mcs-jic-2023]] (high)
- See [[concepts/ECPELLA]] for the full weaning protocol

### Setting-Specific Behaviour of PAPi

#### Advanced HF + Pulmonary Hypertension
- Low PAC makes PAPP highly sensitive to SV changes (steep SV–PAPP slope)
- Progressive RV failure → SV falls → PAPP falls sharply → PAPi declines even if RAP is unchanged
- PAPi may be a **sensitive indicator of progressive RHF** in this population [[sources/papi-ejhf-2020]] (high)

#### Post-LVAD
- LVAD therapy rapidly improves PAWP and PAC via LV unloading → SV–PAPP slope flattens
- Significant PAPi drop post-LVAD only occurs if concurrent RAP increase is present
- PAPi may be **less sensitive** for detecting post-LVAD RHF in absence of device malfunction [[sources/papi-ejhf-2020]] (high)

#### Acute MI Cardiogenic Shock (SHOCK Trial/Registry)
- Mean PAPi 1.5–1.6 in both SHOCK trial and registry
- PAPi was **NOT significantly associated with 30-day mortality** in this setting [[sources/papi-ejhf-2020]] (high)
- Contrasts with its prognostic value in advanced HF (ESCAPE) and PAH — reflects population-specific PAC/PAWP difference

## Contradictions / Open Questions
- **Cutoff non-interchangeability**: AMI-CS (≤0.9), LVAD (<1.85), advanced HF (<3.65), VA-ECMO weaning (≥1.0) thresholds derived from different populations; cross-application invalid but frequently practised [[sources/papi-ejhf-2020]] (high)
- **PAPi vs 30-day mortality in cardiogenic shock**: SHOCK trial/registry showed no significant association — contradicts the prognostic value seen in advanced HF and PAH [[sources/papi-ejhf-2020]] (high) vs [[sources/mcs-jic-2023]] (high; PAPi used as weaning criterion)
- **VA-ECMO preload confound**: standard formula not designed for VA-ECMO; RAP elevation from retrograde flow can artefactually lower PAPi; adjusted interpretation not validated [[sources/mcs-jic-2023]] (high)
- **PAC and PAWP interaction**: PAPi can rise simply from elevated PAWP (reduced PAC) even with unchanged RV function — misidentified as improved RV function if not recognised [[sources/papi-ejhf-2020]] (high)
- **Serial PAPi monitoring**: no studies document serial changes in PAPi over time or with specific therapeutic interventions; optimal timing/frequency not established
- **Thresholds unvalidated**: all reported thresholds carry significant risk of bias (post-hoc analyses, incomplete datasets); none prospectively validated

## Connections
- Related to [[concepts/Cardiogenic-Shock]]
- Related to [[concepts/ECPELLA]]
- Related to [[concepts/Temporary-Mechanical-Circulatory-Support]]
- Related to [[concepts/Invasive-Hemodynamic-Monitoring-CS]]
- Related to [[concepts/Right-Heart-Catheterization]]
- Related to [[concepts/Right-Ventricular-Failure]]
- Related to [[concepts/RV-PA-Coupling]]
- Related to [[concepts/Pulmonary-Hypertension]]

## Sources
- [[sources/papi-ejhf-2020]] (high)
- [[sources/mcs-jic-2023]] (high)
