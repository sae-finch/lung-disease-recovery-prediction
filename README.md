# 🫁 Lung Disease Recovery Prediction 🫁

This project aims to predict whether patients with lung disease will recover based on various patient attributes using machine learning models.

## 👀 Project Overview 👀
This study explores the prediction of lung disease recovery using machine learning models.
The dataset contains **4900 samples** with faetures such as age, gender, smoking status, lung capacity, disease type, treatment type, hospital visits.
Four model were tested: **Logistic Regression, Random Forest, XGBoost, and LightGBM**.

## 📊 Dataset Description 📊
- **Number of Samples:** 4900
- **Features:**
  - Age
  - Gender
  - Smoking Status
  - Lung Capacity
  - Disease Type
  - Treatment Type
  - Hospital Visits
- **Target Variable:** Recovery Status (Recovered / Not Recovered)

## 🔍 Methods & Models 🔍
- Data preprocessing:
  - Categorical variables: **Label Encoding**
  - Missing values: **Median (numerical features), Mode(categorical features)**
- Models tested:
  - **Logistic Regression**
  - **Random Forest**
  - **XGBoost**
  - **LightGBM**

## 📈 Results Summary 📈
- The models achieved low predictive performance, with accuracy around **0.5**.
- **Random Forest** had the highest accuracy (**0.5276**).
- Feature importance analysis showed:
  - **Lung Capacity** had the most important feature for **Random Forest** and **LightGBM**.
  - **Age** and **Hospital Visits** were the next most important factors.
  - **XGBoost** distributed feature importance more evenly, with **Gender** as the most important feature.
- Weak correlations between features suggest that the current dataset may not fully capture the patterns necessary for accurate prediction.

## 🚀 Future Work 🚀
- **Feature Engineering:**
  - Include **medication type, disease severity, symptoms, and complications** to improve predictive power.
- **Model Improvement:**
  - Try ensemble methods or deep learning models.
 
## 📚 References 📚
- Data source: **https://www.kaggle.com/datasets/samikshadalvi/lungs-diseases-dataset**
- Machine Learning libraries: **scikit-learn, XGBoost, LightGBM**
