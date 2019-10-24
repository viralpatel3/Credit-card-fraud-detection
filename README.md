# Problem motivation
For years, fraudsters would simply take numbers from credit or debit cards and print them onto blank plastic cards to use at brick-and-mortar stores. But in 2015, Visa and Mastercard mandated that banks and merchants introduce EMV - chip card technology, which made it possible for merchants to start requesting a PIN for each transaction. Nevertheless, experts predict online credit card fraud to soar to a whopping $32 billion in 2020.

Putting it into perspective, this amount is superior to the profits posted recently by some worldwide household, blue chip companies in 2017, such as Coca-Cola ($2 billions), Warren Buffets Berkshire Hathaway ($24 billions) and JP Morgan Chase ($23.5 billions). In addition to the implementation of chip card technology, companies have been investing massive amounts in other technologies for detecting
fraudulent transactions.

The classification problem involves creating models that have enough intelligence in order to properly classify transactions as either legit or fraudulent, based on transaction details such asamount, merchant, location, time and others. Financial fraud still amounts for considerable amounts of money. Hackers and crooks aroundthe world are always looking into new ways of committing financial fraud at each minute. Relying exclusively on rule-based, conventionally programmed systems for detecting financial fraud would not provide the appropriate time-to-market. This is where Machine Learning comes as a unique solution for this type of problem. The main challenge when it comes to modeling fraud detection as a classification problem comes from the fact that in real world data, the majority of transactions is not fraudulent.

# DESCRIPTION OF THE DATA
The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

# Goal
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. So, with the given dataset I will try to classify the given data in fradulent and non fradulent transactions. Here, Due to given the class imbalance ratio, I will be choosing best model by measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC) and F-1 Score.
