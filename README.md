# credit-risk-classification
A Supervised Machine learning problem which involves classifying customers based on credit risk


* Explain the purpose of the analysis.
This analysis tries to build a model that can identify the creditworthiness of an individual based on past lending activity.
* Explain what financial information the data was on, and what you needed to predict.
The data is on historical lending activity from a peer-to-peer lending services company information in the dataset is centered around the loan size, interest rate,borrower's income, debt to income ratio, number of accounts,derrogatory remarks, total debt.(all of which serve as the features x) and then the loan status(which serves as the labels Y). Based off the following information we are trying to predict if the borrower is a healthy one or not. That is if they are credit worthy or not(0 (healthy loan) and 1 (high-risk loan) 
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
To perform this analysis, the data for the analysis was first created into a pandas data frame after which labels and features were created and the data further split into testing and training data set using train_test_split
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
