---
dg-publish: true
title: "Artificial Intelligence to Enhance Precision Medicine in Cardio-Oncology: A Scientific Statement From the American Heart Association"
date_ingested: 2026-04-25
source_type: consensus
Citation: "Khera R, Asnani AH, Krive J, Addison D, Zhu H, Vasbinder A, Fleming MR, Arnaout R, Razavi P, Okwuosa TM; on behalf of the American Heart Association Cardio-Oncology and Data Science and Precision Medicine Committees. Artificial intelligence to enhance precision medicine in cardio-oncology: a scientific statement from the American Heart Association. Circ Genom Precis Med. 2025;18:e000097."
DOI: "https://doi.org/10.1161/HCG.0000000000000097"
tags: [cardio-oncology, artificial-intelligence, precision-medicine, cardiotoxicity, multi-omics]
rating: high
raw_path: raw/AI-Cardio-Oncology-AHA-2025.md
---

# Artificial Intelligence to Enhance Precision Medicine in Cardio-Oncology

## Authors, Journal, Affiliations, Type, DOI
- **Authors:** Rohan Khera, Aarti H. Asnani, Jacob Krive, Daniel Addison, Han Zhu, Alexi Vasbinder, Matthew R. Fleming, Rima Arnaout, Pedram Razavi, Tochukwu M. Okwuosa; on behalf of AHA Cardio-Oncology and Data Science and Precision Medicine Committees
- **Journal:** Circulation: Genomic and Precision Medicine
- **Type:** AHA Scientific Statement
- **Date:** April 2025
- **DOI:** 10.1161/HCG.0000000000000097

## Overview
This 2025 AHA Scientific Statement provides a comprehensive framework for applying AI and machine learning to precision medicine in cardio-oncology. It surveys the full biomarker landscape — advanced imaging (echo, CMR, cardiac CT, nuclear), traditional biomarkers (troponins, BNP), and multi-omics (genomics, transcriptomics, proteomics, metabolomics) — describing how AI can integrate these data streams into individualized cardiotoxicity risk prediction and management. Key practical AI applications covered include automated LVEF measurement, ECG-based cardiotoxicity detection algorithms, and NLP for EHR data extraction. The statement calls for a national cardio-oncology registry and flags critical ethical challenges including algorithmic bias, health equity, and data privacy.

## Keywords
Artificial intelligence, cardio-oncology, machine learning, precision medicine, cardiotoxicity, multi-omics, biomarkers

## Key Takeaways

### Advanced Imaging in Cardio-Oncology
- Core imaging modalities: echocardiography (LVEF, GLS, diastolic function, valve), CMR (T1/T2 mapping, LGE, ECV), coronary CT (CAC, CCTA, CT-FFR), nuclear imaging (myocardial perfusion, Tc-99m PYP).
- **ICI myocarditis — CMR:** Native T1 elevation was highly predictive of future MACE in 136 patients with suspected ICI myocarditis; LGE and T2-weighted STIR are also diagnostic.
- **SUCCOUR trial:** GLS-guided cardioprotection was equivocal for predicting future HF events in anthracycline/HER2-targeted therapy patients — GLS did not outperform standard care.
- **Ibrutinib cardiotoxicity:** Abnormal LA strain/size by echo and elevated native T1/T2 by CMR were highly predictive of future MACE and adverse events in patients with haematologic malignancy on ibrutinib.
- **AI-based CAC scoring:** Deep learning algorithm for CAC from chest radiotherapy images predicted future acute coronary events.
- **CCTA:** Captures increased rates of CAD requiring intervention after chest radiotherapy and chemotherapy.

### Traditional Biomarkers (Troponins, BNP)
- Cardiac troponins and BNP have been evaluated for predicting CTRCD; evidence is inconsistent in more recent studies using high-sensitivity assays in early-stage breast cancer patients.
- **High negative predictive value (84–100%):** Most useful to rule out cardiotoxicity; no established cancer-specific cut points.
- **Biomarker-guided cardioprotection:** Serial troponin to guide enalapril initiation showed no benefit over universal enalapril (RCT, n=276, limited by small size and low anthracycline dose). Candesartan/carvedilol guided by hsTnI also did not prevent LV dysfunction (prospective multicenter RCT).
- **ICI myocarditis:** Serial hsTnI can detect ICI myocarditis in both symptomatic and asymptomatic patients; relative elevation in cardiac troponin T prognostic for MACE.
- ESC guidelines recommend baseline cardiac biomarker measurement in all patients receiving potentially cardiotoxic agents.

### Multi-Omics Biomarkers

