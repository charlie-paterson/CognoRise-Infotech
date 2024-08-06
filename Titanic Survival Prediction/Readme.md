## Summary

The Titanic Survival Prediction project aimed to develop a robust machine learning model capable of predicting the survival rate of passengers aboard the Titanic tragedy. Four different types of models were employed: Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting. The project focused on identifying the most accurate model to achieve this task.

The dataset was divided into an 80/20 training and testing split to ensure the models were trained on a substantial amount of data while still having a separate dataset for evaluation. Comprehensive data preprocessing was conducted, including handling missing values, encoding categorical variables, and feature scaling. This ensured the models could effectively interpret the input data.

Each model was trained using cross-validation and hyperparameter tuning to maximize their performance. The accuracy scores for each model were as follows:

1. Logistic Regression Model:

* Accuracy Score: 80%

* Performance: The baseline model provided a solid start but lacked the complexity to capture more intricate patterns in the data.

2. Decision Tree Classification Model:

* Accuracy Score: 80%

* Performance: Similar to Logistic Regression, the Decision Tree model had limited accuracy due to its tendency to overfit the training data.

3. Random Forest Classification Model:

* Accuracy Score: 80%

* Performance: The ensemble method of Random Forests significantly improved accuracy by combining multiple decision trees to reduce overfitting and increase generalizability.

4. Gradient Boosting Classification Model:

* Accuracy Score: 83%

* Performance: The Gradient Boosting model achieved the highest accuracy, demonstrating its ability to effectively identify class differences and predict survival outcomes. It also achieved an F1-score of 0.78 and an AUC score of 0.88, further indicating its robustness and reliability.

The Gradient Boosting Classifier's 83% accuracy demonstrates the model's effectiveness in predicting passenger survival, making it the best-performing model among those tested. This accuracy, along with its F1-score and AUC score, highlights the model's capability in balancing precision and recall, and distinguishing between classes.
