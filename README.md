## 📌 Overview
This project investigates the **impact of hospital management practices for hyperglycemia** on patient readmission rates using **machine learning models**.  
It applies various **data preprocessing, feature extraction, and predictive modeling techniques** to discover patterns and relationships in hospital readmission data.

---

## 🎯 Objectives
- Identify factors in hospital management systems that influence **readmission rates** for hyperglycemia patients.
- Apply **machine learning models** to predict readmissions.
- Address **class imbalance** in healthcare datasets.

---

## 📂 Dataset
- **Source:** [UC Irvine Machine Learning Repository – Diabetes 130-US hospitals dataset](https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008)
- **Size:** 101,766 records of diabetic patients from 130 U.S. hospitals.
- **Features:** 50 attributes including demographics, diagnoses, lab results, and medications.
- **Target Variable:** Readmission status (`<30 days`, `>30 days`, `No`).

---

## 🛠 Methodology
- **Data Preprocessing:**
  - Cleaning missing values.
  - Encoding categorical features.
  - Normalizing numerical variables.
- **Feature Engineering:**
  - Feature selection to retain significant predictors.
  - Transformation of diagnosis codes.
- **Modeling Approach:**
  - Decision Trees
  - Random Forest
  - Logistic Regression
  - Support Vector Machines
- **Class Imbalance Handling:** SMOTE (Synthetic Minority Over-sampling Technique)
- **Hyperparameter Tuning:** GridSearchCV and Cross-validation.

---

## 📊 Experimental Results
- **Best Performing Model:** Random Forest
- **Performance Metrics:** Accuracy, Precision, Recall, F1-score, ROC-AUC
- Models using **balanced datasets** via SMOTE improved recall significantly for minority classes.
- **Top Predictors:** Number of inpatient visits, insulin usage, length of stay.

---

## 📈 Key Insights
- Effective **hospital management strategies** can lower readmission rates for hyperglycemia patients.
- **Machine learning** can help identify high-risk patients early.
- Balancing the dataset plays a crucial role in improving prediction for rare readmissions.

---

## 📚 Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/username/hyperglycemia-readmission-analysis.git
   cd hyperglycemia-readmission-analysis
