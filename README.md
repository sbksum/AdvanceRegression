#  Surprise Housing Advance Regression  (Lassso and Ridge)
> .



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

 

- The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

 



## Business Goal 

 

- You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- Top 10 variables that  are significant in predicting the price of a house

- Top 10 Predictor variables for Ridge with optimal value of alpha = 10 are as below. 
1.	MSZoning_RL                                 0.092868
2.	MSZoning_RM                                 0.075064
3.	OverallQual                                 0.065915
4.	GrLivArea                                   0.058130
5.	MSZoning_FV                                 0.045185
6.	GarageCars                                  0.043404
7.	OverallCond                                 0.043175
8.	2ndFlrSF                                    0.040472
9.	Neighborhood_NridgHt                        0 .037209
10.	1stFlrSF                                    0.033143

- For Lasso regression with optimal value of alpha=.001 , predictor and coefficients are as follow. 
1.	GrLivArea                                   0.107182
2.	MSZoning_RL                                 0.071812
3.	OverallQual                                 0.071131
4.	MSZoning_RM                                 0.050647
5.	GarageCars                                  0.045065
6.	OverallCond                                 0.044631
7.	MSZoning_FV                                 0.032043
8.	Neighborhood_NridgHt                        0.031903
9.	Neighborhood_Somerst                        0.028879
10.	Neighborhood_Crawfor                        0.028291

- How well those variables describe the price of a house.

- coefficient weights is listed in front of the predicted variables above for both Ridge and Lasso Regression. 
 

- Also, determine the optimal value of lambda for ridge and lasso regression.

- Ridge Regression, Optimal value of alpha = 10 
- Lasso Regression  - Optimal value of alpha =0.001

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- Pandas
- Numpy
- Matplot library 
- Seaborn library
- sklearn
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@sbksum] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->