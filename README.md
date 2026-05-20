# Samir Kerkar

Healthcare data scientist working in causal inference, quasi-experimental program evaluation, and applied ML for managed care populations. Four years of pharmacist-led intervention studies at a 60,000-patient health system; now supporting publication-track outcomes work for an FDA-cleared cardiac device.

M.S. Data Science, UC San Diego (HDSI, starting Fall 2026) · B.S. Mathematics, UC Irvine

**Available:** Full-time · Contract · Remote-friendly

Samir2000VIP@gmail.com · [LinkedIn](https://www.linkedin.com/in/samir-kerkar-206132172/) · Irvine, CA

---

## Current — Ventric Health
*Clinical Research Data Scientist (Remote)* — Analytical infrastructure and outcomes analyses supporting device validation and post-market evidence generation for an FDA-cleared cardiac device.

---

## Selected Work — Desert Oasis Healthcare (2022–2026)

Data scientist across 20+ facilities, ~60,000 managed care patients. Methods chosen to defend causal claims a reviewer would actually question.

- **COPD pharmacist-led program** — Propensity-matched cohort (n = 997) + difference-in-differences. **$83.50 PMPM cost reduction (p = 0.0027)**; secondary PDC analysis showed **≈20% adherence improvement (p = 0.013)**.
- **Post-discharge pharmacist intervention** (n = 878) — Negative binomial regression (selected over Poisson after overdispersion diagnostics). **Adjusted IRR = 0.78 (p = 0.02)** — 22% reduction in 30-day all-cause readmissions.
- **Hospitalization-risk models** — Random forest / XGBoost over ~40 features (claims, EHR, pharmacy, lab) with SMOTE. AUROC = 0.78 (k-fold CV) on CHF / COPD cohorts. Monthly risk-stratified lists drove clinical-pharmacist outreach.
- **Patient-experience NLP** — ~40K free-text comments / year. DistilBERT sentiment (~90% on a 5K labeled set) + LDA topic modeling, operationalized into provider- and facility-level Power BI dashboards.
- **AFib anticoagulation care-gap study** — ICD-10 cohort identification (n = 1,381); 77 guideline-discordant cases flagged for pharmacist review. Contributed to a poster at the **ASHP National Conference**.

---

## Publications

**Improvements in HF-Related Utilization Outcomes Following Large-Scale Screening for LVEDP as Part of Routine Primary Care** *(under peer review)* — Co-authored; sole DOHC-side analyst on the post-implementation utilization comparison. Year-over-year reductions in urgent care (p < 0.001) and ED (p = 0.006) utilization following screening rollout.

---

## Projects

- **[CausalCare](https://github.com/skerk001/CausalCare)** — Causal inference on ICU mortality. Five-method stack (PSM, IPW, AIPW, Double ML, Causal Forest) on DoWhy's *identify → estimate → refute* workflow; method agreement as a robustness check rather than a single point estimate.
- **[GenomicsGPT](https://github.com/skerk001/genomicsgpt)** — Variant interpretation at scale. XGBoost / LightGBM ensemble over 1.69M ClinVar variants. Leakage-corrected **AUC = 0.985**; feature ablation defends against gene-name memorization (consequence + LoF alone = 0.97; gene-only = 0.78). SHAP audit + LLM-generated ACMG/AMP reports.
- **[ClinicalRAG](https://github.com/skerk001/clinical-rag)** — RAG over 220 clinical documents with retrieval *and* refusal as first-class metrics: 97.6% recall, 85.7% citation rate, 95.2% abstention accuracy.
- **[Diabetic Retinopathy](https://github.com/skerk001/diabetic-retinopathy-classification)** — Custom CNN, 5-class grading. Weighted F1 = 0.94, outperforming ResNet-50 and VGG-16 on the same split. Grad-CAM confirms clinically meaningful attention.

---

## Stack

**Causal & statistics** — PSM, DiD, IPW, AIPW, Double ML, Causal Forest, negative binomial & other GLMs, survival analysis, PMPM modeling
**ML / DL** — XGBoost, LightGBM, scikit-learn, TensorFlow / Keras, SHAP
**LLM / NLP** — RAG, LangChain, ChromaDB, HuggingFace Transformers
**Healthcare data** — EHR, claims, pharmacy, ICD-10, HCC, HIPAA-compliant handling
**Languages & delivery** — Python, SQL, R, Power BI, FastAPI, Git

---

<sub>Outside work: 2500+ rated chess · basketball · piano</sub>
