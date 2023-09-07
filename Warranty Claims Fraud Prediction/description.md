# Warranty Claims Fraud Prediction
![](https://trendsettertelugu.com/wp-content/uploads/2022/12/File-a-warranty-claim.webp)
## Project Overview
The aim of this data science project is to predict the authenticity of warranty claims by analyzing various factors such as region, product category, claim value, and more. The dataset used for this project was sourced from Kaggle and comprises 358 rows and 21 columns.

## Data Dictionary
| Column Name         | Description                                     |
|---------------------|-------------------------------------------------|
| Unnamed: 0          | Index                                           |
| Region              | Region of the claim                             |
| State               | State of the claim                              |
| Area                | Area of the claim                               |
| City                | City of the claim                               |
| Consumer_profile    | Consumer profile (Business/Personal)            |
| Product_category    | Product category (Household/Entertainment)      |
| Product_type        | Product type (AC/TV)                            |
| AC_1001_Issue       | Issue with AC component 1 (0 - No issue/No component, 1 - repair, 2 - replacement) |
| AC_1002_Issue       | Issue with AC component 2 (0 - No issue/No component, 1 - repair, 2 - replacement) |
| AC_1003_Issue       | Issue with AC component 3 (0 - No issue/No component, 1 - repair, 2 - replacement) |
| TV_2001_Issue       | Issue with TV component 1 (0 - No issue/No component, 1 - repair, 2 - replacement) |
| TV_2002_Issue       | Issue with TV component 2 (0 - No issue/No component, 1 - repair, 2 - replacement) |
| TV_2003_Issue       | Issue with TV component 3 (0 - No issue/No component, 1 - repair, 2 - replacement) |
| Claim_Value         | Claim value in INR                              |
| Service_Center      | Service center code                             |
| Product_Age         | Product age in days                             |
| Purchased_from      | Purchased from (Dealer, Manufacturer, Internet) |
| Call_details        | Call duration                                   |
| Purpose             | Purpose of the call                             |
| Fraud               | Fraudulent (1) or Genuine (0) Conclusion       |

## Conclusion
From the exploratory data analysis, it was found that:
- Warranty claims are most frequent in the southern region of India, particularly in Andhra Pradesh and Tamil Nadu.
- Fraudulent claims are more common in urban regions such as Hyderabad and Chennai.
- The dataset includes claims for two products: TVs and ACs. TVs have higher warranty claims when purchased for personal use compared to ACs.
- Fraudulent claims for ACs occur even when there are no issues with the AC parts.
- Fraudulent claims for TVs can occur with or without issues in the TV parts.
- Fraudulent claims are more frequent when purchases are made through the manufacturer.
- Fraudulent claims tend to have higher claim values compared to genuine claims.
- Service center 13 had the highest number of fraudulent claims despite having fewer total warranty claims.
- Fraudulent claims are more frequent when the customer care call duration is less than 3-4 minutes.

Machine learning models, including Decision Tree Classifier, Random Forest Classifier, and Logistic Regression, were employed for prediction. These models achieved excellent accuracy levels of 91-92%. However, due to the limited number of fraudulent claims and a small dataset size, the models exhibited lower recall scores for fraudulent claims. This issue can be mitigated by collecting more data.

This project holds the potential to assist in identifying and preventing warranty claims fraud, thereby saving resources and enhancing the efficiency of warranty claim processing.