#### Genomics
- SNPs associated with anthracycline cardiotoxicity identified in several pathways (Table 2); limited by small sample sizes and lack of consensus cardiotoxicity definition.
- **TTNtv:** Titin-truncating variants associated with anthracycline cardiomyopathy (similar to DCM overlap).
- **RARG:** Variant associated with anthracycline cardiomyopathy in multiple cohorts.
- **CHIP:** Clonal haematopoiesis of indeterminate potential — listed as a genomic biomarker.
- Insufficient validation for routine clinical use in predicting cardiotoxicity.

#### Transcriptomics
- Single-cell RNA sequencing (scRNA-seq) and spatial transcriptomics map immune cell subsets in ICI myocarditis.
- **scRNA-seq + TCR sequencing + mass cytometry:** Identified pathogenic T-cell populations (α-myosin–specific T cells) in ICI myocarditis.
- Spatial transcriptomics would add mechanistic insights into cardiotoxicity distribution within cardiac tissue.

#### Proteomics
- High-throughput proteomics (SomaScan, Olink, CITE-seq) applied to pilot cohorts receiving anthracyclines and carfilzomib.
- **Hemopexin:** Identified as a biomarker in anthracycline cardiotoxicity.
- **CSK (C-terminal Src kinase):** Identified in ibrutinib-associated atrial fibrillation.

#### Metabolomics
- Targeted LC/MS metabolite profiling in breast cancer patients with/without anthracycline cardiotoxicity.
- Early changes in **tricarboxylic acid (TCA) cycle metabolites** differentiated subsequent cardiotoxicity development.
- Patients with cardiotoxicity showed pronounced alterations in purine and pyrimidine metabolism.

### AI-Based Risk Prediction Models
- Classification models trained on 4,309 cancer patients (laboratory, symptoms, demographics, echo) for 6 CV outcomes — proof of concept for CV risk stratification in oncology.
- Breast cancer model: included treatment-related (anthracycline/radiation) and conventional (hypertension, DM) risk factors; predicted MACE at up to 7 years.
- Lung cancer CT scan model: 30,286 low-dose CT scans; predicted CVD mortality risk, outperformed existing models.
- Comprehensive integrative model (troponin, BNP, cancer + CV risk factors): risk discrimination in the **90% range** across multiple cohorts.
- Exome sequencing (289 childhood cancer survivors, anthracycline): differentially enriched variants improved LVEF-decline prediction when combined with clinical predictors.
- **Major limitation:** Systematic review of cardiotoxicity prediction models for breast cancer found only 1 of 6 studies used external validation — generalisability uncertain.

### AI-Enabled Cardiac Imaging Analysis
- Automated LVEF measurement: randomised clinical trial showed benefits for AI-based LVEF assessment.
- Research ongoing for automated LV strain, diastolic function, myocardial perfusion.
- Foundation models and semi-supervised/self-supervised learning reduce need for manual image labelling.
- AI can identify novel imaging biomarkers not observable by human experts; multimodal composite biomarkers possible with appropriate datasets.

### NLP and Large Language Models for Clinical Data Extraction
- NLP supplements discrete EHR data with unstructured clinical note content for cardiotoxicity risk.
- LLMs can extract structured cardiotoxicity data from EHR (erratic data, missing elements, unstructured formats).
- Smart chatbots can enable clinicians to query diverse electronic data sources directly.
- Potential to identify high-risk patients for cardio-oncology referral before oncologic treatment.
- No specific cardio-oncology LLM implementations yet documented in published literature (as of 2025).

### AI-Driven Drug Discovery
- ML algorithms integrated into drug screening, toxicity prediction, and manufacturing pipeline.
- AI holds promise for predicting toxicity of existing drugs and discovering therapeutic approaches to treat cardiotoxicity.
- Currently a future direction; experimental validation is required alongside AI predictions.

### AI-Enabled ECG Algorithms for Cardiotoxicity Detection
- Convolutional neural networks used to analyse ECG signals for cardiotoxicity.
- **ICI myocarditis:** ECG features early during cancer treatment predictive of life-threatening arrhythmias and mortality (125 ICI myocarditis cases + 50 transplant rejection controls, 49 institutions, 11 countries).
- **LV systolic dysfunction/HF risk in anthracycline/trastuzumab patients:** AI-ECG detected cancer therapeutics-related cardiac dysfunction in studies of 3,364 and 889 patients respectively.
- **AF prediction in leukemia:** ECG-based AI predicted AF risk in 754 patients with leukemia.
- Outside cardio-oncology, AI-ECG detects LVEF <40%, myocardial ischaemia, AF during sinus rhythm, and structural cardiac disorders.
- Convolutional neural networks applied to quantify ECG alterations from sotalol — enhanced prediction of drug-induced torsades de pointes and LQTS diagnosis.

