# Credit_Risk_Analysis
## Analysis Overview
The purpose of this project was to build and evaluate various machine learning models to predict credit credit card risk. The credit card credit dataset from LendingClub was heavily unbalanced with 68,470 low_risk and only 347 high_risk. We would employ the different techniques to train and evalute the models with unbalanced classes. 

<img width="296" alt="dataset" src="https://user-images.githubusercontent.com/102785000/183708778-957237de-9df5-4588-839a-8d0be36f2299.png">

* oversample the data using RandomOverSampler and SMOTE algorithms
* undersample the data using ClusterCentroids algorithms
* use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm.
* use and compare BalancedRandomForestClassifier and EasyEnsembleClassifier
We would run these models and evaluate their performance and accuracy.

## Results
### RandomOverSampler

<img width="501" alt="random_over_sampling_acc" src="https://user-images.githubusercontent.com/102785000/183710125-39b951f7-d2cf-472c-ba33-4481c454ee2b.png">
Balanced Accuracy: 
Precision for High_Risk/Low_Risk:
Recall for High_Risk/Low_Risk:

### SMOTE

<img width="463" alt="smote_acc_score" src="https://user-images.githubusercontent.com/102785000/183710645-ec364b94-aaec-4ec3-8ee1-cf128089cb8c.png">
<img width="759" alt="smote_report" src="https://user-images.githubusercontent.com/102785000/183710669-70cf4df2-223f-45dc-826c-b938aceb2364.png">

Balanced Accuracy: 
Precision for High_Risk/Low_Risk:
Recall for High_Risk/Low_Risk:

### ClusterCentroids

<img width="532" alt="cluster" src="https://user-images.githubusercontent.com/102785000/183710803-000aca09-2cf6-470d-a9dc-362a81e272ad.png">
<img width="752" alt="cluser_report" src="https://user-images.githubusercontent.com/102785000/183710829-722a44bc-c3d4-44a5-aca9-8d2c0351375f.png">


Balanced Accuracy: 
Precision for High_Risk/Low_Risk:
Recall for High_Risk/Low_Risk:

### SMOTEENN

<img width="458" alt="smoteen" src="https://user-images.githubusercontent.com/102785000/183711002-7224580a-01ee-41bf-9c0c-7ac5b0504eff.png">

<img width="750" alt="smoteen_report" src="https://user-images.githubusercontent.com/102785000/183711024-5ad5d644-ae37-4845-9eb2-4f45d2120ba5.png">

### BalancedRandomForestClassifier








## Summary
In reviewing all six models, the EasyEnsembleClassifer model yielded the best results with 93% of accuracy rate and 9% precision rate when predicting the High_Risk candidates. The result for predicting the Low_Risk candidates was also the highest among all these six models. 
