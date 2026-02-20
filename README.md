# 📊 Educational Inequality Modeling – ENEM 2023 Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Project Type](https://img.shields.io/badge/Type-Applied%20Data%20Science-orange)

---

## 📌 Overview

This repository contains the analytical framework developed for my MBA capstone project in Big Data & Analytics (FIA Business School – LABDATA).

The project investigates how **school infrastructure** and **socioeconomic variables** impact student performance in Brazil’s national high school exam (ENEM 2023), using statistical modeling and machine learning techniques.

The central research question:

> To what extent can educational inequality be modeled and predicted using structural and socioeconomic indicators?

---

## 🎯 Objectives

- Quantify the impact of school infrastructure on academic performance  
- Evaluate the predictive power of socioeconomic indicators  
- Build classification models to estimate risk of low academic performance  
- Extract interpretable insights to support data-driven educational strategies  

---

## 🗂 Data Sources

- ENEM 2023 Microdata (INEP)
- Brazilian School Census (INEP)
- Municipal-level indicators (IBGE)

### Data Disclaimer

All datasets used in this project are publicly available through official Brazilian government portals (INEP and IBGE).

Raw microdata is **not included** in this repository due to size and licensing considerations.

---

## 🏗 Project Structure

```

enem-infra-socioeconomia-ml/
│
├── notebooks/
│   └── TCC-2.ipynb
│
├── src/
│   └── modeling scripts (if applicable)
│
├── assets/
│   └── Presentation and visual materials
│
├── requirements.txt
├── .gitignore
└── README.md

```

---

## 🧪 Methodology

### 1️⃣ Data Engineering
- Large-scale microdata cleaning
- Handling missing values
- Feature engineering
- Municipal-level aggregation

### 2️⃣ Exploratory Data Analysis
- Correlation analysis
- Distribution mapping
- Infrastructure coverage assessment
- Socioeconomic pattern evaluation

### 3️⃣ Statistical Modeling
- Linear regression (infrastructure-only baseline)
- Multivariate regression including socioeconomic controls

### 4️⃣ Machine Learning
Models tested:

- Logistic Regression  
- Random Forest  
- Gradient Boosting  
- XGBoost (final selected model)

### 5️⃣ Model Evaluation

- ROC-AUC  
- Sensitivity (Recall)  
- Feature Importance  
- Risk Simulation Scenarios  
- SHAP interpretability analysis  

---

## 📈 Model Performance

| Model                | AUC  | Sensitivity |
|----------------------|------|------------|
| Logistic Regression  | ~0.xx | xx% |
| Random Forest        | ~0.xx | xx% |
| XGBoost              | **0.73** | **77%** |

The selected model (XGBoost) demonstrated the best balance between predictive performance and interpretability.

---

## 🔍 Key Findings

- Infrastructure explains a significant portion of performance variation.
- Socioeconomic variables show stronger predictive power.
- It is possible to estimate probability of low academic performance based on student profile characteristics.

Educational inequality is not random — it is statistically structured and predictable.

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

5. Run notebooks in order:
   - Data preprocessing
   - Exploratory analysis
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

## 🎓 Research Context

This project was developed as part of an MBA in Big Data & Analytics.

Beyond academic analysis, it explores how predictive modeling can support strategic decision-making in education and reduce structural inequality through data-driven insights.

---

## 👤 Author

Pedro Henrique Lofiego Sampaio da Silva  
MBA in Big Data & Analytics – FIA Business School  
Data & Strategy Enthusiast  

---

## 📬 Contact

Feel free to connect via LinkedIn or open an issue for discussion.

Qual posicionamento você quer reforçar com esse repositório?
