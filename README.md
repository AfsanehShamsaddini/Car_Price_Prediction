# 🚗 Car Price Prediction

This project aims to predict the **selling price of used cars** based on their features using machine learning techniques.

## 📌 Objective
The main goal is to build a predictive model that helps buyers and sellers estimate fair car prices. This has applications in dealerships, online platforms, and personal use.

## 📊 Dataset
- Source: [Kaggle Vehicle Dataset from CarDekho](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho)
- Features include:
  - Year of manufacture
  - Fuel type
  - Transmission
  - Ownership type
  - Kilometers driven
  - Selling price

## ⚙️ Methodology

### 🔧 Preprocessing & Feature Engineering
- Converted `year` to `car_age`
- Applied one-hot encoding to categorical features
- Removed irrelevant or redundant columns

### 📈 Exploratory Data Analysis
- Visualized correlations and distributions using `seaborn` and `matplotlib`
- Identified key features affecting price

### 🧪 Hypothesis Testing
- Used ANOVA to test if fuel type significantly affects car price
- Result: Fuel type **does** affect price (p < 0.05)

### 📉 Modeling
- Linear Regression as baseline
- Lasso Regression with hyperparameter tuning to prevent overfitting

### 📐 Evaluation
- Metrics: MAE, MSE, RMSE, R²
- Visual inspection of prediction vs actual plots

## ✅ Conclusion
- Simple linear models can provide reasonable accuracy
- Lasso helps reduce overfitting and feature noise
- Future work may involve ensemble methods or deep learning

## 📚 Libraries Used
- Python 3.x
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `scipy`

## 📌 Author
Afsaneh Shamsaddini

