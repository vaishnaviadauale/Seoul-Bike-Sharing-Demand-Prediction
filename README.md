# Seoul-Bike-Sharing-Demand-Prediction

# 📖Problem statement
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

# 📖Attribute Information:

🔶Date : year-month-day

🔶Rented Bike count - Count of bikes rented at each hour

🔶Hour - Hour of he day

🔶Temperature-Temperature in Celsius

🔶Humidity - %

🔶Windspeed - m/s

🔶Visibility - 10m

🔶Dew point temperature - Celsius

🔶Solar radiation - MJ/m2

🔶Rainfall - mm

🔶Snowfall - cm

🔶Seasons - Winter, Spring, Summer, Autumn

🔶Holiday - Holiday/No holiday

🔶Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

![image](https://github.com/user-attachments/assets/eb432c06-4271-491a-a414-876353ed2e5f)

# 📖Project Flowchart:

1 Loading data and Diagnosing the data

2 Data Filtering

3 EDA of Row data to understand inside correlations

4 Feature Engineering

5 Feature Selection : we are not use much beacuase of limited features in our data(only one feature elemenate using hitmap to escalate multicoliniarity issue)

6 Model Building

7 Model Training and Testing

# 📖Conclusion

xgbregressor and Randomforest models shows promising result, therefore it can be used to solve this problem.

Bike rental count is high during week days than on weekend.

Bike demand shows peek around 8-9 AM in the morning and 6 - 7pm in the evening.

People prefer to rent bike more in summer than in winter.

Bike demand is more on clear days than on snowy or rainy days.

Temperature range from 22 to 25(°C) has more demand for bike.

'Hour', 'Temperature(°C)', 'Humidity', 'Wind_speed','Visibility ', 'Dew_point_temperature', 'Solar_Radiation', 'Rainfall', 'Snowfall', 'Seasons', 'Holiday', 'month', 'day of week ' regulates bike demand.
