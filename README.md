# Ridge and Lasso Regression
> You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named **Surprise Housing** has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
- The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- The company wants to know:
    - Which variables are significant in predicting the price of a house, and
    - How well those variables describe the price of a house.
- Also, determine the optimal value of lambda for ridge and lasso regression.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
### After performing the analysis and building the Ridge and Lasso Regression Models, we have reached to the following conclusions:
- The size of the database was around 147 features after creation of dummy variables on categorical features. We used RFE to select top 50 features out of 147 total features. 
- The optimum alpha values selected by Ridge and Lasso using the GridSearchCV method are 50 and 0.001 respectively.
- Ridge Regression gave R2 value on the train data set 0.9197662757946696 and on test data set is 0.885161713208492.
- Ridge Regression gave R2 value on the train data set 0.9220783927747972 and on test data set is 0.8876701333878119.
- Lasso Regression producing slightly better results than Ridge. So Lasso chosen as a final model.
- Lasso Regression shows following factors more beneficial on predicting the SalePrice:
    - MSZoning_RL	0.110563
    - GrLivArea	    0.107530
    - MSZoning_RM	0.073679
    - OverallQual	0.072340
    - YearBuilt	    0.067609
    - OverallCond	0.052744
    - MSZoning_FV	0.050305
    - BsmtFinSF1	0.048439
    - 1stFlrSF	    0.038160
    - 2ndFlrSF	    0.035621


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.8.8
- Jupyter Notebook - version 6.3.0
- Numpy - version 1.20.1
- Pandas - version 1.2.4
- Matplotlib - version 3.3.4
- Seaborn - version 0.11.1
- sklearn - version 0.24.1
- statsmodels - version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- I would like to thank Upgrad and IIIT Bangalore for giving me a chance to work on this project.


## Contact
Created by Amrinder Singh Bajwa (amrinder_bajwa@hotmail.com) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
