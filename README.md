<div align="center">

<!-- ANIMATED HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a365d,100:f59e0b&height=220&section=header&text=Samir%20Kerkar&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Data%20Scientist%20%7C%20Clinical%20Data%20Analyst%20%&descSize=18&descAlignY=55&descColor=fbbf24" width="100%"/>

<br/>

[![Email](https://img.shields.io/badge/Email-Samir2000VIP@gmail.com-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Samir2000VIP@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/samir-kerkar-206132172/)
[![Portfolio](https://img.shields.io/badge/Courtside-NBA%20Analytics-f59e0b?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTEyIDJDNi40OCAyIDIgNi40OCAyIDEyczQuNDggMTAgMTAgMTAgMTAtNC40OCAxMC0xMFMxNy41MiAyIDEyIDJ6bTAgMThjLTQuNDIgMC04LTMuNTgtOC04czMuNTgtOCA4LTggOCAzLjU4IDggOC0zLjU4IDgtOCA4eiIgZmlsbD0id2hpdGUiLz48L3N2Zz4=)](https://github.com/skerk001/court-vision-23-main)

</div>

---

### 👋 About Me

I'm a data scientist with a mathematics background from **UC Irvine** (B.S. Mathematics). I build things at the intersection of **statistical modeling**, **machine learning**, **clinical data**, and **sports analytics** — turning messy real-world data into systems that surface genuine insight.

Previously at **Desert Oasis Healthcare**, I analyzed EHR data across 50,000+ patients and 20+ facilities, built predictive models (AUROC 0.72), and co-authored research presented at **ASHP national conferences** with a manuscript currently under peer review. Currently pursuing my M.S. in Data Science.

<table>
<tr><td>📍</td><td>Southern California</td></tr>
<tr><td>🎓</td><td>B.S. Mathematics — UC Irvine · M.S. Data Science (incoming)</td></tr>
<tr><td>🔭</td><td>Building end-to-end ML systems for healthcare and sports analytics</td></tr>
<tr><td>💡</td><td>NLP/RAG · ML/Statistical Modeling · Healthcare Data · NBA Analytics</td></tr>
</table>

---

### 🔧 Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

### 🏥 Featured Project: ClinicalRAG

> **An end-to-end RAG system for clinical question answering with hallucination guardrails, source citations, and systematic evaluation across chunking strategies.**

<div align="center">

| Metric | Score |
|:--|:-:|
| **Condition Recall** | **97.6%** |
| **Citation Rate** | **85.7%** |
| **Abstention Accuracy** | **95.2%** |
| **Retrieval Diversity** | **99–100%** |
| **Hallucination Detection** | **Active** |

</div>

The system ingests 220 clinical documents across 7 conditions, embeds them with deduplication into ChromaDB, and retrieves via MMR (k=5, fetch_k=20, λ=0.7) to ensure diverse evidence. Llama 3 8B generates structured answers with `[Source N]` citations, and a post-generation guardrail cross-references extracted clinical values against retrieved context — flagging responses where <70% of values are grounded.

**What makes this different:** Most RAG tutorials ship a demo and stop. This project includes a 21-question evaluation framework with expected answer keys, automated metrics, and ablation studies across four chunk sizes — producing quantitative evidence the system works and revealing exactly where it breaks down.

<div align="center">
<img src="https://raw.githubusercontent.com/skerk001/clinical-rag/main/docs/images/chunk_comparison_6panel.png" width="700"/>
<br/>
<em>Performance across all metrics at 4 chunk sizes (256, 512, 1000, 1500)</em>
</div>

<br/>

<div align="center">
<img src="https://raw.githubusercontent.com/skerk001/clinical-rag/main/docs/images/quality_latency_tradeoff.png" width="500"/>
<br/>
<em>512-char chunks optimal: highest keyword recall (61.1%) and citation rate (85.7%) with balanced latency</em>
</div>

<br/>

<div align="center">
<img src="https://raw.githubusercontent.com/skerk001/clinical-rag/main/docs/images/category_heatmap.png" width="500"/>
<br/>
<em>Category-level breakdown: drug safety and cross-condition categories robust across all chunk sizes</em>
</div>

**Tech:** Python · LangChain · Llama 3 8B (Ollama) · ChromaDB · all-MiniLM-L6-v2 · Streamlit · matplotlib

[![ClinicalRAG Repo](https://img.shields.io/badge/🏥_ClinicalRAG-View_Repository-10b981?style=for-the-badge)](https://github.com/skerk001/clinical-rag)

---

### 🏀 Featured Project: Courtside

> **A proprietary NBA analytics platform evaluating every player in league history (1946–2025) on a unified scale.**

**The PMI (Player Metric Index)** is a composite metric I designed from scratch that solves three hard problems in basketball analytics: cross-era stat inflation (within-season z-score normalization + graduated era penalties), missing data before 1973 (ML imputation via `GradientBoostingRegressor`), and position bias (continuous 1–5 interpolation instead of discrete buckets).

```
PMI = OPMI + DPMI
OPMI = Σ w(pos, stat) · clip(z_stat, -3.0, +3.0) × era_penalty(season)
DPMI = (w_stl·z_stl + w_blk·z_blk + w_drb·z_drb + w_pf·z_pf) × 0.72
CPMI = 1.50·z_ppg + 0.40·z_apg + 0.35·z_ts + 0.50·z_±  — clutch metric (last 5 min ±5 pts)
```

<div align="center">

| Regular Season | Playoffs |
|:-:|:-:|
| 🥇 Jordan **+10.96** | 🥇 LeBron **+13.54** |
| 🥈 LeBron **+10.81** | 🥈 Jordan **+11.99** |
| 🥉 Curry **+10.23** | 🥉 Jokić **+10.65** |

</div>

**Tech:** Python · Flask · React · TypeScript · scikit-learn · Tailwind CSS · NBA API · Basketball Reference

[![Courtside Repo](https://img.shields.io/badge/📊_Courtside-View_Repository-f59e0b?style=for-the-badge)](https://github.com/skerk001/court-vision-23-main)
[![Research Paper](https://img.shields.io/badge/📄_Research-PMI_Paper_(PDF)-3b82f6?style=for-the-badge)](https://github.com/skerk001/court-vision-23-main/blob/main/docs/PMI_Research_Paper.pdf)

---

### 👁️ Featured Research: Diabetic Retinopathy Classification

> **Deep learning system for automated detection of diabetic retinopathy severity from retinal fundus images.**

Built during undergraduate research at **UC Irvine**, this project trained CNNs (TensorFlow/Keras) on 5,000+ labeled retinal images for multi-class severity classification, achieving **F1 = 0.94** across all severity grades through systematic architecture search, data augmentation, and cross-validation.

<div align="center">
<img src="https://raw.githubusercontent.com/skerk001/diabetic-retinopathy-classification/main/fig4_confusion_matrix.png" width="400"/>
<img src="https://raw.githubusercontent.com/skerk001/diabetic-retinopathy-classification/main/fig5_roc_curves.png" width="400"/>
</div>

**Tech:** Python · TensorFlow · Keras · NumPy · OpenCV · Matplotlib

[![DR Repo](https://img.shields.io/badge/👁️_Retinopathy-View_Repository-3b82f6?style=for-the-badge)](https://github.com/skerk001/diabetic-retinopathy-classification)
[![Research Paper](https://img.shields.io/badge/📄_Research-CNN_Paper_(PDF)-ef4444?style=for-the-badge)](https://github.com/skerk001/diabetic-retinopathy-classification/blob/main/DR_Classification_CNN_Research_Paper.pdf)

---

### 📊 Other Projects

<table>
<tr>
<td width="50%" valign="top">

#### 🏥 Healthcare Outcomes Research
Statistical analysis across 50,000+ patients at Desert Oasis Healthcare. COPD cost-effectiveness study showing **$83.50 PMPM savings** (p=0.0027, n=997). Co-authored research presented at **ASHP 2024**.

📄 **Co-authored Publication** — *Improvements in HF-related utilization outcomes following large-scale screening for LVEDP as part of routine primary care* · Observational study (n=3,024) demonstrating significant reductions in acute care utilization (ED: p=0.006, UC: p<0.001) across 11 primary care clinics. *Submitted for peer review, 2025.*

`Python` `R` `SQL` `Logistic Regression` `scipy` `statsmodels`
</td>
<td width="50%" valign="top">

#### [🔬 ML Cancer Prediction](https://github.com/skerk001/gene-cancer-prediction)
Gene expression cancer classification using machine learning. Built predictive models on high-dimensional genomic data achieving **96% classification accuracy** on 100,000+ NIH chest X-ray images.

`scikit-learn` `TensorFlow` `Classification`

#### [🏠 Real Estate Condition Prediction](https://github.com/skerk001/real-estate-condition-prediction)
ML model to predict property condition ratings from real estate listing data. Feature engineering on housing attributes for valuation analysis.

`Python` `scikit-learn` `Pandas` `Feature Engineering`

#### ♟️ Chess Meme Tower Defense
A Clash Royale-style tower defense game with chess piece troops, meme characters, spells, and castle upgrades.

`JavaScript` `HTML5 Canvas` `Game AI`
</td>
</tr>
</table>

---

<div align="center">

*"How do you compare a 1962 Wilt Chamberlain season to a 2024 Nikola Jokić season?*
*The same way — by measuring how far each deviated from their peers."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a365d,100:f59e0b&height=100&section=footer" width="100%"/>

</div>
