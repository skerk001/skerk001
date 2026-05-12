<p align="center">
  <img src="./github-header.svg" alt="Samir Kerkar — Data Scientist" width="100%"/>
</p>

# Samir Kerkar

Healthcare data scientist working in causal inference, quasi-experimental program evaluation, and applied ML. Four years evaluating pharmacist-led clinical programs at a 60,000-patient managed care system — most recently a PSM + DiD evaluation that documented **$83.50 PMPM cost reduction (p = 0.0027)** across a COPD cohort.

M.S. Data Science, UC San Diego (starting Fall 2026) · B.S. Mathematics, UC Irvine

**Available:** Full-time · Open to contract / full-time · Remote-friendly

📧 Samir2000VIP@gmail.com · [LinkedIn](https://www.linkedin.com/in/samir-kerkar-206132172/) · Irvine, CA

---

## Selected Work — Desert Oasis Healthcare

Sole data analyst across 11 clinics. Methods chosen to defend causal claims a reviewer would actually question.

- **COPD program evaluation** (n = 997, PSM + DiD): $83.50 PMPM cost reduction (p = 0.0027), driven by lower ED (p = 0.002), inpatient (p = 0.04), and readmission (p = 0.002) utilization.
- **Post-discharge pharmacist intervention** (n = 878, negative binomial regression): 22% reduction in 30-day readmissions (IRR = 0.78, p = 0.02).
- **Heart failure outcomes manuscript** — under peer review.
- **AFib anticoagulation care-gap analysis** — poster, ASHP National Conference.

---

## Featured Projects

### 🧪 [CausalCare](https://github.com/skerk001/CausalCare) — Causal inference on ICU mortality
Five-method stack (PSM, IPW, AIPW, Double ML, Causal Forest) built on DoWhy's identify–estimate–refute workflow. Placebo and random-common-cause refuters at each stage; method agreement used as a robustness check rather than a single point estimate.
**Why it matters:** demonstrates the full causal pipeline most healthcare ML projects skip.

### 🧬 [GenomicsGPT](https://github.com/skerk001/genomicsgpt) — Variant interpretation at scale
XGBoost / LightGBM ensemble over 1.69M ClinVar variants. Leakage-corrected AUC **0.985**, macro-F1 **0.948**. Feature ablation defends against gene-name memorization: consequence + LoF alone reach AUC 0.97, while gene-only collapses to 0.78. SHAP per-variant audit; Llama 3 / Claude narrative engine generates ACMG/AMP-style reports.
**Why it matters:** pre-empts the leakage critique a reviewer would lead with.

---

## Other Projects

- **[ClinicalRAG](https://github.com/skerk001/clinical-rag)** — RAG over 220 clinical documents with retrieval *and refusal* as first-class metrics: 97.6% condition recall, 85.7% citation rate, 95.2% abstention accuracy.
- **[Diabetic Retinopathy](https://github.com/skerk001/diabetic-retinopathy-classification)** — Custom CNN for 5-class DR grading. Weighted F1 = 0.94, outperforming ResNet-50 and VGG-16 on the same split. Grad-CAM confirms attention to clinically meaningful pathology. [Paper](https://github.com/skerk001/diabetic-retinopathy-classification/blob/main/DR_Classification_CNN_Research_Paper.pdf).
- **[REIGN](https://github.com/skerk001/reign-web)** — Cross-era NBA impact models over 29,969 player-seasons with era-specific z-score normalization.

---

## Stack

**Causal & Statistics** — PSM, DiD, IPW, AIPW, Double ML, Causal Forest, negative binomial & other GLMs, survival analysis
**ML** — XGBoost, LightGBM, scikit-learn, TensorFlow / Keras, SHAP
**LLM / NLP** — RAG, LangChain, ChromaDB, HuggingFace Transformers
**Healthcare data** — EHR, claims, pharmacy, ICD-10, HCC, PMPM
**Languages & delivery** — Python, SQL, R, Power BI, FastAPI, Git

---

<sub>Outside work: 2500+ rated chess · basketball · piano</sub>
