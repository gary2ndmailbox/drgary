---
dg-publish: true
title: "Vectorcardiography"
tags: [vectorcardiography, Frank-lead-system, ECG-derived-VCG, QRS-T-angle, cardiac-signal-processing]
source_count: 2
---

# Vectorcardiography

## Details
Vectorcardiography (VCG) represents the cardiac electrical generator as an equivalent dipole (electric heart vector, EHV), displaying continuous loops in three mutually perpendicular planes. Unlike the 12-lead ECG which shows time-domain voltage traces, VCG provides spatial (3D) information about the sequence, direction, and magnitude of cardiac electrical activity. VCG is more sensitive than standard ECG in several specific clinical contexts but is not routinely used in clinical practice today.

## Key Facts

### Lead Systems and Planes
- **Frank lead system (1956)**: First corrected orthogonal lead system; uses 7 measuring electrodes; today's gold standard for direct VCG measurement; generates orthogonal XYZ leads
- **Three planes**: Frontal (X-Y), Transversal (X-Z), Sagittal (Y-Z)
- **Three loops**: P loop (atrial depolarization), QRS loop (ventricular depolarization), T loop (ventricular repolarization)
- Precedes direct VCG: uncorrected systems from Schellong (1937) and others; Frank was first corrected system
- Less commonly used alternatives: McFee-Parungao (1961), SVEC III (Schmitt 1955)
- ([[sources/vcg-fronphysiol-2022]], medium)

### Deriving VCG from 12-Lead ECG
Since Frank lead system is rarely used clinically, VCG leads are typically derived from standard 12-lead ECG using transformation matrices (V = M × E).

**Kors Regression Method (Kors 1990) — BEST OVERALL (~98% accuracy):**
- Derived by minimizing mean error (QRS regression) for CSE database patients
- Not significantly different from directly-measured Frank lead system for QRS-T angle
- Most recommended for clinical/research use where direct VCG unavailable
- X = 0.38·I − 0.07·II − 0.13·V1 + 0.05·V2 − 0.01·V3 + 0.14·V4 + 0.06·V5 + 0.54·V6
- Y = −0.07·I + 0.93·II + 0.06·V1 − 0.02·V2 − 0.05·V3 + 0.06·V4 − 0.17·V5 + 0.13·V6
- Z = 0.11·I − 0.23·II − 0.43·V1 − 0.06·V2 − 0.14·V3 − 0.20·V4 − 0.11·V5 + 0.31·V6

**Inverse Dower Transformation (IDT) — ~97.2% accuracy, most widely used in research:**
- Pseudo-inverse of Dower's forward transformation matrix (torso model)
- Primarily focused on QRS complex; reliable but less accurate for P and T waves
- **Contraindicated for AF f-wave spatial analysis** (Guillem 2009) — P-wave contribution introduces significant error in fibrillatory wave loops
- X = 0.156·I − 0.010·II − 0.172·V1 − 0.074·V2 + 0.122·V3 + 0.231·V4 + 0.239·V5 + 0.194·V6

**Other Transformation Methods:**
- PLSV (P-wave optimized, ~96.8%): best for P-wave analysis (AF, atrial enlargement studies)
- QLSV (QRS-optimized, ~97%): similar to regression approach
- Mason-Likar (~95%): designed for stress testing / exercise ECG (modified electrode positions)
- **Quasi-orthogonal (~90%): NOT recommended** — approximates VCG leads from single ECG leads; poor diagnostic accuracy
- ([[sources/vcg-fronphysiol-2022]], medium)

### Key VCG Parameters
- **QRS-T spatial angle**: most commonly analyzed VCG parameter; angle between mean QRS and T vectors in 3D space; abnormal in LBBB (very wide), HCM, ischemia, hypertension
- **QRS area**: area enclosed by QRS loop; stronger predictor of CRT response than QRS duration and conventional LBBB morphology (van Deursen 2015, Rad 2016)
- **QRS volume**: 3D volume of QRS loop; best single feature for ischemia detection (AUC 0.77, Correa 2012)
- **Ventricular gradient vector (VG)**: net time integral of cardiac cycle; useful for ischemia detection combined with ST vector
- **T-wave vector magnitude (VM)**: lower VM associated with adverse events in HCM (Jimenez 2021)
- **QRS loop planarity, roundness, thickness, rotational angle**: morphological loop descriptors
- **Spatial ventricular gradient (SVG)**: differentiates primary from secondary repolarization abnormalities
- For LBBB: mid-end conduction delay in QRS loop is pathognomonic of true LBBB (absent in pseudo-LBBB/LVH) — see [[concepts/LBBB-Criteria]]
- ([[sources/vcg-fronphysiol-2022]], medium) ([[sources/lbbb-evg-ane-2019]], high)

### VCG Advantages Over 12-Lead ECG by Application

