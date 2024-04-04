# credit-risk-classification

This analysis tries to build a model that can identify the creditworthiness of an individual based on past lending activity.
The data used is on historical lending activity from a peer-to-peer lending services company. Information in the dataset is centered around the loan size, interest rate,borrower's income, debt to income ratio, number of accounts,derrogatory remarks, total debt.(all of which serve as the features x) and then the loan status(which serves as the labels Y). Based off the following information we are trying to predict if the borrower is a healthy one or not. That is if they are credit worthy or not(0 (healthy loan) and 1 (high-risk loan).

To perform this analysis, the data for the analysis was first created into a pandas data frame after which labels and features were created and the data further split into testing and training data set using train_test_split
The Logistic Regression algorithm was used in this analysis as this deals with a non-numerrical classification problem. The logistics regression model was fitted using the x and y train data and predictions were able to be made using the x test data.

To further evaluate the performance of the model a confusion matrix and a classification report was generated.
For the 0's(healthy loans) we have 100% for the precision, Recall and F1 score.
while for the 1's (high-risk loan) we have 87% for the precision score, 89% for the Recall and 88% for the F1 score.The 1's have a lower precision and Recall because of the presence of False positives and false negatives.

For this particular business problem we want to minimize the false positives(Precision) which is saying the borrowers are healthy when they are not,as this could lead to default and loss on the part of the company.
But we also want to minimize the false negatives(recall) which says the customer is a high risk where as they are healthy, as this could lead to business loss for the company. In other to minimize both false positive and negative we focus on the 
accuracy score which is 99%. This is a high score so we can say the model is responsive in classifying the healthy and high risk loans.

