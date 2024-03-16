# Linear Regression

I have attempted to write the Linear Regression algorithm from scratch. This repository is basically my notes and jupyter notebook made public. The implementation includes the following key components:

- **Linear Regression Class**: I have defined a class to encapsulate the Linear Regression algorithm.
- **Gradient Descent**: The algorithm utilizes gradient descent to optimize the model parameters.
- **Fit Method**: The `fit` method is implemented to train the model on the provided data.
- **Predict Method**: A `predict` method is included to make predictions using the trained model.
- **Score**: A `score` method to evaluate the model.

The code is structured to demonstrate a basic implementation of Linear Regression without relying on external libraries like scikit-learn. This project serves as a learning exercise to understand the inner workings of the Linear Regression algorithm.

Feel free to explore the code and provide any feedback or suggestions for improvement. Your contributions and insights are highly appreciated!

## Theory and Notes


#### Linear regression is a fundamental statistical method used to understand the relationship between a dependent variable and one or more independent variables. It aims to find the best-fitting linear equation that predicts the dependent variable based on the independent variables. In simpler terms, linear regression helps us analyze how changes in one variable are associated with changes in another, allowing us to make predictions and uncover patterns in data.
![image](https://github.com/atomikkus/linear_regression/assets/87168509/e705a4fa-286d-4e10-91cc-434f8dc9b47a)

The assumptions of linear regression include several key criteria that need to be met for the model to be valid:
- *Linearity* : The relationship between the independent and dependent variables should be linear.
- *Normality*: The residuals (errors) should follow a normal distribution.
- *Homoscedasticity*: The variance of the residuals should be constant across all values of the independent variable.
- *Independence of Errors*: The errors should be independent of each other.
- *No Multicollinearity*: The independent variables should not be highly correlated with each other.
These assumptions ensure the reliability and accuracy of the linear regression model in making predictions and drawing inferences from the data
