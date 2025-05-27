# 🏡 Task 4: Boston Housing Price Prediction using Linear Regression

This project involves building a **Linear Regression** model to predict median house prices in the Boston area based on various features such as crime rate, number of rooms, and property tax rate.

---

## 📁 Dataset

- **Source**: [Scikit-learn's Boston Housing Dataset]
- **Records**: 506
- **Features**:
  - CRIM: Crime rate per capita
  - RM: Average number of rooms per dwelling
  - LSTAT: % of lower status population
  - TAX, PTRATIO, etc.
- **Target**:
  - MEDV: Median value of owner-occupied homes (in $1000s)

> ⚠️ Note: This dataset has been deprecated in newer versions of scikit-learn due to ethical concerns. Use with awareness for learning purposes only.

---

## 🧠 Objective

To build a regression model that:
- Understands the relationship between input variables and house prices
- Predicts house prices based on features
- Evaluates performance using RMSE and R² score

---

## 🛠️ Tech Stack

- **Python**
- **Jupyter Notebook**
- **Scikit-learn**
- **Pandas**, **NumPy**
- **Matplotlib / Seaborn**

---

## ⚙️ Workflow

1. **Load & explore data**
2. **Feature-target separation**
3. **Train-test split**
4. **Train Linear Regression model**
5. **Predict on test data**
6. **Evaluate using**:
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
   - R² Score
7. **Visualize predictions vs actuals**

---

## 📊 Sample Output

```python
RMSE: 4.79
R² Score: 0.73
