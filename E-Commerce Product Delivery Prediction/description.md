# E-Commerce Product Delivery Prediction
![](https://globalskylogistics.com/wp-content/uploads/2018/04/THE-CHANGING-NATURE-OF-E-COMMERCE-DELIVERY.jpg)
## Project Overview:
The aim of this project is to predict whether products from an international e-commerce company will reach customers on time or not. Additionally, the project analyzes various factors influencing product delivery and studies customer behavior. The company primarily sells electronic products.

## Data Dictionary:
The dataset used for model building contains 10,999 observations of 12 variables, including:

| Variable             | Description                                             |
|----------------------|---------------------------------------------------------|
| ID                   | ID Number of Customers                                 |
| Warehouse_block      | The Company's Warehouse block (A, B, C, D, E)          |
| Mode_of_Shipment     | The mode of shipment (Ship, Flight, Road)              |
| Customer_care_calls  | Number of calls made for shipment inquiries            |
| Customer_rating      | Customer rating (1 - Lowest, 5 - Highest)              |
| Cost_of_the_Product  | Cost of the product in US Dollars                     |
| Prior_purchases      | Number of prior purchases                              |
| Product_importance   | Product importance categorization (low, medium, high)  |
| Gender               | Gender of customers (Male, Female)                    |
| Discount_offered     | Discount offered on specific products                  |
| Weight_in_gms        | Weight of the product in grams                         |
| Reached.on.Time_Y.N  | Target variable (1 - Product did not reach on time, 0 - Product reached on time) |

## Conclusion:
The project aimed to predict product delivery timeliness while examining factors affecting delivery and customer behavior. Exploratory data analysis revealed that product weight and cost significantly impact delivery. Products weighing between 2500 - 3500 grams and costing less than $250 had a higher likelihood of timely delivery. Most products were shipped from Warehouse F via ship, suggesting its proximity to a seaport.

Customer behavior also plays a crucial role in predicting timely delivery. Higher customer call volumes correlated with delayed delivery. Interestingly, customers with more prior purchases had a higher rate of on-time deliveries, indicating their loyalty to the company. Products with a discount of 0-10% were more likely to be delivered late, whereas those with discounts exceeding 10% had a higher on-time delivery rate.

In terms of machine learning models, the decision tree classifier achieved the highest accuracy at 69%, outperforming other models. The random forest classifier and logistic regression achieved accuracies of 68% and 67%, respectively, while the K Nearest Neighbors model had the lowest accuracy at 65%.

