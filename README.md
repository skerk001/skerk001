<div align="center">

<!-- ANIMATED HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a365d,100:f59e0b&height=220&section=header&text=Samir%20Kerkar&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Data%20Scientist%20%7C%20ML%20Engineer%20%7C%20NBA%20Analytics&descSize=18&descAlignY=55&descColor=fbbf24" width="100%"/>

<br/>

[![Email](https://img.shields.io/badge/Email-Samir2000VIP@gmail.com-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Samir2000VIP@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/samir-kerkar-206132172/)
[![Portfolio](https://img.shields.io/badge/Courtside-NBA%20Analytics-f59e0b?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTEyIDJDNi40OCAyIDIgNi40OCAyIDEyczQuNDggMTAgMTAgMTAgMTAtNC40OCAxMC0xMFMxNy41MiAyIDEyIDJ6bTAgMThjLTQuNDIgMC04LTMuNTgtOC04czMuNTgtOCA4LTggOCAzLjU4IDggOC0zLjU4IDgtOCA4eiIgZmlsbD0id2hpdGUiLz48L3N2Zz4=)](https://github.com/skerk001/court-vision-52)

</div>

---

### 👋 About Me

I'm a data scientist with a mathematics background from **UC Irvine** (B.S. Mathematics). I build things at the intersection of **statistical modeling**, **machine learning**, and **sports analytics** — turning messy real-world data into systems that surface genuine insight.

Previously at **Desert Oasis Healthcare**, I analyzed EHR data across 50,000+ patients and 20+ facilities, built predictive models (AUROC 0.72), and co-authored research presented at **ASHP national conferences**. Currently pursuing my **M.S. in Data Science.

```python
class SamirKerkar:
    location = "Southern California"
    education = ["B.S. Mathematics — UC Irvine", "M.S. Data Science — UC San Diego (incoming)"]
    interests = ["NBA Analytics", "ML/Statistical Modeling", "Healthcare Data", "Chess"]
    
    def current_focus(self):
        return "Building Courtside — a cross-era NBA player evaluation platform"
```

---

### 🔧 Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square&logo=python&logoColor=white)

</div>

<div align="center">
<img src="assets/skills-bar.png" width="600"/>
</div>

---

### 🏀 Featured Project: Courtside

> **A proprietary NBA analytics platform evaluating every player in league history (1946–2025) on a unified scale.**

<div align="center">
<img src="assets/pmi-flow.png" width="700"/>
</div>

**The PMI (Player Metric Index)** is a composite metric system I designed from scratch that solves three hard problems in basketball analytics:

| Challenge | Solution |
|-----------|----------|
| Cross-era stat inflation | Within-season z-score normalization + graduated era penalties |
| Missing data before 1973 | ML imputation via `GradientBoostingRegressor` for defensive metrics |
| Position bias | Continuous position interpolation (1–5 scale) instead of discrete buckets |

```
PMI = OPMI + DPMI

OPMI = Σ w(pos, stat) · clip(z_stat, -3.0, +3.0) × era_penalty(season)
DPMI = (w_stl·z_stl + w_blk·z_blk + w_drb·z_drb + w_pf·z_pf) × 0.72
CPMI = 1.50·z_ppg + 0.40·z_apg + 0.35·z_ts + 0.50·z_±  — clutch metric (last 5 min ±5 pts)
```

<div align="center">
<img src="assets/pmi-radar.png" width="450"/>
<br/>
<em>PMI component comparison: Jordan vs LeBron vs Curry</em>
</div>

<br/>

<div align="center">
<img src="assets/courtside-stats.png" width="550"/>
</div>

<div align="center">

| Regular Season | Playoffs |
|:-:|:-:|
| 🥇 Jordan **+10.96** | 🥇 LeBron **+13.54** |
| 🥈 LeBron **+10.81** | 🥈 Jordan **+11.99** |
| 🥉 Curry **+10.23** | 🥉 Jokić **+10.65** |

</div>

**Tech:** Python · Flask · React · TypeScript · scikit-learn · Tailwind CSS · NBA API · Basketball Reference

[![Courtside Repo](https://img.shields.io/badge/📊_Courtside-View_Repository-f59e0b?style=for-the-badge)](https://github.com/skerk001/court-vision-52)
[![Research Paper](https://img.shields.io/badge/📄_Research-PMI_Paper_(PDF)-3b82f6?style=for-the-badge)](https://github.com/skerk001/court-vision-52/blob/main/docs/PMI_Research_Paper.pdf)

---

### 📊 Other Projects

<table>
<tr>
<td width="50%" valign="top">

#### 🏥 Healthcare Outcomes Research
Statistical analysis across 50,000+ patients at Desert Oasis Healthcare. COPD cost-effectiveness study showing **$83.50 PMPM savings**. Regression-based hospital readmission analysis and atrial fibrillation care gap identification. Co-authored research presented at **ASHP 2024**.

`Python` `R` `SQL` `Regression` `NLP`

</td>
<td width="50%" valign="top">

#### 🔬 ML Cancer Prediction
Gene expression cancer classification using machine learning. Built predictive models on high-dimensional genomic data. Earlier work on **diabetic retinopathy classification** using computer vision approaches.

`scikit-learn` `Computer Vision` `Classification`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### ♟️ Chess Meme Tower Defense
A creative game combining chess strategy with tower defense mechanics and internet culture. Built as a fun side project exploring game development patterns.

`JavaScript` `Game Dev`

</td>
<td width="50%" valign="top">

#### 📈 Mathematical Finance
Academic foundation in stochastic processes, derivatives pricing, and quantitative analysis from UC Irvine's Mathematical Finance concentration. Applied to data-driven decision frameworks.

`Calculus` `Linear Algebra` `Probability` `Statistics`

</td>
</tr>
</table>

---

### 📈 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=skerk001&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=f59e0b&icon_color=3b82f6&text_color=c9d1d9" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=skerk001&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=f59e0b&text_color=c9d1d9" height="165"/>

</div>

---

<div align="center">

<img src="https://komarev.com/ghpvc/?username=skerk001&style=flat-square&color=f59e0b&label=Profile+Views" />

*"How do you compare a 1962 Wilt Chamberlain season to a 2024 Nikola Jokić season?*
*The same way — by measuring how far each deviated from their peers."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a365d,100:f59e0b&height=100&section=footer" width="100%"/>

</div>
