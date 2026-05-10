---
dg-publish: true
title: "AI in Cardio-Oncology"
tags: [cardio-oncology, artificial-intelligence, precision-medicine, cardiotoxicity, multi-omics]
source_count: 1
last_updated: 2026-04-25
---

# AI in Cardio-Oncology

## Definition
The application of artificial intelligence (AI) and machine learning (ML) algorithms to cardio-oncology — integrating imaging, biomarkers, multi-omics, and electronic health record data to enable personalised cardiovascular risk prediction and management in patients receiving cancer therapy. AI in this context encompasses ML-based risk prediction models, AI-enabled cardiac imaging analysis, natural language processing (NLP) for EHR data extraction, AI-driven ECG interpretation, and drug toxicity discovery tools.

## Key Concepts

### Why AI in Cardio-Oncology
- Cardiovascular risk in cancer patients is highly heterogeneous: driven by malignancy type, individual patient susceptibility, and the specific cancer treatment used. ([[sources/ai-cardiooncology-aha-2025]], rating: high)
- Novel therapies (targeted therapies, immune checkpoint inhibitors) have broadened the population at risk of cardiotoxicity and introduced complex, unpredictable risk profiles not captured by traditional risk models. ([[sources/ai-cardiooncology-aha-2025]])
- AI can triangulate multiple heterogeneous data streams (imaging, labs, genomics, clinical notes) to identify complex patterns and refine individual risk estimates beyond single-modality approaches. ([[sources/ai-cardiooncology-aha-2025]])

### Multi-Omics Biomarker Landscape

#### Genomics
- **TTNtv:** Titin-truncating variants overlap with anthracycline-induced cardiomyopathy — identified in several small cohorts. ([[sources/ai-cardiooncology-aha-2025]])
- **RARG:** Variant associated with anthracycline cardiomyopathy in multiple studies. ([[sources/ai-cardiooncology-aha-2025]])
- **CHIP** (clonal haematopoiesis of indeterminate potential): Emerging genomic risk marker. ([[sources/ai-cardiooncology-aha-2025]])
- Insufficient validation for routine clinical incorporation; unbiased genome-wide approaches limited by small cohort sizes and inconsistent cardiotoxicity definitions. ([[sources/ai-cardiooncology-aha-2025]])

#### Transcriptomics
- scRNA-seq + T-cell receptor sequencing identified pathogenic α-myosin–specific T-cell populations in ICI myocarditis tissue. ([[sources/ai-cardiooncology-aha-2025]])
- Spatial transcriptomics adds positional context to cell–cell interactions within the myocardium. ([[sources/ai-cardiooncology-aha-2025]])

#### Proteomics
- **Hemopexin:** Identified as a protein biomarker in anthracycline cardiotoxicity using SomaScan aptamer-based proteomics. ([[sources/ai-cardiooncology-aha-2025]])
- **CSK (C-terminal Src kinase):** Identified in ibrutinib-associated atrial fibrillation. ([[sources/ai-cardiooncology-aha-2025]])

#### Metabolomics
- Early changes in **tricarboxylic acid (TCA) cycle metabolites** differentiated subsequent anthracycline cardiotoxicity development before LVEF change. ([[sources/ai-cardiooncology-aha-2025]])
- Patients with cardiotoxicity showed pronounced alterations in purine and pyrimidine metabolism. ([[sources/ai-cardiooncology-aha-2025]])

### AI-Based Risk Prediction Models
- Integrative models combining cancer risk factors, CV risk factors, troponin, BNP achieved **risk discrimination in the 90% range** across multiple cohorts. ([[sources/ai-cardiooncology-aha-2025]])
- Childhood cancer survivor model: exome sequencing + clinical predictors improved LVEF-decline prediction vs. clinical predictors alone (n=289, anthracycline exposure). ([[sources/ai-cardiooncology-aha-2025]])
- Lung cancer low-dose CT model (n=30,286): predicted CVD mortality risk, outperformed existing models. ([[sources/ai-cardiooncology-aha-2025]])
- Key limitation: a 2025 systematic review of breast cancer cardiotoxicity prediction models found only 1 of 6 studies used external validation — risk of overfitting is high. ([[sources/ai-cardiooncology-aha-2025]])

### AI-Enabled Cardiac Imaging
- **Automated LVEF:** Multiple commercial AI-assisted LVEF measurement tools now available; RCT evidence supports benefit over standard measurement. ([[sources/ai-cardiooncology-aha-2025]])
- Foundation models and self-supervised learning reduce the need for large labelled training datasets — accelerating new imaging biomarker discovery. ([[sources/ai-cardiooncology-aha-2025]])
- Radiomics has potential to identify early coronary plaque, inflammatory myocardial change, and novel vascular biomarkers not visible to human experts. ([[sources/ai-cardiooncology-aha-2025]])

