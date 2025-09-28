# Amazon Delivery Time Prediction 🚚

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red.svg)
![MLflow](https://img.shields.io/badge/MLflow-Tracking-orange.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

## 📌 Overview
This project predicts e-commerce delivery times for Amazon orders using Machine Learning. By analyzing factors like product category, distance, traffic, weather, and agent performance, the system estimates delivery duration. A Streamlit web app allows users to input order details and get real-time delivery predictions. Model experiments and metrics are tracked with MLflow.

---

## 🎯 Outcomes
- Cleaned and preprocessed raw dataset with missing values, duplicates, and categorical variables handled.
- Engineered features such as geospatial distance, time-based variables, and agent performance metrics.
- Developed and compared regression models:
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting Regressor
- Evaluated models with RMSE, MAE, and R².
- Best-performing model deployed via a Streamlit interface for interactive predictions.
- MLflow used for experiment tracking, hyperparameter tuning, and version management.

---

## 🛠 Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn  
- **Model Tracking:** MLflow  
- **Frontend:** Streamlit  
- **Version Control:** Git & GitHub  

---

## 📂 Project Structure
```
├── data/ # Raw & processed datasets (tracked with Git LFS)
├── mlruns # Gives temporory webpage and shows metrics also dashboards
├── models/src/ # Trained ML models, Python scripts for preprocessing, feature engineering, modeling
├── ouputs # Displays plots of delivery_time_distance and distance_vs_delivery
├── venu # Enviroloment and configrations 
├── .gitattributes # Git LFS configuration
├── Amazon delivery prediction #Manual/procedure/guidelines given by labmentix team
├── app.py # Streamlit app code
├── requirements.txt # Dependencies
└── README.md
```

---
🔮 Future Enhancements

Integrate live traffic & weather APIs for dynamic predictions.

Deploy as a REST API with Docker/Kubernetes for production scale.

Build dashboard for logistics teams to monitor delivery trends.

Add automated retraining pipeline with CI/CD.
