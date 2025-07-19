# 📉 Customer Churn Prediction Web App

A machine learning-based web application that predicts whether a customer is likely to churn or stay, built using Flask and deployed with a trained Random Forest model.

## 🔍 Problem Statement

Telecom companies often face the problem of customer churn. Retaining existing customers is far more cost-effective than acquiring new ones. This project aims to develop a predictive model to identify customers who are likely to churn, allowing companies to proactively retain them.

---

## 🧠 Machine Learning Pipeline

- **Model Used:** Random Forest Classifier
- **Performance Metrics:** Accuracy, Precision, Recall, F1 Score
- **Features Considered:**
  - Demographic: Gender, Senior Citizen, Partner, Dependents
  - Services: Phone Service, Multiple Lines, Internet Service, Online Security, Online Backup, Device Protection, Tech Support, Streaming TV/Movies
  - Account Info: Tenure, Monthly Charges, Total Charges
  - Billing: Paperless Billing, Payment Method, Contract Type

---

## 🗂 Dataset

The model is trained using a customer churn dataset similar to [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn) from Kaggle. The dataset includes 19 features including both categorical and numerical variables.

---

## 🛠 Tech Stack

| Component         | Technology           |
|------------------|----------------------|
| Backend           | Python, Flask        |
| Machine Learning  | scikit-learn         |
| Frontend          | HTML (Jinja2 via Flask) |
| Model Serialization | pickle            |

---

## 🚀 Features

- 🧮 Takes customer attributes as input via a web form
- 🧠 Predicts whether the customer is likely to **churn or stay**
- 📊 Shows confidence level of the prediction
- 🔁 Uses one-hot encoding and feature engineering (`tenure_group`) for categorical variables

---


## 📦 How to Run Locally

1. **Clone the repo**
   ```bash
   git clone https://github.com/yourusername/customer-churn-prediction.git
   cd customer-churn-prediction
