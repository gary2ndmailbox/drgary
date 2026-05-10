---
dg-publish: true
title: "Circadian Rhythm and Cardiac Electrophysiology"
tags: [circadian-rhythm, sudden-cardiac-death, cardiac-electrophysiology, ion-channels, arrhythmia-mechanisms]
source_count: 1
last_updated: 2026-05-01
---

# Circadian Rhythm and Cardiac Electrophysiology

## Definition
The 24-hour circadian system regulates cardiac electrophysiology through two parallel mechanisms: (1) extrinsic regulation via the suprachiasmatic nucleus (SCN) and autonomic nervous system, which drives day-night rhythms in heart rate, QT interval, and arrhythmogenic triggers; and (2) intrinsic regulation via the BMAL1/CLOCK molecular clock in cardiomyocytes, which directly controls transcription of key ion channel genes. Together, these create time-of-day variation in the "protective properties of the myocardial substrate" — the structural and electrophysiological properties that resist triggered arrhythmias and re-entry. ([[sources/circadian-scd-jmcc-2025]], rating: high)

---

## Key Concepts

### Circadian vs. Day-Night Rhythms
- True **circadian** rhythms are those that persist under constant conditions (darkness, D:D); they reflect intrinsic ~24-h oscillators. **Day-night rhythms** measured under normal conditions (L:D, with environmental cues, behavior, and meals) include both circadian and non-circadian (masked) contributions. ([[sources/circadian-scd-jmcc-2025]], rating: high)
- Masking refers to direct physiological responses to environmental cues that can override intrinsic circadian timing — e.g., feeding acutely alters metabolic and cardiovascular parameters independent of clock phase. Genes rhythmic under L:D but not D:D (e.g., Kcna5, Kcnb1, Kcnk2) are likely driven by masking, not the clock. ([[sources/circadian-scd-jmcc-2025]], rating: high)

### Trigger-Substrate Model for Circadian SCA Risk
- Sudden cardiac arrest (SCA) risk depends on the interaction between **arrhythmogenic triggers** (sympathetic surges, catecholamines, elevated heart rate, afterload, platelet aggregation) and the **protective properties of the myocardial substrate** (conduction velocity, refractory periods, coupling efficiency, repolarization homogeneity).
- The historical morning SCA peak corresponded to morning peaks in both triggers and substrate vulnerability. Contemporary data (Oregon SUDS, SCD-HeFT) no longer confirm a morning SCA peak — likely attributable to widespread beta-blocker use blunting morning sympathetic surges, lifestyle changes (shift work, irregular sleep), and improved CVD risk factor management. ([[sources/circadian-scd-jmcc-2025]], rating: high)
- **Overall daytime SCA incidence persists** regardless of age, sex, and CAD status — reflecting the persistent daytime elevation of arrhythmogenic triggers even when the morning substrate peak has been attenuated. ([[sources/circadian-scd-jmcc-2025]], rating: high)
- Disease can alter the day-night rhythm in substrate protection: (1) reduced amplitude, (2) reduced average level, or (3) adverse phase shift (substrate vulnerability coincides with peak trigger frequency). ([[sources/circadian-scd-jmcc-2025]], rating: high)

### Extrinsic Regulation (SCN and ANS)
- The SCN, entrained to light via the retinohypothalamic tract, orchestrates neurohumoral rhythms (autonomic tone, cortisol, catecholamines, melatonin) that drive day-night cardiovascular rhythms. SCN lesion disrupts day-night rhythms in activity, heart rate, and QT intervals in rodents. ([[sources/circadian-scd-jmcc-2025]], rating: high)
- **RR interval:** Primarily driven by ANS; heart transplant recipients with denervated hearts show very low amplitude (5–10 bpm) day-night HR rhythm vs. 20–25 bpm in reinnervated transplants. Residual amplitude reflects body temperature, catecholamines, and extracellular K⁺ rhythms, plus possible residual intrinsic clock function. ([[sources/circadian-scd-jmcc-2025]], rating: high)
- **QT/QTc interval:** Closely tracks heart rate day-night rhythm; also influenced by body temperature oscillations. A morning QTc spike was historically documented shortly after waking — its persistence in contemporary populations is uncertain and under investigation. ([[sources/circadian-scd-jmcc-2025]], rating: high)
- **Cardiac clock entrainment depends on sympathetic stimulation:** Sympathetic denervation (e.g., transplanted heart) disrupts both extrinsic ANS regulation and intrinsic clock synchronization, explaining the marked reduction in day-night cardiovascular rhythms after transplant. ([[sources/circadian-scd-jmcc-2025]], rating: high)

