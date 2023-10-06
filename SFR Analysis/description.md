# Space Fund Realty (SFR) Analysis
![](https://c4.wallpaperflare.com/wallpaper/81/233/257/smoke-cape-canaveral-rocket-falcon-9-wallpaper-preview.jpg)
## Project Overview
The Space Fund Realty (SFR) Analysis project aims to provide valuable insights into aerospace companies and their missions, ultimately assisting investors in making informed decisions. The SFR is a crucial rating system that evaluates companies based on their missions, payload, launch costs, and other factors, providing an indication of their development and stability. The SFR rating ranges from 1 to 9, with higher ratings signifying more developed companies.

## Data Dictionary
Here is a description of the dataset used in this project:

| Column Name         | Description                                           |
|---------------------|-------------------------------------------------------|
| Company             | Name of the company                                   |
| SFR                 | SpaceFund Realty rating of the company               |
| Payload(kg)         | Payload of the mission                                |
| Launch Cost (million USD) | Launch cost of the mission                      |
| Price per kg        | Price per kg payload of the mission                  |
| Launch Class        | Launch class of the mission                           |
| Orbit Altitude      | Orbit altitude of the mission                         |
| Tech Type           | Technology type of the mission                        |
| Country             | Country of the company                                |
| HQ Location         | Headquarters location of the company                   |
| Description         | Description of the mission                            |

## Conclusion
Based on the exploratory data analysis of the dataset, several key insights were uncovered:

1. **Geographical Distribution**: The majority of companies in the dataset were from the United States, resulting in a higher number of well-rated companies with an SFR greater than 6. However, China ranked second, surpassing the United Kingdom in the number of companies with a high SFR rating.

2. **Mission Characteristics**: Most of the missions in the dataset were rocket-type, small launch class, and focused on Low Earth Orbit missions. This trend is closely related to the distribution of SFR ratings, with a significant number of missions having SFR ratings between 2 and 3.

3. **Launch Cost and Payload Relationship**: A strong correlation was observed between launch cost and payload with SFR ratings. Missions with higher launch costs and payloads tended to have higher SFR ratings. This suggests that well-established companies are capable of carrying heavier payloads into space and investing more in their missions.

4. **Machine Learning Models**: Decision Tree and Random Forest Classifier models were employed in this project. Both models yielded similar results with an accuracy of 87%. However, it's important to note that due to the relatively small dataset, the models had lower recall scores when predicting SFR ratings greater than 6. Increasing the dataset size could potentially improve model performance in this regard.

In conclusion, this analysis provides valuable insights for investors looking to make informed decisions about aerospace companies. Understanding the factors influencing SFR ratings can assist in assessing the development and stability of these companies in the dynamic space industry. Additionally, expanding the dataset could further enhance the accuracy and reliability of predictive models.
