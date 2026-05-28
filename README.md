# 🚗 Insurance Response Prediction — Streamlit App

Predict whether a customer will be interested in vehicle insurance.

## Setup & Run

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Features

| Page | What you can do |
|---|---|
| 📊 Data Explorer | Upload CSV, view KPIs, correlation heatmap, demographic & vehicle charts |
| 🤖 Train Models | Pick models (Logistic Regression, Decision Tree, Random Forest, XGBoost), see ROC curves & confusion matrices |
| 🔮 Predict Customer | Fill in a customer profile and get instant prediction with probability gauge |

## Dataset columns expected

`Gender, Age, Driving_License, Region_Code, Previously_Insured, Vehicle_Age, Vehicle_Damage, Annual_Premium, Policy_Sales_Channel, Vintage, Response`

An optional `id` column will be dropped automatically.