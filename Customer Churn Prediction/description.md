# Customer Churn Prediction
![](https://miro.medium.com/v2/resize:fit:1400/1*47xx1oXuebvYwZeB0OutuA.png)
## Project Overview:
The main objective of the Bank Customer Churn Prediction project is to analyze the demographics and financial information of bank customers, including factors like age, gender, credit score, country, balance, and more, in order to predict whether a customer will leave the bank or not. Customer churn, the decision of customers to leave a bank, can significantly impact the bank's business and profitability. By accurately predicting customer churn, the bank can take proactive measures to retain valuable customers and enhance customer satisfaction.
## About the Dataset:
The dataset used in this project is sourced from Kaggle and comprises 10,000 rows and 14 columns. The dataset's primary objective is to predict whether a customer will churn (leave the bank) based on their demographics and financial information.

The dataset contains several independent variables, which are potential factors that may influence a customer's decision to leave the bank. These variables include customer-specific information like credit score, country (geography), age, tenure (number of years with the bank), bank balance, the number of bank products utilized (NumOfProducts), whether the customer holds a credit card (HasCrCard), and whether the customer is an active member with the bank (IsActiveMember). The target variable, also known as the dependent variable, is labeled "Exited" and is represented by a binary flag: 1 if the customer closed their account with the bank and 0 if the customer is retained.
## Data Dictionary
| Column Name | Description |
| --- | --- |
| RowNumber | Row number |
| CustomerId | Unique identification key for different customers |
| Surname | Customer's last name |
| CreditScore | Credit score of the customer |
|Geography | Country of the customer |
|Age | Age of the customer |
|Tenure | Number of years for which the customer has been with the bank |
|Balance | Bank balance of the customer |
|NumOfProducts | Number of bank products the customer is utilising |
|HasCrCard | Binary flag for whether the customer holds a credit card with the bank or not |
|IsActiveMember | Binary flag for whether the customer is an active member with the bank or not |
|EstimatedSalary | Estimated salary of the customer in Dollars |
|Exited | Binary flag 1 if the customer closed account with bank and 0 if the customer is retained |

By leveraging this dataset and employing appropriate data science techniques, the project aims to build a predictive model that can accurately identify customers likely to churn, enabling the bank to implement targeted retention strategies and ultimately improve customer loyalty and business performance.
