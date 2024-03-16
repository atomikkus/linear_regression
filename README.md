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

### Evaluation of the Model

When assessing the performance of a linear regression model, several evaluation metrics are commonly used to understand how well the model fits the data and makes predictions. Here, we will discuss Mean Absolute Error (MAE), R-squared (R2), and Mean Squared Error (MSE) as key evaluation metrics for linear regression models.

#### Mean Absolute Error (MAE)
- **Definition**: MAE measures the average absolute difference between the actual values and the predicted values.
- **Interpretation**: A lower MAE indicates that the model's predictions are closer to the actual values.
- **Usage**: MAE is suitable when you want to understand the average magnitude of errors in your predictions without considering their direction.
- ![image](https://github.com/atomikkus/linear_regression/assets/87168509/95701390-5ece-46f4-8a56-dcf42bbcd11d)

#### Mean Squared Error (MSE)
- **Definition**: MSE calculates the average of the squared differences between the actual values and the predicted values.
- **Interpretation**: MSE penalizes larger errors more heavily than smaller errors.
- **Usage**: MSE is commonly used to evaluate the accuracy of a regression model by looking at the average squared differences between predicted and actual values.
- ![image](https://github.com/atomikkus/linear_regression/assets/87168509/372825ca-d318-41d6-bad1-b5544724ddbd)


#### R-squared (R2)
- **Definition**: R2 represents the proportion of the variance in the dependent variable that is predictable from the independent variables.
- **Interpretation**: R2 value ranges from 0 to 1, where 1 indicates a perfect fit.
- **Usage**: R2 is used to understand how well the independent variables explain the variability in the dependent variable.
- ![image](https://github.com/atomikkus/linear_regression/assets/87168509/16a55809-4b64-42de-8a65-350092b89a5c)


These evaluation metrics play a crucial role in assessing the performance of linear regression models and provide insights into how well the model generalizes to new data and how accurately it predicts the target variable based on the features.

#### Useful Links
- [Understanding How To Interpret R2, MSE and MAE](https://ai.plainenglish.io/understanding-common-regression-evaluation-metrics-mae-mse-rmse-r2-and-adjusted-r2-6c5709e614c4)
- [Assumtions of Linear Regression](https://www.jmp.com/en_us/statistics-knowledge-portal/what-is-regression/simple-linear-regression-assumptions.html)
- [Visualize Gradient  Descent](https://uclaacm.github.io/gradient-descent-visualiser/)
- [Linear Regression from  scratch in Python](https://machinelearningmastery.com/implement-simple-linear-regression-scratch-python/)