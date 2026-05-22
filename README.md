# House Prices Prediction - Kaggle Competition

![Kaggle](https://img.shields.io/badge/Kaggle-Competition-blue.svg)
![R](https://img.shields.io/badge/R-4.6%2B-blue)
![Markdown](https://img.shields.io/badge/Markdown-Report-green)

**Final Model Performance:** Adjusted R² = **90.16%**

## Project Overview

This repository contains my complete solution for the [Kaggle House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/) competition.

I built a well-specified linear regression model with extensive feature engineering, polynomial terms, and thorough diagnostic checks.

### 📊 View the Full Report

**👉 [View Full HTML Report](HousePrice_Analysis.html)**

**📥 [Download PDF Report]([HousePrice_Analysis.pdf](https://github.com/niklaspfox/HousePricePrediction/blob/main/PredictingHousePrices.pdf))**

---

### Repository Contents

- `HousePrice_Analysis.Rmd` — Main R Markdown file
- `HousePrice_Analysis.html` — Fully rendered interactive report
- `HousePrice_Analysis.pdf` — PDF version of the report
- `data/` — Training and test datasets
- `figures/` — All diagnostic plots and visualizations

---

### Key Highlights

- Extensive EDA and data cleaning
- Handled non-linear relationships (e.g., quadratic terms + splines)
- Rigorous model diagnostics using `performance::check_model()`
- Final model explains **90.16%** of variation in log(SalePrice)

---

*Open to feedback and collaboration!*
