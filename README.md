# 🏠 House Prices Prediction – Regression Project

This project predicts house sale prices using regression models based on the Kaggle competition ["House Prices - Advanced Regression Techniques"](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).

## 📌 Problem Statement
Build a machine learning model that predicts the final price of residential homes using a set of numerical and categorical features.

## 📊 Dataset
- Source: [Kaggle Dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)
- Training size: 1460 entries
- Target column: `SalePrice`

## 🧹 Preprocessing
- Selected top numerical features based on correlation.
- Handled missing values and outliers.
- Used `StandardScaler` where needed.
- Dropped high-cardinality categorical features to avoid data explosion.

## 🧠 Models Used
- Linear Regression
- Random Forest Regressor (with GridSearchCV tuning)
- XGBoost Regressor

## 📈 Evaluation Metrics
- Root Mean Squared Error (RMSE)
- R² Score
- 5-Fold Cross Validation

## ✅ Final Performance
- **Best Model**: Tuned Random Forest
- **R² Score**: ~0.87
- **RMSE**: ~23,000
- Visualizations included:
  - Actual vs Predicted Prices
  - Residuals Plot
  - Feature Importance

## 📂 Files
| File | Description |
|------|-------------|
| `notebook.ipynb` | Main notebook with code, visuals, and evaluation |
| `train.csv` | Dataset used for training |
| `README.md` | Project description |

## 🚀 Future Work
- Feature engineering (e.g. total bathrooms, age)
- Try log-transforming `SalePrice`
- Use full dataset with one-hot encoding
- Try LightGBM or CatBoost

---

👨‍💻 **Author:** [Mohamed Henaish]  
📅 **Date:** June 2025

