# ❤️ Heart Disease Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on predicting the presence of heart disease using **Machine Learning classification algorithms**. The dataset contains health and clinical information about patients, such as age, blood pressure, cholesterol, chest pain type, maximum heart rate, and other heart-related indicators.

The main objective is to develop a model that can effectively identify patients who are likely to have heart disease. Since missing a positive case can be critical in a medical prediction problem, **Recall for the positive class is given particular importance** during model evaluation.

## 🎯 Objectives

* Explore and understand the heart disease dataset.
* Perform **Exploratory Data Analysis (EDA)** to identify patterns, distributions, and relationships.
* Clean and preprocess the data.
* Handle missing values and outliers.
* Encode categorical variables.
* Transform skewed numerical features.
* Apply feature scaling where required.
* Build and tune multiple classification models.
* Compare model performance using **Precision, Recall, and F1-Score**.
* Identify a suitable model for predicting heart disease.

## 📊 Dataset

The dataset contains **303 patient records and 14 columns**.

Some important features include:

* `age` – Age of the patient
* `sex` – Gender
* `cp` – Chest pain type
* `trestbps` – Resting blood pressure
* `chol` – Serum cholesterol
* `fbs` – Fasting blood sugar
* `restecg` – Resting ECG results
* `thalach` – Maximum heart rate achieved
* `exang` – Exercise-induced angina
* `oldpeak` – ST depression induced by exercise
* `slope` – Slope of the peak exercise ST segment
* `ca` – Number of major vessels
* `thal` – Thalium stress test result
* `target` – Heart disease status

### Target Variable

```text
0 → No heart disease
1 → Presence of heart disease
```

## 🔍 Exploratory Data Analysis

EDA was performed to understand:

* Numerical feature distributions
* Categorical feature distributions
* Feature relationships
* Relationships between features and the target variable
* Potential outliers
* Skewness in numerical features

## 🛠️ Data Preprocessing

The following preprocessing steps were performed:

1. **Irrelevant feature removal**
2. **Missing value checking and treatment**
3. **Outlier treatment**
4. **Categorical variable encoding**
5. **Feature scaling**
6. **Transformation of skewed features**

Scaling was particularly important for models such as **KNN and SVM**, where differences in feature scales can affect model performance.

## 🤖 Machine Learning Models

The following classification algorithms were implemented:

* 🌳 **Decision Tree**
* 🌲 **Random Forest**
* 📍 **K-Nearest Neighbors (KNN)**
* ⚙️ **Support Vector Machine (SVM)**

Hyperparameter tuning was also performed to find better model configurations.

## 📈 Model Evaluation

The models were evaluated using:

* **Precision**
* **Recall**
* **F1-Score**
* **Accuracy**

### Why Recall is Important

In this project, recall for **Class 1 (patients with heart disease)** is particularly important.

A false negative means:

> The model predicts that a patient does not have heart disease when the patient actually has it.

Therefore, the project prioritizes identifying as many actual positive cases as possible.

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Understanding
   ↓
Exploratory Data Analysis
   ↓
Data Preprocessing
   ↓
Train-Test Split
   ↓
Model Building
   ↓
Hyperparameter Tuning
   ↓
Model Evaluation
   ↓
Model Comparison
   ↓
Final Model Selection
```

## 💡 Key Learning Outcomes

Through this project, I gained practical experience in:

* Data exploration and visualization
* Data preprocessing
* Handling categorical and numerical features
* Feature scaling and transformation
* Classification algorithms
* Hyperparameter tuning
* Model evaluation
* Comparing multiple machine learning models
* Understanding why different evaluation metrics are important

## ⚠️ Disclaimer

This project is developed for **educational and machine learning practice purposes**. It should not be considered a substitute for professional medical diagnosis or clinical decision-making.
