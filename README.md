# World-Happiness-Insights-2019-Regression-Analysis

This project analyzes the **2019 World Happiness Report** dataset using R. It aims to uncover which socioeconomic and psychological factors most influence a country's happiness score, using data visualization, correlation analysis, and multiple linear regression.

---

## Dataset

- **Source**: 2019 World Happiness Report
- **Columns**:
  - `Overall rank`: Global ranking of happiness
  - `Country or region`: Country name
  - `Score`: Happiness score (target variable)
  - `GDP per capita`
  - `Social support`
  - `Healthy life expectancy`
  - `Freedom to make life choices`
  - `Generosity`
  - `Perceptions of corruption`

---

## Project Objectives

- Understand the distribution of happiness scores globally
- Visualize relationships between happiness and other variables
- Calculate correlations between variables
- Build a multiple linear regression model to:
  - Explain what drives happiness
  - Predict happiness score based on other metrics

---

## Steps Performed

1. **Data Loading & Inspection**
2. **Missing Value Check**
3. **Exploratory Data Analysis (EDA)**
   - Histograms, scatter plots
4. **Correlation Analysis**
   - `corrplot` used to visualize numerical relationships
5. **Regression Modeling**
   - Built using `lm()` function in R
   - Examined statistical significance (p-values)
   - Evaluated model diagnostics (residual plots)
6. **Country-level Analysis**
   - Top 10 happiest countries listed

---