### Intrinsic Cardiac Circadian Clock
- The molecular clock operates in virtually all cells including cardiomyocytes; it involves the BMAL1/CLOCK heterodimer (positive limb) → transcriptional activation of Per/Cry genes; PER/CRY proteins accumulate and feed back to inhibit BMAL1/CLOCK (negative limb). An auxiliary loop: BMAL1/CLOCK targets REV-ERBα (Nr1d1), which represses Bmal1 via RORE elements; ROR transcription factors compete with REV-ERBα to activate Bmal1. ([[sources/circadian-scd-jmcc-2025]], rating: high)
- **Ex vivo isolated heart studies** (constant temperature, 1 hour post-perfusion to wash out ANS residual): time-of-day differences in APD, effective refractory period (ERP), Ca²⁺ transient duration, and adrenergic responsiveness persist — confirming intrinsic cardiac clock function. ([[sources/circadian-scd-jmcc-2025]], rating: high)
- At the **start of the dark (active) cycle**: shorter APD and ERP, reduced adrenergic responsiveness, greater arrhythmia resistance — a time-of-day peak in myocardial substrate protection coinciding with peak activity. ([[sources/circadian-scd-jmcc-2025]], rating: high)
- **Bmal1 cardiomyocyte-specific knockout** prolongs RR and QT intervals, decreases steady-state ion channel mRNA levels, reduces depolarizing (INa, If) and repolarizing (IKr) currents, alters pacemaking, and abolishes time-of-day differences in cardiac electrophysiology. ([[sources/circadian-scd-jmcc-2025]], rating: high)
- **Aging reduces circadian amplitude:** Aged mice (18–20 months) lose the time-of-day peak in arrhythmia resistance seen in young mice; middle-aged women show attenuated HR day-night rhythms in some human studies. ([[sources/circadian-scd-jmcc-2025]], rating: high)
- **Forced desynchrony in humans** (20-h day protocol): 24-h heart rate rhythms persist when disconnected from external cues — strong evidence for intrinsic circadian control of cardiac function in humans. ([[sources/circadian-scd-jmcc-2025]], rating: high)

### Most Robust Rhythmically Expressed Genes (REGs) in the Heart
Genes are ranked by consistency across four databases (CircaDB D:D/L:D; CircaAge young/aged/old; CircaMET DRF/NRF; GEO GSE262714 male/female Bmal1 KO vs. control):

| Gene | Protein | Function | Key REG Evidence |
|---|---|---|---|
| **Kcnh2** | Kv11.1/IKr | Ventricular repolarization | D:D p=2.4e-7; all CircaAge (weakens in Old); both sexes GEO; both feeding schedules |
| **Gja1** | Cx43 | Gap junction/conduction | D:D p=3.2e-5; all CircaAge ages; both sexes GEO; BMAL1-dependent (abolished in KO) |
| **Scn5a** | Nav1.5 | AP upstroke | D:D p=5.0e-3 only; female WT GEO p=1.6e-4; male not rhythmic |
| **Hcn4** | HCN4/If | Pacemaker | D:D p=9.2e-3 |
| **Pkp2** | Plakophilin-2 | Desmosomal adhesion | D:D p=3.0e-3; L:D; DRF; NRF; both sexes GEO; BMAL1-dependent |
| **Dsc2** | Desmocollin-2 | Desmosomal adhesion | D:D p=4.4e-4; young CircaAge; NRF; female WT GEO |
| **Dsg2** | Desmoglein-2 | Desmosomal adhesion | Young and old CircaAge; NRF; female WT GEO |
| **Arntl1** (Bmal1) | BMAL1 | Core clock | All databases, all conditions |
| **Clock** | CLOCK | Core clock | All databases, all conditions |
| **Per2** | PER2 | Negative limb | All databases, all conditions |
| **Cry2** | CRY2 | Negative limb | All databases, all conditions |
| **Nr1d1** | REV-ERBα | Auxiliary loop | All databases, all conditions |

