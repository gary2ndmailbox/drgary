---
dg-publish: true
title: "Review of Processing Pathological Vectorcardiographic Records for the Detection of Heart Disease"
date_ingested: 2026-05-30
source_type: review article
Citation: "Vondrak J and Penhaker M (2022) Review of Processing Pathological Vectorcardiographic Records for the Detection of Heart Disease. Front. Physiol. 13:856590."
DOI: "https://doi.org/10.3389/fphys.2022.856590"
tags: [vectorcardiography, ECG-derived-VCG, Frank-lead-system, QRS-T-angle, cardiac-signal-processing]
rating: medium
raw_path: raw/VCG-FronPhysiol-2022.md
---

# Review of Processing Pathological Vectorcardiographic Records for the Detection of Heart Disease

## Authors, Journal, Affiliations, Type, DOI
- Authors: Jaroslav Vondrak, Marek Penhaker
- Journal: Frontiers in Physiology (Front. Physiol.), Volume 13, Article 856590
- Affiliation: Faculty of Electrical Engineering and Computer Science, VSB-Technical University of Ostrava, Ostrava, Czech Republic
- Type: Review article
- DOI: https://doi.org/10.3389/fphys.2022.856590

## Overview
This review covers VCG signal processing methods and their application to detecting heart disease from VCG records (directly measured or derived from 12-lead ECG). VCG provides spatial three-dimensional information about cardiac electrical activity not captured by standard 12-lead ECG. The paper compares transformation methods for deriving VCG from ECG (Kors regression best at ~98%, IDT ~97.2%, quasi-orthogonal unreliable), and reviews VCG diagnostic applications across six cardiac pathologies: acute ischemia/MI, myocardial scar, LBBB/CRT selection, hypertrophic cardiomyopathy, long QT syndrome, and atrial fibrillation. A key clinical finding is that QRS area from VCG outperforms QRS duration and LBBB morphology as a predictor of CRT response.

## Keywords
vectorcardiography, heart disease, VCG features, transformation methods, electrocardiography

## Key Takeaways

### 1. VCG Basics and History

**Physiological Basis:**
- VCG represents the cardiac electrical generator as an equivalent dipole (electric heart vector, EHV), displayed as continuous loops in three orthogonal planes
- Three loops correspond to P wave, QRS complex, and T wave
- Three projections: frontal plane (X-Y), transversal plane (X-Z), sagittal plane (Y-Z); also displayed as 3D image
- Cardiac activation sequence: SA node → atrial walls → AV node (slow, allowing ventricular filling) → Purkinje fibers → septum (right to left) → ventricular walls (left wall last due to thickness); LV depolarized via anterior/posterior fascicles; lateral basal region last activated
- Repolarization: epicardium first, inward direction; T-wave signal same sign as depolarization due to inward direction; amplitude much smaller, duration longer

**Historical Development:**
- 1887: Augustus Waller described dipolar nature of cardiac generator
- 1920s: Mann introduced the concept of a "loop" from three Einthoven leads
- 1937: Schellong — first uncorrected orthogonal lead system
- 1956: Frank — first corrected lead system (mathematical model, 7 electrodes); today one of the most widely used

**VCG vs 12-lead ECG:**
- VCG provides additional spatial information (phase relationships between leads, 3D loop morphology)
- Higher sensitivity than standard ECG in: atrial enlargement, right ventricular hypertrophy, LQTS detection, MI classification
- Currently not routinely used in clinical practice; 12-lead ECG remains the standard
- Most analyzed VCG parameter today: QRS-T angle

### 2. Transformation Methods (ECG → VCG)

**Why Derivation is Needed:**
- Frank lead system direct measurement uses 7 electrodes — rarely available in practice
- Transformation matrices allow VCG derivation from standard 12-lead ECG
- All linear transformations: V = M × E (M = transformation matrix, E = ECG leads)

**Transformation Method Comparison:**

| Method | Derivation | Primary Use | Accuracy |
|---|---|---|---|
| Kors regression | Minimizing mean error (QRS regression, CSE database) | All types of ECG | ~98% |
| Inverse Dower (IDT) | Pseudo-inverse of Dower forward matrix (torso model) | Pathology affecting QRS | ~97.2% |
| PLSV | Least squares (P-wave optimized, 124 patients) | P wave | ~96.8% |
| QLSV | Least squares (QRS-optimized) | QRS complex | ~97% |
| Mason-Likar | Regression (modified electrode positions) | Stress testing/exercise ECG | ~95% |
| Quasi-orthogonal | Approximation (ECG leads ≈ VCG leads) | All types | ~90% — NOT reliable |

