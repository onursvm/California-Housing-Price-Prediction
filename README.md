# California Housing Price Prediction

This project focuses on predicting house prices in California based on census data, using various regression models to understand the factors affecting real estate values.

## 🎯 Objective
To develop a high-performance regression model that predicts median house values by analyzing features such as location, income level, and housing physical attributes.

## 🛠️ Technical Process
* **Data Preprocessing:** Implemented Mean Imputation for missing values and used `StandardScaler` for feature standardization to improve model convergence.
* **Regression Algorithms:** Implemented and compared **Linear Regression**, **Random Forest Regressor**, and **Gradient Boosting**.
* **Performance Metrics:** Evaluated models using **$R^2$ Score**, **RMSE**, and **MAE** to assess predictive accuracy.
* **Key Findings:** **Random Forest Regressor** achieved the highest accuracy ($R^2 \approx 0.82$), proving that non-linear relationships (like location and income influence) are crucial in price determination.

## 🚀 Tech Stack
Python, Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn.

## 📈 Insights
* **Feature Importance:** Analyzed which factors drive price the most, identifying
* **Median Income** and **Ocean Proximity** as the dominant drivers of housing value.
