# 🏡 House Price Prediction (XGBoost + Stacking)

This project builds a machine-learning model to predict house prices using the popular **Kaggle House Prices dataset**.  
The main model is a **Stacking Regressor** combining:

- XGBoost Regressor  
- Ridge Regression  
- Linear Regression (final estimator)

---

## 📌 What This Project Includes
- Loading and exploring the dataset  
- Checking and filling missing values  
- Removing and capping outliers  
- Correlation analysis  
- Simple visualisations (scatter, histograms, heatmaps)  
- Feature engineering  
- One-Hot Encoding  
- Training the stacked model  
- Saving predictions as `sample_submission.csv`

---

## 📂 Key Features
- ⭐ Clean preprocessing pipeline  
- 🔧 Custom engineered features  
- 📊 Improved distribution of SalePrice using log transform  
- 🚀 XGBoost tuned with Optuna  
- 🧠 Model stacking for higher accuracy  

---

## 🛠️ Tech Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-Learn  
- XGBoost  
- SciPy  

---
