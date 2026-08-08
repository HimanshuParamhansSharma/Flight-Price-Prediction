# ✈️ Flight Price Prediction Pipeline

An end-to-end Machine Learning regression framework designed to predict airline ticket fares using historical metadata. This project processes messy transit records, optimizes multiple regression models, and incorporates an interactive Power BI dashboard for business trend analysis.

---

## 📊 Key Highlights & Metrics

- **Peak Performance:** Achieved an **$R^2$ score of 0.88** and reduced **RMSE by 14%** through systematic hyperparameter tuning and cross-validation.
- **Data Engineering:** Streamlined messy transit records by structuring time attributes, imputing missing routes using SQL, and applying robust normalization.
- **Model Evaluation:** Benchmarked Decision Trees, Random Forest, KNN, and XGBoost models.
- **Business Intelligence:** Designed an interactive Power BI dashboard to visualize fare trends across departure times and airlines.

---

## 🛠 Tech Stack

- **Language:** Python
- **Database:** SQL (MySQL)
- **Libraries:** `pandas`, `numpy`, `scikit-learn`, `xgboost`, `matplotlib`, `seaborn`
- **Visualization & BI:** Power BI, Matplotlib, Seaborn

---

## 📁 Repository Structure

```text
Flight-Price-Prediction/
│
├── data/                  # Raw and processed flight metadata
├── notebooks/             # EDA, Data Cleaning & Model Experimentation
├── src/                   # Source scripts (Preprocessing, Feature Engineering, Training)
├── models/                # Saved model checkpoints (.pkl / .joblib)
├── dashboard/             # Power BI dashboard files (.pbix)
├── .gitignore
├── README.md
└── requirements.txt
