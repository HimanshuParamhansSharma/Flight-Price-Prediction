<div align="center">

# ✈️ Flight Price Prediction Pipeline
### End-to-End Machine Learning & Analytics Framework

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![XGBoost](https://img.shields.io/badge/XGBoost-111111?style=for-the-badge&logo=xgboost&logoColor=white)](https://xgboost.readthedocs.io)
[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

An end-to-end Machine Learning regression solution that predicts airline ticket fares from historical flight metadata. This project cleans messy transit records, resolves missing route parameters using SQL queries, benchmarks multiple regression algorithms, and exposes key cost-saving insights through an interactive Power BI dashboard.

[View Portfolio README](https://github.com/HimanshuParamhansSharma) • [Report Issue](https://github.com/HimanshuParamhansSharma/Flight-Price-Prediction/issues)

</div>

---

## 📌 Executive Summary

Predicting flight ticket prices is inherently challenging due to volatile dynamic pricing algorithms, seasonal demand spikes, and complex routing variables. This project builds a robust regression framework that automates data ingestion, feature engineering, and model training processes to forecast fares with high statistical precision.

### Key Business Metrics & Benchmarks
- **$R^2$ Score:** Peak **0.88** achieved via tuned **XGBoost Regressor**.
- **Error Reduction:** Achieved a **14% reduction in RMSE** through hyperparameter tuning and 5-fold cross-validation.
- **Data Engineering:** Automated time-attribute restructuring, SQL-based missing route imputation, and log-transform scale normalization across multi-city transit logs.

---

## 🛠 Tech Stack & Tools

- **Core Programming:** Python 3.10+
- **Database & Querying:** SQL (MySQL Workbench)
- **Data Manipulation:** `Pandas`, `NumPy`
- **Machine Learning & Modeling:** `Scikit-learn`, `XGBoost`
- **Data Visualization & BI:** Power BI, `Matplotlib`, `Seaborn`
- **Model Persistence:** `Joblib`

---

## ⚙️ Architecture & Pipeline Flow

```text
[ Raw Flight Data ] 
       │
       ▼
[ Data Cleaning & Imputation ] ---> (Handled missing routes via SQL queries)
       │
       ▼
[ Feature Engineering ]        ---> (Extracted Duration, Stops, Departure/Arrival Windows)
       │
       ▼
[ Model Benchmarking ]         ---> (Trained Decision Tree, Random Forest, KNN, XGBoost)
       │
       ▼
[ Hyperparameter Tuning ]      ---> (GridSearchCV / 5-Fold Cross Validation)
       │
       ▼
[ Model Export & BI Output ]   ---> (Serialized XGBoost model + Power BI Visual Dashboard)
