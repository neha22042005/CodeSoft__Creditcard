# 💳 Credit Card Fraud Detection

## 📌 Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning. It uses a Logistic Regression model to classify transactions as either genuine or fraudulent.

## 🎯 Objective

* Classify transactions as **Fraud (1)** or **Genuine (0)**
* Handle imbalanced dataset effectively

## ⚙️ Tech Stack

* Python
* Pandas
* Scikit-learn

## 🔄 Steps

1. Load dataset
2. Preprocess data (normalize `Amount`)
3. Perform train-test split
4. Train model using Logistic Regression (`class_weight='balanced'`)
5. Evaluate model performance

## 📊 Result

* Achieved accuracy of approximately **99%**
* Good recall for detecting fraudulent transactions

## 📌 Conclusion

The model performs well in identifying fraudulent transactions despite data imbalance. It demonstrates the effectiveness of Logistic Regression with proper preprocessing and class balancing techniques.
