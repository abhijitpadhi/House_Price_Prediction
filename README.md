# HOUSE PRICE PREDICTION USING REGULARISATION 
> A US-based housing company named Surprise Housing has  decided to enter the Australian market. The company uses data analytics to  purchase houses at a price below their actual values and flip them on at a  higher price. For the same purpose, the company has collected a data set  from the sale of houses in Australia.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- It is required to model the price of houses with the available independent variables. This  model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market..
- Analysis of data set using Advance Regression with Regularisation
- A  regression model using regularization in order to predict the actual value of the prospective properties and decide whether to invest in them or not Which variables are significant in predicting the price of a house, and How well those variables describe the price of a house.
- The data set with name "train.csv" is used.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- the Ridge Regression is showing better than Lasso Regression as R2 Score(Test) is slightly higher, RSS and MSE is comparatively lower than Lasso.
- The R2 Score of Ridge is 0.88 in training set where as 0.85 in test set and the difference is not more than 4.
- What we need is lowest total error, i.e., low bias and low variance, such that the model identifies all the patterns and is also able to perform well with unseen data.
- So we conclude that our model is robust and generalisable.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy version	    : 1.20.3
- pandas version	: 1.3.4
- seaborn version	: 0.11.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Advance Regression with Regularisation.
- This project was based on "house price predection".


## Contact
Created by [@abhijitpadhi] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->