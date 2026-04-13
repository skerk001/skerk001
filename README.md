<p align="center">
  <img src="./github-header.svg" alt="Samir Kerkar — Data Scientist" width="100%"/>
</p>

Healthcare data scientist — causal inference, quasi-experimental program evaluation, applied ML. M.S. Data Science at UC San Diego starting Fall 2026; B.S. Mathematics, UC Irvine.

Samir2000VIP@gmail.com · [LinkedIn](https://www.linkedin.com/in/samir-kerkar-206132172/) · Irvine, CA

Four years evaluating pharmacist-led clinical programs at a 60,000-patient managed care system using propensity score matching, difference-in-differences, and negative binomial regression. Representative results:

- $83.50 PMPM cost reduction (p = 0.0027, n = 997) from a COPD program evaluation — PSM + DiD over a 12-month pre/post window, balance verified via love plot and standardized mean differences.
- 22% reduction in 30-day readmissions (adjusted IRR = 0.78, p = 0.02, n = 878) from a post-discharge pharmacist intervention — negative binomial over Poisson after diagnosing overdispersion.
- Co-authored heart failure outcomes manuscript under peer review; sole data analyst on the DOHC side (11 clinics, multi-thousand-patient cohort).
- Analysis contribution to a pharmacy-resident-led AFib anticoagulation care-gap poster at the ASHP National Conference.

Currently open to full-time and contract data scientist roles, healthcare or adjacent. Remote-friendly.

## Projects

[CausalCare](https://github.com/skerk001/CausalCare) — Causal inference on ICU mortality using the eICU dataset. Implements a five-method stack (PSM, IPW, AIPW doubly-robust, Double ML, Causal Forest) with DoWhy's identify–estimate–refute workflow and method agreement as a robustness check. Placebo and random-common-cause refuters included. Built with EconML and DoWhy.

[GenomicsGPT](https://github.com/skerk001/genomicsgpt) — End-to-end variant interpretation platform. XGBoost/LightGBM ensemble on 1.69M ClinVar variants across 40 engineered features: leakage-corrected AUC 0.985, macro-F1 0.948. Feature ablation validates biological signal (consequence and LoF features alone reach AUC 0.97 versus 0.78 for gene-only), ruling out gene-name memorization. SHAP for per-variant audit; Llama 3 / Claude narrative engine generates structured ACMG/AMP reports.

[ClinicalRAG](https://github.com/skerk001/clinical-rag) — Retrieval-augmented QA over 220 clinical documents, treating retrieval quality and refusal behavior as first-class metrics: 97.6% condition recall, 85.7% citation rate, 95.2% abstention accuracy. Systematic chunk-size sweep selected 512-character chunks as the recall/precision optimum.

[Diabetic Retinopathy Classification](https://github.com/skerk001/diabetic-retinopathy-classification) — Self-directed undergraduate project. Custom CNN for 5-class DR grading on 5,000+ retinal images, weighted F1 = 0.94, outperforming fine-tuned ResNet-50 and VGG-16 on the same split. Grad-CAM confirmed the network attended to clinically meaningful pathology rather than artifacts. [Paper](https://github.com/skerk001/diabetic-retinopathy-classification/blob/main/DR_Classification_CNN_Research_Paper.pdf).

Also: [REIGN](https://github.com/skerk001/reign-web) — cross-era NBA player impact models over 29,969 player-seasons with era-specific z-score normalization and playoff opponent-strength adjustment. [Gene Expression Cancer Prediction](https://github.com/skerk001/gene-cancer-prediction) — AML vs. ALL classification, F1 = 0.95.

## Stack

Python (pandas, NumPy, SciPy, statsmodels, scikit-learn), SQL (SQL Server, PostgreSQL), R. Causal and statistical methods: PSM, DiD, IPW, AIPW, Double ML, Causal Forest, negative binomial and GLMs, survival analysis. ML: XGBoost, LightGBM, random forests, SHAP, TensorFlow/Keras. LLM and NLP: RAG, LangChain, ChromaDB, HuggingFace Transformers, LDA. Healthcare data: EHR, claims, pharmacy, ICD-10, CPT, HCC, PMPM, HEDIS/Stars and VBP familiarity. Delivery: matplotlib, seaborn, Power BI, FastAPI, Git.

Outside work: 2500+ rated chess player, basketball, piano.
