<div align="center">

# Hi, I'm Mohamad Badra 👋

### Data Science Graduate · Applied Machine Learning · Neuroimaging · NLP

B.Sc. Mathematics — Data Science, Saint Joseph University of Beirut (USJ)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-mohamad--badra-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/mohamad-badra)
[![Email](https://img.shields.io/badge/Email-mohamad.badra.au%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:mohamad.badra.au@gmail.com)
[![GPA](https://img.shields.io/badge/GPA-3.7%2F4.0-1B2A5E?style=flat-square)](#)
[![Location](https://img.shields.io/badge/Based%20in-Tripoli%2C%20Lebanon-B5894A?style=flat-square)](#)

</div>

<br>

I build end-to-end data science projects spanning data preprocessing, feature engineering, model development, evaluation, interpretability, and deployment — with a focus on **healthcare AI**, **neuroimaging**, and **NLP**. Projects emphasize documented pipelines, reproducible code, and leakage-aware evaluation.

Currently preparing for postgraduate study in Data Science and Machine Learning.

<br>

## 💼 Professional Experience

**Intern — TELEPATY & VIVA INTERNATIONAL**
`May 2025 – Jul 2026` · Tripoli, North Lebanon

Gained exposure to software and web/mobile application development, Data Science, Machine Learning, and AI workflows, with introductory familiarity with databases, digital platform integration, FinTech/electronic payment systems, and technology project lifecycles.

<br>

## 🧠 Featured Project

<div align="center">

### Parkinson's Disease Classification from Resting-State fMRI
*Final Year Project · Supervised by Dr. Michel Abboud, Saint Joseph University of Beirut*

</div>

End-to-end machine learning pipeline for Parkinson's disease classification using resting-state fMRI from 55 subjects (33 PD, 22 healthy controls).

- 🧬 Preprocessed fMRI data using fMRIPrep and Docker — skull stripping, motion correction, slice-timing correction, MNI152 spatial normalization
- 🔗 Extracted mean BOLD signals from 116 AAL brain regions and computed Pearson functional connectivity → **6,670 connectivity features per subject**
- ⚙️ Compared 10 classifiers using variance filtering, robust scaling, SMOTE, mutual-information feature selection, PCA, and cross-validation
- 🌐 Built **NeuroVision**, a Flask web app integrating the feature-extraction pipeline and ensemble model for PD probability predictions and downloadable PDF reports

<div align="center">

| Metric | Result |
|---|---|
| **F1-score** (linear SVM) | 0.875 |
| **ROC-AUC** (linear SVM) | 0.857 |
| **PD Recall** (soft-voting ensemble) | 1.00 |

</div>

`Python` `scikit-learn` `fMRIPrep` `Docker` `Nilearn` `ANTs` `imbalanced-learn` `Flask` `SQLite` `ReportLab` `FSLeyes`

[**→ View Repository**](https://github.com/MohamadBadra20)

<br>

## 📂 Other Projects

<table>
<tr>
<td width="50%" valign="top">

### 🗣️ CyberShield
**Multi-Class Cyberbullying Detection**

NLP system classifying social media text into six cyberbullying categories (~47,700 labeled tweets). Compared TF-IDF classical models against a fine-tuned RoBERTa transformer.

**Result:** 85.0% accuracy · 0.844 weighted F1
Applied SHAP/LIME for interpretability; deployed via FastAPI.

`Python` `PyTorch` `Transformers` `NLTK` `SHAP` `LIME` `FastAPI`

[Repository →](https://github.com/MohamadBadra20)

</td>
<td width="50%" valign="top">

### 📊 Customer Lifetime Value Analytics
**Segmentation & Prediction**

End-to-end pipeline on 1.05M+ e-commerce transactions. RFM analysis, BG/NBD and Gamma-Gamma models for 6-month CLV estimation, K-Means segmentation, and Apriori rule mining.

**Result:** Silhouette 0.530 · 81.0% accuracy · 0.812 F1-macro
Tuned Random Forest for customer value-tier prediction.

`Python` `pandas` `scikit-learn` `Lifetimes` `mlxtend` `Seaborn`

[Repository →](https://github.com/MohamadBadra20)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📈 Bank Marketing Prediction
**Predictive Modeling**

*(Add 2–3 bullets here: dataset size, approach, and headline metric, in the same style as the other projects.)*

[Repository →](https://github.com/MohamadBadra20)

</td>
<td width="50%" valign="top">

</td>
</tr>
</table>

<br>

## 🛠️ Skills

<div align="center">

**Programming**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Data Science & ML**
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Deep Learning & NLP**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/🤗%20Transformers-FFD21E?style=flat-square)
![NLTK](https://img.shields.io/badge/NLTK-3776AB?style=flat-square)

**Neuroimaging**
![fMRIPrep](https://img.shields.io/badge/fMRIPrep-1B2A5E?style=flat-square)
![Nilearn](https://img.shields.io/badge/Nilearn-B5894A?style=flat-square)
![ANTs](https://img.shields.io/badge/ANTs-1B2A5E?style=flat-square)

**Deployment**
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Tools**
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

</div>

<br>

## 🔬 Research Interests

- Healthcare AI and medical machine learning
- Neuroimaging and fMRI analysis
- Applied machine learning
- Natural language processing
- Interpretable and reliable machine learning

<br>

## 🎓 Education

**Saint Joseph University of Beirut (USJ)**
B.Sc. Mathematics — Option in Data Science
GPA: 3.7/4.0 · Dean's Honor List: Semesters 4, 5 & 6

**Final Year Project:** Parkinson's Disease Classification from Resting-State fMRI
**Supervisor:** Dr. Michel Abboud

<br>

<div align="center">

## 📬 Get in Touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mohamad-badra)
[![Gmail](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohamad.badra.au@gmail.com)

</div>