**Key Points on Transformation Accuracy:**
- Kors regression method most accurate overall; values do not differ significantly from directly-measured Frank lead system for QRS-T angle
- IDT (Edenbrandt & Pahlm 1988): pseudo-inverse of Dower's forward matrix; most commonly used in research; focused on QRS
- **IDT should NOT be used for AF f-wave analysis** — fibrillatory waves are P-wave-dependent; significant error introduced (Guillem 2009)
- Quasi-orthogonal methods are NOT suitable for diagnostic processing due to high error rate (one ECG lead per VCG lead approximation)
- For pathologies affecting multiple ECG segments, combining methods may be preferable

**IDT Transformation Matrix (Edenbrandt & Pahlm 1988):**
- X: 0.156·I − 0.010·II − 0.172·V1 − 0.074·V2 + 0.122·V3 + 0.231·V4 + 0.239·V5 + 0.194·V6
- Similar formulas for Y and Z leads

**Kors Regression Coefficients (Table):**
- X: 0.38·I − 0.07·II − 0.13·V1 + 0.05·V2 − 0.01·V3 + 0.14·V4 + 0.06·V5 + 0.54·V6
- Y: −0.07·I + 0.93·II + 0.06·V1 − 0.02·V2 − 0.05·V3 + 0.06·V4 − 0.17·V5 + 0.13·V6
- Z: 0.11·I − 0.23·II − 0.43·V1 − 0.06·V2 − 0.14·V3 − 0.20·V4 − 0.11·V5 + 0.31·V6

### 3. VCG in LBBB and CRT Selection

- LBBB hallmark: mismatch between main axes of QRS complex and T wave → very wide QRS-T angles
- Frank lead system is gold standard for defining mean spatial and vertex angles of QRS-T in LBBB (Schreurs 2010)
- **QRS area (from VCG) is a stronger predictor of CRT response than QRS duration and conventional LBBB morphology** (van Deursen 2015a,b; Rad 2016)
- Rad 2016: used 51 VCGs derived by Kors regression; QRS area is a non-invasive alternative to intracardiac measurement identifying delayed lateral wall activation better than QRS duration and LBBB morphology
- Shvilkin 2010: QRS/T vector magnitude ratio and deepest-S/largest-T ratio from derived VCG allow 100% sensitivity and 96–68% specificity to distinguish new from old LBBB — relevant in chest pain management
- Nguyên 2018: QRS area (from Kors VCG) and focal scar CMR parameters are independent predictors of CRT response; combination of CMR+VCG parameters improves CRT response prediction
- Okafor 2020: reducing QRS area improves acute hemodynamic response to CRT; myocardial scar adversely affects QRS area and response

### 4. VCG in Myocardial Ischemia and Infarction

**Myocardial Ischemia:**
- Sun 2017 (IDT-derived VCG, 14 features, 132 records): accuracy 98.07%, sensitivity 98.63%, specificity 99.04%
- Dehnavi 2011 (PCA+ICA+NNC, 60 ischemic records): VCG accuracy 86% vs ECG 73% — VCG higher than ECG for automated ischemia detection
- QRS volume is the best individual feature (Correa 2012): sensitivity 64.5%, specificity 74.6%, AUC 0.77
- ST and T segment combined with QRS improves detection (Treskes 2015: ST vector + ventricular gradient ≥ conventional ECG; van Hellemond 2013: scar risk area better with QRS+ST combined)

**Myocardial Infarction:**
- VCG AMI detection accuracy: 97–99% in multiple studies (Yang 2012: 97.28%/95%; Huang 2011: 96.96%/99.89%; Tripathy 2017: 99.80%/99.67%; Hafshejani 2021: 99.4%/100%)
- Ge 2008: VCG 98% vs ECG 73% for AMI/SAMI classification
- VCG can distinguish anterior from inferior MI (Kan 2012: accuracy >94.7%; 96.5% anterior vs inferior)
- Goernig 2015: MI detected in 75.2% of ECGs vs 83.2% of T-vector/loop VCG parameters
- VCG superior sensitivity for inferior infarction detection vs ECG (Hurd 1981, Edenbrand 1990)
- T-vector beat-to-beat variability (Waks 2015): increased variability associated with SCD risk

### 5. VCG in Hypertrophic Cardiomyopathy (HCM)

