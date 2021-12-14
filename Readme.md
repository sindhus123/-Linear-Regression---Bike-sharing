# Demand prediction of Bike sharing company	
 ## Business Case
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. 
The company is finding it very difficult to sustain in the current market scenario. 
So, it has decided to come up with a mindful business plan to be able to accelerate its revenue.

- Objective:
	To build a multiple linear regression model for the prediction of demand for shared bikes.

- Scope:
	Demand history for the period of 2018 and 2019

## Steps Followed
* Business Case
* Data cleaning
* EDA
* Preparing the data for Linear Regression
* Building the Model
* Residual Analysis
* Prediction of the dependent variable
* Model Evaluation

## Model Interpretation
  1. Model 2 - all the p values are <0.05 & hence the coefficients are significant
  2. Temp has the highest co-efficient value of 0.57. This is aligned with the strong correlation between 'cnt' & 'temp'
  3. Next to 'temp', weather(0.25) & Year (0.23) are important co efficients in predicting the values
  4. All the coefficients have value (not equal to zero). Null hypothesis rejected
  5. P(F- static) is very less which explains fit is not by chance
  6. R Square is 84.5% & Adjusted R Square is 84% which explains the variance of the model
  7. Constant (intercept) is 0.284.So without any other predictor value we will have increase of 0.284 units

## Result

*Train Data: R Square = 0.845 ; Adjusted R Square = 0.841
*Test Data: R Square = 0.819 ; Adjusted R Square = 0.791

## Technologies Used
- pandas- version 1.0.1
- numpy- version 1.18.1
- seaborn- version 0.11.2
- skilearn
- stats models

## Contact
Created by [@sindhus123] - feel free to contact me!