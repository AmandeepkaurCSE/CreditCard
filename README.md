# Credit Card Fraud Detection App

![Credit Card Fraud Detection App](https://github.com/AmandeepkaurCSE/CreditCard/assets/64351796/03b1da68-98cb-4ac5-81cc-3bb1c58d3f06)

### Dataset
The Dataset that is used for credit card fraud detection is derived from the Kaggle.

This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

The link for dataset is https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud 

### Objective
The main objective is to build a model that can accurately classify credit card transactions as fraudulent or non-fraudulent.

### Convert Imbalanced Dataset to Balanced Dataset
The resampling method is used to balanced the imbalanced data.

The method that i used to perform the resampling is Oversampling using SMOTE

![Screenshot (145)](https://github.com/AmandeepkaurCSE/CreditCard/assets/64351796/4bba5576-79a2-4b83-8e4f-1366aba96d1a)

![Screenshot (144)](https://github.com/AmandeepkaurCSE/CreditCard/assets/64351796/d5e04c70-7e36-4cc2-910a-2f6561e7c6f6)

### Algorithms Used
Different algorithms such as Logistic Regression, k-Nearest Neighbors (KNN), Random Forest, and Decision Tree are being utilized in this project.
![Screenshot (45)](https://github.com/AmandeepkaurCSE/CreditCard/assets/64351796/17b6db63-2d5f-415b-8306-6acc35bff27b)

### Conclusion
Finally, I designed a system that can detect fraud in credit card transaction. This system is capable to detect whether the credit card transaction is fraudulent or non fraudulent with 99.93% accuracy using K nearest neighbor.
