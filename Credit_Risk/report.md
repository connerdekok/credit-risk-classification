# Module 12 Report Template

## Overview of the Analysis

The main purpose of the module was to find whether or not a loan was at high risk or was a healthy loan to take.  

* The main concept was trying to find and predict the loan status throughout the assignment.
* The data set contains a total of 77536 total loans.
* When looking throughout the data the loan status was giving to the y variable and the rest of the data was given to the X variable throughout my code. 
* Using the test_train_split from sklearn 75% of the data was trained, and 25% of it was test.  This also has the X and Y variables split into test and train variables respectively. 
* We then fit the X and y training variables into a LogisitcalRegression module using sklearn.model_selection.
* Fit the X and y test variables to the trained LogisticRegression model for predictions
* Then generated a confusion_matrix and a classification_matrix to find the totatl accuracy of the model. 

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Machine Learning Model 1:
LogisticRegression model
Accuracy: Healthy loan 100%, High-risk loan 89%, Overal 99%
Precision: Healthy loan 100%, High-risk loan 84%
Recall: Healthy loan 99%, High-risk loan 94%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* The LogisticRegression module performed the best for predicting a healthy loan status. 
* It is very important for us to be able to predict if a loan is at a high risk (1)

The model does an excellent job at finding healthy loans at 100% but could be better at finding the high risk loans. The f1 score was 89% which means that a total of 11% of the high risk loans were missed when scanning for accuracy. 
