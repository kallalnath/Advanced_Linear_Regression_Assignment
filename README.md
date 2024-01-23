# Assignment: Advanced Linear Regression
- We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)


## General Information
- This assignment is a programming assignment wherein we have to build a multiple linear regression model for the prediction of demand for house prices. We will need to submit a Jupyter notebook for the same. We will use Advanced Linear Regression techniques, viz., Ridge and Lasso.


**Problem Statement:**

- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

- The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

- The company wants to know:
 
 - Which variables are significant in predicting the price of a house, and
 - How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

**Business Goal:**

- We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Conclusions

- The variables (including from both Ridge and Lasso) significant in predicting the price of a house are: -
    - OverallQual_Very Excellent
    - 2ndFlrSF
    - Neighborhood_NoRidge
    - OverallQual_Excellent
    - GrLivArea
    - FullBath
    - 1stFlrSF
    - GarageCars
    - OverallQual_Very Good
    - TotRmsAbvGrd
    - LotArea
    - Neighborhood_NridgHt

**How well those variables describe the price of a house?** 
   1. **OverallQual_Very Excellent, OverallQual_Excellent, OverallQual_Very Good -** This is also evident from the box plot of OverallQual vs SalePrice that when the OverallQual is Excellent, Very Excellent or Very Good, there is highest impact om sale price.


   2. **1stFlrSF, 2ndFlrSF-** This is also evident from the scatter plot that both First Floor sq. ft. and 2nd floor sq. ft. are highly positively correlated to the sale price.


   3. **Neighborhood_NoRidge, Neighborhood_NridgHt -** This is evident from the box plot also that when the neighborhood is NoRidge, there is highest impact om sale price. This is followed by when the the neighborhood is NridgHt, there is second highest impact om sale price.


   4. **GrLivArea -** This is also highly positively correlated with sale price as is evident from the scatter plot. The correlation matrix below also shows that there is a positive correlation of 0.70.


   5. **FullBath -** This is evident from the scatter plot that if the number of Full bathrooms above ground increases the sale price also increases.


   6. **GarageCars -** As evident from the scatter plot, as the number of rooms increases the sale price also proportionately increases. This is observed till the number of garage cars is 3. When the number of garage cars is 4, the sale price decreases.


   7. **TotRmsAbvGrd -** As evident from the scatter plot, as the number of rooms increases the sale price also proportionately increases.


   8. **LotArea -** As evident from the scatter plot, sale price increases drastically with slight increase in lot area. This trend is seen upto a sq. ft. 40,000.



## Technologies Used
- numpy - 1.24.3
- python - 3.11.4
- seaborn - 0.13.0
- pandas - 1.5.3
- plotly - 5.17.0
- matplotlib - 3.7.1
- statsmodel - 0.14.0
- scikit-learn - 1.1


## Acknowledgements
Give credit here.
- This project was based on [Advanced Regression Assignment from Upgrad](https://learn.upgrad.com/course/4705/segment/27807/265961/812435/4081307).


## Contact
Created by [https://github.com/kallalnath] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

