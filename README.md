# House Price Prediction using Advanced Regression Techniques
> Surprise Housing, a housing firm based in the United States, has chosen to expand its operations into
the Australian market. Utilizing data analytics, the company strategically acquires properties at prices 
lower than their market worth, subsequently reselling them at higher prices for profit.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
1. Project Background:
A housing company based in the United States, Surprise Housing, has made the strategic decision to expand into the Australian market. Employing data analytics, the company aims to purchase properties below market value and sell them for a profit.

2. Business Problem:
The company is seeking potential properties to invest in as it enters the market. The task involves constructing a regression model using regularization to predict the true value of these prospective properties, facilitating investment decisions. Key objectives include identifying significant variables for predicting house prices and optimizing lambda values for ridge and lasso regression.

3. Dataset:
The dataset is contained within a CSV file named train.csv.

4. Project Objective:
The primary objective is to model house prices using available independent variables. Management intends to utilize this model to gain insights into how house prices vary with different variables, enabling strategic decision-making to maximize returns in the market. Additionally, the model will provide valuable insights into the pricing dynamics of the new market.

5. Approach to Solving the Business Problem:
   - Data Understanding and Exploratory Data Analysis (EDA)
   - Data Preparation
   - Model Training
   - Model Prediction and Evaluation
   - Ridge and Lasso Regularization
   - Conclusions and Results


## Conclusions
The top 5 predicted variables are:
> OverallQual - Higher material and finish quality of the house correlates with increased price.
> GrLivArea - Larger living area square footage corresponds to higher house prices.
> YearBuilt - Older houses tend to have higher prices.
> Total_sqr_footage - Greater overall square footage leads to higher house prices.
> Neighborhood_StoneBr - Houses located in Stone Brook neighborhood generally have higher prices.


## Technologies Used
- pandas==2.0.3
- numpy==1.24.3
- matplotlib==3.7.2
- seaborn==0.12.2
- statsmodels==0.14.0
- scikit-learn==1.3.0


## Contact
Created by [@anagharavishankar] - feel free to contact me!