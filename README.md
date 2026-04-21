# Project_2_TaskA
Best model fit for credit card default:

The goal of this project was to determine the best model for predicting credit card defaults.
The data is a csv file of 30,000 individuals payment history and certain categorical features such as education
and sex. We decided the goal should be interpretability(what feature indicates credit card payment will default) over 
slightly higher metrics obtained through feature engineering. For this reason colinear features were dropped and
feature importance was calculated for a final list of features. 8 total features were selected. Using cross validation,
multiple classification models were ran with these 8 features and key metrics were compared(accuracy, recall, f1, precision, ROC-AUC,
specificity). The models assesed were logistic, random forest, decision tree, SVM, lda, qda, and kNN. THe fianl model that was chosen
was a decision tree for higher metrics plus interpretability.

