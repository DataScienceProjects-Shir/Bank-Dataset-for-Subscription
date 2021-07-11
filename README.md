# Bank-Dataset-for-Subscription
Running a machine learning analysis on Portuguese bank data to evaluate a customer's likelihood of subscribing to a term deposit.

Summary

Evaluate subscription likelihood using a Random Forest model. Data exploration, feature engineering and building a machine learning model. Evaluate dataset using F1 Score/Confusion Matrix/Accuracy Score.
Data

The data was sourced from this Kaggle competition, which in turn references this academic article

The academic article runs their own regression on the Portuguese bank data.

The definitions of the columns are available in bank-additional-names.txt
Approach

Exploratory analysis of the dataset itself, evaluating the types of data available, examining the data types separately.

Evaluate the distribution of the variables: age, marital status, pdays, consumer price indices etc. using violin plots and histograms.

Apply dummy variables for the categorical data (job, marital, education, poutcome).

Map boolean data to 1 & 0.

Cleanse N/A values.

Split data into training and test sets.

Feature impute and scaling

Evaluate a Random Forest model on the dataset, evaluate 10 most important features.

Experiment with further machine learning models.

Evaluate data, measuring accuracy.
