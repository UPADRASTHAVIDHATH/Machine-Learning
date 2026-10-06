# ANTI-MONEY LAUNDERING DETECTION THROUGH INTELLIGENT TRANSACTION MONITORING

**Author:** UPADRASTHA VIDHATH  
**Contact:** [upadrastavidhath@gmail.com](mailto:upadrastavidhath@gmail.com) | [GitHub Profile](https://github.com/UPADRASTHAVIDHATH)  
**Domain:** Financial Crime Compliance, Anti-Money Laundering (AML), Machine Learning  

---

## 📌 Project Overview
Money laundering introduces severe systemic risks to global banking systems. Conventional rule-based Transaction Monitoring Systems (TMS) generate over 95% false positives, overburdening compliance teams while failing to detect sophisticated laundering schemes like structuring, smurfing, and pass-through mule accounts.

This project delivers an **Intelligent Machine Learning-driven AML Framework** designed to detect illicit financial transactions with high recall and precision, providing automated risk scoring and Suspicious Activity Report (SAR) generation.

---

## 🏗️ Architecture & Modules
The architecture comprises a five-stage intelligent pipeline:
1. **Transaction Ingestion**: Ingesting core banking transaction streams, payment gateways, and wire transfers.
2. **Feature Engineering**: Calculating transaction velocity, origin/destination balance discrepancies, structuring flags, and customer risk tiers.
3. **Machine Learning Classifier**: Cost-sensitive ensemble models (Random Forest, Gradient Boosting, Logistic Regression) optimized for imbalanced financial data.
4. **Risk Scoring Engine**: Mapping continuous model probabilities into four actionable operational risk tiers (Low, Medium, High, Critical).
5. **SAR Auto-Filer**: Automated generation of regulatory Suspicious Activity Reports for compliance analysts.

---

## 📊 Dataset Description
- **Total Transactions**: 25,000+
- **Features**: `step`, `type`, `amount`, `nameOrig`, `oldbalanceOrg`, `newbalanceOrig`, `nameDest`, `oldbalanceDest`, `newbalanceDest`, `isFlaggedFraud`, `customerRiskScore`, `countryRiskIndex`, `transactionVelocity`, `isStructuring`, `isLaundering`
- **Class Imbalance**: ~2.32% positive laundering cases (reflecting realistic industry distributions).

---

## 🏆 Model Performance Benchmark

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Logistic Regression** | 94.8% | 82.1% | 88.5% | 85.2% | 0.941 |
| **Decision Tree** | 96.2% | 87.4% | 89.1% | 88.2% | 0.925 |
| **Gradient Boosting** | 97.9% | 92.3% | 93.8% | 93.0% | 0.968 |
| **Optimized Random Forest (Final)** | **98.6%** | **94.8%** | **95.2%** | **95.0%** | **0.982** |

---

## 📂 Repository Structure
```
├── ABOUT/
│   ├── ABSTRACT.pdf              # Academic paper and project abstract
│   ├── LITERATURE REVIEW.png     # Pipeline architecture diagram
│   └── README.md                 # Project documentation
├── dataset/
│   ├── AML_Complete_Transaction_Dataset.csv
│   ├── X_train_processed.csv
│   ├── X_test_processed.csv
│   ├── y_train.csv
│   └── y_test.csv
└── notebook/
    ├── 01_Dataset_Description.ipynb
    ├── 02_Data_Preprocessing.ipynb
    ├── 03_Exploratory_Data_Analysis.ipynb
    ├── 04_Feature_Engineering_and_Selection.ipynb
    ├── 05_Model_Building_and_Training.ipynb
    ├── 06_Hyperparameter_Tuning.ipynb
    ├── 07_Model_Evaluation.ipynb
    ├── 08_Model_Comparison.ipynb
    ├── 09_Results_and_Discussion.ipynb
    ├── 10_Final_Prediction_Demonstration.ipynb
    ├── Exploratory Data Analysis and Data Preprocessing of AML Dataset.ipynb
    ├── Anti_Money_Laundering_Detection_Final.ipynb
    ├── final_aml_detection_model.joblib
    ├── model_comparison_baseline.csv
    └── model_comparison_final.csv
```
