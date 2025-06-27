# 🧠 Credit Risk Classification Model

This project focuses on developing a supervised machine learning model to classify loan applicants into credit risk tiers (P1–P4) based on structured financial and behavioral data.

## 📌 Objective

To assist financial institutions in evaluating creditworthiness by predicting approval categories, thereby reducing manual effort and improving decision accuracy.

---

## 🛠️ Tech Stack

- **Language:**: Python  
- **Libraries:**: Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn  
- **Tools:**: Jupyter Notebook, PyInstaller  
- **Deployment:**: `.exe` application for scoring Excel inputs

---

## 📊 Dataset

- **Source:**: Proprietary / Case Study Excel files  
- **Features:**: Includes demographic, financial behavior, and credit history information  
- **Target Variable:** `Approved_Flag` — categories: P1, P2, P3, P4

---

## 🔍 Key Steps

1. **Data Cleaning**
   - Handled missing values represented as `-99999`
   - Removed high-null columns
2. **Feature Engineering**
   - Chi-square test for categorical variables
   - ANOVA & VIF for numerical selection
   - One-hot and ordinal encoding
3. **Model Building**
   - XGBoost Classifier (best performance)
   - Compared with Random Forest, Decision Tree
4. **Evaluation**
   - Accuracy: ~79%
   - Precision, Recall, F1-Score per class
5. **Deployment**
   - Final model packaged as `.exe` using PyInstaller for non-technical use

---

## 📈 Results

- Model achieved **~79% accuracy** on unseen data.
- Balanced performance across all risk classes with special attention to minority class (P3).
- Deployed tool enables fast scoring on Excel files without code interaction.

---


