# Regression Diagnostic with R
## INTRODUCTION: - 
In this project we are going to fit, interpret and evaluate linear regression model on “AmesHousing” dataset. We are also going to implement diagnostic techniques to identify and correct issues with the model. We are also going to test that our model is following the assumption of linear regression.
## LINEAR REGRESION MODEL: -
Linear regression is a predictive analysis method used to model the relationship between a dependent variable and one or more independent variables. The basic idea behind linear regression is to find the best-fit straight line that determines the relationship between the variables.
A linear regression model can be written as 
### `Y=βo+β1X1+β2X2+β3X3+…….βNXN +ε`
where Y=target variable
X1, X2,X3….XN:-Predictor variables 
β0 is intercept, β1,β2,β3….βN are coefficients and ε<- it is the error
  
## ORDINARY LEAST SQUARE METHOD:-
The Ordinary Least Squares (OLS) method is a commonly used technique in linear regression analysis. It is used to estimate the parameters (coefficients) like β0,β1 of a linear regression model that minimizes the sum of the squared differences between the predicted value and actual values of the target variable.
### `Residuals ε=Y(Observed)-Y(Predicted`

### ASSUMPTIONS OF LINEAR REGRESSION: -
### 1.Linearity of the data: - 
The linear relationship between the predictor and the target (y) .We have assumed that there is a linear relationship between our target variables and predictor variables . This means that change in independent variable should be proportional to dependent variable.
### 2.Normality of residuals:- 
The residuals should be distributed normally. This means that distribution should follow the bell curve.
### 3.Homogeneity of residuals variance:- 
The residuals should have a constant variance.
### 4.No Multicollinearity: - 
The predictor variables should be independent of each other .
## Exploratory Data Analysis


