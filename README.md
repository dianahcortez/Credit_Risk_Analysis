# Credit_Risk_Analysis

## Overview
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Resources
- Jupyter Notebook, provided CSV files

## Deliverables
- Use Resampling Models to Predict Credit Risk
- Use the SMOTEENN Algorithm to Predict Credit Risk
- Use Ensemble Classifiers to Predict Credit Risk
- A Written Report on the Credit Risk Analysis (README.md)


## Results

### Resampling Models - Deliverable 1
<img width="600" alt="balanced accuracy score" src="https://user-images.githubusercontent.com/104927745/194765342-d8bad24e-bb32-43fa-832c-8a4107a4ba85.PNG">

<img width="600" alt="confusion matrix" src="https://user-images.githubusercontent.com/104927745/194765343-6bcd2c86-d42d-4f87-8532-cc761825db84.PNG">

<img width="600" alt="classification report" src="https://user-images.githubusercontent.com/104927745/194765344-def36e16-2474-49cd-9e9c-f63d2b4246a2.PNG">
 


### SMOTEENN Algorithm - Deliverable 2
<img width="600" alt="smoteenn accuracy score" src="https://user-images.githubusercontent.com/104927745/194765316-f77466d3-59e5-4582-ae5b-2964888d09e3.PNG">

<img width="600" alt="smoteenn confusion matrix" src="https://user-images.githubusercontent.com/104927745/194765318-277aa531-97cb-47cf-8cba-d096f4042590.PNG">

<img width="600" alt="smoteenn classification report" src="https://user-images.githubusercontent.com/104927745/194765319-f7118ac0-072f-4e7f-9fa9-8304f009db73.PNG">

### Ensemble Classifiers - Deliverable 3

## Summary
