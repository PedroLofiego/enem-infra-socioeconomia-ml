# 📊 Educational Inequality Modeling – ENEM 2023 Analysis

## Overview

This repository contains the analytical framework developed for my MBA capstone project in Big Data & Analytics (FIA Business School – LABDATA).

The project investigates how **school infrastructure** and **socioeconomic variables** impact student performance in Brazil’s national high school exam (ENEM 2023), using statistical modeling and machine learning techniques.

The central research question:

> To what extent can we model and predict educational performance using structural and socioeconomic indicators?

---

## 🎯 Objectives

- Quantify the impact of school infrastructure variables on academic performance
- Evaluate the predictive power of socioeconomic indicators
- Build classification models to estimate risk of low academic performance
- Extract interpretable insights to support data-driven educational strategies

---

## 🗂 Data Sources

- ENEM 2023 Microdata (INEP)
- Brazilian School Census (INEP)
- Municipal-level indicators (IBGE)

> Raw microdata is not included in this repository due to size and licensing constraints. See the Reproducibility section for instructions.

---

## 🏗 Project Structure

```

├── data/
│   ├── raw/              # External datasets (not versioned)
│   └── processed/        # Cleaned datasets
├── notebooks/            # Jupyter notebooks (EDA & modeling)
├── src/                  # Reusable scripts and functions
├── outputs/              # Model results, plots and reports
├── assets/               # Presentation files and visual material
├── requirements.txt
└── README.md

```

---

## 🧪 Methodology

### 1. Data Engineering
- Cleaning and preprocessing large-scale microdata
- Handling missing values
- Feature engineering
- Municipal-level aggregation

### 2. Exploratory Data Analysis (EDA)
- Correlation analysis
- Distribution mapping
- Infrastructure coverage evaluation
- Socioeconomic pattern identification

### 3. Statistical Modeling
- Linear regression (infrastructure-only baseline model)
- Multivariate regression including socioeconomic controls

### 4. Machine Learning
Models tested:
- Logistic Regression
- Random Forest
- Gradient Boosting
- XGBoost (selected final model)

### 5. Model Evaluation
- ROC-AUC
- Sensitivity (Recall)
- Feature importance
- Risk simulation scenarios
- Interpretability analysis (SHAP values)

---

## 📈 Key Findings

- Infrastructure explains a significant portion of municipal-level variation.
- Socioeconomic variables demonstrate stronger predictive power.
- XGBoost achieved:
  - AUC ≈ 0.73
  - Sensitivity ≈ 77%
- It is possible to estimate probability of low academic performance based on student profile characteristics.

The inequality is not random — it is statistically structured and predictable.

---

## 🔁 Reproducibility

To reproduce this analysis:

1. Download ENEM microdata from the official INEP portal.
2. Download School Census and IBGE datasets.
3. Place datasets inside:

```

data/raw/

```

4. Install dependencies:

```

pip install -r requirements.txt

```

5. Run notebooks in the following order:
- Data preprocessing
- EDA
- Modeling
- Evaluation

---

## 🧠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- SHAP
- Matplotlib
- Seaborn

---

## 📌 Research Context

This project was developed as part of an MBA in Big Data & Analytics and aims to explore how predictive modeling can support strategic decision-making in education.

---

## 👤 Author

Pedro Henrique Lofiego Sampaio da Silva  
MBA in Big Data & Analytics – FIA Business School  
Data & Strategy Enthusiast  

```
