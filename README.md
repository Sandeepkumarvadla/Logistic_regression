# Logistic Regression – Cancer Classification

## 📌 Project Overview
This project implements a **Logistic Regression** machine learning model to classify whether a person is **cancerous or non-cancerous** based on blood parameters.

The model is built as part of my **internship learning project** to understand supervised machine learning and classification techniques.

---

## 🧠 Problem Statement
Early detection of cancer is critical.  
This project aims to classify patients using blood test values:
- **WBC (White Blood Cells)**
- **RBC (Red Blood Cells)**
- **HMG (Hemoglobin)**

---

## 📊 Dataset
- File: `blood_dataset_100_rows_wbc_rbc_hmg.csv`
- Rows: 100
- Features:
  - WBC
  - RBC
  - HMG
- Target:
  - Cancer (1)
  - Non-Cancer (0)

---

## ⚙️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## 🧮 Model Used
- Logistic Regression
- Train-Test Split

---

## 📈 Results
- The model successfully classifies cancer and non-cancer cases
- Predictions are made on test data

---

## ▶️ How to Run the Project
1. Clone the repository
```bash
git clone https://github.com/Sandeepkumarvadla/Logistic_regression.git

## Install required libraries
pip install pandas numpy matplotlib scikit-learn

##Run the Python file
python logistic_regression_cancer_classification.py
