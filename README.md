# credit_risk_analisys

in this module we have tried to analise the crediwortiness of borrowers and use various prediction models to flag any clients who will have difficulty repaing the loan
Original data set had included most imoportanat information about borrowers- and the last column had been described as credit risk category.
This is our main focus data point - hece it is descibed as label ( y )
We had split the dataset into Train and Test samples, that we can first train the model on original data and test the data with LogistiC Regression model.
Logistic Regression Model showed 94% of balanced accuracy with random state being equal to 1. Also clssification report showed perfect prediction rate of test samples for healty loans and a bit less accurate prediction for unhealty loans. 
To test this model even further , we have used overbalanced sampling , where we have increased number of smaples marked 1( high risk loans)and made the sample sizes for both categories equal.
Using Logostic Regression Model with oversampled train and test data we have achieved 99% accuracy and prediction state for both bad and good loan categories givning us further confidance in using this model to make future predictions

