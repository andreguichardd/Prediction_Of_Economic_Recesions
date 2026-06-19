# Economic Recession Prediction — EY Thesis Project

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/andreguichardd/Prediction_Of_Economic_Recesions/blob/main/recession_prediction.ipynb)

**Machine learning model for predicting US economic recessions.**
Developed as part of the Executive Master in Big Data & Data Science thesis project, in collaboration with EY.

---

## Problem

Predicting economic recessions ahead of time is one of the most valuable and challenging problems in macroeconomic forecasting. This project builds a machine learning model to anticipate US recession periods using historical macroeconomic indicators.

---

## Approach

- **Data collection** — historical macroeconomic time series (yield curve, unemployment, industrial production, consumer indices, among others)
- **Feature engineering** — lagged indicators, rolling statistics, yield curve spread calculations
- **Modelling** — supervised classification to predict recession vs. non-recession periods
- **Evaluation** — model performance assessed against historical recession dates (NBER-defined)

---

## Tech Stack

```
Python    Pandas · NumPy · Scikit-learn · Matplotlib · Statistical Analysis
```

---

## Project Structure

```
├── recession_prediction.ipynb   # Full pipeline: data collection, feature engineering, modelling
└── README.md
```

---

## Notes

This project was developed as an academic thesis in partnership with EY and is shared here for portfolio purposes.
