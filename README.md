# 🫁 Lung Cancer Risk Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-green)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20MacOS-lightgrey)

A machine learning based system that predicts lung cancer risk using survey-based clinical and behavioral data.  
The project applies multiple ML algorithms, handles class imbalance, and explains predictions using SHAP.

---

## 📌 Project Overview

Early detection of lung cancer significantly improves survival rates.  
This project builds and evaluates multiple machine learning classification models to predict whether a person is likely to have lung cancer based on symptoms and lifestyle factors.

---

## 🚀 Models Used

- Logistic Regression  
- Support Vector Classifier (SVC)  
- Random Forest  
- Gradient Boosting  
- XGBoost  

---

## 🧠 Key Features

- Data cleaning and duplicate removal  
- Label encoding of categorical features  
- Feature engineering (interaction feature creation)  
- Class imbalance handling using SMOTE  
- Standardization using StandardScaler  
- ROC curve comparison  
- Feature importance analysis  
- SHAP explainability  

---

## 📊 Results

- Achieved ~97% accuracy across models  
- ROC-AUC scores close to 1.0  
- Random Forest and XGBoost showed best performance  

---

## 🗂 Dataset

Survey Lung Cancer Dataset (Kaggle)

---

## 🛠 Technologies Used

- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Imbalanced-learn (SMOTE)  
- Matplotlib, Seaborn  
- SHAP  

---

## ▶ How to Run

### 1. Clone Repository
git clone https://github.com/Jegan2003/lung-cancer-risk-prediction-ml.git

cd lung-cancer-risk-prediction-ml

### 2. Install Dependencies
pip install -r requirements.txt


### 3. Run Project
python Src/Lung cancer project.py

---

## 📈 Outputs

- Correlation Heatmap  
- ROC Curves  
- Confusion Matrices  
- Feature Importance Plot  
- SHAP Summary Plot  

---

## 📷 Sample Outputs

![Heatmap](images/heatmap.png)
![ROC Curve](images/roc_curve.png)
![Feature Importance](images/feature_importance.png)
![SHAP](images/shap_summary.png)

---

## 👨‍💻 Author

Jegan Kamalnath  
MSc Cybersecurity Threat Intelligence & Forensics, University of Salford  
BE Computer Science and Engineering, Sathyabama Institute of Science and Technology  

---

⭐ If you found this project useful, give it a star!
