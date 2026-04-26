# 💳 Loan Approval Prediction & Model Interpretability

This project builds a machine learning pipeline to predict loan approval outcomes and analyze feature importance using interpretable techniques.

It combines ensemble learning (Random Forest), permutation-based feature importance, and decision tree modeling for explainability.

---

##  Objective

- Predict whether a loan will be approved or not
- Identify the most important factors influencing decisions
- Build interpretable models for transparency

---

##  Dataset

- Source: Kaggle Loan Approval Dataset
- Contains demographic, financial, and loan-related features

Example features:
- Income
- Loan interest rate
- Loan intent
- Credit history
- Previous loan defaults

---

##  Methodology

### 1. Data Preprocessing
- Loaded dataset using Pandas
- Encoded categorical variables using Label Encoding
- Split data into training and validation sets

---

### 2. Model 1 – Random Forest Classifier
- Trained a Random Forest model for loan approval classification
- Used ensemble learning for improved performance and robustness

---

### 3. Feature Importance (Permutation Importance)
- Applied permutation importance using ELI5
- Measured how shuffling each feature impacts model performance

 Top important features identified:
- Previous loan defaults
- Loan interest rate
- Loan percent income
- Home ownership
- Income

---

### 4. Model 2 – Decision Tree (Interpretability)
- Trained a Decision Tree model using top features
- Provides human-readable decision logic
- Helps understand model decision pathways

---

## 📈 Results

- Identified key financial indicators affecting loan approval
- Demonstrated how feature importance can guide model simplification
- Built an interpretable model using selected features

---

## 🛠️ Tech Stack

- Python
- Pandas
- Scikit-learn
- ELI5 (Permutation Importance)

---
