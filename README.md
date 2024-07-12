# Credit Risk Analysis Report


## Purpose of Analysis

This analysis classifies the loans in two different categories: "Healthy Loans" and "High Risk Loans", when accurately predicting the credit risks, the informations can be made more informed on wether or not lend money to a client. 

The dataset included loan infortmation about the applicants, such as loan size, income, number of accounts, total debt, etc.

## Stages of the process:

- Loaded and prepared the dataset 
- Separeted in into X (loan status) and Y (the rest of the dataset minus loan status)
- Split the data in training/testing sets using "train_test_split" and a random state value of 1.
- Created a Logistic Regression model with the training data
- Made predicitons on the dest data and with classification report printed the precission, recall, accuracy and F1-score.

## The logistic regression model was used for these predicitons.


## Results

- ### Accuracy 0.99
    -This means 99% of the predicitons made in this model are correct. This model is highly reliable

- ### Precision 
    - Healthy 1.00:
    100% of the loans predicted as Healthy were correctly labeled. It has a perfect precision to predict healthy loans. 

    - High Risk .85:
    85% of the loans predicted as High Risk were correctly labeled. It is less precise on High Risk than in Healthy ones.



- ### Recall 
    - Healthy .99:
    Out of all healthy loans 99% were correctly identified.
    - High Risk .91:
    Out of all healthy loans 91% were correctly identified.

This model is very useful to identify both high risk and healthy loans.

## Summary
This model has a very good perfomance in predicting healthy loans almost with a perfect precision. For high risks the model has a good performance with a precision of 85%. 

The overall accuracy is 99%

High Risks loans are more important to be predicted precisely in order to minimize financial loses. This model identifies 91% of the actual high risks loans.
