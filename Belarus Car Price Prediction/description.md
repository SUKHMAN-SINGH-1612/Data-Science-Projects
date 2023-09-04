# Belarus Car Price Prediction
![](https://i0.wp.com/bestsellingcarsblog.com/wp-content/uploads/2020/01/Geely-Atlas-Belarus-2019.jpg?fit=600%2C400&ssl=1)
## Project Overview:
The Belarus Car Price Prediction project aims to forecast the prices of cars in Belarus by leveraging a dataset containing essential car features. These features include the make, model, year of production, condition, mileage, fuel type, engine volume, color, transmission type, drive unit, and segment. With a total of 56,244 rows and 12 columns, this project seeks to identify the key variables that have the most significant impact on car prices within the Belarusian market.

## Data Dictionary:

| Variable        | Description                                                |
|-----------------|------------------------------------------------------------|
| make            | Machine firm or car manufacturer                           |
| model           | Machine model                                              |
| price USD       | Price in USD (target variable)                             |
| year            | Year of production                                         |
| condition       | Represents the condition at the sale moment                |
| mileage         | Mileage in kilometers                                      |
| fuel type       | Type of fuel (electro, petrol, diesel)                     |
| volume(cm3)     | Volume of the engine in cubic centimeters                  |
| color           | Color of the car                                           |
| transmission    | Type of transmission                                       |
| drive unit      | Drive unit                                                 |
| segment         | Segment of the car                                         |

## Impact:
Through exploratory data analysis, several key insights were discovered. Notably, there was a significant increase in car prices in Belarus after the year 2000. Cars running on petrol with automatic transmission tend to have higher prices compared to diesel cars with manual transmission. Electric cars stand out as notably more expensive than other car types. Furthermore, cars with all-wheel drive exhibit the highest prices among all drive units, and speciality segment cars command the highest prices among all segments, followed by luxury European, American, and Asian car segments.

For the predictive modeling, a decision tree regressor was employed to forecast car prices. This model achieved an impressive accuracy rate of 85.29%. The most influential features in predicting car prices were identified as the year of production and the engine's volume in cubic centimeters.

This project offers valuable insights for both car buyers and sellers in Belarus, helping them make informed decisions in a dynamic automotive market.

