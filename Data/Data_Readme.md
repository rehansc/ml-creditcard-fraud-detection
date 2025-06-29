# 📁 Data Folder

This folder is intended to store:

- ✅ Sample or test datasets (e.g. `creditcard_sample.csv`)
- ✅ Processed outputs (e.g. `creditcard_balanced.parquet`)
- ✅ Metadata, schema, or notes for reproducibility

---

## ⚠️ Full Dataset Not Included

The full **Kaggle Credit Card Fraud Detection** dataset is **not included** in this repository due to licensing and size constraints.

You can download the original dataset here:  
👉 https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

After downloading, you can upload it to your Databricks workspace using:  
`/FileStore/tables/creditcard.csv`

---

## 📌 Notes

- The final balanced dataset (`creditcard_balanced.parquet`) was generated using **random undersampling** of the majority class (non-fraud).
- You may choose to experiment with **SMOTE** or **over-sampling** alternatives.

---

## 📎 File Descriptions

| File                         | Description                                     |
|------------------------------|-------------------------------------------------|
| `creditcard_sample.csv`      | Optional small test file (not included)         |
| `creditcard_balanced.parquet`| Cleaned & balanced dataset used in model training |
| `README.md`                  | This documentation file                         |

---

Feel free to modify this folder as you expand the project (e.g., add features, more datasets, metadata, or logs).

