# 🎮 Predict League of Legends Matches using Machine Learning

This repository provides machine learning models to **predict the outcome of League of Legends (LoL) matches**.  
The project explores different ML approaches such as **Logistic Regression** and **XGBoost**, combined with preprocessing and feature engineering to improve accuracy.

---

## 📂 Repository Structure

- predict-LOL-matches-using-ML/
  - Logistic_Regression_fillNaN(0).ipynb # Logistic Regression with missing values handling
  - Logistic_Regression_fillNaN(0)_without_optimization.ipynb
  - Logistic_Regression_fillNaN_by_algorithm.ipynb # Logistic Regression with algorithm-based imputation
  - XGboost.ipynb # XGBoost model for match prediction
  - draw.ipynb # Visualization & result plotting
  - result.csv # Prediction results
  - code/ # Source code scripts
  - raw_data/ # Original raw dataset
  - clean_data/ # Preprocessed dataset

---

## ⚙️ Features
- Preprocessing raw League of Legends match data (handling missing values, cleaning).
- Exploratory Data Analysis (EDA) and visualization.
- **Machine Learning models:**
  - Logistic Regression (with multiple strategies for NaN filling).
  - XGBoost for boosted decision trees.
- Model evaluation and comparison.
- Output predictions stored in `result.csv`.
