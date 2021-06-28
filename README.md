# Credit_Risk_Analysis

## Overview of Analysis

Python is used to build and evaluate several machine learning models to predict credit risk. The data was oversampled using the RandomOverSampler and SMOTE algorithms and undersampled using the ClusterCentroids algorithm. We also used a combinatorial approach of over and undersampling using the SMOTEENN algorithm and compared 2 machine learning models that reduce bias (BalancedRandomForestClassifier and EasyEnsembleClassifier). 

We evaluate the performance of these models and suggest if they should be used to predict credit risk. 

## Results
Here are the results from the 6 machine learning models:

### SMOTEEN:
![](https://github.com/MuddassirR/Credit_Risk_Analysis/blob/main/r4.png)

### SMOTE:
![](https://github.com/MuddassirR/Credit_Risk_Analysis/blob/main/r1.png)

### RandomOverSample:
![](https://github.com/MuddassirR/Credit_Risk_Analysis/blob/main/r2.png)

### ClusterCentroids:
![](https://github.com/MuddassirR/Credit_Risk_Analysis/blob/main/r3.png)

### EasyEnsembleClassifier:
![](https://github.com/MuddassirR/Credit_Risk_Analysis/blob/main/r6.png)

### BalancedRandomForestClassifier:
![](https://github.com/MuddassirR/Credit_Risk_Analysis/blob/main/r5.png)

## Summary
It appears that the EasyEnsembleClassifier is the most effective as it had more improvement on the sensitivity of the high risk credits. The EasyEnsembleClassifier model shows a recall of 92% so it detects almost all high risk credit. However, since all the models have a low precision, a lot of low risk credits are still falsely detected as high risk which could result in the bank missing out on business oportunities.
