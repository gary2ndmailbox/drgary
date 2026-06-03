---
dg-publish: true
title: "Fascicular Ventricular Tachycardia"
tags: [fascicular-ventricular-tachycardia, ventricular-arrhythmias, electrocardiography, idiopathic-VT, verapamil-sensitive]
source_count: 1
last_updated: 2026-05-21
---

# Fascicular Ventricular Tachycardia

## Definition
Fascicular ventricular tachycardia (FVT) is idiopathic VT originating from or near the left fascicular (Purkinje) network in structurally normal hearts. It is the most common form of idiopathic left VT. The defining clinical features are: (1) RBBB-pattern QRS with left or right axis deviation; (2) termination by IV verapamil (calcium channel blocker sensitivity); (3) inducibility on EP study; (4) absence of structural heart disease. Because activation exits through the Purkinje system, initial ventricular activation is FAST — the opposite of myocardial VT — causing all standard wide-complex tachycardia algorithms to misclassify FVT as SVT with aberrancy.

## Key Concepts

### Subtypes
Three recognised subtypes based on fascicular exit site:
1. **Left posterior fascicular VT (LPF-VT)** — most common (~80%): RBBB morphology + left-axis deviation (superior axis, typically −70° to −100°); exits from left posterior fascicle or adjacent Purkinje network
2. **Left anterior fascicular VT (LAF-VT)** — ~15%: RBBB morphology + right-axis deviation; exits from left anterior fascicle
3. **Upper septal (interfascicular) VT** — rare (~5%): narrow QRS with normal axis; circuit involves upper septal Purkinje network

### Mechanism
- **Macroreentry within the Purkinje network**: the circuit involves a slow-conduction zone (verapamil-sensitive calcium-channel-dependent tissue) and a fast-conduction retrograde limb via the posterior or anterior fascicle
- Verapamil sensitivity: the slow zone of the circuit is calcium-channel-dependent; IV verapamil terminates LPF-VT by blocking slow conduction in this zone
- Because the VT exits directly through the left Purkinje fascicle, the **initial ventricular activation is rapid** (Purkinje-mediated, not muscle-to-muscle) — this is the physiological basis for all algorithm failures

### Why Standard WCT Algorithms Fail for LPF-VT
All mainstream WCT algorithms assume VT involves slow initial myocardial activation. LPF-VT violates this assumption ([[sources/lpfvt-svt-circep-2017]] — high):

| Criterion | Assumes in VT | LPF-VT Reality | Consequence |
|---|---|---|---|
| RS interval >100 ms (Brugada Step 2; [[sources/vt-brugada-circ-1991]]) | Slow muscle-to-muscle spread | <80 ms (median 62 ms; Purkinje exit) | Classified as SVT |
| Vi/Vt ≤1 (Vereckei Step 4; [[sources/vt-vereckei-ehj-2007]]) | Slow initial / fast terminal | Vi/Vt >1 (fast initial Purkinje) | Classified as SVT |
| Initial R in aVR (Vereckei Step 2) | Initial slow superior force → R wave | Narrow q precedes R (qR complex; q <40 ms) | Criterion not triggered |
| QRS >140 ms (Wellens) | Wide due to myocardial spread | Mean 127.5 ms; most <140 ms | Wrong direction |
| Absence of BBB/fascicular morphology (Vereckei Step 3) | VT has atypical morphology | LPF-VT has fascicular-block morphology | Classified as SVT at Step 3 |
| OQL pattern (Chen LLA Criterion 3; [[sources/vt-chen-hrs-2019]]) | VT produces concordant vertical frontal vector | LPF-VT inferior leads discordant (biphasic) — no OQL | LLA Criterion 3 not met; Criteria 1/2 also typically absent |

### Clinical Context — LPF-VT vs SVT with RBBB+LAHB
The closest ECG mimic is SVT with RBBB + left anterior hemiblock (LAHB) aberrancy. Standard criteria that distinguish structural VT from SVT do NOT reliably distinguish LPF-VT from RBBB+LAHB SVT ([[sources/lpfvt-svt-circep-2017]] — high).

**Key distinguishing features (Michowitz 2017, multivariate model; n=183 LPF-VT vs 61 RBBB+LAHB):**

| Criterion | LPF-VT | RBBB+LAHB | OR | Notes |
|---|---|---|---|---|
| Atypical V1 morphology (R′ NOT > R) | 45.8% | 8.2% | 5.1 | 54% of LPF-VT have TYPICAL V1 — cannot use typical V1 to exclude VT |
| Positive QRS in aVR (R>S or R>Q) | 94.2% | 50.8% | 19.2 | qR pattern common in LPF-VT; narrow q <40 ms → Vereckei "initial R" NOT triggered |
| V6 R/S ratio ≤1 | 88.3% | 59% | 6.7 | Overlap large; R/S <0.15 in V6 = seen ONLY in LPF-VT (21.9%) |
| QRS ≤140 ms | most | minority | 7.7 | RBBB+LAHB is WIDER than LPF-VT — Wellens criterion inverted |

