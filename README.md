# Superstore Churn Analysis

This project performs **end-to-end customer churn analysis** on a retail Superstore dataset and builds a predictive model to identify churn drivers.

## 📊 Project Overview
- Dataset: ~10k transactions, 22 features (orders, customers, products, sales, profit, churn labels).
- Goal: Predict customer churn (binary classification) and understand key drivers.
- Approach: Exploratory Data Analysis (EDA), Feature Engineering, Machine Learning models.

## 🔎 Steps Performed
1. **Exploratory Data Analysis (EDA)**
   - Churn distribution across segments, regions, discounts.
   - Profitability vs churn relationship.
   - Visualizations: churn rates, scatter plots, box plots.

2. **Feature Engineering**
   - Aggregated to **customer-level features** (RFM-style: recency, frequency, monetary).
   - Derived features: total sales, total profit, avg/max discount, monthly order frequency.
   - Category sales mix (Furniture, Office Supplies, Technology).
   - Mode of customer segment & region.

3. **Modeling**
   - **Logistic Regression** with scaling.
   - **Random Forest** (tree-based ensemble).
   - Balanced class weights for imbalanced churn data.

4. **Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC.
   - Confusion Matrices.
   - ROC & Precision-Recall Curves.
   - Feature Importance & Coefficients.

5. **Artifacts**
   - Engineered customer-level dataset: `superstore_customer_features.csv`
   - Notebook: `Superstore_Churn_Analysis.ipynb`

## 📈 Key Insights
- High **discount levels** correlate with churned customers.
- Customers with **low recency** and **low order frequency** are more likely to churn.
- Specific **product categories** and **regions** show higher churn rates.

## 🚀 Tools Used
- Python (pandas, numpy, matplotlib, scikit-learn)
- Jupyter Notebook
- Machine Learning (Logistic Regression, Random Forest)



