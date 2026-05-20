<p align="center">
  <img src="./github-header.svg" alt="Samir Kerkar — Data Scientist" width="100%"/>
</p>

Healthcare data scientist working in causal inference, quasi-experimental program evaluation, and applied ML for managed care populations. Four years designing and executing pharmacist-led intervention studies at a 60,000-patient health system; now supporting publication-track outcomes work for an FDA-cleared cardiac device.

M.S. Data Science, UC San Diego (HDSI, starting Fall 2026) · B.S. Mathematics, UC Irvine (Dean's Honor List)

**Available:** Full-time · Contract · Remote-friendly

Samir2000VIP@gmail.com · [LinkedIn](https://www.linkedin.com/in/samir-kerkar-206132172/) · Irvine, CA

---

## Current — Ventric Health
*Clinical Research Data Scientist (Remote)*

Sole owner of an OCR / computer-vision pipeline for a Vivio-vs-echocardiogram gold-standard comparison study. Python + Tesseract with a full preprocessing stack (deskew, denoise, adaptive thresholding, layout-detected ROI extraction), regex normalization, and confidence-thresholded auto-flagging. Validated against ~500 manually abstracted echo reports at **>95% field-level accuracy** — replacing weeks of chart abstraction and producing the structured dataset feeding the device-validation analysis.

---

## Selected Work — Desert Oasis Healthcare (2022–2026)

Data scientist on a small analytics team across 20+ facilities, ~60,000 managed care patients. Methods chosen to defend causal claims a reviewer would actually question.

- **COPD pharmacist-led program evaluation** — Propensity-matched cohort (n = 997, 1:1, balance verified via love plot + SMD), 12-month pre/post difference-in-differences. **$83.50 PMPM cost reduction (p = 0.0027)**, driven by ED (p = 0.002), inpatient (p = 0.04), and 30-day readmission (p = 0.002) utilization. Secondary PDC analysis: **≈20% adherence improvement (p = 0.013)** vs. matched controls.
- **Post-discharge pharmacist intervention** (n = 878) — Negative binomial regression (selected over Poisson after overdispersion diagnostics), adjusted for age, sex, race, and comorbidities. **Adjusted IRR = 0.78 (p = 0.02)** — 22% reduction in 30-day all-cause readmissions.
- **Hospitalization-risk models** — Random forest / XGBoost over ~40 features (claims, EHR, pharmacy, lab) with SMOTE. **AUROC = 0.78** (k-fold CV) on CHF / COPD cohorts. Monthly risk-stratified lists handed to clinical pharmacists who validated flags and enrolled patients into care management — closing the loop from model output to clinical action.
- **Patient-experience NLP** — ~40K free-text comments / year. DistilBERT sentiment validated against 5,000 manually labeled comments at ~90% accuracy, plus LDA topic modeling (k = 30). Operationalized by the BI team via SQL Server Agent into provider- and facility-level Power BI dashboards.
- **AFib anticoagulation care-gap study** — Cohort identification via ICD-10 (n = 1,381); 77 cases of guideline-discordant therapy flagged for pharmacist review. Contributed to a poster at the **ASHP National Conference**.

---

## Publications

**Improvements in HF-Related Utilization Outcomes Following Large-Scale Screening for LVEDP as Part of Routine Primary Care** *(under peer review)* — Co-authored with Ventric Health and DOHC clinical pharmacy leadership. Sole DOHC-side data analyst: independently extracted and analyzed EHR + claims data to construct the post-implementation comparison across 11 primary care clinics (multi-thousand-patient high-risk cohort, 10-month rollout in 2024). Identified newly diagnosed HF cohorts via ICD-10 → HCC 226. Quantified year-over-year reductions in **urgent care (p < 0.001)** and **ED (p = 0.006)** utilization following screening rollout.

---

## Featured Projects

### [CausalCare](https://github.com/skerk001/CausalCare) — Causal inference on ICU mortality
Five-method stack (PSM, IPW, AIPW doubly-robust, Double ML, Causal Forest) built on DoWhy's *identify → estimate → refute* workflow. Placebo and random-common-cause refuters at each stage; method agreement used as a robustness check rather than a single point estimate. Causal Forest for heterogeneous treatment effects.

### [GenomicsGPT](https://github.com/skerk001/genomicsgpt) — Variant interpretation at scale
XGBoost / LightGBM ensemble over 1.69M ClinVar variants across 40 engineered features. Leakage-corrected **AUC = 0.985**, macro-F1 = 0.948. Feature ablation defends against gene-name memorization: consequence + LoF alone reach AUC 0.97, while gene-only collapses to 0.78. SHAP per-variant audit; Llama 3 / Claude narrative engine generates structured ACMG/AMP reports.

---

## Other Projects

- **[ClinicalRAG](https://github.com/skerk001/clinical-rag)** — RAG over 220 clinical documents treating retrieval quality and refusal as first-class metrics: 97.6% condition recall, 85.7% citation rate, 95.2% abstention accuracy. Systematic chunk-size sweep selected 512-char chunks as the recall / precision optimum.
- **[Diabetic Retinopathy](https://github.com/skerk001/diabetic-retinopathy-classification)** — Custom CNN, 5-class grading on 5,000+ retinal images. Weighted F1 = 0.94, outperforming fine-tuned ResNet-50 and VGG-16 on the same split. Grad-CAM confirms attention to clinically meaningful pathology. [Paper](https://github.com/skerk001/diabetic-retinopathy-classification/blob/main/DR_Classification_CNN_Research_Paper.pdf).
- **[REIGN](https://github.com/skerk001/reign-web)** — Cross-era NBA impact models across 29,969 player-seasons, 3,484 players (1946–2025). Era-specific regressions with rolling 5-year z-score normalization and playoff opponent-strength adjustment.

---

## Stack

**Causal & statistics** — PSM, DiD, IPW, AIPW, Double ML, Causal Forest, negative binomial & other GLMs, survival analysis, PMPM modeling
**ML & deep learning** — XGBoost, LightGBM, scikit-learn, TensorFlow / Keras, SHAP, Grad-CAM
**LLM / NLP** — RAG, LangChain, ChromaDB, HuggingFace Transformers, LDA, sentiment
**Computer vision & OCR** — Tesseract, OpenCV, image preprocessing, layout detection / ROI
**Healthcare data** — EHR, administrative claims, pharmacy / Rx, ICD-10, CPT, HCPCS, HCC, HIPAA-compliant handling
**Languages & delivery** — Python, SQL (SQL Server, PostgreSQL), R, Power BI, FastAPI, Git, LaTeX

---

<sub>Outside work: 2500+ rated chess · basketball · piano</sub>
