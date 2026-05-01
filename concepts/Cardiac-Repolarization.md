---
dg-publish: true
title: "Cardiac Repolarization"
tags: [cardiac-electrophysiology, long-qt-syndrome, short-qt-syndrome, channelopathies, arrhythmia]
source_count: 2
last_updated: 2026-05-01
---

# Cardiac Repolarization

## Definition
Cardiac repolarization is the restoration of the resting membrane potential in cardiomyocytes following depolarization, mediated by coordinated outward K⁺ currents (IKs, IKr, IK1) that overcome residual inward Ca²⁺ and Na⁺ currents during action potential phases 2 and 3. On the surface ECG, ventricular repolarization is captured as the T-wave; its duration is approximated by the QT interval.

## Key Concepts

### Ion Currents and Regional Heterogeneity
- Ventricular repolarization is governed by the net balance of outward K⁺ currents (IKs/KCNQ1, IKr/KCNH2, IK1/KCNJ2) against inward currents (ICaL/CACNA1C, INaLate/SCN5A). ([[sources/repolarisation-jaccep-2023]], rating: high)
- **Regional heterogeneity in ion channel expression** creates spatial gradients in action potential duration (APD) across the heart: subepicardium vs. subendocardium, right vs. left ventricle, base vs. apex. These APD gradients generate the potential differences that manifest as the T-wave on the ECG. ([[sources/repolarisation-jaccep-2023]])
- The **T-wave shape** (not just QT duration) reflects these regional repolarization gradients and differs systematically between LQTS genetic subtypes as a consequence of where each gene's channel is most abundantly expressed. ([[sources/repolarisation-jaccep-2023]])
- **KCNQ1/IKs:** Higher expression in subepicardium and right ventricle; relatively inactive at low heart rates; becomes dominant at higher rates. At rest, IKs contributes minimally to repolarization — mutations in KCNQ1 cause little QT prolongation at rest but unmask dramatically with exercise (LQT1 pattern). ([[sources/repolarisation-jaccep-2023]])
- **KCNH2/IKr:** Relatively large at low heart rates; IKr reduction causes greater APD prolongation in LV than RV (where IKs compensates) → **bifid T-wave** seen in LQT2. ([[sources/repolarisation-jaccep-2023]])
- **SCN5A/INaLate:** Gain-of-function mutation produces persistent late Na⁺ influx throughout phase 2, prolonging the plateau → **delayed T-wave onset and long ST-segment** (LQT3 pattern). ([[sources/repolarisation-jaccep-2023]])
- **Heart-rate dependence:** QTc correction formulas (Bazett: QT/√RR; Fridericia: QT/∛RR) adjust for the inverse QT-heart rate relationship. IKs increases at higher rates, shortening APD — this is the basis of exercise testing in LQTS. ([[sources/repolarisation-jaccep-2023]])

### ECG Parameters of Repolarization
- **QTc interval** is the primary clinical parameter; Bazett formula used most commonly but Fridericia preferred at higher heart rates. ([[sources/repolarisation-jaccep-2023]])
- **Tpeak-to-T-end (TpTe):** Reflects transmural dispersion of repolarization; distinguishes LQTS mutation carriers from controls and differentiates LQTS subtypes — but is not sensitive enough to separate symptomatic from asymptomatic LQTS patients. ([[sources/repolarisation-jaccep-2023]])
- **T-wave morphology:** Small variations in T-wave shape independently predict life-threatening arrhythmias in both low- and moderate-risk populations. AI-based morphology analysis achieves AUC 0.741 for identifying concealed LQTS (normal QTc). ([[sources/repolarisation-jaccep-2023]])
- In **SQTS:** Short/absent ST segments; tall asymmetrical T-waves; prolonged TpTe; shorter J-point-to-Tpeak interval in symptomatic patients. QTc shortening severity does NOT correlate with arrhythmia risk. ([[sources/repolarisation-jaccep-2023]])

### Arrhythmogenesis from Repolarization Abnormalities
- **Trigger — EADs (prolonged repolarization):** Prolonged APD → reactivation of ICaL and/or spontaneous SR Ca²⁺ release → depolarising INCX current → early afterdepolarizations. ~700,000 synchronised cardiomyocytes required to propagate an EAD to tissue-level triggered action potential. ([[sources/repolarisation-jaccep-2023]])
- **Trigger — R-from-T phenomenon:** Spontaneous wavefront arising at the border between long and short repolarization regions, independent of EADs per se. ([[sources/repolarisation-jaccep-2023]])
- **Trigger — SQTS (shortened repolarization):** APD shortening relative to calcium transient duration → elevated intracellular Ca²⁺ remains when the cell repolarizes → reverse-mode NCX provides inward INCX → afterdepolarization → triggered activity. Tracked clinically by the **electromechanical window** (negative EM window = increased arrhythmia risk). ([[sources/repolarisation-jaccep-2023]])
- **Substrate:** Spatial heterogeneity in refractoriness → unidirectional conduction block → functional re-entry. Shortened QTc (SQTS) facilitates re-entry because refractory periods are abbreviated. ([[sources/repolarisation-jaccep-2023]])
- **TdP mechanism (LQTS):** Initiated by focal beats in the long-repolarization zone. Multiple premature focal beats in this zone shorten APD locally more than in surrounding myocardium → reversal of the repolarization gradient → substrate for unidirectional block → transition from focal to re-entrant mechanism. ([[sources/repolarisation-jaccep-2023]])
- **Post-repolarization refractoriness (ischaemia):** During ischaemia, the refractory period extends beyond the end of the action potential → APD is no longer a reliable estimate of refractoriness → T-wave duration does not reflect heterogeneity in refractoriness during acute ischaemia. ([[sources/repolarisation-jaccep-2023]])

