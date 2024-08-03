## Summary

The Car Price Prediction project aims to develop an accurate and reliable model for predicting car prices based on various features. By utilizing multiple machine learning algorithms, the project seeks to determine the most effective model for this regression task. The ultimate goal is to provide a tool that can estimate car prices with high precision, aiding consumers and businesses in making informed decisions.

To achieve the highest accuracy in car price prediction, three different machine learning models were employed: Linear Regression, Random Forest Regressor, and Support Vector Regression (SVR). Each model was evaluated based on its R-squared score, a key metric that measures the proportion of variance in the dependent variable that can be predicted from the independent variables.

1. Linear Regression Model

* R-squared Score: 100%

* Performance: The Linear Regression model achieved a perfect fit for the target variable, indicating that it explained all the variability in car prices based on the input features.
Random Forest Regressor Model

2. R-squared Score: 99%
*Performance: The Random Forest Regressor also performed exceptionally well, closely matching the accuracy of the Linear *Regression model. This ensemble method leveraged multiple decision trees to enhance predictive performance and robustness.

3. Support Vector Regression Model
R-squared Score: 86%
Performance: The SVR model, while still producing a respectable score, lagged behind the other two models. Despite efforts to optimize its performance through grid search, it remained the lowest-performing model in this comparison.

To further improve the SVR model's accuracy, a grid search was conducted. This hyperparameter tuning technique systematically explored different combinations of parameters to identify the optimal settings for the SVR model. Although this process led to some improvement in the R-squared score, the SVR model still did not surpass the performance of the Linear Regression and Random Forest models.

Feature engineering played a crucial role in enhancing the performance of these machine learning models by transforming raw data into meaningful features that better represent the underlying patterns in the data.

Given the Linear Regression model's perfect R-squared score, it was selected as the basis for developing a car price prediction tool. This tool allows users to input various features from the training model and provides a rough estimate of the car's price based on the trained model. The user-friendly interface ensures that even those without technical expertise can easily obtain accurate price predictions

The Car Price Prediction project successfully identified the Linear Regression model as the most accurate predictor of car prices. With an R-squared score of 100%, this model demonstrated its capability to precisely estimate car prices based on the provided features.
