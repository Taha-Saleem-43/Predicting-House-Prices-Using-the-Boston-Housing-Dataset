# 🏡 Task 4: Boston Housing Price Prediction using Multiple Regression Models

This project focuses on predicting **Boston house prices** using multiple regression algorithms and comparing their performance on accuracy and generalization.

---

## 📁 Dataset

- **Source**: Scikit-learn’s built-in Boston Housing dataset
- **Samples**: 506
- **Features**: 13 numerical features
- **Target**: MEDV — Median value of owner-occupied homes (in $1000s)

> ⚠️ Note: The dataset has been deprecated in scikit-learn due to ethical concerns. It's used here for educational purposes only.

---

## 🧠 Objective

To predict housing prices based on various neighborhood and property-related attributes using:
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

---

## 🛠️ Tech Stack

- **Python**
- **Jupyter Notebook**
- **Scikit-learn**
- **XGBoost**
- **Pandas**, **NumPy**
- **Matplotlib / Seaborn**

---

## ⚙️ Workflow

1. **Data Exploration & Cleaning**
2. **Feature and Target Separation**
3. **Train-Test Split**
4. **Model Training**:
   - 🔹 Linear Regression
   - 🌲 Random Forest Regressor
   - ⚡ XGBoost Regressor
5. **Performance Metrics**:
   - Root Mean Squared Error (RMSE)
   - R² Score
6. **Visual Analysis**:
   - Predicted vs Actual plots
   - Residual plots

---

## 📊 Model Comparison

| Model               | RMSE   | R² Score |
|--------------------|--------|----------|
| Linear Regression   | 4.79   | 0.73     |
| Random Forest       | 2.90   | 0.91     |
| XGBoost Regressor   | 2.72   | 0.93     |

> ✅ XGBoost gave the **best performance**, followed closely by Random Forest.

---

## 📈 Visual Insights

- Linear regression showed higher residuals on outliers
- Random Forest smoothed predictions better
- XGBoost handled variance and bias optimally

---

## ✅ Key Learnings

- Tree-based models outperform linear models for complex relationships
- XGBoost provides regularization and better control over overfitting
- RMSE and R² are key to evaluating regression models beyond just accuracy

---


