# Car Price Prediction

## Objective: 
To predict the price of the cars

## Metric Used: 
Root Mean Square Log Error(RMSLE)
<p> Ideally a value closer to 0.0 indicates a better performing model. 

## Dataset: 
The training dataset consisted of 19,236 rows and 18 columns. 
The test dataset consisted of 8,245 rows and 18 columns. 

## Method: 
1. **Base-line model**: Linear Regression Model
* RMSLE on cross-validation dataset = 1.62,
* RMSLE on test dataset = 1.63

2. **Final Model**: Random Forest Regressor 
* RMSLE on cross-validation dataset = 1.34,
* RMLSE on test dataset = 1.45

#### NOTE: 
This project was as part of the MATHCO.THON hackathon hosted by MachineHack. [View details](https://machinehack.com/hackathons/data_hack_mathcothon_car_price_prediction_challenge/overview)
