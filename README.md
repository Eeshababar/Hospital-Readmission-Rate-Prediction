# Hospital Readmission Rate Prediction for Diabetes Patients

## 📌 Overview  
This project predicts **hospital readmission rates** for diabetes patients using machine learning techniques.  
It includes **data preprocessing, exploratory data analysis, feature engineering, and predictive modeling** to classify patients at high risk of readmission.  

---

## 📂 Dataset  
This project uses the **Diabetes 130-US Hospitals for Years 1999–2008** dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008).  
It contains over **10 years of clinical records** from 130 U.S. hospitals and integrated delivery networks, focusing on inpatients with diabetes.  

**Key facts:**  
- **Instances:** 101,766  
- **Features:** 50 (including demographics, diagnoses, lab results, medications, and hospital stay details)  
- **Target:** Readmission status (within 30 days, after 30 days, or no readmission)  
- **License:** CC BY 4.0 (attribution required)  
- **Citation:**  
  > Strack, B., DeShazo, J.P., Gennings, C., et al. (2014). *Diabetes 130-US Hospitals for Years 1999–2008*. UCI Machine Learning Repository. https://doi.org/10.24432/C5230J  

---

## 🧾 Description  
The workflow involves:  
- Loading and preprocessing the dataset.  
- Performing **exploratory data analysis (EDA)** to understand feature distributions.  
- Applying **feature extraction** and **encoding** for categorical variables.  
- Handling class imbalance using **SMOTE**.  
- Using **GridSearchCV** and **cross-validation** to optimize model parameters.  
- Evaluating models with **accuracy** and **ROC-AUC** scores.  

---

