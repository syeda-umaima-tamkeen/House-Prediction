# Predicting House Prices Using Linear Regression

**Project by:** Syeda Umaima Tamkeen

## 📝 Summary

This project involves building a **predictive model** to estimate house prices using **Linear Regression**. The model uses features such as size, number of bedrooms, bathrooms, and location. A dataset containing property characteristics (including both numerical and categorical variables) was used to train and evaluate the model for accurate price prediction.

---

## 🔍 Key Steps

### 1. Data Exploration
- Loaded and examined dataset structure, data types, and missing values.
- Visualized correlations between features like `bedrooms`, `bathrooms`, and `price`.
- Analyzed price distribution across **cities** and **property types**.

### 2. Data Preprocessing
- Cleaned data: handled missing values and removed duplicates.
- Applied **one-hot encoding** to categorical features like `city`, `property type`, and `purpose`.
- Created new features like `Area_in_Squareft` and `bed_bath_interaction`.
- Scaled numerical variables to ensure uniform input for the model.

### 3. Feature Engineering
- Added **interaction terms** and log-transformed the target variable (`price`) to reduce skewness and improve model performance.

### 4. Model Training
- Trained a **Linear Regression** model using the preprocessed and transformed dataset.

### 5. Model Evaluation
Evaluated model performance using the following metrics:
- **Mean Absolute Error (MAE):** 0.2675  
- **Mean Squared Error (MSE):** 0.1482  
- **Root Mean Squared Error (RMSE):** 0.3850  
- **R² Score:** 0.9763

Also visualized **residuals** and analyzed **prediction errors** to identify patterns and potential outliers.

### 6. Model Fine-Tuning
- Performed minor improvements like:
  - Adjusting feature selection
  - Trying different scaling strategies
- Optimized performance while avoiding overfitting.

---

## ✅ Results

| Metric          | Value        |
|-----------------|--------------|
| MAE             | 0.2675       |
| MSE             | 0.1482       |
| RMSE            | 0.3850       |
| R² Score        | 0.9763       |

The model accurately captured linear relationships and showed strong predictive power, with a high **R² score** close to 1.

---

## 📌 Conclusion

The **Linear Regression** model achieved excellent performance in predicting house prices. Its high R² score of **0.976** indicates strong explanatory power. However, further improvements could include:

- Trying **Lasso or Ridge Regression** to address potential multicollinearity.
- Implementing **non-linear models** like **Random Forests** or **Gradient Boosting Machines**.
- Enhancing features with **geolocation granularity** or domain-specific indicators.

This project demonstrates how even basic regression techniques, when properly engineered and evaluated, can deliver **high-value predictions** for real-world applications in real estate and finance.


