# Summary of Projects

### 1 - Car Price Prediciton

Using a car price dataset, I built a machine learning model to predict car prices based on various features within the dataset. Given the continuous nature of the target variable (price), I employed regression algorithms rather than classification models. The dataset contained numerous columns that could be feature-engineered to enhance the model's accuracy.

To optimize the feature selection process, I utilized a heatmap to analyze the correlations between the features and the target variable. This visual tool helped identify the most relevant features for training, ensuring that the final model was as accurate and effective as possible. By focusing on the most significant features, I aimed to improve the model's predictive performance and provide more precise car price estimations.


### 2 - Titanic Survival Prediciton

Using a Titanic survival dataset, which indicated whether a passenger survived the Titanic disaster, I built a machine learning model requiring classification algorithms for this project. To prepare the data for training, I cleaned and encoded it, converting all non-numeric data into numerical values, as machine learning models require integers and floats to process the information effectively.

Next, I performed feature engineering to enhance the predictive accuracy of the model. This involved creating new features and selecting the most relevant ones to better predict the survival chances of passengers. By carefully engineering these features, I aimed to improve the model's ability to distinguish between survivors and non-survivors more accurately.

To maximize the model's performance, I opted for a smaller test size, thereby increasing the training set's size. A larger training set provides the machine learning model with more data to learn from, enabling it to identify patterns more effectively. This approach ultimately contributed to a higher overall accuracy for the classification model, resulting in more reliable predictions of passenger survival based on the given dataset


### 3 - Fake News Detection 

The Fake News Prediction project aims to develop a machine learning model capable of distinguishing between genuine and fake news articles. This project addresses the growing concern of misinformation spreading through various media channels, which can have significant societal and political impacts. By leveraging natural language processing (NLP) techniques and machine learning algorithms, the project seeks to provide a reliable tool for news verification.

I used different machine learning classification models to gain an accuracy score of 94% using a logistic regression model. This meant that my predicted target varibales were very similar to that of the actual targets. I also got an AUC score of 0.98 which means that many patterns were found within my model as an AUC score of 0.5 means the model is just randomly guessing and an AUC score of 1 means the model knows exactly what is coming next from the patterns within the dataset. So, from this my model
