# Superstore Sales Profitability Analysis & Prediction

A data mining project analyzing the Superstore dataset to predict profitability and derive actionable business insights.

## 📌 Project Overview
This project analyzes a retail superstore dataset (9,994 records) to:
- Predict profit using regression models
- Identify key drivers of profitability
- Provide data-driven business recommendations
- Achieved **99% prediction accuracy (R²)** with tuned Gradient Boosting

## 🗂 Dataset
**Source:** [Kaggle Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)  
**Features:** 20 attributes including:
- Sales
- Quantity
- Discount
- Product Category
- Region
- Order Date

## 🛠 Key Features
- **Data Preprocessing**: Outlier handling, feature engineering (profit margin, order duration), and scaling
- **Exploratory Analysis**: 8+ visualizations (trends, correlations, category performance)
- **Model Comparison**: Linear Regression, SVR, Random Forest, Gradient Boosting
- **Hyperparameter Tuning**: Optimized models using RandomizedSearchCV
- **Business Insights**: Actionable recommendations for pricing, discounts, and inventory

## ⚙️ Installation
1. Clone repo:
   ```bash
   git clone https://github.com/vinuvii/Superstore-Profit-Analysis.git
   ```
2. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```
**Dependencies**: pandas, numpy, scikit-learn, matplotlib, seaborn, jupyter

## 🚀 Usage
1. Run Jupyter notebook:
   ```bash
   jupyter notebook Superstore_Profit_Analysis.ipynb
   ```
2. Execution flow:
   - Data preprocessing & cleaning
   - Exploratory Data Analysis (EDA)
   - Model training/evaluation
   - Hyperparameter tuning
   - Business insights generation

## 📊 Results
| Model | R² Score | MAE | RMSE |
|-------|----------|-----|------|
| Gradient Boosting (Tuned) | 0.9993 | 0.33 | 0.75 |
| Random Forest (Tuned) | 0.9407 | 5.06 | 7.20 |

## 💡 Business Recommendations
1. Implement dynamic pricing strategies
2. Optimize discount thresholds for bulk purchases
3. Prioritize high-margin Technology products
4. Negotiate better shipping rates
5. Develop weekend promotion campaigns

