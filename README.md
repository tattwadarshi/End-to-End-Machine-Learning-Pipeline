# End-to-End-Machine-Learning-Pipeline #

## Complete Pipeline for House Prices Prediction ##

_In this project we built an entire end to end machine learning pipeline for accurate house prices prediction. We divide the project into 4 steps. Each step has a separate purpose._

* Step 1: In the first stage we do a prelimnary data analysis to identify:
  * Missing values
  * Numerical variables
  * Distribution of the numerical variables
  * Outliers
  * Categorical variables
  * Cardinality of the categorical variables
  * Potential relationship between the variables and the target: SalePrice
  
* Step 2: In the second stage we apply a variety of feature engineering techniques to engineer the variables so that we tackle:
   * Missing values
   * Temporal variables
   * Non-Gaussian distributed variables
   * Categorical variables: remove rare labels
   * Categorical variables: convert strings to numbers
   * Standarise the values of the variables to the same range
   
* Step 3: In the third stage we select a group of variables, the most predictive ones, to build our machine learning model. We will select variables using the Lasso regression: Lasso has the property of setting the coefficient of non-informative variables to zero. This way we can identify those variables and remove them from our final model.
 
* Step 4: In this stage we finally build our machine learning model, utilising the engineered data and the pre-selected features.

* Step 5: **Here, we will summarise the key pieces of code, that we need to take forward for this particular project, to put our model in production.**
_Now we want to deploy our model. We want to create an API, which we can call with new data, with new characteristics about houses, to get an estimate of the SalePrice. In order to do so, we need to write code in a very specific way._
   
   
 
