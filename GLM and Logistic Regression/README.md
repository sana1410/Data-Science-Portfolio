# GLM and LOGISTIC REGRESSION
## INTRODUCTION :-
## Generalised Linear Models :-
Generalised liner modeling technique is the generalisation of linear regression predictive model to various non linear distribution.For GLM we do not need our target variable to be normally distributed. The target variable can be binary or even counts.
GLM is advanced modelling technique and is applied when the relationship between predictor and target variable is non linear . 
The various types of GLM are :-
1.	Logistic Regression-used when target variable is 0 or 1
2.	Possion Regresion-used when target variable is counts or frequency
3.	Linear Regression-for normally distributed target variable
There are 3 componenets of GLM 
### 1.	Random component :- 
the target variable distribution
### 2.	System component :- 
the linear combination of predictor variables 
### 3.	Link Functions :- 
function that specifies the link between random and systematic components
## LOGISTIC REGRESSION :-
Logistic Regression is a type of genaralised linear model in which the target variable is binary or categorical variable expressed in form of either 0 or 1 . It can be treated as classification model.
In logistic regression we predict the probabilities of occurance of target variable based on given set of predictor variables . The relationship between predictor variables and probabilities is non linear and ranges between 0 and 1 .
 
Hence the link function used in logistics regression is logit or probit function which gives the outcome in form of 0 or 1 .
![](Images/Module 3 formula.jpg)
 
## OBJECTIVE:-
The objective of this project is use college dataset having list of public and private US colleges from the 1995 with various measures like no of appication , enrollment and acceptance rate , tution fees and no of graduates etc .
1. We need to build a logistic regression model to predict whether a college with given set of measures is public/private .The target variable is binary with 2 level that is “yes /No”.
2. After model Creation we need to test the model with test data and check the model accuracy .


