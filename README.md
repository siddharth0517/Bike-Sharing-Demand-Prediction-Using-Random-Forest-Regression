# Bike Sharing Demand Prediction
This project aims to predict bike sharing demand using a Random Forest Regression model. The dataset includes features related to bike sharing and weather conditions. The goal is to predict the number of bike rentals based on various factors.

## Project Overview
The Bike Sharing Demand Prediction project uses machine learning techniques to forecast the demand for bike rentals. The model is trained on historical bike sharing data and includes features such as temperature, humidity, wind speed, hour of the day, and season.

## Dataset
The dataset used for this project is the Bike Sharing Dataset from the UCI Machine Learning Repository. It contains the following columns:

+ instant: Record index
+ dteday: Date
+ season: Season (1 = spring, 2 = summer, 3 = fall, 4 = winter)
+ yr: Year (0 = 2011, 1 = 2012)
+ mnth: Month (1 to 12)
+ hr: Hour of the day (0 to 23)
+ holiday: Whether the day is a holiday (0 = no, 1 = yes)
+ weekday: Day of the week (0 = Sunday to 6 = Saturday)
+ workingday: Whether the day is a working day (0 = weekend or holiday, 1 = working day)
+ weathersit: Weather situation (1 = Clear, Few clouds, Partly cloudy, 2 = Mist + Cloudy, 3 = Light Snow, 4 = Heavy Rain + Ice Pallets)
+ temp: Normalized temperature in Celsius (values ranging from 0 to 1)
+ atemp: Normalized "feels like" temperature in Celsius
+ hum: Normalized humidity levels
+ windspeed: Normalized wind speed
+ casual: Count of casual users
+ registered: Count of registered users
+ cnt: Total count of bike rentals (target variable)

## Model

## Random Forest Regression
A Random Forest Regression model is used to predict the number of bike rentals (cnt). The model is trained on features such as temperature, humidity, wind speed, hour, and season.

## Results
The project demonstrates how machine learning can be used to predict bike sharing demand. Key insights include the effect of weather conditions and time of day on bike rentals.

## Contributing
Feel free to open issues or submit pull requests if you have suggestions for improvements or additional features.
