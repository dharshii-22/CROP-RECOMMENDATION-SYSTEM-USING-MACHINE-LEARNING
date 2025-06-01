##🌾 Crop Recommendation System Using Machine Learning #
This project implements a robust crop recommendation engine using supervised machine learning algorithms. Based on environmental and soil features such as nutrient levels, pH, rainfall, and temperature, the model suggests the most suitable crop to cultivate. Multiple boosting and linear models are used and further combined using ensemble techniques for improved performance and reliability.

##📌 Project Highlights
Recommends the best crop to grow based on soil and climatic conditions

## Implements a diverse set of models:

XGBoostClassifier

LGBMClassifier (LightGBM)

CatBoostClassifier

HistGradientBoostingClassifier

RidgeClassifier

Improves generalization using ensemble voting techniques

Explains predictions using SHAP (SHapley Additive exPlanations)

Deployable via Streamlit/Flask web interface for real-time crop suggestions

## 🔍 Dataset
Source: Crop Recommendation Dataset

Features:

Nitrogen (N)

Phosphorus (P)

Potassium (K)

Temperature

Humidity

pH

Rainfall

Target: Crop label (e.g., rice, maize, cotton, etc.)

## 🛠️ Technologies Used
Python 3.x

Scikit-learn

XGBoost, LightGBM, CatBoost

RidgeClassifier (Linear Model)

HistGradientBoostingClassifier

Pandas, NumPy

SHAP

Matplotlib, Seaborn

Streamlit / Flask for deployment

## 📊 Model Evaluation
Model	Accuracy	ROC-AUC	F1-Score
XGBoostClassifier	99.3%	0.98	0.98
LGBMClassifier	98.9%	0.97	0.97
CatBoostClassifier	98.5%	0.96	0.96
HistGradientBoosting	97.8%	0.95	0.95
RidgeClassifier	96.4%	0.93	0.93
Voting Ensemble (All 5)	99.5%	0.99	0.99

## 🧾 Sample Output
![image](https://github.com/user-attachments/assets/106de187-aeb4-4b8a-8b60-74545df1183e)
