# ⚽ TalentScope_AI

## 📌 Project Overview

This project uses **machine learning techniques** to predict whether a **young football player** has the potential to become a **high-value or top-performing player** in the future.  
Using real-world data from the **FIFA dataset**, the system can assist **scouting departments** in identifying promising talents early.

---

## 🎯 Purpose

The goal is to build a **classification model** that predicts if a player (usually under a certain age, e.g., 21) is likely to reach a **high potential score**. This can help clubs or agencies:

- Filter scouting targets from large datasets
- Reduce manual screening time
- Highlight talents that may be undervalued

> ✅ Focused on predictive scouting — **no manual ratings or subjective input required**

---

## 📁 Dataset

- **Source**: FIFA Player Dataset (public or scraped version)
- **Filtered**: Only players under a certain age (e.g., 21 years old)
- **Target variable**: `HighPotential` (1 = high future potential, 0 = not high)
- **Features used** (examples):
  - Technical stats: passing, dribbling, finishing, etc.
  - Physical attributes: speed, stamina, strength
  - Player traits: preferred foot, position, work rate

---

## 🧠 Machine Learning Pipeline

1. **Data Cleaning & Preprocessing**
   - Handle missing values
   - Normalize / scale numeric features
   - Encode categorical features

2. **Feature Engineering**
   - Create target label (`HighPotential`)
   - Select top correlated features
   - Optionally perform dimensionality reduction (e.g., PCA)

3. **Modeling**
   - Algorithms tested:
     - Logistic Regression
     - Random Forest
     - XGBoost
     - SVM
   - Cross-validation and hyperparameter tuning included

4. **Evaluation**
   - Accuracy, Precision, Recall, F1-Score
   - Confusion Matrix
   - ROC Curve / AUC
