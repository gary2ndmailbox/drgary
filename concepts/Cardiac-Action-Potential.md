---
dg-publish: true
title: "Cardiac Action Potential"
tags: [cardiac-electrophysiology, channelopathies, ion-channels]
source_count: 4
last_updated: 2026-05-01
---

# Cardiac Action Potential

## Definition
The cardiac action potential (AP) is the sequence of voltage changes across the cardiomyocyte membrane driven by the coordinated opening and closing of ion channels. It has five phases (0–4) and governs the timing of contraction and relaxation of the heart.

## Key Concepts
- **Phase 0 (Depolarization):** Rapid influx of Na⁺ through voltage-gated sodium channels (Nav1.5, encoded by SCN5A). Gain-of-function mutations in SCN5A cause persistent Na⁺ influx into the plateau phase, prolonging repolarization as in LQT3. ([[sources/channelopathies-jaha-2025]])
- **Phase 1 (Early repolarization):** Transient outward K⁺ current (Ito). Gain-of-function mutations increasing Ito contribute to Brugada syndrome and early repolarization syndrome. ([[sources/channelopathies-jaha-2025]])
- **Phase 2 (Plateau):** Balance of inward Ca²⁺ (ICa,L) and Na⁺ currents against outward K⁺ currents. Reduction in inward currents (e.g., loss-of-function CACNA1C mutations) shortens the plateau and contributes to BrS and SQTS. ([[sources/channelopathies-jaha-2025]])
- **Phase 3 (Repolarization):** Dominated by rapid (IKr, KCNH2) and slow (IKs, KCNQ1) delayed rectifier K⁺ currents. Loss-of-function mutations in KCNH2 or KCNQ1 reduce repolarizing current, prolonging the QT interval as in LQT1 and LQT2. ([[sources/channelopathies-jaha-2025]])
- **Phase 4 (Resting potential):** Maintained by inward rectifier K⁺ current (IK1, KCNJ2). Mutations here are implicated in Andersen-Tawil syndrome (LQT7) and SQTS3. ([[sources/channelopathies-jaha-2025]])
- **Phase 2 (Late Na⁺ current — INaLate):** In addition to ICa,L, a small persistent ("late") Na⁺ current (INaLate, carried by Nav1.5) flows throughout the plateau. Normally INaLate is minor, but it is upregulated by CaMKII (in heart failure and HCM), by gain-of-function SCN5A variants (LQT3), and by ischaemia/oxidative stress. INaLate prolongs APD, causes intracellular Na⁺ overload → Ca²⁺ overload via NCX reverse mode, and provides the mechanistic substrate for EADs at slow heart rates. Ranolazine and mexiletine selectively block INaLate. ([[sources/membrane-potential-physrev-2021]], rating: very high)
- Abnormalities in the AP predispose patients to delayed afterdepolarizations, early afterdepolarizations, and life-threatening arrhythmias including torsades de pointes and VF. ([[sources/channelopathies-jaha-2025]])

- **Tissue-specific ion channel composition:** The AP waveform is not uniform — each cardiac region expresses a distinct ion channel repertoire, producing characteristic APD and conduction properties. Key profiles: (1) **Sinoatrial node:** dominant If (HCN4) + ICa,T → spontaneous phase 4; no Phase 0 INa; (2) **AV node:** ICa,L-driven slow upstroke → decremental conduction; (3) **Purkinje fibres:** large Ito, prominent IKr; longest APD in the conduction system; prone to EADs; (4) **Atrial myocytes:** IKur (Kv1.5, KCNA5) — a rapid outward K⁺ current absent in ventricles — + IKACh; faster repolarization than ventricle; (5) **Ventricular layers:** subepicardial cells have prominent Ito (largest notch), M-cells (midmyocardial) have lowest IKs → longest APD, subendocardial have more IKs. ([[sources/membrane-potential-physrev-2021]])
- **M-cell transmural heterogeneity:** M cells occupy the midmyocardium and express the lowest density of IKs of the three ventricular layers. At slow heart rates when IKs contribution is minimal, M-cell APD is disproportionately prolonged relative to subepicardium and subendocardium, generating the peak of the T-wave on surface ECG. This transmural dispersion of repolarization (TDR) is the substrate for the "R-on-T" phenomenon and TdP initiation — the M-cell generates the T-wave summit while repolarization dispersion across layers creates the window for re-entry. ([[sources/membrane-potential-physrev-2021]])

