# 🛡️ Credit Card Fraud Detection System

A machine learning-based fraud detection system using Random Forest and SMOTE to identify fraudulent credit card transactions with high accuracy.

---

## 📌 Project Overview

This project builds a classification model to detect fraudulent transactions using the [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).  
Due to heavy class imbalance, we use SMOTE for balancing and train a Random Forest classifier to achieve high recall and precision.

---

## 🧪 Features

- Handles class imbalance using SMOTE
- Trains a Random Forest classification model
- Evaluates with Accuracy, Precision, Recall, and F1-Score
- Displays Confusion Matrix for visual evaluation
- Command-line interface (CLI) for testing custom transaction inputs

---

## 📁 Dataset

- Download from: [Kaggle - Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- File: `creditcard.csv`; is too large, so not possible to add here.
- Columns: 30 anonymized features + `Time`, `Amount`, and `Class` (0 = Legitimate, 1 = Fraudulent)

---

## ⚙️ Installation & Run

Clone the repository and install dependencies:

```bash
git clone https://github.com/Khansa05/fraud-detection-system.git
cd fraud-detection-system
pip install -r requirements.txt