- QRS-T spatial angle strongly associated with HCM (Cortez 2017b: n=967 VCGs by Kors, HCM vs HC)
- Spatial ventricular gradient (SVG) and spatial QRS, QT, T intervals differ between HCM genotype+ and genotype−
- LVH diagnosis: QRS vector magnitude and T loop direction are useful; ECG criteria have low accuracy (57%); VCG discriminatory model achieves 79% accuracy (Man 2012)
- Minimum volume ellipsoid (MVEE) features + random forest: accuracy 0.904 (Kataoka 2021)
- Spatial QRS-T angle outperforms Italian and Seattle ECG criteria for HCM in pediatric patients (Cortez 2015)
- T-wave vector magnitude (VM): lower VM associated with higher sentinel event risk in pediatric HCM (Jimenez 2021)

### 6. VCG in Long QT Syndrome

- VCG QT measurement superior to ECG in LQTS children: 86% sensitivity vs 69% sensitivity (Diamant 2013; n=70, 35 LQTS)
- Specificity comparable: 80% VCG vs 77% ECG
- VCG detects concealed LQTS (ecLQTS) that is not visible on standard ECG (Cortez 2017a: n=610, QT peak analysis)
- Automatic VCG detection achieves high precision and reliability for LQTS (Diamant 2010)

### 7. VCG in Atrial Fibrillation

- VCG (Frank lead) achieves higher sensitivity for echocardiographic left atrial enlargement detection than 12-lead ECG (Bartall 1978)
- P-loop analysis: abnormal P-wave VCG findings precede PAF onset in hypertensive patients (Filipova 2017; n=276)
- PAF patients: prolonged P-wave duration/amplitude, abnormal P-loop notches, increased spatial velocity
- AF detection from P-wave VCG: classification accuracy 93.75% (Filos 2017, SVM classifier, 7 features)
- **Caveat:** IDT should NOT be used for AF f-wave spatial analysis — IDT works with P-wave contribution → significant error in AF records (Guillem 2009)
- Alternative electrode configuration for AF: at least 1 back electrode needed for optimal atrial dipolar activity observation

### 8. Current Problems and Limitations of VCG

- No standardized VCG diagnostic criteria for any pathology — caused by lack of cardiologist validation
- Most studies are performed offline on pre-existing datasets (primarily PhysioNet PTB database)
- VCG features are not cross-validated between different databases
- Small dataset sizes in most studies; few authors use their own measured records
- Transformation accuracy problem: IDT and Kors regression lag on P and T waves compared to QRS
- Quasi-orthogonal derivation → only approximate spatial information; not suitable for diagnostic processing
- Pathway to standardization: consultation between engineers and cardiologists, frank lead clinical deployment, multi-part VCG analysis (QRS + ST + T combined)

## Limitations of the Document
- Technical/engineering-focused review; limited direct clinical applicability without cardiologist validation of VCG features
- Most cited studies use small retrospective datasets (30–370 records) from PhysioNet PTB database — not representative of clinical populations
- VCG features are not standardized across pathologies; results are dataset-specific
- No systematic comparison of clinical outcomes using VCG vs ECG-based decisions
- No direct comparison with current guideline-based approaches for most pathologies

## Key Concepts Mentioned
- [[entities/Vectorcardiography]] — comprehensive VCG entity (new page)
- [[concepts/LBBB-Criteria]] — QRS area from VCG superior to QRS duration and LBBB morphology for CRT selection
- [[concepts/Cardiac-Resynchronization-Therapy]] — QRS area as non-invasive predictor of LV lateral wall activation delay
- [[concepts/ECG-Conduction-Disturbances]] — VCG criteria for LBBB; QRS-T angle in conduction disorders
- [[concepts/HCM-Risk-SCD]] — QRS-T spatial angle for HCM detection
- [[concepts/Sudden-Cardiac-Death]] — T-vector beat-to-beat variability as SCD marker

## Key Entities Mentioned
- [[entities/Vectorcardiography]] — Frank lead system, transformation methods, loop parameters

## Wiki Pages Updated
- Created: `wiki/sources/vcg-fronphysiol-2022.md`
- Created: `wiki/entities/Vectorcardiography.md`
- Updated: `wiki/sourceindex.md`
- Updated: `wiki/wikiindex.md`
- Updated: `wiki/concepts/LBBB-Criteria.md` — QRS area from VCG as stronger CRT predictor; new/old LBBB discrimination
- Updated: `wiki/concepts/Cardiac-Resynchronization-Therapy.md` — QRS area VCG parameter