- **Regional and transmural APD heterogeneity:** Ion channel expression is non-uniform across the heart, producing spatial gradients in APD that underlie the T-wave. Key differences include: (1) **Subepicardium vs subendocardium** — IKs higher in subepicardium; (2) **RV vs LV** — IKs more prominent in RV; (3) **Apex vs base** — activation-repolarization patterns differ. These gradients explain why loss-of-function in different genes produces different T-wave morphologies: KCNQ1 mutations → loss of subepicardial-subendocardial gradient; KCNH2 mutations → loss of LV-RV gradient → bifid T-wave; SCN5A gain-of-function → plateau prolongation → delayed T-wave onset. ([[sources/repolarisation-jaccep-2023]], rating: high)

- **Ischemic AP changes:** Hypoxia → ↓ ATP → ↓ Na⁺/K⁺ ATPase pump activity + ATP-sensitive K⁺ channel opening → ↑ extracellular K⁺ → initial hyperpolarization followed by partial depolarization (resting membrane potential less negative than −90 mV). Partial depolarization shortens APD and causes earlier repolarization of ischemic myocardium — the cellular basis for reversal of the normal epicardium-to-endocardium repolarization gradient and the ST-T changes in ACS. ([[sources/STT-mechanism-ACA-2026]], rating: medium)
- **Hyperkalemia AP effects:** ↑ extracellular K⁺ → resting membrane potential less negative → partial depolarization → shortened APD → exaggerated phase 2–3 slope → tall peaked T waves (shortened QT) on ECG. With severe hyperkalemia, Na⁺ channels become inactivated → slowed phase 0 → widened QRS, prolonged PR, sine-wave pattern, impending cardiac arrest. ([[sources/STT-mechanism-ACA-2026]])
- **Hypokalemia AP effects:** Inhibits Na⁺/K⁺ ATPase → hyperpolarization (more negative resting potential, not partial depolarization); inhibits IKr (delayed rectifier) → reduced repolarization reserve → prolonged APD and QT interval; increased susceptibility to EADs, prominent U waves, and life-threatening arrhythmias. ([[sources/STT-mechanism-ACA-2026]])

## Contradictions / Open Questions
- **Species differences limit translational electrophysiology:** Mouse and rat ventricular APs are triangular and very short (~50–100 ms) because IKr/IKs are nearly absent and Ito dominates repolarization. Human APs have a sustained plateau (Phase 2) maintained by ICa,L vs. IKr/IKs balance. This means rodent in vivo models of LQT syndrome or repolarization changes have fundamental limitations in APD biology and drug sensitivity — findings from rodents require confirmation in large-animal or human iPSC-CM models before clinical translation. ([[sources/membrane-potential-physrev-2021]])
- **Brugada pathophysiology — repolarization vs. depolarization:** Phase 1 Ito gain-of-function is the basis of the repolarization hypothesis for Brugada syndrome. The alternative depolarization hypothesis holds that reduced INa causes conduction slowing in the RVOT rather than AP morphology changes. Both are consistent with phase 1 abnormality but differ in mechanism and in the therapeutic implications (repolarization → Ito blockers; depolarization → Nav1.5 enhancers or ablation targeting conduction substrate). This unresolved mechanistic debate directly influences the rationale for catheter ablation in BrS. ([[sources/channelopathies-jaha-2025]])
- **SCN5A bidirectional phenotype:** GOF SCN5A mutations prolong the AP plateau (phase 0/2) causing LQT3; LOF mutations reduce INa causing Brugada. The same gene, depending on mutation effect direction, produces physiologically opposite syndromes — a fundamental insight that requires variant-specific effect characterization before any therapy is initiated. VUS interpretation in SCN5A is therefore particularly high-stakes. ([[sources/channelopathies-jaha-2025]])

- Related to [[concepts/ST-T-Changes]]

## Connections
- Related to [[concepts/Ion-Channel-Mutations]]
- Related to [[concepts/Torsades-de-Pointes]]
- Related to [[concepts/Electrical-Remodeling]]
- Related to [[entities/Long-QT-Syndrome]]
- Related to [[entities/Brugada-Syndrome]]
- Related to [[entities/CPVT]]
- Related to [[entities/Atrial-Fibrillation]]
- Related to [[entities/Heart-Failure]]
- Related to [[entities/HCM]]
- Related to [[entities/SCN5A]]
- Related to [[entities/KCNQ1]]
- Related to [[entities/KCNH2]]
- Related to [[concepts/Cardiac-Repolarization]]
- Related to [[sources/repolarisation-jaccep-2023]]
- Related to [[sources/membrane-potential-physrev-2021]]
