# 🩸 Blood Donation Eligibility Prediction

## 📌 Project Overview

This project focuses on predicting whether a person is eligible to donate blood using Machine Learning. The model analyzes past donation behavior and classifies donors as **eligible (1)** or **not eligible (0)**.

The goal is to help blood banks and healthcare organizations identify potential donors efficiently.

---

## 🎯 Objectives

* Predict donor eligibility using historical data
* Improve decision-making in blood donation systems
* Apply machine learning concepts to a real-world problem

---

## 📊 Dataset Information

The dataset contains information about blood donors based on the **RFMT model**:

* **Recency (R)** → Time since last donation
* **Frequency (F)** → Total number of donations
* **Monetary (M)** → Total blood donated
* **Time (T)** → Time since first donation

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib & Seaborn
* Scikit-learn

---

## 🔄 Project Workflow

### 1. Data Loading

* Imported dataset using Pandas
* Checked shape and preview

### 2. Data Cleaning

* Handled missing values using median
* Ensured dataset consistency

### 3. Outlier Treatment

* Used IQR (Interquartile Range) method
* Applied clipping instead of removing data

### 4. Exploratory Data Analysis (EDA)

* Visualized data using count plots and heatmaps
* Identified relationships between features

### 5. Feature Scaling

* Applied StandardScaler
* Ensured all features are on the same scale

### 6. Train-Test Split

* Split dataset into 80% training and 20% testing

### 7. Model Building

* Used **Logistic Regression** for binary classification

### 8. Model Evaluation

* Accuracy Score
* Confusion Matrix
* Classification Report

---

## 📈 Results

The model successfully predicts donor eligibility with good accuracy.
It can be used as a decision-support tool for identifying potential blood donors.

---

## 🔍 Key Concepts Used

* Machine Learning Classification
* Logistic Regression
* Feature Scaling
* Outlier Detection (IQR Method)
* Data Visualization

---

## 💡 Future Improvements

* Use advanced models like Random Forest or XGBoost
* Deploy as a web application
* Integrate real-time donor data

---

## 🏥 Real-World Application

This system can help:

* Blood banks identify eligible donors
* Hospitals manage blood supply efficiently
* Improve emergency response systems

---

## 👨‍💻 Author

* Dherya Varshney
* KIET Group of Institutions, Ghaziabad

---

## 📌 Conclusion

This project demonstrates how machine learning can be used to solve real-world healthcare problems. By predicting donor eligibility, we can improve blood donation systems and save lives.

---
