# Credit_Risk_Classification Report

## overview of the analysis: 

In this Challenge, I used various techniques to train and evaluate a model based on loan risk. I used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.


The method I used for the analysis is logistic regression model.

------------------------------------------------------------
Step 1: Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

Step 2: Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

Step 3: Check the balance of the labels variable (y) by using the value_counts function.

Step 4: Split the data into training and testing datasets by using train_test_split.


------------------------------------------------------------

Create a Logistic Regression Model with the Original Data

Step 1: Fit a logistic regression model by using the training data (X_train and y_train).

Step 2: Save the predictions on the testing data labels by using the testing feature data (X_test) and the fitted model.

Step 3: Evaluate the model’s performance by doing the following:

   -Calculate the accuracy score of the model.
   
   -Generate a confusion matrix.
   
   -Print the classification report.
   

## The results: 

* Machine Learning Model 1:
  * f1-score: 1.00
  * Precision: 1.00
  * Recall scores: 1.00



* Machine Learning Model 2:
  * f1-score: 0.88
  * Precision: 0.87
  * Recall scores: 0.89


## Summary: 

I recommand the Logistic Regression Model for use by the company. The predication of 0 (healthy loan) is highly accurate, with the score of 1.00 of all precision,recall, and f1-score. 

The prediction of 1 (high-risk loan) is less accurate but still have 0.87 to 0.89 of the precision,recall, and f1-score. 

Total accuracy if 0.99 wich is very high.
