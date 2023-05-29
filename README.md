# Comparing Classifiers

## Business Purpose
Using a marketing campaign data set, we are goign to compare the performances of different classifiers. 

The classifiers in the scope will be:

- Logistic Regression
- KNN 
- Decision Tree
- SVM

The metric to measure the performance will be average time needed to compute the accuracy for the train and test set. This exercise will be done for models with default parameters and also for a best model which will be found thanks to a GridSearchCV.


## Data Set
Data set is from a Portugese banking institution and is a collection of the results of multiple marketing campaigns. 
We make sure there are non NaN values in the dataset.

## Conclusions
Only a given number of features will be used for this analysis, but further features could be added. Those used are the bank-related columns. 
Among all models, the best performance is shown by the KNN. The worst is the SVM model.
For each model, only one hyperparameter has been tested during the GridSearchCV but a bigegr number of hyperparameters can be potentially studied. 
