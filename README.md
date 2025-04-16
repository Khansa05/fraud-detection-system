# 🛡️ Credit Card Fraud Detection System

A machine learning-based fraud detection system using Random Forest and SMOTE to identify fraudulent credit card transactions with high accuracy.

---

## 📌 Project Overview

This project builds a classification model to detect fraudulent transactions using the [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). Due to heavy class imbalance, we use SMOTE for balancing and train a Random Forest classifier to achieve high recall and precision.

---

## 🧪 Features

- Handles class imbalance with SMOTE
- Trains a Random Forest model
- Evaluates using Accuracy, Precision, Recall, F1-Score
- Displays Confusion Matrix
- CLI-based testing interface for predicting custom transactions

---

## 📁 Dataset

- Download from: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
- File: `creditcard.csv`
- Contains 31 columns including `Time`, `Amount`, and `Class` (0 = Legitimate, 1 = Fraudulent)

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Khansa05/fraud-detection-system.git
cd fraud-detection-system
pip install -r requirements.txt


