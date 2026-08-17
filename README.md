# Mohamad Badra

**Data Science Graduate | Applied Machine Learning | AI | Neuroimaging**

B.Sc. Mathematics — Data Science, Saint Joseph University of Beirut (USJ)

I am a Data Science graduate interested in applied machine learning, healthcare AI, neuroimaging, and natural language processing. I build end-to-end data science projects spanning data preprocessing, feature engineering, model development, evaluation, interpretability, and deployment. Projects emphasize documented pipelines, reproducible code, and leakage-aware evaluation.

My main project is a Parkinson's disease classification pipeline using resting-state fMRI, complemented by projects in NLP, customer analytics, and predictive modeling.

I am currently preparing for postgraduate study in Data Science and Machine Learning.

---

## Professional Experience

**Intern — TELEPATY & VIVA INTERNATIONAL**
*May 2025 – Jul 2026 · Tripoli, North Lebanon*

Gained exposure to software and web/mobile application development, Data Science, Machine Learning, and AI workflows, with introductory familiarity with databases, digital platform integration, FinTech/electronic payment systems, and technology project lifecycles.

---

## Featured Project

### 🧠 Parkinson's Disease Classification from Resting-State fMRI
*Final Year Project · Supervised by Dr. Michel Abboud, Saint Joseph University of Beirut*

End-to-end machine learning pipeline for Parkinson's disease classification using resting-state fMRI from 55 subjects (33 PD, 22 healthy controls).

- Preprocessed fMRI data using fMRIPrep and Docker (skull stripping, motion correction, slice-timing correction, MNI152 spatial normalization)
- Extracted mean BOLD signals from 116 AAL brain regions and computed Pearson functional connectivity, generating 6,670 connectivity features per subject
- Compared 10 classifiers using variance filtering, robust scaling, SMOTE, mutual-information feature selection, PCA, and cross-validation
- **Held-out test set:** F1 = 0.875, ROC-AUC = 0.857 (linear SVM); PD recall = 1.00 for the soft-voting ensemble
- Built **NeuroVision**, a Flask web app integrating the feature-extraction pipeline and ensemble model to generate PD probability predictions and downloadable PDF reports

**Technologies:** Python, scikit-learn, fMRIPrep, Docker, Nilearn, ANTs, imbalanced-learn, Flask, SQLite, ReportLab, FSLeyes

[Repository →](https://github.com/MohamadBadra20)

---

## Other Projects

### 🗣️ CyberShield — Multi-Class Cyberbullying Detection
NLP system classifying social media text into six cyberbullying categories (~47,700 labeled tweets). Compared TF-IDF classical models against a fine-tuned RoBERTa transformer (85.0% accuracy, 0.844 weighted F1). Applied SHAP/LIME for interpretability; deployed via FastAPI.
**Technologies:** Python, scikit-learn, PyTorch, Transformers, NLTK, SHAP, LIME, FastAPI
[Repository →](https://github.com/MohamadBadra20)

### 📊 Customer Lifetime Value Analytics
End-to-end customer analytics pipeline on 1.05M+ e-commerce transactions. RFM analysis, BG/NBD and Gamma-Gamma models for 6-month CLV estimation, K-Means segmentation (silhouette = 0.530), and a tuned Random Forest classifier for value-tier prediction (81.0% accuracy, 0.812 F1-macro). Apriori association-rule mining for product bundling insights.
**Technologies:** Python, pandas, NumPy, scikit-learn, Lifetimes, mlxtend, Matplotlib, Seaborn
[Repository →](https://github.com/MohamadBadra20)

### 📈 Bank Marketing Prediction
*(Add a short technical description here — this project isn't detailed in your CV, so I've left it as a placeholder.)*
[Repository →](https://github.com/MohamadBadra20)

---

## Skills

**Programming:** Python, C++, JavaScript
**Data Science & Machine Learning:** scikit-learn, imbalanced-learn, feature engineering, feature selection, dimensionality reduction, classification, regression, clustering, model evaluation, cross-validation
**Deep Learning & NLP:** PyTorch, Hugging Face Transformers, RoBERTa, NLTK, SHAP, LIME
**Neuroimaging:** fMRIPrep, Nilearn, ANTs, BIDS, fMRI analysis, functional connectivity
**Deployment:** Flask, FastAPI, Docker
**Data Analysis & Visualization:** pandas, NumPy, Matplotlib, Seaborn
**Tools:** Jupyter, Git, GitHub, SQLite

---

## Research Interests

- Healthcare AI and medical machine learning
- Neuroimaging and fMRI analysis
- Applied machine learning
- Natural language processing
- Interpretable and reliable machine learning

---

## Education

**Saint Joseph University of Beirut (USJ)**
B.Sc. Mathematics — Option in Data Science
GPA: 3.7/4.0 · Dean's Honor List: Semesters 4, 5 & 6

**Final Year Project:** Parkinson's Disease Classification from Resting-State fMRI
**Supervisor:** Dr. Michel Abboud

---

## Contact

[LinkedIn](https://linkedin.com/in/mohamad-badra) · mohamad.badra.au@gmail.com
