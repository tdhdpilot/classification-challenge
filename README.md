# classification-challenge

## Module 13 Challenge

### Overview

Internet Service Provider (ISP) We are trying to improve the email filtering system for our customers. We have been provided with a dataset that contains information about emails, with two possible classifications: spam and not spam. We would like to use supervised machine learning (ML) model that will accurately detect spam emails so it can filter them out of its customers' inboxes.

We will create two classification models to fit the provided data, and evaluate which model is more accurate at detecting spam. The models will be a logistic regression model and a random forest model.

### Splitting the data into training and testing sets

We will use the train_test_split method from sklearn to split the data into training and testing sets. We will assign y to the Spam column and X to the remaining columns.

### Scale the features

Next we will scale the features for train and test using the StandardScaler from sklearn.

### Logistic Regression model

We will create a logistic regression model using the LogisticRegression module from sklearn. We will fit the model using the training data, and make predictions using the testing data. From this we get the training and testing scoresas below

- _Training Data Score:_ 0.929

- _Testing Data Score:_ 0.921

- _Logistic Regression Model Accuracy Score:_ 0.921

This model is 92.1% accurate at detecting spam and this is a good model.

### Random forest model

We will create a random forest model using the RandomForestClassifier module from sklearn. We will fit the model using the training data, and make predictions using the testing data. From this we get the training and testing scores as below

Training Data Score: 0.999 Testing Data Score: 0.948

- _Training Data Score:_ 0.999

- _Testing Data Score:_ 0.948

- _Logistic Regression Model Accuracy Score:_ 0.948

### Evaluate the models

Based on the accuracy score for the models using the accuracy_score method from sklearn. The accuracy score for the logistic regression model is 0.921 and the accuracy score for the random forest model is 0.948. The Random Forest model is more accurate at detecting spam with a accuracy score of 0.948, however with the training accuracy score so close to 1, this could be over-fit.

### Resources

- Class work
- ChatGPT
- Xpert Learning