([[sources/circadian-scd-jmcc-2025]], rating: high)

- **Kcnh2 age dependence:** Rhythmicity declines with advanced age (Young p=1.5e-3, Aged p=1.0e-4, Old p=0.056 [not significant]). ([[sources/circadian-scd-jmcc-2025]], rating: high)
- **Sex differences in rhythmicity:** Kcnh2 rhythmic in both sexes but stronger in females (p=1.4e-8 vs. p=1.81e-3); Kcna4 and Kcnk2 rhythmic in females only; Kcnj3 rhythmic in males only; some sex differences are BMAL1-independent. ([[sources/circadian-scd-jmcc-2025]], rating: high)
- **ARVC-linked structural genes as cardiac REGs:** Pkp2, Dsg2, Dsc2 (core desmosomal proteins mutated in ARVC) are among the most robust circadian REGs in the heart across multiple databases. Circadian variation in desmosomal protein levels may represent an unexplored mechanism of time-of-day arrhythmia risk in ARVC. See [[entities/ARVC]]. ([[sources/circadian-scd-jmcc-2025]], rating: high)

### Direct Clock Regulation of Ion Channel Transcription
- **BMAL1/CLOCK directly transactivate Kcnh2, Scn5a, and Hcn4** via E-box elements in their promoters (confirmed by luciferase reporter assays for Kcnh2 and Scn5a). ([[sources/circadian-scd-jmcc-2025]], rating: high)
- Bmal1 KO in cardiomyocytes reduces Kv11.1 current (IKr), Nav1.5 current (INa), and HCN4 current (If) — linking transcriptional rhythmicity to functional ionic rhythm. ([[sources/circadian-scd-jmcc-2025]], rating: high)

### Indirect Clock Regulation (Transcriptional Intermediaries)
- **KLF15 pathway:** BMAL1/CLOCK → circadian expression of KLF15 (Krüppel-like factor 15) → KLF15 protein drives Kcnip2 expression → KChIP2 modulates Kv4.2 (Ito) → influences cardiac repolarization. First demonstrated by Jeyaraj et al. (2012). ([[sources/circadian-scd-jmcc-2025]], rating: high)
- **E4BP4:** Additional clock-controlled repressor transcription factor that provides a second regulatory layer for Kcnip2 — demonstrating multi-pathway indirect clock-to-channel regulation. ([[sources/circadian-scd-jmcc-2025]], rating: high)
- **Tbx5 and Gata4** exhibit circadian expression patterns in the heart; as critical cardiac transcription factors, their rhythmic regulation has broad potential effects on myocardial substrate properties. ([[sources/circadian-scd-jmcc-2025]], rating: high)
- **miRNA:** Bmal1 KO → ~70% upregulation of differentially expressed miRNAs; REV-ERBα/β double KO increases cardiomyocyte miRNAs; clock-driven miRNAs regulate Gja1 (Cx43) and Kcnj2 (Kir2.1) post-transcriptionally. ([[sources/circadian-scd-jmcc-2025]], rating: high)
- **Steroid hormones:** Sex hormones (oestrogen, testosterone) regulate K⁺ channel expression (IKr, IKs) through genomic and non-genomic pathways; glucocorticoids modulate ion channels via GR; steroid hormone receptors may be circadianly regulated, adding a temporal layer to hormone-mediated channel regulation. ([[sources/circadian-scd-jmcc-2025]], rating: high)

### mRNA-to-Protein Translation: The Half-Life Problem
- Rhythmic mRNA does not reliably produce rhythmic protein; protein amplitude is generally much smaller than mRNA amplitude due to protein stability. Only proteins with short half-lives (t½ ≤6 h) show meaningful protein oscillation; proteins with longer half-lives buffer mRNA oscillations. ([[sources/circadian-scd-jmcc-2025]], rating: high)
- **Kv11.1 (KCNH2):** Wild-type t½ ≈ 12 h → blunted protein rhythm under normal conditions despite robust Kcnh2 mRNA oscillation. Decreased mRNA oscillation amplitude (e.g., in aging or disease) → reduced steady-state protein → less IKr → longer APD. ([[sources/circadian-scd-jmcc-2025]], rating: high)
- **LQT2 mechanism:** KCNH2 mutations shortening Kv11.1 t½ to <6 h produce two simultaneous effects: (1) lower median steady-state Kv11.1 protein → less IKr → longer APD baseline; and (2) larger protein amplitude oscillation → larger time-of-day APD swing → arrhythmias at predictable times of day. This may explain why some LQT2 patients have time-of-day clustering of arrhythmic events. See [[entities/Long-QT-Syndrome]]. ([[sources/circadian-scd-jmcc-2025]], rating: high)
- The rhythmic proteome in cardiac tissue is primarily regulated at translational and posttranslational levels — meaning only a subset of transcriptional REGs will produce functionally rhythmic proteins. ([[sources/circadian-scd-jmcc-2025]], rating: high)

