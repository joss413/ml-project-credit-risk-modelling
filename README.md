# 💳 Credit Risk Prediction System (Classification)

![Streamlit](https://img.shields.io/badge/App-Streamlit-FF4B4B?style=for-the-badge)
![ML](https://img.shields.io/badge/ML-XGBoost%2BRidge-FF6B00?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge)

## 📋 Project Overview
A production-ready machine learning system for credit risk prediction that classifies loan applicants as default or non-default.
The system uses statistical and machine learning models and evaluates performance using confusion matrix, ROC-AUC, KS statistic, and decile analysis.

This project demonstrates how financial risk modeling and explainable AI can be applied in real-world banking and fintech applications.

---

## 🚀 Live Application

<img src="images/credit_risk_model_layout.png" alt="credit_risk_model_layout" width="400">

🔗 **Try the live app:**  
[credit-risk-modelling-pro](https://credit-risk-modelling-pro.streamlit.app/)

---

## 📊 Model Performance

### 1️⃣ Classification Task
- **Problem Type**: Binary Classification  
- **Target Variable**: Loan Default (1 = Default, 0 = Non-default)
 

### 2️⃣ Models Used
- Logistic Regression 
- Random Forest Classifier
- XGBoost Classifier
  
### 3️⃣ Evaluation Metrics
-Accuracy
- Precision, Recall, F1-score
- ROC-AUC
- KS Statistic
- Decile Analysis 
---

## 🧩 Confusion Matrix
<img src="images/Confusion_matrix.png" alt="Confusion Matrix" width="400">

The confusion matrix shows model predictions for defaulters and non-defaulters and highlights classification errors.

## 📈 Feature Importance

<img src="images/Feature_Importatnce.png" alt="Feature Importance" width="400">

Key features influencing credit risk prediction:

- Credit Utilization Ratio
- Delinquency Ratio
- Average Spend
- Residence Type
- Loan Purpose
- Loan Tenure

This helps explain which financial behaviors contribute most to default risk.

---

## 📊 Model Evaluation & KS Analysis
<img src="images/Model_Evaluation.png" alt="Model Evaluation" width="400">

- KS statistic measures model separation power between defaulters and non-defaulters
- Decile table shows concentration of defaulters in high-risk groups
- Higher KS values indicate strong discriminatory performance
---

## ⚙️ Installation

1. Clone & Install: 

```bash
git clone https://github.com/yourusername/ml-project-credit-risk-modelling.git
cd ml-project-credit-risk-modelling
pip install -r requirements.txt

```
2. **Run the app:**:   
```bash
streamlit run main.py
```

## 🎮 Key Features

- End-to-End Credit Risk Modeling Pipeline
- Data Cleaning & Feature Engineering
- Class Imbalance Handling
- Multiple ML Classification Models
- Confusion Matrix & ROC Curve Evaluation
- KS Statistic & Decile Table (Banking Industry Standard)
- Feature Importance for Model Explainability

## 📁 Project Structure

```bash
health-insurance-predictor/
│
├──  main.py                 # Streamlit application
│──  prediction_helper.py    # ML prediction logic
│   
│
├── artifacts/
│   ├── models/                 # Trained ML models
│
├── images/
│   └── screenshots/            # UI & result images

│
├── requirements.txt            # Project dependencies
├── README.md                   # Project documentation
└── .gitignore
```
👨‍💻 Author

Yoseph Negash

📧 yosephn22@gmail.com

📅 2026
