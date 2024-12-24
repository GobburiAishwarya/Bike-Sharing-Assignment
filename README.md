# Bike-sharing-assignment
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

- Boom Bikes have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

1) Which variables are significant in predicting the demand for shared bikes.
2) How well those variables describe the bike demands

## Business Goal is as below:

We have to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations.

## Conclusions

- Model 6 from the notebook have lesser predictors making it easier to interpret how each variable affect the demand for bikes
- It is also simpler. Simpler model is always prefferable.
    - Variables to predict the demand for bikes are :
    - temperature
    - Year
    - season_spring
    - season_summer
    - season_winter
    - weathersit_Misty
    - windspeed
    - mnth_Sep
    - weekday_sun
    - weathersit_Light_snow_rain
- We have used the data set - day.csv

## Technologies Used
- numpy - version 1.26.4
- pandas - version 2.2.2
- matplotlib - version 3.8.4
- seaborn - version 0.13.2
- statsmodels - version 0.14.2
- sklearn - version 1.4.2

## Acknowledgements
- This project was inspired by Linear Regression session on Upgrad by Dinesh J Babu (https://in.linkedin.com/in/dinesh-babu-jayagopi-22a706)
- UpGrad tutorials on Linear Regression are on the learning platform
  
## Contact
Created by [@AishwaryaGobburi](https://github.com/GobburiAishwarya) - feel free to contact me!
