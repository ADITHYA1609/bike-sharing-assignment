# BIKE SHARING SYSTEM 
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [FINAL REPORT](#FINAL REPORT)
* [Acknowledgements](#acknowledgements)

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
- In this project i have modelled the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features..
- data set - day.csv(present in this respository)

# FINAL REPORT

- As per our final Model, the top 3 predictor variables that influences the bike booking are:
- Temperature (temp) - A coefficient value of ‘0.5636’ indicated that a unit increase in temp variable increases the bike hire numbers by 0.5636 units.

- Weather Situation 3 (weathersit_3) - A coefficient value of ‘-0.3070’ indicated that, w.r.t Weathersit1, a unit increase in Weathersit3 variable decreases the bike hire numbers by 0.3070 units.

- Year (yr) - A coefficient value of ‘0.2308’ indicated that a unit increase in yr variable increases the bike hire numbers by 0.2308 units.

- So, it's suggested to consider these variables utmost importance while planning, to achive maximum Booking

- The next best features that can also be considered are

- season_4: - A coefficient value of ‘0.128744’ indicated that w.r.t season_1, a unit increase in season_4 variable increases the bike hire numbers by 0.128744 units.

- windspeed: - A coefficient value of ‘-0.155191’ indicated that, a unit increase in windspeed variable decreases the bike hire numbers by 0.155191 units.


## Technologies Used
- basic libraries - numpy, pandas, mathplotlib
- ml libraries - statsmodels, sklearn, 

## Acknowledgements
Give credit here.
- This project was inspired by and based on "https://learn.upgrad.com/course/3094/segment/26812/166535/510153/2623181".


## Contact
Created by [@ADITHYA1609] - feel free to contact me!
