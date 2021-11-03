# insurance-using-linearregression
We will use a real dataset to demonstrate simple linear regression. The dataset is called the “Auto Insurance in Sweden” dataset and involves predicting the total payment for all the claims in thousands of Swedish Kronor (y) given the total number of claims (x).

This means that for a new number of claims (x) we will be able to predict the total payment of claims (y).

Linear regression assumes a linear or straight line relationship between the input variables (X) and the single output variable (y). More specifically, that output (y) can be calculated from a linear combination of the input variables (X). When there is a single input variable, the method is referred to as a simple linear regression.

In simple linear regression we can use statistics on the training data to estimate the coefficients required by the model to make predictions on new data.

The line for a simple linear regression model can be written as:

𝑦=𝑏0+𝑏1∗𝑥

where 𝑏0 and 𝑏1 are the coefficients we must estimate from the training data. Once the coefficients are known, we can use this equation to estimate output values for 𝑦 given new input examples of 𝑥 . It requires that you calculate statistical properties from the data such as mean, variance and covariance.
