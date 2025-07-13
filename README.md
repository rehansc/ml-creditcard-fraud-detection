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

## 📊 Dataset Overview

- **Transactions**: 284,807  
- **Fraud Cases**: 492 (≈ 0.17%)  
- **Features**: `V1` to `V28` (anonymized via PCA), `Time`, and `Amount`  
- The original dataset is highly imbalanced and requires special care during training.

---

## 🔧 Techniques Used

### Data Preprocessing
- Handled class imbalance using **undersampling**
- Converted raw CSV to **Parquet** for Spark compatibility

### Exploratory Data Analysis (EDA)
- Visualized fraud distribution over time
- Detected outliers using boxplots
- Analyzed feature correlation heatmaps

### Model Training
- Trained **Logistic Regression** (baseline)
- Trained **Random Forest Classifier** (best performing)

### Model Evaluation
- Plotted **ROC Curve** and calculated AUC
- Built **Confusion Matrix**
- Calculated **Precision, Recall, F1 Score**

---

## 🚀 Deployment Plan (Summary)

Outlined in `5_deployment_notes.md`, including:

- 🗓️ Batch Scoring via scheduled Databricks Jobs
- ⚡ Real-Time Scoring using MLflow model serving (REST API)
- 📊 BI Integration with Power BI or Tableau via Delta tables
- 🧪 Monitoring for precision-recall drift over time

---

## 🧠 Future Improvements

- Integrate **SMOTE** or ensemble balancing
- Use **Gradient-Boosted Trees (GBTClassifier)**
- Deploy as a live **MLflow REST API**
- Build a **fraud alert dashboard**

---

## 📌 Author & Motivation

This project is part of my hands-on ML/AI learning journey as I transition into the field professionally. I'm particularly interested in applying ML in **fintech** and **healthcare** domains.

Feel free to fork, reuse, or reach out with questions!

> 🔗 Connect with me on [LinkedIn]([https://www.linkedin.com/in/YOUR-PROFILE](https://www.linkedin.com/in/rehanchaudhry/))  
> https://www.linkedin.com/in/rehanchaudhry/

---

## 📎 Reproduce This Project

You can run this on any Databricks workspace (Community or Pro).  
Dataset: [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

---

## 📁 Folder Structure

- ml-creditcard-fraud-detection/
  - data/ # Dataset and derived files
  - notebooks/ # Jupyter/Databricks notebooks
    - 1_data_preprocessing.ipynb
    - 2_eda.ipynb
    - 3_model_training.ipynb
    - 4_model_evaluation.ipynb
    - 5_deployment_notes.md # Strategy for production deployment
  - README.md # Project overview and summary

---

## 📬 Contact

Built by [Rehan Chaudhry](https://github.com/rehansc) — exploring the intersection of **ML + Markets**.  
Open to feedback, forks, and collaboration!

