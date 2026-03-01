# Skin-Disorder-Prediction
Skin Disorder Prediction using Machine Learning with EDA and model comparison. An end-to-end ML project for analyzing medical data and predicting skin diseases.


🔹 Short Description (GitHub Repo Description)

**Skin Disorder Prediction using Machine Learning with EDA and model comparison.**
An end-to-end ML project for analyzing medical data and predicting skin diseases.


# 🩺 Skin Disorder Prediction

> Machine Learning Project | Classification | Medical Data Analysis



## 📌 Project Overview

This project focuses on predicting different types of skin disorders using machine learning techniques. The workflow includes data preprocessing, exploratory data analysis (EDA), feature engineering, model building, and evaluation.

The goal is to build an accurate classification model that can assist in early detection of skin diseases.


## 🎯 Objectives

* Perform detailed **Exploratory Data Analysis (EDA)**
* Handle missing values and data cleaning
* Apply feature scaling and encoding
* Train multiple classification models
* Compare model performance
* Select the best-performing model

## 📂 Dataset Information

* File: `dataset.xls`
* Contains medical features related to skin conditions
* Target variable: Skin Disorder Type / Class

## 🔎 Exploratory Data Analysis (EDA)

Performed analysis on:

* Class distribution
* Feature distribution
* Correlation heatmap
* Outlier detection
* Feature importance

📊 Key Insights:

* Some features show strong correlation with specific skin disorders.
* Data imbalance was analyzed and handled.
* Feature scaling improved model performance.

## ⚙️ Data Preprocessing

* Handling missing values
* Label Encoding / Ordinal Encoding
* Feature Scaling (StandardScaler / MinMaxScaler)
* Train-Test Split

## 🤖 Machine Learning Models Implemented

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* XGBoost (if implemented)

## 📈 Model Evaluation Metrics

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Cross Validation
* Hyperparameter Tuning (GridSearchCV)

## 🏆 Best Model

After comparing multiple models:

* **Random Forest / XGBoost** achieved the highest accuracy.
* Tree-based models performed better due to handling complex feature relationships.

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Jupyter Notebook

## 📌 Project Structure


📦 Skin-Disorder-Prediction
 ┣ 📜 dataset.xls
 ┣ 📜 Skin Disorder Prediction.ipynb
 ┣ 📜 README.md
 ┗ 📜 requirements.txt


## 🔮 Future Improvements

* Deploy using Streamlit / Flask
* Add medical dataset balancing (SMOTE)
* Improve hyperparameter tuning
* Create web-based diagnostic interface