| Application | VCG Advantage |
|---|---|
| LQTS detection | 86% sensitivity (VCG) vs 69% (ECG) in children; detects concealed LQTS (Diamant 2013, Cortez 2017) |
| MI classification | ~98% accuracy (VCG) vs ~73% (ECG) in automated detection; can localize (anterior vs inferior) |
| Atrial enlargement | Higher sensitivity for echocardiographic left atrial enlargement (Bartall 1978) |
| HCM | Spatial QRS-T angle outperforms ECG Seattle/Italian criteria in pediatric patients |
| CRT selection | QRS area > QRS duration and LBBB morphology for predicting CRT response |
| True vs pseudo-LBBB | Mid-end QRS loop conduction delay pathognomonic of true LBBB (not detectable on standard ECG) |
| AF P-wave analysis | P-loop abnormalities precede PAF onset; better atrial enlargement detection |

- ([[sources/vcg-fronphysiol-2022]], medium)

### VCG in Specific Cardiac Conditions

**LBBB and CRT:**
- Hallmark of LBBB: very wide QRS-T spatial angle (mismatch between QRS and T-wave axes)
- Frank lead system gold standard for spatial and vertex QRS-T angles in LBBB (Schreurs 2010)
- QRS area (Kors-derived VCG): non-invasive alternative to intracardiac measurement identifying delayed lateral wall activation; outperforms QRS duration and LBBB morphology for CRT prediction (Rad 2016)
- New vs old LBBB: QRS/T vector magnitude ratio and deepest-S/largest-T ratio → 100% sensitivity, 96–68% specificity (Shvilkin 2010; IDT)
- See [[concepts/LBBB-Criteria]] for true LBBB VCG criteria (mid-end conduction delay)

**Myocardial Infarction and Ischemia:**
- QRS loop octant distribution (Yang 2012): sensitivity 97.28%, specificity 95.00%
- Combined QRS + ST + T analysis outperforms single-component analysis
- VCG features detect MI in 98% vs 73% for ECG (Ge 2008)
- T-vector beat-to-beat spatial variability (IDT): increased variability = higher SCD risk (Waks 2015)
- Myocardial scar: QRS area (Kors VCG) + focal scar CMR = best CRT response predictor (Nguyên 2018)

**HCM:**
- Spatial QRS-T angle and SVG distinguish HCM from healthy controls; QRS-T angle associated with genotype
- Spatial QRS-T angle outperforms Italian/Seattle ECG criteria for HCM in pediatric patients

**LQTS:**
- QT interval measurement from VCG loop more accurate than single-lead ECG measurement
- Can unmask concealed LQTS (ecLQTS) by QT-peak analysis

**Atrial Fibrillation:**
- P-loop analysis best with PLSV transformation (not IDT)
- PAF patients: abnormal P-loop notches, prolonged P duration/amplitude, increased spatial velocity
- IDT cannot be used for f-wave analysis in AF

### Current Limitations
- Not routinely measured in clinical practice; Frank lead system requires 7 specific electrodes
- No standardized VCG criteria for clinical use due to lack of cardiologist validation
- Most published VCG datasets are small (30–370 records) and institution-specific
- Transformation accuracy: IDT/Kors both lag on P and T waves vs directly measured VCG; accuracy depends on pathology type
- VCG features are not cross-validated between databases; individual study results may not generalize
- ([[sources/vcg-fronphysiol-2022]], medium)

## Contradictions / Open Questions
- **Kors vs IDT for clinical use:** Both achieve >97% accuracy; Kors more consistently matches Frank lead system for QRS-T angle across published studies; IDT is more widely cited in research but IDT is formally derived from a torso model rather than patient data — practical performance difference is small but Kors is preferred where QRS-T angle analysis is the goal
- **QRS area as CRT predictor:** Van Deursen 2015 and Rad 2016 show QRS area outperforms QRS duration and LBBB morphology for CRT selection — but these are observational studies with small sample sizes; no large RCT confirming QRS area-guided CRT selection strategy
- **IDT in AF:** Guillem 2009 shows IDT introduces significant error for AF f-wave analysis — yet IDT is still commonly used for AF studies in the literature; results of IDT-based AF spatial analysis should be interpreted with caution
- **Standardization gap:** Despite decades of research, no VCG features have been formally validated or accepted into clinical guidelines — represents a significant unmet need

## Connections
- Related to [[concepts/LBBB-Criteria]] — mid-end QRS loop delay pathognomonic of true LBBB; QRS area > QRS duration for CRT selection
- Related to [[concepts/Cardiac-Resynchronization-Therapy]] — QRS area from VCG as superior CRT predictor
- Related to [[concepts/ECG-Conduction-Disturbances]] — VCG in LBBB classification; QRS-T angle in conduction disorders
- Related to [[concepts/HCM-Risk-SCD]] — spatial QRS-T angle for HCM detection and genotype stratification
- Related to [[concepts/Sudden-Cardiac-Death]] — T-vector beat-to-beat variability as SCD risk marker

## Sources
- [[sources/vcg-fronphysiol-2022]] — comprehensive VCG processing review; transformation methods; disease-specific diagnostic accuracy
- [[sources/lbbb-evg-ane-2019]] — VCG criteria for true LBBB; mid-end conduction delay; concordant/discordant LBBB
