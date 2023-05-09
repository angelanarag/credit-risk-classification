# credit-risk-classification
Module 20 Supervised Learning Challenge

By A.Narag May 17, 2023

This challenge uses various techniques to train and evaluate a model based on loan risk. A dataset of historical lending activity from a peer-to-peer lending services company is used to build a model that can identify the creditworthiness of borrowers.

Split the Data into Training and Testing Sets
1. Created a Pandas DataFrame using the lending_data.csv data from the Resources folder.
2. Created the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

Create a Logistic Regression Model
1. Fit a logistic regression model by using the training data (X_train and y_train).
2. Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
3. Evaluate the model’s performance by doing the following:
    a. Calculate the accuracy score of the model.
    b. Generate a confusion matrix.
    c. Print the classification report.
4. Confirm how well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels

Credit Risk Analysis Report
Analysis Overview: 
[Explain the purpose of this analysis.]

Results: 
[Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.]

Summary: 
[Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.]
