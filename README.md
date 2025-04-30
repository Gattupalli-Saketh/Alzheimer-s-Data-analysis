🧠 Alzheimer's Dataset Analysis & Prediction
Welcome to my project on Alzheimer's Disease Prediction & Feature Impact Analysis. This project dives deep into exploring how lifestyle and health factors influence Alzheimer's diagnosis, using data-driven insights and machine learning techniques.

📂 Dataset Overview
This dataset contains a variety of features related to patient health, lifestyle, and cognitive status:

🧾 Features:

PatientID, Age, Gender, Ethnicity, EducationLevel, BMI

Smoking, AlcoholConsumption, PhysicalActivity 🚶

DietQuality 🥗, SleepQuality 😴

FamilyHistoryAlzheimers 🧬, CardiovascularDisease ❤️, Diabetes, Depression

HeadInjury, Hypertension, SystolicBP, DiastolicBP

Cholesterol (Total, LDL, HDL, Triglycerides)

MMSE, FunctionalAssessment, MemoryComplaints, BehavioralProblems

ADL, Confusion, Disorientation, PersonalityChanges

DifficultyCompletingTasks, Forgetfulness

Diagnosis (Target), DoctorInCharge

🎯 Objective
This project aims to uncover which factors truly impact Alzheimer's diagnosis, focusing especially on lifestyle choices:

❓ Key Questions:
How does physical activity impact diagnosis? 🚶‍♂️

How does diet impact diagnosis? 🥦

How does sleep quality impact diagnosis? 🛏️

🔍 Exploratory Data Analysis & Statistical Testing
🔄 Data Preprocessing: Cleaned, encoded, and normalized.

📊 Correlation Analysis: Explored relationships between features and diagnosis.

✅ Chi-Squared Test:

Test between Family History of Alzheimer's and Diagnosis

Result: P-Value ≈ 0.14

🧠 Insight: No statistically significant correlation at 95% confidence level.

🤖 Machine Learning Approach
🧪 Logistic Regression Model Results:

Metric	Value
Accuracy	0.73
Precision (Class 0)	0.76
Recall (Class 0)	0.86
Precision (Class 1)	0.66
Recall (Class 1)	0.51
F1-Score (Class 0)	0.80
F1-Score (Class 1)	0.58
🔍 Macro Avg F1: 0.69
⚖️ Weighted Avg F1: 0.72

🧠 Feature Importance without Cognitive Features
To gain clearer insights into non-cognitive influences on diagnosis, I removed:

'Diagnosis', 'MMSE', 'ADL', 'FunctionalAssessment'

Then, I trained a Linear Model and analyzed feature coefficients:

📈 What I Did:

Extracted coefficients

Calculated absolute impact

Sorted and visualized in a horizontal bar chart 📊

🎯 Purpose: To identify which non-cognitive features strongly influence the model’s prediction of Alzheimer's Disease.

📌 Conclusion
🔍 Takeaways:

Lifestyle features such as physical activity, diet, and sleep quality play an important role.

Family history surprisingly didn’t have a strong statistical correlation on its own.

Machine Learning helped reveal subtle, complex relationships in the data.

📌 Next Steps
✅ Try advanced models like Random Forest, XGBoost, or Neural Networks
✅ Perform SHAP or LIME explainability
✅ Expand dataset and include longitudinal tracking if available

📷 Sample Visuals
📊 Feature importance chart
📉 Model performance graph
(Consider adding here if available)

👨‍💻 Made With
Python 🐍

Pandas, NumPy, Scikit-Learn

Matplotlib, Seaborn

💡 Curiosity and the desire to fight Alzheimer’s!
