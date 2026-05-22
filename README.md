# House Prices Prediction - Kaggle Competition

![Kaggle](https://img.shields.io/badge/Kaggle-Competition-blue.svg)
![R](https://img.shields.io/badge/R-4.6%2B-blue)
![Markdown](https://img.shields.io/badge/Markdown-Report-green)

**Final Model Performance:** Adjusted R² = **90.16%**

## Project Overview

This repository contains my complete solution for the [Kaggle House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/) competition.

I built a well-specified linear regression model with extensive feature engineering, polynomial terms, and thorough diagnostic checks.

### 📊 View the Full Report

**👉 [View Full HTML Report](https://github.com/niklaspfox/HousePricePrediction/blob/main/PredictingHousePrices.html)**

**📥 [Download PDF Report](https://github.com/niklaspfox/HousePricePrediction/blob/main/PredictingHousePrices.pdf)**

---

### Repository Contents

- `PredictingHousePrices.Rmd` — Main R Markdown file
- `PredictingHousePrices.html` — Fully rendered interactive report
- `PredictingHousePrices.pdf` — PDF version of the report
- `train` — Training dataset
- `test` — Test dataset

---

### Key Highlights

- Extensive EDA and data cleaning
- Handled non-linear relationships (e.g., quadratic terms + splines)
- Rigorous model diagnostics using `performance::check_model()`
- Final model explains **90.16%** of variation in log(SalePrice)

---

*Open to feedback and collaboration!*
