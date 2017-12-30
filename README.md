# brainwaves17
A competition hosted by Societe Generale. Code for the fraud prediction problem.

##Download the data set from: https://he-s3.s3.amazonaws.com/media/hackathon/brainwaves-17-1/predict-fraud-transactions/f992303a-d-BW2017_2.zip

## Problem Statement:
Societe Generale (SocGen) is a French multinational banking and financial services company. With over 1,54,000 employees, based in 76 countries, they handle over 32 million clients throughout the world on a daily basis.

They provide services like retail banking, corporate and investment banking, asset management, portfolio management, insurance and other financial services.

While dealing with innumerable money transactions, they’ve set up an internal team which closely monitors and alarms the transactions which could be deemed fraudulent.

In this problem, given an anonymised data of transactions, you have to predict the probability of a transaction being fraudulent.

### Data Description
You are given three files to download: train, test and sample submission.

### Variable Name	Description
#### transaction_id	unique transaction id
*num_var	numeric variables
*cat_var	categorical variables
target	target variable (1 = Fraudulent, 0 - Not Fraudulent)


### Submission
A participant has to submit a csv file(or a zipped csv file) with transaction_id and target as predicted probability. Check the sample submission file for reference.

#### transaction_id, target
id_1, 0.34214
id_6, 0.01233
id_9, 0.53421
id_14, 0.87671
id_15, 0.12201


### Evaluation Metric
Submissions will be evaluated based on AUC-ROC score.


