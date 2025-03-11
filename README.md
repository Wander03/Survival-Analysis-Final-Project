---
title: "Telco Customer Churn Dataset"
author: "IBM"
date: "2025-03-10"
format: html
---

# Telco Customer Churn Dataset

The **Telco Customer Churn** dataset is a fictional dataset created by IBM to simulate customer data for a telecommunications company. This dataset was designed to help predict customer churn, referring to customers who stop using the company’s services, with the goal of analyzing customer behavior and developing strategies to retain customers. 

## Creation of Dataset

This dataset simulates customer data for a telecommunications company that provided home phone and Internet services to 7043 customers in California during the third quarter.

## Variables

The dataset contains 21 columns:

- **CustomerID**: A unique identifier for each customer.
- **Gender**: The gender of the customer (Male, Female).
- **SeniorCitizen**: Indicates whether the customer is a senior citizen (1 for Yes, 0 for No).
- **Partner**: Indicates whether the customer has a partner (Yes, No).
- **Dependents**: Indicates whether the customer has dependents (Yes, No).
- **Tenure**: The number of months the customer has been with the company.
- **PhoneService**: Indicates whether the customer has a phone service (Yes, No).
- **MultipleLines**: Indicates whether the customer has multiple lines (Yes, No, No phone service).
- **InternetService**: The type of internet service the customer has (DSL, Fiber optic, No).
- **OnlineSecurity**: Indicates whether the customer has online security (Yes, No, No internet service).
- **OnlineBackup**: Indicates whether the customer has online backup (Yes, No, No internet service).
- **DeviceProtection**: Indicates whether the customer has device protection (Yes, No, No internet service).
- **TechSupport**: Indicates whether the customer has tech support (Yes, No, No internet service).
- **StreamingTV**: Indicates whether the customer has streaming TV (Yes, No, No internet service).
- **StreamingMovies**: Indicates whether the customer has streaming movies (Yes, No, No internet service).
- **Contract**: The type of contract the customer has (Month-to-month, One year, Two year).
- **PaperlessBilling**: Indicates whether the customer has paperless billing (Yes, No).
- **PaymentMethod**: The payment method used by the customer (Electronic check, Mailed check, Bank transfer, Credit card).
- **MonthlyCharges**: The amount charged to the customer monthly.
- **TotalCharges**: The total amount charged to the customer over the tenure.
- **Churn**: Indicates whether the customer churned (Yes, No).

### Time to Event and Censoring Variables

- **Time to event variable**: `tenure` (Column 6).
- **Censoring variable**: `Churn` (Column 21).
