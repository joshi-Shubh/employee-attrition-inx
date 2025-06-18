# 🔥 Employee Attrition Prediction – INX Future Inc.

## 🏢 Business Case

INX Future Inc. is experiencing a decline in employee performance and an 8% drop in client satisfaction. The company wants to understand and reduce employee attrition without harming morale or employer branding.

This project leverages data science to:
- Predict employee attrition (whether an employee will leave)
- Identify key drivers contributing to attrition
- Recommend proactive retention strategies

---

## 📁 Project Contents

- `Employee_Attrition_INX.ipynb`: Complete analysis and model notebook
- `requirements.txt`: Required Python packages

---

## 📊 Dataset Overview

- Employee features: age, gender, education, department, years at company, job satisfaction, performance score, etc.
- **Target variable**: `Attrition` (Yes/No)

---

## 🧠 Techniques Used

- Exploratory Data Analysis (EDA)
- Feature Engineering
- Label Encoding / One-Hot Encoding
- Classification Models:
  - Logistic Regression
  - Random Forest
  - XGBoost
  - Decision Tree
- SHAP for explainability

---

## ✅ Results

- Best Model: **Random Forest** (or update with your actual best)
- Accuracy: **XX%**
- Top attrition drivers: job role, monthly income, satisfaction, years at company, etc.
- SHAP plots provide transparent insight for HR decision-making

---

## 🔧 Requirements

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
shap
