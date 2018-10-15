# Kaggle-Competiton
My predictions on "Find the secret binary outcome" using different models.
  ## 1. Logistic Regression Model(https://github.com/aparnaaidith/Kaggle-Competiton/blob/master/Find%20the%20secret%20binary%20outcome%20-%20using%20Logistic%20Regression.ipynb)
   ### What is Logistic Regression?
   Logistic regression is the appropriate regression analysis to conduct when the dependent variable is dichotomous (binary).    Like all regression analyses, the logistic regression is a predictive analysis.  Logistic regression is used to describe      data and to explain the relationship between one dependent binary variable and one or more nominal, ordinal, interval or      ratio-level independent variables.
   
   ### Assumptions in Logistic Regression :
   Any logistic regression example in Python is incomplete without addressing model assumptions in the analysis. The important    assumptions of the logistic regression model include:

   1. Target variable is binary
   2. Predictive features are interval (continuous) or categorical
   3. Features are independent of one another
   4. Sample size is adequate – Rule of thumb: 50 records per predictor
  ## 2. Linear Regression Model(https://github.com/aparnaaidith/Kaggle-Competiton/blob/master/Find%20the%20secret%20binary%20outcome%20-%20using%20Linear%20Regression.ipynb)
  ### What is Linear Regression?
  Linear regression is a basic and commonly used type of predictive analysis.  The overall idea of regression is to examine     two things: 
  (1) does a set of predictor variables do a good job in predicting an outcome (dependent) variable?  
  (2) Which variables in particular are significant predictors of the outcome variable, and in what way do they–indicated by      the magnitude and sign of the beta estimates–impact the outcome variable?  
  
  These regression estimates are used to explain therelationship between one dependent variable and one or more independent     variables.The simplest form of the regression equation with one dependent and one independent variable is defined by the       formula y = c + b*x, where y = estimated dependent variable score, c = constant, b = regression coefficient, and x = score     on the independent variable.
  ## 3. XGBRegressor Model (https://github.com/aparnaaidith/Kaggle-Competiton/blob/master/Find%20the%20secret%20binary%20outcome%20-%20using%20XGBRegressor.ipynb)
   For more details click on https://www.kdnuggets.com/2017/10/xgboost-top-machine-learning-method-kaggle-explained.html
  ## 4. Ridge and Lasso Regression
   Ridge and Lasso regression are powerful techniques generally used for creating parsimonious models in presence of a ‘large’    number of features. Here ‘large’ can typically mean either of two things:

   1. Large enough to enhance the tendency of a model to overfit (as low as 10 variables might cause overfitting)
   2. Large enough to cause computational challenges. With modern systems, this situation might arise in case of millions or          billions of features
   Though Ridge and Lasso might appear to work towards a common goal, the inherent properties and practical use cases differ      substantially. If you’ve heard of them before, you must know that they work by penalizing the magnitude of coefficients of    features along with minimizing the error between predicted and actual observations. These are called ‘regularization’          techniques. The key difference is in how they assign penalty to the coefficients:

   ### Ridge Regression:
   1. Performs L2 regularization, i.e. adds penalty equivalent to square of the magnitude of coefficients
   2. Minimization objective = LS Obj + α * (sum of square of coefficients)
   ### Lasso Regression:
   1. Performs L1 regularization, i.e. adds penalty equivalent to absolute value of the magnitude of coefficients
   2. Minimization objective = LS Obj + α * (sum of absolute value of coefficients)
   
   Note that here ‘LS Obj’ refers to ‘least squares objective’, i.e. the linear regression objective without regularization.
   
   ## 5. Random Forest
   Random Forest is a supervised learning algorithm. Like you can already see from it’s name, it creates a forest and makes it    somehow random. The „forest“ it builds, is an ensemble of Decision Trees, most of the time trained with the “bagging”          method. The general idea of the bagging method is that a combination of learning models increases the overall result.

   To say it in simple words: Random forest builds multiple decision trees and merges them together to get a more accurate and    stable prediction.
   
   One big advantage of random forest is, that it can be used for both classification and regression problems, which form the    majority of current machine learning systems. I will talk about random forest in classification, since classification is      sometimes considered the building block of machine learning.

