# 🏡 House Price Prediction Model

This project uses **machine learning models** — including **Linear Regression** and **Random Forest Regressor** — to predict the **price of a unit area** in real estate, based on features such as:

- Distance to the nearest MRT station
- Number of convenient stores nearby
- House age

---

## 📈 Objective

The main goal of this project is to **predict real estate prices** using feature-based regression models, and to compare their performance using evaluation metrics such as:

- R² Score
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)

---

## 🔍 Models Used

1. **Linear Regression**  
   A simple baseline model to understand linear relationships between features and price.

2. **Random Forest Regressor**  
   A more advanced, non-linear model that captures complex patterns and delivers higher accuracy.

---

## 📊 Evaluation Summary

| Metric       | Linear Regression | Random Forest |
|--------------|-------------------|---------------|
| R² Score     | 0.65              | 0.77          |
| RMSE         | 58.89             | 38.88         |
| MAE          | —                 | 4.47          |

- 📌 **Random Forest outperformed Linear Regression**, especially in handling outliers and non-linear relationships.
- Outliers were detected in the target variable using boxplots.
- Feature importance was visualized for Random Forest to interpret model behavior.

---

## 📦 Features Used

| Feature Name                     | Description |
|----------------------------------|-------------|
| `dist_to_the_nearest_MRT_station` | Distance from the property to the nearest MRT |
| `num_convenient_stores`         | Number of convenience stores nearby |
| `house_age`                     | Age of the house in years |

---

## 🧪 How to Use

1. Clone the repository:
   ```bash
   gi clone https://github.com/mikeo24/house_price_prediction_model.git
   cd house_price_prediction_model