### AI-Enabled ECG Algorithms
- **ICI myocarditis:** Early ECG patterns from convolutional neural networks predictive of life-threatening arrhythmias and mortality (125 ICI myocarditis cases, 49 institutions, 11 countries). ([[sources/ai-cardiooncology-aha-2025]])
- **Anthracycline/trastuzumab LV dysfunction:** AI-ECG detected cancer therapeutics-related cardiac dysfunction in two studies (n=3,364 and n=889). ([[sources/ai-cardiooncology-aha-2025]])
- **AF prediction in leukemia:** ECG-based AI predicted AF risk among 754 patients on treatment. ([[sources/ai-cardiooncology-aha-2025]])
- **Drug-induced arrhythmia:** Convolutional networks quantified sotalol-induced ECG changes to predict drug-induced torsades de pointes and diagnose LQTS. ([[sources/ai-cardiooncology-aha-2025]])
- Outside cardio-oncology, AI-ECG can detect LVEF <40%, myocardial ischaemia, and AF during sinus rhythm — methods applicable to cancer populations. ([[sources/ai-cardiooncology-aha-2025]])

### NLP and Large Language Models
- NLP extracts structured data from unstructured EHR notes (erratic formats, missing elements, LVEF ranges) for cardiotoxicity surveillance. ([[sources/ai-cardiooncology-aha-2025]])
- LLMs enable smart chatbots for clinician interaction with diverse electronic data without advanced programming. ([[sources/ai-cardiooncology-aha-2025]])
- Potential to flag high-risk patients for cardio-oncology referral before initiation of cardiotoxic treatment. ([[sources/ai-cardiooncology-aha-2025]])
- No published cardio-oncology LLM implementations as of April 2025. ([[sources/ai-cardiooncology-aha-2025]])

### EHR-Based Algorithms and Registries
- Programmatic EHR rules can identify oncology patients with relevant diagnosis codes + cardiotoxic treatment records for surveillance and quality improvement. ([[sources/ai-cardiooncology-aha-2025]])
- AHA called for a national cardio-oncology database registry to consolidate multi-omic, imaging, and clinical data — must purposefully represent community hospital populations to avoid selection bias. ([[sources/ai-cardiooncology-aha-2025]])

### Ethical Considerations
- **Algorithmic bias:** AI trained on biased datasets (historically lower health care use in underrepresented groups) can underestimate cardiac risk in those groups. ([[sources/ai-cardiooncology-aha-2025]])
- **Data privacy:** Google Project Nightingale and Royal Free/DeepMind incidents illustrate risks of large-scale patient data use without adequate consent. ([[sources/ai-cardiooncology-aha-2025]])
- **Health equity:** Multi-omics datasets predominantly from populations of European ancestry; AI models trained on these may not generalise to diverse populations. ([[sources/ai-cardiooncology-aha-2025]])
- **Equitable access:** Rural counties with limited broadband access experience poorer CV outcomes; AI-driven precision care risks widening this gap without deliberate policy interventions. ([[sources/ai-cardiooncology-aha-2025]])

## Contradictions / Open Questions
- No AI risk prediction tools have been validated prospectively in clinical trials — all current models are proof-of-concept. ([[sources/ai-cardiooncology-aha-2025]])
- Cardiotoxicity definitions are inconsistent across studies, creating a moving target for AI algorithm development and cross-study comparison. ([[sources/ai-cardiooncology-aha-2025]])
- Biomarker-guided cardioprotection (troponin-guided enalapril; hsTnI-guided candesartan/carvedilol) did not outperform universal cardioprotection strategies in RCTs — AI-enhanced biomarker integration has not yet been tested clinically. ([[sources/ai-cardiooncology-aha-2025]])
- Multi-omics biomarkers (genomics, transcriptomics, proteomics, metabolomics) remain at pilot stage; large prospective cohorts with serial sampling are lacking. ([[sources/ai-cardiooncology-aha-2025]])
- The lack of a national cardio-oncology registry is a major obstacle to training representative AI models. ([[sources/ai-cardiooncology-aha-2025]])

## Connections
- Related to [[concepts/Cardio-Oncology]]
- Related to [[concepts/Cancer-Therapy-Related-CV-Toxicity]]
- Related to [[concepts/HFA-ICOS-Risk-Stratification]]
- Related to [[concepts/Late-Gadolinium-Enhancement]]
- Related to [[concepts/Drug-Induced-Arrhythmia]]
- Related to [[concepts/Torsades-de-Pointes]]
- Related to [[entities/Atrial-Fibrillation]]
- Related to [[entities/Heart-Failure]]
- Related to [[entities/DCM]]
- Related to [[sources/ai-cardiooncology-aha-2025]]

## Sources
- [[sources/ai-cardiooncology-aha-2025]]
