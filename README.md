## 🏢 Apartment Rental Price Prediction using Machine Learning

**"Smart Rent: Predicting Apartment Prices Using ML & PCA"**

---

### 📌 Project Overview

This project applies machine learning techniques to accurately predict apartment rental prices using various housing features like square footage, number of bedrooms, bathrooms, and location. It is built using a clean pipeline that includes data cleaning, feature transformation, dimensionality reduction (PCA), and regression modeling.

We used the **Random Forest Regressor** as the primary model, supported by comparison with **Gradient Boosting Regressor** and **XGBoost**. The model achieved strong predictive performance with an **R² score of 0.90**, proving its practical use in real estate analytics.

---

### 👩‍💻 Team Members

* Faryal Zahra
* Ayesha Noor
* Hira Khalid
  *Department of Computer Science*
  National University of Computer and Emerging Sciences, Lahore

---

### 🧠 Machine Learning Workflow

1. **Data Collection**
   Sourced from publicly available apartment rental listings via UCI ML Repository.

2. **Preprocessing**

   * Missing value imputation
   * Frequency encoding for categorical data
   * Outlier treatment with log transforms/capping

3. **Exploratory Data Analysis (EDA)**

   * Correlation matrix
   * Scatter plots

4. **Dimensionality Reduction**

   * Applied **Principal Component Analysis (PCA)** to retain 95% variance

5. **Model Development**

   * Used **Random Forest Regressor**
   * Comparison with **Gradient Boosting** and **XGBoost**

6. **Evaluation Metrics**

   * **R² Score:** 0.90
   * **Mean Absolute Error (MAE):** 0.0035
   * **Root Mean Squared Error (RMSE):** 0.0092

---

### 🔍 Key Findings

* Square footage and room count are significant indicators of price.
* PCA significantly reduced model complexity while maintaining high accuracy.
* Random Forest Regressor provided the most robust results.

---

### 🔮 Future Work

* Explore time-series forecasting for rental trends.
* Try deep learning models (e.g., Neural Networks).
* Cluster-based approaches like **K-Means** for market segmentation.
