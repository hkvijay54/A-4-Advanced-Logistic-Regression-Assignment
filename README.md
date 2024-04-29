# Surprise Housing - Housing Price Prediction Assignment
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

 Business Goal 

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
-through the model performance by Ridge Regression was better in R2 value of Train and test, it is better to use Lasso, since it brings and assigns a zero value to insignificant features, enabling us to choose the predictive variables.
-Suggestions for Surprise Housing is to keep a check on these predictors affecting the price of the house.¶
-The higher values of positive coeeficients suggest a high sale value.¶
-The higher values of negative coeeficients suggest a decrease in sale value.
-When the market value of the property is lower than the Predicted Sale Price, its the time to buy.¶

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
-numpy - version 1.20.3 -pandas - version 1.3.4 -matplotlib - version 3.4.3 -plotly - version 5.6.0 -seaborn - version 0.11.2 -statsmodels - version 0.12.2 -sklearn - version 0.24.2 -scipy - version 1.7.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project was based on upgrad .


## Contact
Created by [@hkvijay54] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
