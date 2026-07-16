# CreditSense-AI

An end-to-end Machine Learning project for intelligent credit risk assessment and loan default prediction using the Home Credit Default Risk dataset.

---

## Project Overview

CreditSense-AI predicts whether a loan applicant is likely to default by analyzing demographic, financial, employment, and credit history data.

The project demonstrates the complete machine learning lifecycle—from data preprocessing and feature engineering to model training, explainability, deployment, and dashboard visualization.

---

## Objectives

- Predict loan default risk
- Assist financial institutions in making data-driven lending decisions
- Explain model predictions using Explainable AI
- Deploy a production-ready prediction API

---

## Dataset

**Home Credit Default Risk Dataset**

- Source: Kaggle
- 300,000+ loan applications
- Multiple relational tables
- Real-world financial data

> Note: Dataset files are not included in this repository because of their size. Download them from Kaggle and place them inside `data/raw/`.

---

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Plotly
- Jupyter Notebook
- Git & GitHub

**Upcoming**

- XGBoost
- LightGBM
- SHAP
- FastAPI
- PostgreSQL
- Docker
- React

---

## Project Structure

```text
CreditSense-AI/

├── data/
│   ├── raw/
│   ├── processed/
│   └── external/
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_preprocessing.ipynb
│   ├── 03_feature_engineering.ipynb
│   ├── 04_model_training.ipynb
│   └── 05_model_evaluation.ipynb
│
├── src/
├── dashboard/
├── models/
├── reports/
├── docs/
└── README.md
```

---

## Current Progress

- [x] Project setup
- [x] GitHub repository
- [x] Exploratory Data Analysis
- [ ] Data preprocessing
- [ ] Feature engineering
- [ ] Model training
- [ ] Model evaluation
- [ ] Explainable AI
- [ ] API development
- [ ] Interactive dashboard

---

## Key Features (Planned)

- Credit default prediction
- Feature engineering pipeline
- Class imbalance handling
- Model comparison
- SHAP Explainability
- REST API
- Interactive dashboard

---

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/CreditSense-AI.git
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate it:

Windows

```bash
venv\Scripts\activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Future Improvements

- Hyperparameter tuning
- MLflow experiment tracking
- CI/CD pipeline
- Docker deployment
- Cloud deployment (AWS)

---

## Author

**Shruti Dwivedi**

B.Tech Artificial Intelligence & Data Science
