# Housing Price Prediction

## Introduction
Welcome to the Housing Price Prediction project! This README provides an overview of the project's specifications and the performance metrics of different regression models. The project aims to predict the actual value of prospective properties in Australia and determine the significance of variables in predicting house prices.

## Performance Metrics
The table below shows the performance metrics for different regression models:

| Metric            | Linear Regression | Ridge Regression | Lasso Regression |
|-------------------|-------------------|------------------|------------------|
| R2 Score (Train)  | 0.867513          | 0.929289         | 0.934527         |
| R2 Score (Test)   | 0.779924          | 0.857665         | 0.854518         |
| RSS (Train)       | 13.903831         | 7.420784         | 6.871023         |
| RSS (Test)        | 10.734863         | 6.942799         | 7.096313         |
| MSE (Train)       | 0.125555          | 0.091726         | 0.088263         |
| MSE (Test)        | 0.168298          | 0.135347         | 0.136835         |

## Conclusion
Based on the performance metrics, the Ridge Regression and Lasso Regression models outperform the Linear Regression model. They achieve higher R2 scores on both the training and testing datasets, indicating better prediction accuracy. Additionally, they demonstrate lower residual sum of squares (RSS) and mean squared error (MSE) values, suggesting reduced prediction errors.

The Lasso Regression model slightly outperforms the Ridge Regression model in terms of R2 score, although the difference is minimal. Therefore, both regularization techniques (ridge and lasso) offer improved predictive capabilities compared to standard linear regression.

These findings indicate that the selected independent variables have a significant impact on predicting house prices in the Australian market. The management of Surprise Housing can utilize these models to understand the pricing dynamics, prioritize investment opportunities, and maximize returns in the Australian housing market.

For a detailed analysis and further insights, please refer to the ipynb file.

If you have any questions or require additional information, please don't hesitate to reach out.