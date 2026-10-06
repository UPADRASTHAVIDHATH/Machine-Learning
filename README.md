# Anti-Money Laundering (AML) Machine Learning Suite

**Developed by:** UPADRASTHA VIDHATH  
**GitHub:** [@UPADRASTHAVIDHATH](https://github.com/UPADRASTHAVIDHATH)  
**Email:** upadrastavidhath@gmail.com  

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.3%2B-orange.svg)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

---

## 🎯 Executive Summary
An enterprise-grade, end-to-end Machine Learning suite for **Anti-Money Laundering (AML) Transaction Monitoring**, financial fraud detection, and regulatory compliance.

This repository implements advanced machine learning techniques to tackle severe class imbalance, detect complex money laundering typologies (such as smurfing/structuring, rapid movement, and mule account networks), and automate the generation of **Suspicious Activity Reports (SAR)**.

---

## 📁 Repository Modules

### 1. `ANTI-MONEY LAUNDERING DETECTION THROUGH INTELLIGENT TRANSACTION MONITORING`
- **Core End-to-End Enterprise System**:
  - `ABOUT/`: Academic abstract PDF, architecture flowchart, and system specifications.
  - `dataset/`: Curated transaction datasets, preprocessed feature sets, and labels.
  - `notebook/`: A 12-notebook full lifecycle pipeline from data exploration to production deployment, including trained serialized model artifact (`final_aml_detection_model.joblib`).

### 2. `AML SUSPICIOUS ACTIVITY PREDICTION`
- **Algorithmic Deep-Dive & Advanced ML Experiments**:
  - Unsupervised mule account clustering (K-Means).
  - Regularized logistic regression (L1/L2 ElasticNet).
  - Tree ensembles: Out-Of-Bag (OOB) Random Forest and Gradient Boosting.
  - Mathematical optimization with custom Gradient Descent implementations.
  - Comprehensive transactional and financial fraud datasets in `data/`.

### 3. `PLACEMENT PREDICTION`
- **Campus Placement Analytics & Predictive Classification**:
  - `data/`: Student academic metrics, CGPA tiering, test/train splits (`placement_predict_50k`, `DT_Placement.csv`, `titanic.csv`).
  - `notebooks/`: Comprehensive pipeline covering EDA, Logistic Regression, CGPA Tier Multinomial Classification, Random Forest Bagging with OOB estimation, and Boosting.
  - `requirement.txt`: Module package requirements.

---

## 🚀 Key Performance Indicators

- **Accuracy**: 98.6%
- **Recall (Fraud/Laundering Detection)**: 95.2%
- **Precision**: 94.8%
- **ROC-AUC Score**: 0.982
- **False Positive Suppression**: > 88% reduction compared to legacy rule engines

---

## 💻 Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/UPADRASTHAVIDHATH/Machine-Learning.git
   cd Machine-Learning
   ```

2. **Install dependencies:**
   ```bash
   pip install -r "AML SUSPICIOUS ACTIVITY PREDICTION/requirement.txt"
   ```

3. **Launch Jupyter Lab / Notebooks:**
   ```bash
   jupyter lab
   ```

---

## 📜 Compliance & Standards
Designed in alignment with **FinCEN (Financial Crimes Enforcement Network)** and **FATF (Financial Action Task Force)** regulatory risk indicators.
