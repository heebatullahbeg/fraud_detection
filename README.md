# Fraud Detection

[Credit Card Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/).

Credit card companies are able to recognize fraudulent transactions so that customers aren't charged for items that they did not purchase.

The dataset contains transactions made by credit cards in September 2013 by European cardholders. The transactions happened in 2 days with about 492 frauds out of 284,807 transactions. This makes the dataset highly unbalanced.

The dataset contains numerical input variables which are the result of a PCA transformation. Due to confidentiality issues, the original features and more background information about the data aren't provided.

Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'.

Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset.

The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.


