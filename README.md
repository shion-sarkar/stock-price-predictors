# Stock Price Predictors

This project analyzes stock price behavior using various linear regression models. It applies econometric techniques to identify the effects of different financial predictors, including categorical variables and interaction terms, on stock returns.

## 🧪 Models Used
- Ordinary Least Squares (OLS) – `statsmodels.api`
- Dummy Variable Regression – to handle categorical factors (e.g., sector, firm)
- Interaction Term Regression – to explore conditional effects
- Panel Regression – using `linearmodels` for firm-fixed or time-fixed effects

## 📁 Files
- `StatisticsProject.ipynb`: Full analysis in Jupyter Notebook — data cleaning, regression models, interpretation, and visualizations.
- `Fundamentals, Sectoral Effects, and Interaction Dynamics.pdf`: Academic-style summary of methodology and findings.

## 🧰 Python Tools & Libraries
- `pandas` – for data manipulation
- `numpy` – for numerical calculations
- `matplotlib` & `seaborn` – for plotting
- `statsmodels.api` – for OLS, dummy, and interaction regressions
- `linearmodels` – for panel data regression models (e.g., fixed effects)


## 🎯 Objectives
- Model stock return variations using multiple regression techniques
- Understand the impact of firm-specific and market-specific variables
- Explore interactions between financial indicators
- Apply panel data regression to control for unobserved heterogeneity

## 👤 Author
Shion Sarkar

---

Disclaimer: This project is academic and exploratory. Results depend on data quality and model assumptions.
