# Crop Yield Prediction
<img src = "https://img.in-part.com/resize?stripmeta=true&noprofile=true&quality=95&url=https%3A%2F%2Fs3-eu-west-1.amazonaws.com%2Fassets.in-part.com%2Ftechnologies%2Fheader-images%2F2aVv2twTYW9qZGGhPrxw_AdobeStock_241906053.jpeg&width=1200&height=820" width = "700" height = "500">

The aim of this data science project is to predict crop yield using the dataset provided from Crop Yield Prediction. The dataset includes various environmental and agricultural factors such as rainfall, temperature, fertilizer usage, and macronutrient levels, along with the corresponding crop yield in Quintals per acre.

## Data Dictionary

| Column Name     | Description                                  |
|-----------------|----------------------------------------------|
| Rain Fall (mm)  | Rainfall in millimeters                      |
| Temperature (C) | Temperature in Celsius                       |
| Fertilizer (kg) | Fertilizer in kilograms                      |
| Nitrogen (N)    | Nitrogen macro nutrient                      |
| Phosphorous (P) | Phosphorous macro nutrient                   |
| Potassium (K)   | Potassium macro nutrient                     |
| Yield (Q/acres) | Crop yield Quintals per acre                 |

## Data Preprocessing

Upon examining the dataset, it was found that the temperature column contained invalid values represented as ":". These entries were removed, and the column was converted to a float data type. Missing values were replaced with the median of their respective columns.

## Exploratory Data Analysis (EDA)

EDA revealed several insights:
- The dataset likely represents two distinct crops, indicated by clusters in graphs of rainfall, temperature, and crop yield.
- Fertilizer usage appears to have a proportional relationship with crop yield, with some exceptions.
- Temperature and rainfall also exhibit distinct patterns possibly corresponding to different crop seasons.
- Macronutrients (Nitrogen, Phosphorus, Potassium) show varying distributions, indicating potential differences in crop requirements.
- Temperature emerges as the most influential factor in predicting crop yield, followed by rainfall.

## Model Building and Evaluation

Two regression models, Decision Tree Regressor and Random Forest Regressor, were trained and evaluated. Random Forest Regressor outperformed Decision Tree Regressor, achieving an R2 score of 0.802 compared to 0.77. Both models indicate the importance of temperature and rainfall in predicting crop yield.

## Conclusion

The dataset represents two distinct crops with varying environmental and agricultural factors influencing crop yield. Temperature emerges as the most significant predictor, followed by rainfall, while fertilizer and macronutrient levels also play a role. The Random Forest Regressor model proves effective in predicting crop yield based on these factors. However, further analysis could explore additional variables and factors impacting crop yield.
