# Simple-Linear-Regression
Code for simple linear regression model in machine learning from scratch.

We imported the dataset 'Salary_Data.csv'.
Then, the data was preprocessed where a matrix of independent variables 'X' and a dependent variable vector 'Y' was created.
We also dealt with missing data and categorical data as many ML algorithms can't work on label data directly so there is a need to convert categorical data into numberical data.
The dataset was split into the training set and test set.

From the sklearn.linear_model library, we import the LinearRegression Class. An object 'Regressor' is created and to fit this regressor into the training set, 'fit' method is used. 
Fit implies that the Regressor learnt the correlation between independent and dependent variables. 

To predict the test set results, a vector 'y_pred' containing the predictions of the test set salaries was created and then the results were visualised. 
