---
dg-publish: true
title: "OTVA ECG Localization"
tags: [outflow-tract-ventricular-arrhythmia, ECG-localization, catheter-ablation, PVC, ventricular-tachycardia]
source_count: 2
last_updated: 2026-05-29
---

# OTVA ECG Localization

## Definition
Systematic use of the 12-lead ECG to localize the anatomic site of origin (SOO) of outflow tract ventricular arrhythmias (OTVAs) before catheter ablation. Accurate preprocedural localization guides vascular access, informs patient counselling regarding site-specific risks, and improves ablation success. RVOT origins account for 70–80% of OTVAs; LVOT 15–25%; LV summit ~12%.

## Key Concepts

### Anatomy and Directional Logic
- RVOT: anterior and leftward; activation from here propagates away from V1 → LBBB morphology
- LVOT (aortic sinuses): posterior and central; activation toward V1 → larger/longer R waves in precordial leads
- AMC/anterolateral MA: most posterior → RBBB pattern
- There is a gradient from pure LBBB (anterior RVOT free wall) to RBBB (AMC/anterolateral MA) as SOO shifts posteriorly; AMC is the only break from this gradient (qR in V1 due to remnant His-Purkinje exit) ([[sources/RVOT-LVOT-circ-ep-2019]], rating: high)

### Step 1: Bundle Branch Pattern and Axis (V1 + inferior leads)
- **LBBB + inferior axis** → RVOT or LVOT aortic sinus → apply ECG algorithms
- **RBBB + inferior axis** → AMC or anterolateral mitral annulus
- **LBBB + superior axis** → LV summit (inaccessible/distal GCV) or crux region ([[sources/RVOT-LVOT-circ-ep-2019]])

### Step 2: Classical ECG Signatures by Site

#### RVOT Sites
| Site | V1 | Lead I | Transition | Other |
|------|----|--------|------------|-------|
| Free wall (anterior) | rS | rS (negative) | ≥V4 | QRS ≥140 ms, notching ≥2 inferior leads |
| Septal (posterior) | rS | R (positive) | ≤V3 | Taller, narrower, monophasic inferior R |
| PSC Right cusp | rS | R (tall) | ≥V3 | Notching inferior, small aVL/aVR ratio |
| PSC Left cusp | rS | S (negative) | ≥V3 | Large aVL/aVR ratio, tall inferior R |
| Pulmonary artery | rS | — | ≥V3 | Tallest inferior R, greatest aVL/aVR ratio |
| Parahisian | QS | R (large) | >V3 | Narrow LBBB, R in I/aVL, II > III voltage |

#### LVOT Sites
| Site | V1 | Lead I | Transition | Other |
|------|----|--------|------------|-------|
| RCAS | rS, RS | R | ≤V3 | Early transition; broad R in V2 |
| LCAS/RCAS junction | qrS | R/Rsr' | V3 | QS notch in V1 downstroke |
| LCAS | rS, RS (M or W) | rS | ≤V2 | Multiphasic M or W in V1; R >50% QRS duration + R/S >30% |
| AMC | qR | R/Rs | Positive concordance | RBBB; no S wave in V6 |
| Anterolateral MA | R | rS | Early | RBBB + right inferior axis; late notching inferior |
| LV summit (accessible) | rS/QS | rS | Early | V2 pattern break; pseudodelta; RBBB at proximal GCV |
| LV summit (inaccessible) | — | negative | V2–V3 | LBBB, left superior axis, more negative aVL > aVR |
| Crux | Variable | Rs | Early | RBBB, left superior axis, positive concordance V2–V6 |

([[sources/RVOT-LVOT-circ-ep-2019]]; [[sources/PVC-ablation-jaccep-2024]])

### Step 3: ECG Prediction Algorithms (RVOT vs LVOT)

