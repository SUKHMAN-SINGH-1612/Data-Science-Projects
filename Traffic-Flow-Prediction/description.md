# Traffic Flow Prediction
<img src = "https://th.bing.com/th/id/R.2f52a356c87d4d40374404cd30140c35?rik=CYZ0xVw1sOqSgQ&riu=http%3a%2f%2fi.huffpost.com%2fgen%2f1324194%2fimages%2fo-DRIVERS-TRAFFIC-facebook.jpg&ehk=AT7XxdZq5EDQ%2fMl%2bQzQuogHdXmQXglRKGUiBVhx4FlU%3d&risl=&pid=ImgRaw&r=0" width = "700" height = "500">

This project aims to predict traffic flow based on historical data, including vehicle counts (cars, bikes, buses, trucks), time, and day of the week. By analyzing this data, we seek to identify patterns in traffic flow, predict traffic situations, and provide actionable insights to manage congestion and improve urban mobility. The model also aids in optimizing traffic control strategies and contributes to sustainability goals by reducing emissions and fuel consumption through better traffic management.

## Data Dictionary

The dataset contains traffic flow records, including:

Time: Timestamp of the observation
Date: Date of the observation
Day of the week: Day corresponding to the observation
CarCount: Number of cars counted at the observation point
BikeCount: Number of bikes counted
BusCount: Number of buses counted
TruckCount: Number of trucks counted
Total: Total number of vehicles at the timestamp
Traffic Situation: The categorized traffic condition (e.g., congestion levels)

## Data Preprocessing

Steps:
Time & Date Formatting: The Time and Date columns were converted to appropriate formats (datetime). New features, such as Hour, Month, and Day, were extracted to capture temporal patterns.
Handling Categorical Data: The Day of the week and Traffic Situation were label encoded into numerical values for model compatibility.
Missing Values: Missing values in the dataset were replaced with median values of the respective columns.

## Exploratory Data Analysis (EDA)

Through EDA, several important traffic patterns emerged:

Peak Hours: Morning and evening rush hours showed spikes in car and bike counts, while bus and truck counts remained relatively stable throughout the day.
Vehicle Types: Cars consistently represented the highest volume of traffic, followed by bikes, buses, and trucks. Trucks had the lowest overall volume.
Traffic Situations: Traffic conditions worsened as truck traffic increased, with fewer occurrences of light or no traffic (lower traffic situation categories).
Day of the Week: There was no significant variation in total traffic across different days, although individual vehicle types showed some variability in their distributions.

## Model Building and Evaluation
Model: Random Forest Classifier
A Random Forest Classifier was trained to predict traffic situations based on the available features. The model performed well in predicting high-traffic periods, offering valuable insights for traffic management.

Evaluation Metrics:
Confusion Matrix: Used to analyze prediction errors and true positives.
Classification Report: Provided precision, recall, and F1-score for each traffic situation category.
Accuracy: The model achieved a satisfactory accuracy in classifying traffic situations.

Feature Importance
The most significant features affecting traffic flow prediction were:
1) CarCount
2) BikeCount
3) Day of the week
4) Hour of the day These features played a critical role in predicting the traffic situation.

Graphical Insights
Several visualizations were generated to enhance understanding:

Traffic volume over time: Cars and bikes dominate during peak hours, while trucks remain steady.
Day-wise Traffic Spread: Different vehicle types exhibit unique spread patterns across the week, though total traffic volume remains fairly stable.
Pairwise Correlation: Positive correlation between CarCount and BikeCount, and a negative correlation between TruckCount and Traffic Situation, indicating heavier truck traffic during congested conditions.

## Conclusion

The Traffic Flow Prediction project highlights the significant role of vehicle counts, time, and day in understanding traffic patterns. It provides critical insights into peak congestion periods and informs strategies to manage urban traffic effectively. By predicting traffic flow, city planners and traffic authorities can optimize signal timings, adjust public transport schedules, and improve road usage during off-peak times. These predictions contribute to building smart cities by integrating real-time data for dynamic traffic management, minimizing disruptions, and reducing environmental impact.

Moreover, this project emphasizes the broader implications for sustainable urban mobility, suggesting ways to enhance traffic management systems and reduce vehicular emissions. Accurate traffic predictions can lead to more efficient road networks, supporting economic productivity by reducing time spent in traffic and improving overall transportation systems.
