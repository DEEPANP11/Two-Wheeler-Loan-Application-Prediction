#Two-Wheeler Loan Application Prediction
Project Overview
This project aims to predict whether a two-wheeler loan application will be accepted or rejected based on various features provided by the applicant. The goal is to build and evaluate machine learning models to classify applications into two categories: "APPROVED" or "DECLINED."

Dataset
Training Data: Assignment_Train.csv
Contains 10,000 entries with features related to loan applications and the target variable Application Status.

Test Data: Assignment_Test.csv
Contains 2,000 entries with features similar to the training data but without the target variable.

Approach
Data Exploration and Preprocessing

Loaded and explored training and test datasets.
Preprocessed data including handling missing values, encoding categorical features, and scaling numerical features.
Model Building

Built two classification models:
Random Forest Classifier
Gradient Boosting Classifier
Model Evaluation

Evaluated models based on accuracy, precision, recall, and F1 score.
Selected the Gradient Boosting Classifier as the best model based on the highest F1 score.
Prediction and Submission

Generated predictions for the test dataset using the Gradient Boosting Classifier.
Created submission files with predictions for further analysis.
Results
Random Forest Classifier:

Accuracy: 0.8295
Precision: 0.8777
Recall: 0.8295
F1 Score: 0.8342
Gradient Boosting Classifier:

Accuracy: 0.8365
Precision: 0.8671
Recall: 0.8365
F1 Score: 0.8407
The Gradient Boosting Classifier outperformed the Random Forest Classifier based on F1 Score.#
