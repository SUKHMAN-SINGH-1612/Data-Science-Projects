# Occupancy Prediction from Sensor Data
![](https://code.datasciencedojo.com/datasciencedojo/datasets/raw/master/Occupancy%20Detection/O6YGSH0.jpg)
The Occupancy Prediction project aims to predict whether a room is occupied or not based on the data collected from various sensors. The dataset used in this project is obtained from the UCI Machine Learning Repository and consists of 7 attributes, namely date, temperature, humidity, light, CO2, humidity ratio, and occupancy.
## Dataset Description
The dataset contains experimental data used for binary classification of room occupancy in an office room. The key features used for prediction are Temperature, Humidity, Light, and CO2. The ground-truth occupancy labels were obtained from time-stamped pictures taken every minute.
## Data Attributes
- Date: The date and time of the data entry.
- Temperature: The ambient temperature of the room.
- Humidity: The relative humidity of the room.
- Light: The light intensity in the room.
- CO2: The carbon dioxide level in the room.
- Humidity Ratio: The ratio of water vapor in the air to the amount of dry air.
- Occupancy: The binary target variable indicating whether the room is occupied (1) or not (0).

## Data Dictionary
| Column   Position 	| Atrribute Name 	| Definition                                                                                           	| Data Type    	| Example                                        	| % Null Ratios 	|
|-------------------|----------------|---------------------------------------|--------------|------------------------------------------------|---------------|
| 1                 	| Date           	| Date & time in year-month-day hour:minute:second format                                              	| Qualitative  	| 2/4/2015 17:57, 2/4/2015 17:55, 2/4/2015 18:06		 	| 0             	|
| 2                 	| Temperature    	| Temperature in degree Celcius                                                                        	| Quantitative 	| 23.150, 23.075, 22.890                         	| 0             	|
| 3                 	| Humidity       	| Relative humidity in percentage                                                                      	| Quantitative 	| 27.272000, 27.200000, 27.390000                	| 0             	|
| 4                 	| Light          	| Illuminance measurement in unit Lux                                                                  	| Quantitative 	| 426.0, 419.0, 0.0	                              	| 0             	|
| 5                 	| CO2            	| CO2 in parts per million (ppm)                                                                       	| Quantitative 	| 489.666667,   495.500000, 534.500000           	| 0             	|
| 6                 	| HumidityRatio  	| Humadity ratio:  Derived quantity from temperature and   relative humidity, in kgwater-vapor/kg-air  	| Quantitative 	| 0.004986, 0.005088, 0.005203                   	| 0             	|
| 7                 	| Occupancy      	| Occupied or not: 1 for occupied and 0 for not occupied                                               	| Quantitative 	| 1, 0                                           	| 0             	|
## Goal
The primary goal of this project is to build an efficient binary classification model that accurately predicts room occupancy based on sensor data.
## Model Selection
To achieve this goal, machine learning algorithms, random forests was used and it gave an accuracy of 98%.
## Impact
The Occupancy Prediction project has the potential to revolutionize various domains, including energy efficiency, resource allocation, safety, and IoT applications. By accurately predicting room occupancy based on sensor data, it can enable smart building automation, optimize resource usage, enhance security measures, and promote sustainable practices. Additionally, it offers valuable insights into occupancy patterns, empowering researchers and policymakers to make informed decisions for a more efficient and comfortable living and working environment.
