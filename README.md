# Hotel-Cancellation-Prediction
This is a classification project that will predict the probability of a booking cancellation using machine learning based on historical data. In this notebook we have performed Feature Engineering and data pre-processing using different techniques.

Removed all null values by imputing and cleansed the data further by removing outliers using ecliptic envelope.

Feature engineering is done by using label encoders and one hot encoding. Furthermore, predictors are selected using pearson correlation coefficients.

Both Logistic Regression and XGBoostClassifier models are built and performance is evaluated using accuracy and ROC curve.

An accuracy score of 88.8% is observed using XGBClassifier and 82.3% is observed using Logistic regression.
