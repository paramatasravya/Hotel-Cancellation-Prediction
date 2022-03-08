# Hotel-Cancellation-Prediction
This is a classification project that will try to predict whether a booking will be cancelled or a booking will not be cancelled using machine learning based on historical data. We also do Feature Engineering and Pre-processing using different techniques and select the dataset from the original data.

I first removed and imputed the null variables and clean the data further by removing outliers using ecliptic envelope.

Feature engineering is done by using label encoders and one hot encoding. Furthermore, predictorsare selected using pearson correlation coefficients.

Both Logistic Regression and XGBoostClassifier models are built and performance is evaluated using accuracy and ROC curve.
An accuracy score of 88.8% is observed using XGBClassifier and 82.3% is observed using Logistic regression.
