# CREDIT-CARD-FRAUD-DETECTION-USING-MACHINE-LEARNING

A machine learning project that detects fraudulent credit card transactions using Python, Logistic Regression, SMOTE, and Scikit-learn. The project covers data preprocessing, feature scaling, class balancing, model training, prediction, and performance evaluation.

# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning. The dataset is highly imbalanced, so **SMOTE (Synthetic Minority Oversampling Technique)** is used to balance the classes before training a **Logistic Regression** model. The project demonstrates a complete machine learning workflow, including data preprocessing, feature scaling, model training, prediction, and performance evaluation.

---

## 🎯 Objective

* Detect fraudulent credit card transactions.
  
* Handle class imbalance using SMOTE.
  
* Build a reliable fraud detection model.
  
* Evaluate model performance using standard classification metrics.

---

## 📂 Dataset

* **Dataset:** Credit Card Fraud Detection
  
* **Source:** Kaggle (Machine Learning Group - ULB)
  
* **Rows:** 284,807
  
* **Columns:** 31
  
* **Target Variable:** `Class`

  * `0` → Genuine Transaction
    
  * `1` → Fraudulent Transaction

---

## 🛠️ Technologies Used

* Python
  
* Pandas
  
* Scikit-learn
  
* Imbalanced-learn (SMOTE)

---

## 📚 Python Libraries

* pandas
  
* StandardScaler
  
* train_test_split
  
* SMOTE
  
* LogisticRegression
  
* accuracy_score
  
* classification_report

---

## 🔄 Project Workflow

1. Import Required Libraries
   
3. Load Dataset
   
5. Explore Dataset
   
7. Check Missing Values
   
9. Analyze Class Distribution
    
11. Separate Features and Target
    
13. Standardize Features
    
15. Balance Dataset using SMOTE
    
17. Split Training and Testing Data
    
19. Train Logistic Regression Model
    
21. Predict Test Data
    
23. Evaluate Model Performance
    
25. Generate Classification Report

---

## 📊 Results

* Successfully handled class imbalance using SMOTE.
  
* Built a Logistic Regression model for fraud detection.
  
* Evaluated the model using Accuracy, Precision, Recall, and F1-Score.
  
* Achieved strong performance in identifying fraudulent transactions.

---

## 📈 Key Insights

* The original dataset was highly imbalanced.
  
* SMOTE significantly improved class balance.
  
* Feature scaling improved model performance.
  
* Logistic Regression effectively detected fraudulent transactions.

---


```

## 🚀 Future Improvements

* Random Forest Classifier

* XGBoost Classifier

* LightGBM

* ROC Curve & AUC Analysis

* Confusion Matrix Visualization

* Hyperparameter Tuning