### Repolarization Reserve
- The concept of **repolarization reserve** (Roden 1998) holds that multiple redundant mechanisms (IKr, IKs, IK1, INa-L, etc.) maintain normal repolarization. When one mechanism is already perturbed (e.g., by a latent LQTS mutation or low-frequency variant), the addition of an IKr-blocking drug depletes reserve and unmasks QT prolongation and TdP risk. ([[sources/repolarisation-jaccep-2023]])
- The KCNE1 p.Asp85Asn variant (MAF ~1%, European) exerts a 7.42 ms/allele QTc effect and has been shown to predispose to both congenital LQTS and drug-induced TdP — exemplifying the role of low-frequency modulatory variants in depleting repolarization reserve. ([[sources/repolarisation-jaccep-2023]])
- Concomitant factors that further deplete reserve: hypokalemia, hypomagnesemia, bradycardia, female sex (estrogen inhibits IKr), disease-related ion channel remodeling. ([[sources/repolarisation-jaccep-2023]])

### Common Genetic Variants and Heritability
- QT interval heritability in the general population: **25–50%.** ([[sources/repolarisation-jaccep-2023]])
- 2022 multiancestry GWAS meta-analysis (n=252,977) identified **176 independent QT-SNPs;** common variants have small individual effects (<1–2 ms/allele). ([[sources/repolarisation-jaccep-2023]])
- Many QT-SNPs cluster near known LQTS/SQTS ion channel genes; many are at novel loci representing unexplored biology relevant to repolarization. ([[sources/repolarisation-jaccep-2023]])
- Genome-wide genetic correlation exists between QT interval in the general population and congenital LQTS susceptibility — confirming a shared biology. ([[sources/repolarisation-jaccep-2023]])
- See [[concepts/Polygenic-Risk-Score]] for details on PRS application in LQTS.

### Primary vs Secondary ST-T Classification
- **Primary ST-T changes** are repolarization abnormalities: myocardial ischemia, electrolyte disturbances (hyperkalemia, hypokalemia), tachycardia, sympathetic activation, and drug effects. In primary changes, the **QRS complex is normal** — the abnormal force originates in the repolarization process itself.
- **Secondary ST-T changes** are activation (depolarization) abnormalities: LBBB, LVH, pre-excitation, PVCs, pacemaker. In all secondary cases, the mechanism is the same — slow, abnormal endocardium-to-epicardium depolarization → subendocardium repolarizes before subepicardium → reversed repolarization direction → discordant ST-T relative to QRS. ([[sources/STT-mechanism-ACA-2026]], rating: medium)
- **Ischemia injury current mechanism:** Partial depolarization of ischemic myocardium creates a voltage gradient at rest; during the TP/PQ period (when normal myocardium is fully repolarized), current flows between ischemic and normal zones. In subendocardial ischemia, this elevates the TP/PQ baseline, making the ST segment (which remains at its true position during AP phase II) appear **depressed**. In transmural ischemia, the baseline is depressed, making ST appear **elevated**. ([[sources/STT-mechanism-ACA-2026]])

## Contradictions / Open Questions
- **Injury current theory completeness:** The diastolic/systolic injury current model of ST displacement (TP/PQ baseline shift) is the dominant teaching model, but quantitative accuracy in human ischemia has been questioned. Alternative models exist (systolic injury current — ST shift during depolarisation rather than baseline during rest). ([[sources/STT-mechanism-ACA-2026]])
- **T-wave as refractoriness surrogate fails in ischaemia:** The T-wave is used clinically as an estimate of repolarization heterogeneity and refractoriness, but post-repolarization refractoriness during acute ischaemia makes the T-wave an unreliable guide. This limits the use of ECG repolarization parameters for arrhythmia risk prediction during acute coronary events. ([[sources/repolarisation-jaccep-2023]])
- **EADs vs. R-from-T — relative contribution unresolved:** Both EADs and the R-from-T phenomenon have been proposed as the primary trigger for LQTS arrhythmias. Their relative contributions in human disease (vs. ex vivo/in silico models) remain unresolved. ([[sources/repolarisation-jaccep-2023]])
- **Electromechanical window direction paradox:** Logic predicts that a longer mechanical systole relative to electrical systole (positive EM window) should be protective. However, clinical data show that a **decreased or negative** EM window is the risk factor for arrhythmias. The exact mechanism — implicating stretch-activated ion channels — is not yet fully understood. ([[sources/repolarisation-jaccep-2023]])
- **SQTS: QTc severity does not predict arrhythmia risk** — unlike LQTS. This distinction is clinically important but lacks mechanistic explanation at the individual-patient level and has no clinical risk stratification tool equivalent to the Schwartz Score or LQTS 1-2-3 calculator. ([[sources/repolarisation-jaccep-2023]])

- Related to [[concepts/ST-T-Changes]]
- Related to [[sources/STT-mechanism-ACA-2026]]

## Connections
- Related to [[concepts/Cardiac-Action-Potential]]
- Related to [[concepts/Torsades-de-Pointes]]
- Related to [[concepts/Ion-Channel-Mutations]]
- Related to [[concepts/Polygenic-Risk-Score]]
- Related to [[concepts/Drug-Induced-Arrhythmia]]
- Related to [[concepts/Schwartz-Score]]
- Related to [[entities/Long-QT-Syndrome]]
- Related to [[entities/Short-QT-Syndrome]]
- Related to [[entities/Brugada-Syndrome]]
