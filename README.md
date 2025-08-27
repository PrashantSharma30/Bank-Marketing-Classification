# 📊 Bank Marketing Classification – ML Prediction Project

![Python](https://img.shields.io/badge/Python-3.10-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3-orange)
![Status](https://img.shields.io/badge/Status-Active-success)

## 📌 Overview
This repository contains a **machine learning pipeline** that predicts whether a bank client will subscribe to a term deposit using the **UCI Bank Marketing Dataset**.  
We apply multiple classification models, compare their performances, and visualize key trends in client behavior.

---

## 🏗️ Tech Stack
- **Programming Language:** Python (v3.10+)
- **Data Analysis & EDA:** Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning:** scikit-learn, XGBoost, CatBoost, Decision Trees, Logistic Regression
- **Model Evaluation:** Accuracy, Confusion Matrix, Classification Report
- **Environment:** Jupyter Notebook
- **Version Control:** Git & GitHub

---

## 📂 Dataset Information
- **Source:** UCI Bank Marketing Dataset
- **Rows:** ~45,000
- **Features:** 16 (numeric + categorical)
- **Target:** `y` – Yes/No (term deposit subscription)

---

## ⚙️ Project Workflow
1. **Data Preprocessing**
   - Handle missing values
   - Encode categorical variables
   - Normalize numeric features
2. **EDA & Visualization**
   - Target distribution plot
   - Feature-wise bar charts (job, marital, education, etc.)
3. **Model Training**
   - Logistic Regression  
   - Decision Tree    
   - XGBoost
   - CatBoost
4. **Evaluation & Comparison**
   - Accuracy scores table
   - Confusion matrices
5. **Insights & Conclusion**

---

## 📊 Exploratory Data Analysis

### Correlation Mtrix Between Features and Target Variable
![Correlation Mtrix Between Features and Target Variable](images/Screenshot%202025-08-27%20193817.png)

### Education Category Distribution
![Education Distribution](images/images/Screenshot%202025-08-27%20193853.png)

### Marital Status Distribution
![Marital Status Distribution](images/images/Screenshot%202025-08-27%20193934.png)

---

## 📈 Model Performance

| Model                | Accuracy |
|----------------------|----------|
| Logistic Regression  | 89.12%   |
| Decision Tree        | 91.25%   |
| XGBoost              | 91.30%   |
| CatBoost             | 91.34%   |

---

## 💡 Insights
- Ensemble methods (CatBoost, XGBoost) outperform single models.
- **Top predictors:** `duration`, `poutcome`, `month`, `balance`.
- Clients contacted in **March, September, December** had higher subscription rates.
