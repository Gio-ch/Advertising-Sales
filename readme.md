# Sales Prediction using Linear Regression
This project explores the use of Linear Regression on a dataset that describes the relationship between 'Sales' and three types of advertising budget: 'TV', 'Radio', and 'Newspaper'. The model was trained to predict 'Sales' given the budgets for the advertising types.

## Project Objective
The objective was to create a model that can accurately predict Sales based on the amounts spent on different types of advertising.

## Methodology
The project used a Linear Regression model from the scikit-learn library in Python. The model was trained on 70% of the data, and tested on the remaining 30%. 

## Results
The model achieved an R-squared of 86.56%, indicating that it was able to explain about 86.56% of the variance in the Sales from the advertising budgets. However, the Root Mean Squared Error was 1.915, indicating that the model predictions are, on average, approximately ±1.915 (sales unit as per your data) away from the actual sales. This suggests there might be other factors influencing Sales that our model does not account for.

## Future Work

Future iterations of the project could explore more complex models like polynomial regression or random forests, or using feature engineering to uncover more complex relationships within the data.