### Integration of EHR-Based Algorithms and Registries
- EHR-based clinical decision support systems: patient registry at national level for research + care; quality improvement; care gap identification; CVD risk algorithms.
- Programmatic rules filter eligible oncology patients with relevant diagnosis codes + chemotherapy/RT/targeted/immunotherapy records.
- Tools can identify women with early-stage breast cancer on estrogen-deprivation therapy at increased remote CVD risk.

### Barriers to AI Integration
- Erratic data with missing elements; difficulty converting unstructured/range data; disparate data systems.
- Evolving cardiotoxicity definitions — moving target for algorithm developers.
- Algorithmic output must be interpretable to clinicians ("algorithmic bias" = opaque outputs).
- Requires multidisciplinary buy-in across clinicians, researchers, industry, regulators, and payers.

### Ethical Considerations
| Challenge | Example | Potential Solution |
|---|---|---|
| Security | Annual large-scale data breaches | Cybersecurity measures; network security |
| Data privacy & consent | Google Project Nightingale (21-state data without consent); Royal Free/DeepMind UK Data Protection breach | Consent at care initiation; uniform definitions of data risk |
| Algorithmic fairness & bias | Health cost-focused AI underestimated cardiac risk in underrepresented racial/ethnic groups due to historically lower health care use | Independent algorithm assessment; diverse training datasets |
| Equitable access | Rural counties with low broadband have less CV care access | Public policy for broadband/telehealth expansion |

- Multi-omics datasets largely derived from populations of European ancestry — limits scalability across diverse populations.
- AHA 2023 principles for data sharing, patient privacy, and equity in big data research.

### Future Directions
- National cardio-oncology database registry needed: alleviates multi-omic cost and small dataset limitations; must represent community hospital populations to avoid selection bias.
- Large prospective cohort studies with deep cardiac and cancer phenotyping.
- ML + polygenic risk scores for cardiotoxicity susceptibility prediction.
- Clinical trials to test AI/ML models for predicting and diagnosing CV outcomes in patients with cancer.
- Continuous model re-training as cardio-oncology landscape evolves.

## Limitations of the Document
- Scientific Statement rather than guideline; no formal GRADE or COR/LOE methodology.
- Evidence base is heterogeneous: varied populations, inconsistent cardiotoxicity definitions, small cohorts, limited external validation.
- Most AI models reviewed are proof-of-concept with no prospective clinical validation.
- Multi-omics literature largely derived from European-ancestry populations — generalisability limited.
- Rapidly evolving field; some cited applications may be superseded quickly.

## Key Concepts Mentioned
- [[concepts/Cardio-Oncology]] — overarching discipline framework; AI as future priority
- [[concepts/Cancer-Therapy-Related-CV-Toxicity]] — ICI myocarditis imaging, biomarker-guided cardioprotection, multi-omics
- [[concepts/AI-in-Cardio-Oncology]] — primary concept page for this source
- [[concepts/Late-Gadolinium-Enhancement]] — ICI myocarditis T1/T2 mapping
- [[concepts/HFA-ICOS-Risk-Stratification]] — baseline risk stratification context
- [[concepts/Torsades-de-Pointes]] — sotalol ECG AI quantification for TdP prediction
- [[concepts/Drug-Induced-Arrhythmia]] — drug-induced ECG changes and AI prediction

## Key Entities Mentioned
- [[entities/Atrial-Fibrillation]] — ibrutinib-induced AF; AI-ECG AF prediction in leukemia
- [[entities/DCM]] — TTNtv overlap with anthracycline cardiomyopathy
- [[entities/Heart-Failure]] — CTRCD endpoint; AI HF risk prediction

## Wiki Pages Updated
- `wiki/sources/ai-cardiooncology-aha-2025.md` — created
- `wiki/concepts/AI-in-Cardio-Oncology.md` — created
- `wiki/concepts/Cardio-Oncology.md` — updated (AI precision medicine section)
- `wiki/concepts/Cancer-Therapy-Related-CV-Toxicity.md` — updated (multi-omics, AI ECG, biomarker-guided therapy RCTs)
- `wiki/concepts/Late-Gadolinium-Enhancement.md` — updated (ICI myocarditis CMR data)
- `wiki/wikiindex.md` — updated
- `wiki/sourceindex.md` — updated
