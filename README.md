# customer-churn-prediction

## Project Overview:

Customer churn prediction is the process of identifying the customers who are likely to leave a company or service. This project aims to build a predictive model that can accurately identify customers who are likely to churn from a bank using their demographic and financial information.

## Problem Statement:

Customer churn is a major concern for any business. It is estimated that the cost of acquiring a new customer is 5 times more than the cost of retaining an existing customer. Customer churn can significantly impact the business performance and profitability of a bank. By accurately predicting customer churn, the bank can take proactive measures to retain valuable customers and enhance customer satisfaction.

## About the Dataset:

The dataset used in this project is sourced from Kaggle and comprises 10,000 rows and 14 columns. The dataset's primary objective is to predict whether a customer will churn (leave the bank) based on their demographics and financial information.

The dataset contains several independent variables, which are potential factors that may influence a customer's decision to leave the bank. These variables include customer-specific information like credit score, country (geography), age, tenure (number of years with the bank), bank balance, the number of bank products utilized (NumOfProducts), whether the customer holds a credit card (HasCrCard), and whether the customer is an active member with the bank (IsActiveMember). The target variable, also known as the dependent variable, is labeled "Exited" and is represented by a binary flag: 1 if the customer closed their account with the bank and 0 if the customer is retained.

## Data Dictionary

| Column Name     | Description                                                                              |
| --------------- | ---------------------------------------------------------------------------------------- |
| RowNumber       | Row number                                                                               |
| CustomerId      | Unique identification key for different customers                                        |
| Surname         | Customer's last name                                                                     |
| CreditScore     | Credit score of the customer                                                             |
| Geography       | Country of the customer                                                                  |
| Age             | Age of the customer                                                                      |
| Tenure          | Number of years for which the customer has been with the bank                            |
| Balance         | Bank balance of the customer                                                             |
| NumOfProducts   | Number of bank products the customer is utilising                                        |
| HasCrCard       | Binary flag for whether the customer holds a credit card with the bank or not            |
| IsActiveMember  | Binary flag for whether the customer is an active member with the bank or not            |
| EstimatedSalary | Estimated salary of the customer in Dollars                                              |
| Exited          | Binary flag 1 if the customer closed account with bank and 0 if the customer is retained |

## Objectives:

The main objectives of this project are:

- To develop a predictive model that can accurately identify customers who are likely to churn from a bank.
- To identify the most important factors that influence a customer's decision to leave the bank.
- To develop a strategy for retaining valuable customers and enhancing customer satisfaction.

## Methodology:

The methodology used in this project is as follows:

- Data preprocessing: The dataset will be cleaned and preprocessed to remove any missing or irrelevant data.
- Feature engineering: The dataset will be transformed into a format that can be used for modeling.
- Model selection: A suitable machine learning algorithm will be selected and trained on the dataset.
- Model evaluation: The performance of the model will be evaluated using appropriate metrics.
- Model deployment: The model will be deployed in a suitable environment for use by the bank.

## Expected Outcomes:

The expected outcomes of this project are:

- A predictive model that can accurately identify customers who are likely to churn from a bank.
- A strategy for retaining valuable customers and enhancing customer satisfaction.
- A better understanding of the factors that influence a customer's decision to leave the bank.

## Conclusion:

Customer churn prediction is an important task for any business. By accurately predicting customer churn, a bank can take proactive measures to retain valuable customers and enhance customer satisfaction. This project aims to build a predictive model that can accurately identify customers who are likely to churn from a bank using their demographic and financial information. The project will follow a structured approach, including data preprocessing, feature engineering, model selection, model evaluation, and model deployment. The expected outcomes of the project are a predictive model, a strategy for retaining valuable customers, and a better understanding of the factors that influence a customer's decision to leave the bank.
