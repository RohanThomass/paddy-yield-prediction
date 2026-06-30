# 🌾 Paddy Yield Prediction using Machine Learning

## Project Overview

This project predicts paddy yield using machine learning by analyzing agricultural, climatic, soil, and fertilizer-related factors. The objective is to identify the key variables influencing crop productivity and build predictive models that can assist farmers and agricultural planners in making data-driven decisions.

---

## Problem Statement

Paddy yield is affected by several factors such as land characteristics, soil properties, weather conditions, and fertilizer usage. Traditional estimation methods often fail to capture these complex relationships.

This project develops and compares multiple machine learning models to accurately predict paddy yield and analyze the factors contributing to agricultural productivity.

---

## Dataset

- **Records:** 2,338
- **Features:** 45
- **Target Variable:** Paddy Yield

The dataset includes:

- Land Characteristics
- Crop Information
- Soil Information
- Weather & Climate
- Fertilizer Usage

---

## Project Workflow

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Feature Engineering
- Model Building
- Model Evaluation
- Feature Importance Analysis

---

## Machine Learning Models

The following regression models were evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

---

## Model Performance

| Model | R² Score |
|--------|----------|
| Linear Regression | 0.9879 |
| Decision Tree | 0.9888 |
| Random Forest | 0.9890 |
| XGBoost | **0.9897** |

**Best Model:** XGBoost

---

## Key Findings

- Cultivated land area is the strongest predictor of total paddy yield.
- Fertilizer usage (Urea and DAP) significantly influences yield.
- Soil type and nursery management practices play an important role in yield efficiency.
- Weather variables become more influential when predicting yield per hectare instead of total yield.
- Ensemble learning models outperform traditional regression techniques.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## Repository Structure

```
paddy-yield-prediction/
│
├── Final_Analysis_of_Interim_Report.ipynb
├── paddydataset.csv
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/RohanThomass/paddy-yield-prediction.git
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Open the notebook:

```bash
jupyter notebook
```

---

## Future Improvements

- SHAP Explainability
- Streamlit Web Application
- Hyperparameter Optimization
- Model Deployment
- Real-time Yield Prediction Dashboard

---

## Author

**Rohan Thomass**

GitHub: https://github.com/RohanThomass

---

## License

This project is licensed under the MIT License.
