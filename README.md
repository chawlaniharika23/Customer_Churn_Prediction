# Customer Churn Prediction

A machine learning project that predicts customer churn using the **IBM Telco Customer Churn** dataset. The objective is to identify customers who are likely to discontinue a service, enabling businesses to take proactive retention measures and improve customer retention.

---

## Overview

Customer churn is a major challenge for subscription-based businesses. This project explores the use of supervised machine learning models to classify customers as likely to churn or remain with the company.

Two classification models were trained and evaluated:

- Logistic Regression
- Random Forest Classifier

---

## Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Categorical feature encoding
- Feature scaling
- Model training using multiple classifiers
- Performance evaluation using classification metrics and ROC-AUC

---

## Dataset

**IBM Telco Customer Churn Dataset**

- Source: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

---

## Tech Stack

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## Workflow

1. Load and inspect the dataset
2. Handle missing values
3. Encode categorical features
4. Scale numerical features
5. Split data into training and testing sets
6. Train Logistic Regression and Random Forest models
7. Evaluate model performance

---

## Model Performance

| Model | Accuracy | ROC-AUC |
|--------|---------:|--------:|
| Logistic Regression | **71%** | **0.8643** |
| Random Forest | **68%** | **0.8637** |

### Evaluation Metrics

**Logistic Regression**

- Accuracy: **71%**
- ROC-AUC Score: **0.8643**
- Churn Recall: **88%**
- Churn Precision: **47%**

**Random Forest**

- Accuracy: **68%**
- ROC-AUC Score: **0.8637**
- Churn Recall: **92%**
- Churn Precision: **45%**

**Observation:** Logistic Regression achieved better overall accuracy while Random Forest achieved higher recall for identifying customers who are likely to churn.

---

## Repository Structure

```
Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/chawlaniharika23/Customer_Churn_Prediction.git
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Open **Customer_Churn_Prediction.ipynb** in **Google Colab** or **Jupyter Notebook** and execute the notebook cells sequentially.

---
