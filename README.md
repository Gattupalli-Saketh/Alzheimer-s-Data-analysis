# Alzheimer's Disease Prediction & Analysis  
**Keywords**: Alzheimer’s Disease, Machine Learning, Lifestyle Factors, Health Data, Feature Importance, Predictive Modeling, Data Analysis, Python  

---

## 📖 Project Overview  
This project explores how lifestyle and health factors affect Alzheimer’s disease diagnosis using data analysis and machine learning. We aim to find key influences like physical activity, diet, and sleep quality on Alzheimer’s risk.  

---

## 📂 Dataset Summary  
The dataset includes patient health, lifestyle, and cognitive features:  

- **Patient Info**: PatientID, Age, Gender, Ethnicity, EducationLevel, BMI  
- **Lifestyle**: Smoking, AlcoholConsumption, PhysicalActivity, DietQuality, SleepQuality  
- **Medical History**: FamilyHistoryAlzheimers, CardiovascularDisease, Diabetes, Depression, HeadInjury, Hypertension  
- **Vitals**: SystolicBP, DiastolicBP, Cholesterol (Total, LDL, HDL, Triglycerides)  
- **Cognitive**: MMSE, FunctionalAssessment, MemoryComplaints, BehavioralProblems, ADL, Confusion, Disorientation, PersonalityChanges, DifficultyCompletingTasks, Forgetfulness  
- **Target**: Diagnosis (Alzheimer’s or not)  
- **Other**: DoctorInCharge  

---

## 🎯 Goals  
- Understand how **physical activity**, **diet**, and **sleep quality** impact Alzheimer’s diagnosis.  
- Identify key non-cognitive factors influencing Alzheimer’s risk.  
- Build a predictive model for Alzheimer’s diagnosis.  

---

## 🔍 Data Analysis  
### 🧹 Data Preprocessing  
- Cleaned data, encoded categories, and normalized values.  

### 📊 Correlation Analysis  
- Checked relationships between features and Alzheimer’s diagnosis.  

### ✅ Statistical Test (Chi-Squared)  
- Tested **Family History of Alzheimer’s** vs. Diagnosis.  
- **Result**: P-Value ≈ 0.14 (no significant correlation at 95% confidence).  

---

## 🤖 Machine Learning Model  
### Logistic Regression Results  
| Metric                | Value  |  
|-----------------------|--------|  
| Accuracy              | 0.73   |  
| Precision (Class 0)   | 0.76   |  
| Recall (Class 0)      | 0.86   |  
| Precision (Class 1)   | 0.66   |  
| Recall (Class 1)      | 0.51   |  
| F1-Score (Class 0)    | 0.80   |  
| F1-Score (Class 1)    | 0.58   |  
| Macro Avg F1          | 0.69   |  
| Weighted Avg F1       | 0.72   |  

### Feature Importance (Non-Cognitive)  
- Removed cognitive features: Diagnosis, MMSE, ADL, FunctionalAssessment.  
- Trained a linear model and analyzed feature coefficients.  
- Visualized top features in a **horizontal bar chart**.  

**Purpose**: Highlight non-cognitive factors (e.g., lifestyle, medical history) driving Alzheimer’s predictions.  

---

## 📌 Key Findings  
- **Lifestyle matters**: Physical activity, diet, and sleep quality significantly influence Alzheimer’s risk.  
- **Family history**: No strong statistical link to diagnosis in this dataset.  
- **Machine learning**: Uncovered complex patterns in the data.  

---

## 🚀 Next Steps  
- Test advanced models: Random Forest, XGBoost, Neural Networks.  
- Use SHAP or LIME for better model explainability.  
- Expand dataset with longitudinal data if available.  

---

## 📊 Visuals  
- Feature importance bar chart.  
- Model performance graph.  

---

## 🛠️ Tools Used  
- **Python**: Pandas, NumPy, Scikit-Learn  
- **Visualization**: Matplotlib, Seaborn  
- **Motivation**: Fighting Alzheimer’s through data!  

---
