# Credit_Risk_Analysis
## Analysis Overview
The purpose of this project was to build and evaluate various machine learning models to predict credit credit card risk. The credit card credit dataset from LendingClub was heavily unbalanced with 68,470 low_risk and only 347 high_risk. We would employ the different techniques to train and evalute the models with unbalanced classes. 
* oversample the data using RandomOverSampler and SMOTE algorithms
* undersample the data using ClusterCentroids algorithms
* use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm.
* use and compare BalancedRandomForestClassifier and EasyEnsembleClassifier
We would run these models and evaluate their performance and accuracy.

## Results
RandomOverSampler



## Summary
In reviewing all six models, the EasyEnsembleClassifer model yielded the best results with 93% of accuracy rate and 9% precision rate when predicting the High_Risk candidates. The result for predicting the Low_Risk candidates was also the highest among all these six models. 