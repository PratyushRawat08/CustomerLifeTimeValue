# 📊 Customer Lifetime Value (LTV) Prediction

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

---
## 📄 Abstract
Predicting Customer Lifetime Value (LTV) helps businesses focus their marketing strategies and maximize profits.This project focuses on predicting the Customer Lifetime Value (LTV) using customer purchase behavior data. By applying regression models and customer segmentation, it supports targeted marketing strategies for businesses.I built machine learning models to predict LTV using purchase behavior, followed by customer segmentation for targeted marketing campaigns.

---
- ## 🛠 Tools & Technologies Used
- **Programming:** Python (Pandas, NumPy, Matplotlib, Seaborn)
- **Machine Learning Models:** 
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - Gradient Boosting Regressor
  - XGBoost Regressor (Optional)
- **Data Handling:** Excel
- **Visualization:** Seaborn, Matplotlib

---

## 🔥 Project Workflow

1. **Import Libraries** 📚  
2. **Load and Clean Data** 🧹  
   - Removed null `Customer ID`s
   - Excluded canceled invoices
   - Created `TotalPrice` field
3. **Feature Engineering** 🏗️  
   - Calculated Recency, Frequency, AOV (Average Order Value), and LTV
4. **Train-Test Split** 🔍  
5. **Model Training and Evaluation** 🧠  
   - Metrics: MAE (Mean Absolute Error) and RMSE (Root Mean Squared Error)
6. **Model Comparison** ⚖️  
7. **Customer Segmentation** 🎯  
   - Segments: Low, Medium, High LTV
8. **Export Final Predictions** 💾  
9. **Visualization** 📈  
   - Customer segments and feature distributions

---

## 🔥 Steps Involved in Building the Project
1. **Import Libraries:** Load essential Python libraries for data manipulation, modeling, and visualization.
2. **Load and Prepare Data:** Read the dataset, remove missing Customer IDs, exclude canceled invoices, and create a `TotalPrice` feature.
3. **Feature Engineering:** Calculate Recency, Frequency, Monetary (LTV), and Average Order Value (AOV) for each customer.
4. **Train-Test Split:** Split the data into training and testing sets for model evaluation.
5. **Model Training & Evaluation:** Train models including Linear Regression, Decision Tree, Random Forest, Gradient Boosting, and XGBoost (if available).
6. **Model Comparison:** Evaluate each model using MAE and RMSE metrics.
7. **Customer Segmentation:** Segment customers into Low, Medium, and High LTV categories based on predicted values.
8. **Export Results:** Save the final LTV predictions and customer segments to a CSV file.
9. **Visualization:** Generate plots to understand the distribution of LTV predictions and customer segments.

## 📊 Visualizations
- Boxplots comparing customer segments (Low, Medium, High) based on LTV
- Distribution plots for Recency, Frequency, and AOV
- Scatterplots highlighting relationships between features and LTV
- Recommendation: Log-scaled y-axis to better visualize mid-range LTVs.

## 🧠 Learning Outcome
Working on this project enhanced my skills in:
- **Data Cleaning:** Handling outliers, missing values, and noisy data.
- **Feature Engineering:** Selecting impactful features like Recency, Frequency, AOV.
- **Model Evaluation:** Comparing multiple regression models using MAE and RMSE.
- **Customer Segmentation:** Applying predictive analytics for business strategy.
---

> _"The dataset contained outliers and key features that directly affected LTV. Data cleaning and feature selection improved model performance and gave me deeper insights into data-driven decision making."_

---

## ✅ Conclusion
This project highlights the critical role of data quality and smart feature engineering in building reliable machine learning models.  
The predictive insights from customer LTV estimation can empower businesses to optimize marketing investments and customer retention strategies.

---

## 🚀 Future Improvements
- **Hyperparameter tuning** for boosting model accuracy.
- **Advanced outlier detection** using IQR or Isolation Forest.
- **Add more features** like customer demographics for richer models.
- **Deploy model** via a simple API or dashboard.

---

# ✨ Thank you for visiting my project! ✨

---

Would you also like me to give you a ready-to-copy folder structure (like `/data`, `/notebooks`, `/outputs`) for organizing this project perfectly for GitHub? 🚀  
It’ll make your repo look even more professional! 🎯
