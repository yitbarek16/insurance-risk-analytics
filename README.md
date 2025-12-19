# 🛡️ Insurance Risk Analytics & Predictive Pricing

[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/)
[![DVC](https://img.shields.io/badge/DVC-enabled-lightgrey.svg)](https://dvc.org/)
[![Jupyter Notebook](https://img.shields.io/badge/jupyter-notebook-orange.svg)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📘 Overview

Insurance companies face a critical challenge: pricing policies accurately while remaining profitable. Charging too little leads to losses, while charging too much drives customers away.

In this project, I analyze historical motor insurance data from AlphaCare Insurance Solutions (ACIS) to uncover risk patterns, identify low-risk customer segments, and build predictive models that support smarter, data-driven premium pricing. The analysis combines exploratory data analysis, hypothesis testing, and machine learning to directly inform marketing and pricing strategy.

This project is completed as part of the 10 Academy – Artificial Intelligence Mastery Program.

## 🎯 Business Problem

AlphaCare Insurance Solutions aims to optimize its car insurance marketing and pricing strategy in South Africa. The company is currently experiencing inefficient pricing, with certain customer segments generating losses while others may be overcharged.

The objectives of this project are to:

- Discover low-risk customer segments where premiums can be reduced
- Improve customer acquisition through risk-based pricing
- Support fair, explainable, and data-driven insurance decisions

## 🔍 What This Project Does

The project progresses from exploration to prediction:

1️⃣ Risk Exploration & Understanding

- Analyzed claim behavior across regions, vehicles, demographics, and time
- Identified loss-driving segments
- Flagged data quality and potential fraud indicators

2️⃣ Statistical Validation

- Applied hypothesis testing to validate risk factors
- Confirmed the impact of geography and vehicle type
- Ensured decisions were statistically justified

3️⃣ Reproducible Data Pipeline

- Implemented Data Version Control (DVC)
- Ensured reproducibility and auditability for compliance

4️⃣ Predictive Modeling for Pricing

- Built models to predict:
  - Claim Probability
  - Claim Severity
- Combined predictions into a risk-based premium formula
- Best performance achieved using XGBoost

## 📊 Key Insights

- Risk varies significantly by province and postal code
- Luxury and SUV vehicles carry significantly higher risk
- Claim frequency is increasing over time
- Gender alone is not a strong predictor of risk
- ML models can identify high-risk policies before losses occur

## 🚀 Outcome

A data-driven pricing framework that:

- Improves profitability through targeted premium adjustments
- Supports fair pricing based on measurable risk
- Provides explainable results using SHAP interpretability

## 🧰 Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn
- SHAP
- DVC
- Jupyter Notebook

## 📂 Dataset

The dataset contains historical motor insurance records from February 2014 to August 2015, provided by AlphaCare Insurance Solutions. It includes over one million policies with detailed information across:

- Policy and transaction details
- Customer demographics
- Geographic location (province, postal code, zones)
- Vehicle characteristics
- Insurance plan features
- Premium payments and claims

This rich structure enables both risk segmentation and predictive modeling at multiple levels.

## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

---
Let's stay in touch! Feel free to connect with me on LinkedIn:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yitbarektesfaye)
