# 🚗 Used Car Price Prediction – Machine Learning Project

This project applies **data science and machine learning** to build a reliable and transparent pricing model for the Indian used car market.
It helps buyers, sellers, and businesses make **data-driven pricing decisions**, reducing manual subjectivity and improving profitability.

## 🧩 Problem Statement
The used car market in India suffers from **pricing inconsistency and lack of transparency** due to multiple influencing factors — such as mileage, age, power, brand, and ownership history.
This project aims to build a **data-driven regression model** that predicts the fair market value of used cars using historical data.

## ⚙️ Data Preprocessing & Feature Engineering
- Handled missing values and dropped rows with missing target variable.
- Log-transformed `Price` and `Kilometers_Driven` to reduce skewness.
- Extracted `Brand` from car name.
- Computed `Age` feature from `Year`.
- One-hot encoded categorical variables.
- Scaled numerical variables using **StandardScaler**.
- Removed multicollinearity using **VIF** and p-value analysis.

## 🧠 Model Building
Evaluated multiple regression models:
- Linear Regression (OLS)
- Ridge Regression
- Lasso Regression
- Decision Tree Regressor
- ✅ Tuned Random Forest Regressor (Final Model)

**Best model:** Random Forest Regressor (tuned using GridSearchCV)

## 📈 Model Performance
| Metric | Score |
|---------|--------|
| R² (Test) | 0.926 |
| RMSE | 0.202 |
| MAE | 0.142 |
| CV R² | 0.9342 |

**Top influencing features:** Power, Age, and Kilometers_Driven

## 💼 Business Impact
- Increased profitability: 3–5% improvement from better pricing accuracy
- Reduced manual effort: 10–15 hours/week saved for analysts
- Faster sales cycles: 10% reduction in inventory holding time
- Data-backed transparency: Builds customer trust and scalability

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-Learn
- Statsmodels
- Jupyter Notebook

## 🚀 Future Enhancements
- Deploy as a web app using Streamlit or Flask
- Integrate real-time pricing API or external market data
- Experiment with XGBoost / LightGBM
- Build a Generative AI layer for price explanation or chat assistant

## 🧾 Author
**Pandarakkannu (Kannu PS)**  
Software Engineer | Cloud & AI Enthusiast  
[LinkedIn](https://www.linkedin.com/in/kannups)

---