Algorithms apply when LBBB/inferior axis is confirmed. Most discriminate by precordial R-wave duration and amplitude (RVOT foci are anterior/closer to V1–V2 → smaller, shorter R waves; LVOT aortic sinus foci are central/posterior → larger, longer R waves).
![](/raw/assets/RVOT-LVOT-CircEP-2019.pdf-10-0.png)
#### Standard Lead Algorithms

| Algorithm | Formula / Cutoff | Predicts LVOT if | Sensitivity | Specificity |
|-----------|-----------------|-----------------|-------------|-------------|
| Earliest QRS onset in V2 (Yang) | V2 has earliest onset or peak/nadir | NOT V2 earliest → LVOT | 92% (RVOT) | 88% (RVOT) |
| R-wave duration index + R/S amplitude (Ouyang/Ito) | RDI = R-wave/QRS in V1 or V2; R/S = R/S amplitude in V1 or V2 | RDI ≥0.5 OR R/S ≥0.3 | 88% | 95% |
| V3 transition: R-deflection + V1 R amplitude (Cheng) | V3 R-deflection interval >80 ms AND V1 R amplitude >0.3 mV | Both criteria met | 100% | 83% |
| V2 transition ratio (Betensky) | R/QRS(PVC in V2) ÷ R/QRS(SR in V2); ≥0.6 | ≥0.6 | 95% | 100% |
| TZ index (Yoshida) | TZ score(PVC) − TZ score(SR) | <0 | 88% | 82% |
| V2S/V3R index (Yoshida) | V2 S-amplitude ÷ V3 R-amplitude | ≤1.5 | 89% | 94% |
| **Combined TZ + V2S/V3R (He)** | **Y = −1.15×(TZ) − 0.494×(V2S/V3R)** | **Y ≥ −0.76** | **90%** | **87%** |
| V1−V2 S-R difference (Kaypakli) | (V1S + V2S) − (V1R + V2R) | <1.625 (RVOT if >1.625) | 95% (RVOT) | 85% (RVOT) |

**Best overall algorithm:** Combined TZ + V2S/V3R (He et al., n=695, Youden index 0.77) ([[sources/RVOT-LVOT-circ-ep-2019]])
**Best for V3 transition:** V2S/V3R index (sensitivity 94% in V3 subgroup) ([[sources/RVOT-LVOT-circ-ep-2019]])

#### Alternative ECG Configuration Algorithms

| Algorithm | Modification | Cutoff | Accuracy |
|-----------|-------------|--------|----------|
| Synthesized right leads (Nakano) | Virtual Syn-V3R, V4R, V5R | R>S in all syn-leads → LVOT | Sens/spec 100% for LVOT vs RVOT FW |
| V5R morphology (pacemapping study) | V5R lead | Rs or rS pattern → RVOT | Sens 87%, spec 91% |
| V4/V8 index | V8 = posterior lead (left of spine); V4/V8(PVC) ÷ V4/V8(SR) | >2.28 → LVOT | Spec 98%, PPV 89%; best for V3 transition |
| **V3R/V7 index (Cheng)** | **V3R (right) + V7 (posterior)** | **≥0.85 → LVOT** | **AUC 0.95; sens 87%, spec 96%; prospective accuracy 98.6%** |

**Best novel algorithm:** V3R/V7 index (highest AUC of all published algorithms; superior in cardiac rotation and V3 transition) ([[sources/RVOT-LVOT-circ-ep-2019]])

### RVOT Sub-localization: Septal vs Free Wall
- QRS ≥140 ms + R-wave notching in ≥2 inferior leads → free wall (sens 74%, spec 93%) (Joshi)
- After confirming transition >V4 and RVOT origin by RDI/R/S: PVC QRS ÷ sinus QRS ≥1.9 → free wall (Zhang; free wall accuracy 92%)
- Lead I negative/isoelectric → anterior; positive → posterior
- aVL isoelectric/positive → caudal (>2 cm from pulmonary valve)

