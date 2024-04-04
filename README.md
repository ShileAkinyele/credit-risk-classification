# credit-risk-classification

This analysis tries to build a model that can identify the creditworthiness of an individual based on past lending activity.
The data used is on historical lending activity from a peer-to-peer lending services company. Information in the dataset is centered around the loan size, interest rate,borrower's income, debt to income ratio, number of accounts,derrogatory remarks, total debt.(all of which serve as the features x) and then the loan status(which serves as the labels Y). Based off the following information we are trying to predict if the borrower is a healthy one or not. That is if they are credit worthy or not(0 (healthy loan) and 1 (high-risk loan).

To perform this analysis, the data for the analysis was first created into a pandas data frame after which labels and features were created and the data further split into testing and training data set using train_test_split
The Logistic Regression algorithm was used in this analysis as this deals with a non-numerrical classification problem. The logistics regression model was fitted using the x and y train data and predictions were able to be made using the x test data.

To further evaluste the performance of the model a confusion matrix was generated.
