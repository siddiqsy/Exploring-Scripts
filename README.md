# Exploring-Scripts
Learning python and pyspark

## Classifying data with logistic regression: 

- What you should know: Understanding machine learning, Basic knowledge o python, Some familiarity with pandas and sklearn packages, how to interat with a Jupyter notebook

## What is regression?
regression analysis refers to the family of machine learning algorithms that are used to quantify size and strength of two or more variables. One of the type of supervised machine learning algorithm is regression and the other is classification 
Classification has response varibale as qualitative or catagorical value.  
Regression has response varibale to be quantitative or continuous value. Eg: Prediction of annual sales. 
To build models we need data that is related to real world extracted
Using dependent and independent variables regression model can be developed. 
A function can be generated with estimation to predict new data. 

## The anatomy of regression model: 
Three components to a regression model:
1. The response that we want to predict 2. One or more predictor variables 3. Coefficients which descibe the relationship between predictor variables. 

## Common types of regression models: 
Simple Liner Regression: If we have a single predictor variable X and assume that the relationship between the predictor variable and the response Y is linear, then we use simple linear regression. 
Multiple Linear Regression: If we have more than one predictor variable and assume that the relationship between the predictor variable and the response Y is linear, then we use multiple linear regression. 
Poisson Regression: If we assume that the relationship between the predictor variable X and the response Y is log-linear or exponential, then we use Poisson Regression. 
Logistic Regression: If we assume that the relationship between the predictor variables X and the response varibale Y is binary or dichotomous then we use Logistic Regression. 

## Types of Logistic regression models: 
1. Binomial - Only two possible values for the response variable. 2. Multinomial - Three or more values for the response variable. 3. Ordered - Response values have an inherent order. 

## Prediction making using logistic regression: 
logit function used here varies from -inf to + inf. Convertion from linear expression to odds and odds to probability needs to be calculated. 

## Interpreting the coefficients of logistic regression: 
log odds need to be calculated. from log odds probability can be calculated. If coefficient for the predictor is positive increase in predictor will result in increase in probability of the response, and vice versa

## When to use logistic regression model: 
Generally they are easy to train and doesnot require hyperparameter values, very efficient to train, does not require that predictors be scaled, output is easy to understand, able to handle a resonable number of categorical features. 
Disadvantages are they underperform when there are multiple or non-linear decision boundaries, makes strong assumptions about the data, doesnot naturally capture complex relationships, does not do well with missing or outliers data. 
