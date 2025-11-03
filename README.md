# 🧠 Alzheimer Disease Diagnosis - ML

This project applies supervised Machine Learning models to support the triage of patients with a possible Alzheimer’s diagnosis, using structured clinical data.

## 🔍 Objective
Train and compare classification models (Logistic Regression, Decision Tree, and Random Forest) to predict the `Diagnosis` variable, indicating whether a patient shows signs of Alzheimer’s disease.

## ⚙️ Technologies
- Python 3.x  
- Google Colab  
- Pandas, NumPy  
- Scikit-Learn  
- Matplotlib, Seaborn

## 🚀 Execution
1. Open the notebook directly in **Google Colab**.  
2. Run all cells in order — the code automatically downloads the Kaggle dataset and performs data exploration, preprocessing, and model training.  
3. Review the generated metrics and visualizations at the end of execution.

## 📊 Results

| Model | Accuracy | F1-score |
|:------|:---------:|:--------:|
| **Random Forest** | **0.95** | **0.93** |
| Decision Tree | 0.92 | 0.88 |
| Logistic Regression | 0.85 | 0.78 |
| Baseline (Dummy) | 0.55 | 0.35 |

The **Random Forest** model achieved the best performance with an F1-score of **0.93**, showing strong predictive power and robust generalization.

## ⚠️ Disclaimer
The dataset used in this project originates from a public source and may include curated or synthetic data.  
Although this implementation is primarily educational, the resulting model demonstrates **production-level potential** when integrated into a broader healthcare system capable of:
- Collecting structured patient inputs (e.g., age, BMI, memory complaints, behavioral indicators);  
- Translating user responses into validated numerical features;  
- Applying domain-specific calibration, monitoring, and continuous evaluation.

In such a setup, the model could function as a **clinical decision-support component**, helping identify patients who may require further neurological assessment.  
However, it should **not operate autonomously** and must always be supervised by qualified healthcare professionals, following medical ethics and data governance standards.