**Practical counting rule:**
- **0–1 positive criteria → RBBB+LAHB aberrancy** (virtually excludes LPF-VT)
- **2 criteria → probable LPF-VT**
- **≥3 criteria → high probability LPF-VT**
- Model Sn 82.1%, Sp 78.3%, AUC 0.889

**Single discriminators (seen ONLY in LPF-VT):**
- QRS <120 ms (31% of LPF-VT)
- QRS axis <−100° (16.7% of LPF-VT)
- V6 R/S ratio <0.15 (21.9% of LPF-VT)

**Precordial RS time is NOT discriminating**: median 62 ms (LPF-VT) vs 70 ms (RBBB+LAHB), P=0.4 — both groups fall below any clinically useful threshold.

### AV Dissociation and Fusion Beats
- AV dissociation is present in ~70% of LPF-VT patients when specifically sought (Andrade et al. 1996)
- When present, AV dissociation is diagnostic of VT and should always be looked for first before applying morphological criteria
- When absent (1:1 VA conduction or retrograde P concealed), and when fusion/capture beats are absent, ECG diagnosis becomes challenging — the 4-criterion model should then be applied

### Clinical Approach to RBBB+LAHB-Pattern Tachycardia (Figure 5, Michowitz 2017)
1. **AV dissociation or fusion/capture beats present?** → Yes → VT confirmed
2. **Structural heart disease?** → Yes → apply standard WCT algorithms (Brugada, Vereckei, Basel)
3. **No structural disease, RBBB+LAHB-like morphology** → apply 4-criterion model:
   - Check: (1) atypical V1; (2) positive aVR; (3) V6 R/S ≤1; (4) QRS ≤140 ms
   - ≥3 criteria: LPF-VT; ≤1 criterion: RBBB+LAHB aberrancy

### Treatment
- **Acute termination**: IV verapamil (calcium channel blocker) — terminates by blocking the slow Purkinje zone
- **Catheter ablation**: curative; success rate high; typical target is the slow conduction zone of the posterior fascicle or posterior Purkinje network
- **Caution**: IV verapamil should NOT be given to any WCT of uncertain origin — risk of haemodynamic collapse if the diagnosis is wrong and the underlying rhythm is structural VT or pre-excited AF

### LPF-VT vs Posterior Papillary Muscle VT
- PPM-VT: NOT verapamil-sensitive; focal mechanism; QRS >160 ms (rarely seen in LPF-VT); variable spontaneous morphologies
- Overlap in R/S <1 in lead I (33.5% of LPF-VT)
- Most reliable single distinguisher of PPM-VT: QRS >160 ms

## Contradictions / Open Questions
- The 4-criterion model has NOT been prospectively validated — performance in an independent cohort is unknown; internal cross-validation may overestimate real-world accuracy
- Control group in Michowitz 2017 was in sinus rhythm (older patients), not tachycardia — rate-dependent changes to RBBB+LAHB morphology during SVT may reduce specificity of the model in clinical practice
- Sex differences: women with LPF-VT have positive aVR less frequently (88% vs 99% men) — model performance may be lower in women; whether sex-specific thresholds improve accuracy is unstudied
- LAF-VT (RBBB + right axis) and upper septal FVT have not been systematically characterised against SVT with RBBB+right axis or narrow-QRS SVT respectively
- The relationship between LPF-VT and posterior papillary muscle VT remains incompletely defined — ECG overlap is significant and mechanistic boundary is unclear

## Connections
- Related to [[concepts/Wide-Complex-Tachycardia]] — LPF-VT is the most clinically important blind spot of all standard WCT algorithms
- Related to [[concepts/Bidirectional-Ventricular-Tachycardia]] — separate entity; bifascicular VT (alternating fascicular origin) seen in digitalis toxicity and Andersen-Tawil syndrome
- Related to [[concepts/ECG-Conduction-Disturbances]] — RBBB and LAHB morphological criteria

## Sources
- [[sources/lpfvt-svt-circep-2017]] — Michowitz/Belhassen et al. 2017 Circ EP; first systematic ECG characterisation of LPF-VT vs RBBB+LAHB; 4-criterion prediction model; Sn 82.1%/Sp 78.3%; confirms algorithm failures (rating: high)
