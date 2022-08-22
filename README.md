# Credit_Risk_Analysis
## Analysis Overview
The purpose of this project was to build and evaluate various machine learning models to predict credit card risk. The credit card credit dataset from LendingClub was heavily unbalanced with 68,470 low_risk and only 347 high_risk. We would employ the different techniques to train and evalute the models with unbalanced classes. 

<img width="296" alt="dataset" src="https://user-images.githubusercontent.com/102785000/183708778-957237de-9df5-4588-839a-8d0be36f2299.png">

* oversample the data using RandomOverSampler and SMOTE algorithms
* undersample the data using ClusterCentroids algorithms
* use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm.
* use and compare BalancedRandomForestClassifier and EasyEnsembleClassifier
We would run these models and evaluate their performance and accuracy.

## Results
### RandomOverSampler

<img width="501" alt="random_over_sampling_acc" src="https://user-images.githubusercontent.com/102785000/183710125-39b951f7-d2cf-472c-ba33-4481c454ee2b.png">

<img width="770" alt="RandomOverSampling" src="https://user-images.githubusercontent.com/102785000/183714995-1238eb26-45ac-4b36-81fa-f7cd4ac75f33.png">


Balanced Accuracy: 0.63

Precision for High_Risk/Low_Risk: 0.01/1.0

Recall for High_Risk/Low_Risk: 0.56/0.69

### SMOTE

<img width="463" alt="smote_acc_score" src="https://user-images.githubusercontent.com/102785000/183710645-ec364b94-aaec-4ec3-8ee1-cf128089cb8c.png">

<img width="759" alt="smote_report" src="https://user-images.githubusercontent.com/102785000/183710669-70cf4df2-223f-45dc-826c-b938aceb2364.png">

Balanced Accuracy: 0.66

Precision for High_Risk/Low_Risk: 0.01/1.0

Recall for High_Risk/Low_Risk: 0.67/0.66

### ClusterCentroids

<img width="532" alt="cluster" src="https://user-images.githubusercontent.com/102785000/183710803-000aca09-2cf6-470d-a9dc-362a81e272ad.png">

<img width="752" alt="cluser_report" src="https://user-images.githubusercontent.com/102785000/183710829-722a44bc-c3d4-44a5-aca9-8d2c0351375f.png">


Balanced Accuracy: 0.66

Precision for High_Risk/Low_Risk: 0.01/1.0

Recall for High_Risk/Low_Risk: 0.67/0.66

### SMOTEENN

<img width="458" alt="smoteen" src="https://user-images.githubusercontent.com/102785000/183711002-7224580a-01ee-41bf-9c0c-7ac5b0504eff.png">

<img width="750" alt="smoteen_report" src="https://user-images.githubusercontent.com/102785000/183711024-5ad5d644-ae37-4845-9eb2-4f45d2120ba5.png">

Balanced Accuracy: 0.64

Precision for High_Risk/Low_Risk: 0.01/1.0

Recall for High_Risk/Low_Risk: 0.70/0.57

### BalancedRandomForestClassifier

<img width="607" alt="brfc_acc_score" src="https://user-images.githubusercontent.com/102785000/183711369-00737c89-0653-437d-a0c4-981fcbb1eea1.png">

<img width="757" alt="brfc_report" src="https://user-images.githubusercontent.com/102785000/183711394-df588f83-49ce-4518-943a-3b54fd75020b.png">

Balanced Accuracy: 0.79

Precision for High_Risk/Low_Risk: 0.04/1.0

Recall for High_Risk/Low_Risk:0.67/0.91

### EasyEnsembleClassifier

<img width="463" alt="eec_socre" src="https://user-images.githubusercontent.com/102785000/183711541-18250a2c-832e-4129-961a-922cf19d0f98.png">

<img width="607" alt="brfc_acc_score" src="https://user-images.githubusercontent.com/102785000/183711554-c22d7671-72e0-461d-83d5-01ca23a73832.png">

Balanced Accuracy: 0.93

Precision for High_Risk/Low_Risk: 0.07/1.0

Recall for High_Risk/Low_Risk: 0.91/0.94

## Summary
In reviewing all six models, the EasyEnsembleClassifer model yielded the best results with  accuracy rate at 0.93 and precision rate at 0.07 when predicting the High_Risk candidates. Also this model had the highest precision rate comparing to the other five models. I would recommend using EasyEnsembleClassifier model against the other five models for predicting credit card risks. 
