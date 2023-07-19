# credit_card_fraud_detection

In this project, I predict fraudulent credit card transactions with the help of Machine learning models.
<br>
## <b>Problem Statement</b>
The problem statement is to predict fraudulent credit card transactions with the help of machine learning models.

## <b>Dataset</b>
The data set is taken from the <a href="https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud">Kaggle</a> and has a total of 2,84,807 transactions; out of these, 492 are fraudulent. Since the data set is highly imbalanced, it needs to be handled before model building.
It consists of numerical input variables that have undergone a PCA transformation. Unfortunately, we are unable to provide the original features or additional background information about the data due to confidentiality concerns. The features V1, V2, ... V28 represent the principal components obtained through PCA, while 'Time' and 'Amount' are the only features that have not undergone this transformation. The 'Time' feature indicates the number of seconds elapsed between each transaction and the first transaction in the dataset. On the other hand, the 'Amount' feature represents the transaction amount, which can be utilized for tasks such as example-dependent cost-sensitive learning. Lastly, the 'Class' feature serves as the response variable and takes a value of 1 in cases of fraud and 0 otherwise
