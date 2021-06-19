# supervised_learning_creditworthiness_model
I will be using an imbalanced data to build a model that can identify the creditworthiness of borrowers for a lending service. Assignment for FinTech Bootcamp.

### Results

Machine Learning Model 1:
* Balanced accuracy score = 95%
* Precision for Healthy Loans = 100%
* Precision for Risky Loans = 85%
* Recall for Healthy Loans = 99%
* Recall for Risky Loans = 91%

Machine Learning Model 2:
* Balanced accuracy score = 99%
* Precision for Healthy Loans = 100%
* Precision for Risky Loans = 84%
* Recall for Healthy Loans = 99%
* Recall for Risky Loans = 99%

### Summary
Based on the results of the accuracy score it seems that model 2 outperformed model 1. But the precision of the risky loans actually decreased by 1%, from 85% to 84%. Since there are more healthy loans than risly ones it is more important for the model to predict the risky ones correct so I would suggest using model 1. 