---

## Contradictions / Open Questions
- **Loss of morning SCA peak — mechanism uncertain:** Multiple mechanisms are proposed (beta-blockers, lifestyle changes, improved risk factor management) but the causal attribution is poorly established. Contemporary SCA registries show diverse circadian patterns without a consistent morning peak in many populations; whether this reflects a true population-level shift or sampling and ascertainment differences is unresolved. ([[sources/circadian-scd-jmcc-2025]], rating: high)
- **Intrinsic cardiac clock vs. extrinsic ANS in transplanted hearts:** The residual amplitude in denervated transplanted hearts reflects body temperature, catecholamines, extracellular K⁺ cycling, AND the status of the intrinsic cardiac clock. Cardiac clock entrainment depends on sympathetic stimulation; transplanted hearts may have disrupted intrinsic clock function. The relative contribution of these mechanisms to residual rhythmicity is not established. ([[sources/circadian-scd-jmcc-2025]], rating: high)
- **mRNA oscillation amplitude → functional protein oscillation → physiological consequence:** This causal chain is largely assumed rather than directly demonstrated for most cardiac ion channels. Direct proteomic measurement of circadian protein oscillations for cardiac ion channels in humans is essentially absent. ([[sources/circadian-scd-jmcc-2025]], rating: high)
- **Aging reduces circadian amplitude — mechanism and clinical implication:** Aged mice lose the time-of-day arrhythmia protection peak; Kcnh2 loses rhythmicity in old mice. Whether this translates to higher time-of-day-independent arrhythmia risk in elderly humans remains unproven. ([[sources/circadian-scd-jmcc-2025]], rating: high)
- **No clinical translation yet:** All insights remain mechanistic or epidemiological. No RCT has demonstrated SCD reduction by optimizing drug timing (chronotherapy) based on circadian principles in cardiac patients. The review explicitly notes this as a future direction. ([[sources/circadian-scd-jmcc-2025]], rating: high)

---

## Bioinformatic Resources
- **CircaDB** (http://circadb.org): Multiple tissues and organisms; D:D and L:D datasets; 2–4h resolution; interactive threshold filtering
- **CircaAge** (https://circaage.shinyapps.io/circaage/): D:D male mouse; Young/Aged/Old comparison; age-related shifts in circadian amplitude and phase
- **CircaMET** (http://www.circametdb.org.cn): L:D female mouse heart; DRF vs. NRF metabolic-circadian interaction
- **GEO GSE262714**: D:D sex-specific (male/female) data in cardiomyocyte-specific Bmal1 KO vs. control

---

## Connections
- Related to [[concepts/Sudden-Cardiac-Death]] — circadian distribution of SCA/SCD and trigger-substrate framework
- Related to [[concepts/Cardiac-Action-Potential]] — circadian modulation of APD, IKr, INa, If
- Related to [[entities/Long-QT-Syndrome]] — LQT2/KCNH2 protein half-life and time-of-day APD amplification
- Related to [[entities/ARVC]] — Pkp2/Dsg2/Dsc2 as robust circadian REGs in the heart
- Related to [[entities/Atrial-Fibrillation]] — Gja1/Cx43 as BMAL1-dependent circadian REG relevant to AF substrate
- Related to [[concepts/Electrical-Remodeling]] — clock-driven transcriptional remodeling of ion channel expression
- Related to [[concepts/OSA-Arrhythmogenic-Substrate]] — circadian clock disruption by OSA; shared pathway with SCA risk
- Related to [[sources/circadian-scd-jmcc-2025]]

## Sources
- [[sources/circadian-scd-jmcc-2025]]
