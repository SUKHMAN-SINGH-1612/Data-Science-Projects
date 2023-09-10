# Hotel Reservations Cancellation Prediction
![](https://static.vecteezy.com/system/resources/previews/000/474/062/original/hotel-reservation-conceptual-illustration-design-vector.jpg)
## Project Overview:

The goal of the Hotel Reservations Cancellation Prediction project is to anticipate potential reservation cancellations by analyzing various features and variables associated with hotel bookings. In the context of the project, online hotel reservation channels have revolutionized booking methods and customer behavior. However, a significant number of reservations are canceled, leading to revenue loss for hotels. Cancellations occur for reasons such as changes in plans or scheduling conflicts, often facilitated by the option of free or low-cost cancellations. This project seeks to predict such cancellations based on available data.

## Data Dictionary:

Here is a data dictionary summarizing the key columns in the dataset:

| Column Name                     | Description                                           |
|---------------------------------|-------------------------------------------------------|
| Booking_ID                      | Unique identifier of each booking                     |
| no_of_adults                    | Number of adults                                      |
| no_of_children                  | Number of children                                    |
| no_of_weekend_nights            | Number of weekend nights (Saturday or Sunday)        |
| no_of_week_nights               | Number of weeknights (Monday to Friday)              |
| meal_type                       | Meal type booked by the customer                     |
| required_car_parking_spaces     | Does the customer require a car parking space? (0 - No, 1 - Yes) |
| lead_time                       | Number of days between the booking date and arrival date |
| arrival_year                    | Year of arrival                                       |
| arrival_month                   | Month of arrival                                      |
| arrival_date                    | Date of arrival                                       |
| market_segment                  | Market segment designation                           |
| repeated_guest                  | Is the customer a repeated guest? (0 - No, 1 - Yes)   |
| no_previous_cancellations       | Number of previous bookings canceled by the customer prior to the current booking |
| previous_bookings_not_canceled  | Number of previous bookings not canceled by the customer prior to the current booking |
| avg_price_per_room              | Average price per day of the reservation (in euros)  |
| no_of_special_requests          | Total number of special requests made by the customer (e.g., high floor, view from the room, etc) |
| booking_status                  | Flag indicating if the booking was canceled or not  |

## Conclusion:

The exploratory data analysis of the Hotel Reservations Cancellation Prediction project revealed several key insights:

1. **Guest Composition**: Reservations made for 2 adults with no children, possibly representing couples, had the highest cancellation count. Reservations with children involved had lower cancellation rates.

2. **Booking Timing**: Most reservations were made for weeknights and had significantly higher cancellations compared to those made for weekend nights. 

3. **Year and Month**: The year 2018 had a higher cancellation rate compared to 2017, with the highest cancellations occurring in July and October.

4. **Services Impact**: Services opted for during reservation did not significantly impact reservation cancellations.

5. **Lead Time**: Lead time had a significant impact on reservation cancellations. Guests with shorter lead times were less likely to cancel, while longer lead times increased the likelihood of cancellations. This suggests that the hotel should consider accepting reservations with shorter lead times.

6. **Market Segment**: Reservations made through online platforms had the highest number of cancellations, emphasizing the importance of the hotel's online reputation.

In terms of predictive modeling, Decision Tree Classifier demonstrated the highest accuracy (85%) among the models employed, making it a promising choice for predicting reservation cancellations.

This project provides valuable insights for hotel management to optimize their reservation policies and reduce cancellations, ultimately improving revenue and customer satisfaction.
