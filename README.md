# 💳 Credit Card Fraud Detection (Machine Learning Project)

This project applies machine learning techniques to detect fraudulent credit card transactions using the [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). Built entirely in **PySpark + Databricks**, this project simulates a real-world fraud analytics pipeline, including preprocessing, EDA, model training, evaluation, and deployment planning.

---

## 🧠 Project Highlights

- ✅ Loaded, cleaned, and balanced a highly imbalanced dataset (0.17% fraud rate)
- 📊 Performed exploratory data analysis on anonymized PCA features
- ⚙️ Trained multiple classifiers (Logistic Regression, Random Forest)
- 🧪 Achieved high evaluation metrics:
  - **AUC**: 0.9859 (Random Forest)
  - **Precision**: 0.9691
  - **Recall**: 0.9973
  - **F1 Score**: 0.9725
- 🚀 Outlined real-world deployment strategies (batch and real-time)

---

## 📁 Folder Structure

# Credit Card Fraud Detection (ML Project)

This project uses machine learning techniques to detect fraudulent credit card transactions using the [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

## Folder Structure

- ml-creditcard-fraud-detection/
  - data/
    -## 📊 Dataset Overview
    - Transactions: 284,807
    - Fraud Cases: 492 (≈ 0.17%)
    - Features: `V1` to `V28` (anonymized via PCA), `Time`, and `Amount`

The original dataset is highly imbalanced and requires special care during training. 
  - notebooks/                  <!-- Jupyter/Databricks notebooks -->
    - 1_data_preprocessing.ipynb
    - 2_eda.ipynb
    - 3_model_training.ipynb
    - 4_model_evaluation.ipynb
  - 5_deployment_notes.md      <!-- Notes on deployment options -->
  - README.md