### LV Summit: Accessible vs Inaccessible Zone
- Accessible (ablatable via GCV/AIV): RBBB pattern (TZ <V1) + aVL/aVR amplitude ratio >1.1 + S wave in V5 or V6 (Yamada; sens 87%, spec 100%)
- Inaccessible zone: LBBB, left superior axis, V2–V3 transition, more negative aVL > aVR

### Proposed Stepwise Localization Algorithm
1. **V1 + inferior leads**: RBBB → AMC or anterolateral MA; LBBB/inferior axis → proceed
2. **Apply RVOT vs LVOT algorithm** (combined TZ+V2S/V3R, or V3R/V7 if available)
3. **Apply site-specific morphological signatures** (Table 1/2 features)
4. **Sub-localize within RVOT** (septal vs free wall; proximal vs distal)
5. **Sub-localize LV summit** (accessible vs inaccessible) if epicardial origin suspected
![](/raw/assets/RVOT-LVOT-CircEP-2019.pdf-10-1.png)
### Key Pitfalls
- **Preferential conduction** (~25% of aortic sinus OTVAs): earliest activation at RVOT breakout despite LVOT origin; pacemap at RVOT excellent but ablation fails; earliest near-field signal at adjacent LVOT is the true target ([[sources/RVOT-LVOT-circ-ep-2019]])
- **V3 transition** (38% of cases): most ECG algorithms least accurate here; V2S/V3R, V4/V8, V3R/V7 preferred
- **Cardiac rotation**: counter-clockwise (37%), clockwise (13%) — shifts precordial transition; algorithms correcting for SR transition (V2 transition ratio, TZ index) are more robust
- **Exit site shift after initial RF** (~4%): new ECG morphology → ablate new earliest site (88% success)
- **Pacemapping spatial resolution** ~1.8 cm² (inferior to activation mapping 1.2 cm²); far-field capture is a real concern at distal posterior RVOT near LVOT

![](/raw/assets/RVOT-LVOT-CircEP-2019.pdf-3-0.png)
## Contradictions / Open Questions
- No direct head-to-head prospective comparison of all 18 algorithms in a single population; predictive values across studies not directly comparable ([[sources/RVOT-LVOT-circ-ep-2019]])
- V3R/V7 index has highest AUC (0.95) in the Cheng study but has not been compared head-to-head with the combined TZ+V2S/V3R formula prospectively ([[sources/RVOT-LVOT-circ-ep-2019]])
- More accurate algorithms (Zhang, Ito) are more computationally complex and harder to apply at bedside; simpler algorithms (Dixit, Joshi) are easier but less accurate — optimal balance unresolved ([[sources/RVOT-LVOT-circ-ep-2019]])
- Role of shared myocardial connections between left and right OTs: 25% of aortic sinus OTVAs breakout at RVOT; whether routinely mapping both OTs improves outcomes is not established ([[sources/RVOT-LVOT-circ-ep-2019]])
- The RCAS/RCAS-LVOT continuum shows no overlap in Ito et al.'s ratio cutoffs despite close anatomy — possibly due to the ventriculo-infundibular fold creating a true tissue barrier; not confirmed histologically ([[sources/RVOT-LVOT-circ-ep-2019]])

## Connections
- Related to [[concepts/PVC-Mapping-Ablation]] — ablation strategy; site-specific approaches
- Related to [[concepts/PVC-Induced-Cardiomyopathy]] — non-RVOT sites at higher risk
- Related to [[concepts/Fascicular-Ventricular-Tachycardia]] — parahisian region differential
- Related to [[concepts/VT-Ablation-Ischemic-Cardiomyopathy]] — structural vs idiopathic VT distinction
- Related to [[concepts/Sudden-Cardiac-Death]] — OTVAs generally benign but non-RVOT sites have greater coupling interval variability

## Sources
- [[sources/RVOT-LVOT-circ-ep-2019]]
- [[sources/PVC-ablation-jaccep-2024]]
