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
<img width="600" alt="BRFC Accuracy" src="https://user-images.githubusercontent.com/104927745/194767367-0bf15222-d6ac-49df-b438-906f77a42885.PNG">

<img width="600" alt="BRFC confusion matrix" src="https://user-images.githubusercontent.com/104927745/194767368-dde773c3-1ff5-4314-b5af-cc239517ad2e.PNG">

<img width="600" alt="BRFC classification report" src="https://user-images.githubusercontent.com/104927745/194767370-67da4932-e70a-4f75-aa89-3455c40521ef.PNG">

<img width="600" alt="BRFC features sorted descending" src="https://user-images.githubusercontent.com/104927745/194767371-dc53d93b-d274-4596-964e-ae4d41f68aee.PNG">


## Summary
- Looking back at all models reviewed the Ensemble AdaBoost Classifier model provided the best results for our data set, with a Balanced Accuracy resuult of 93.2%, precision of 9%, recall of 92% and F1 score of 16%.
- Future recomendations for analysis would be to dive deeper into the ratio of "high risk" to "low risk" applications.  The original data set was comprised of 99% "low risk" and only 1% of "high risk" applications.  This could lead to our results from machine learning algorithms drawing results from an unbalanced dataset, thus skewing the results.  Banks might not be willing to accept this margin of risk.

<img width="600" alt="Summary Results from all Models" src="https://user-images.githubusercontent.com/104927745/194768177-a5a8b30f-bc41-4d79-9849-82981873dc38.PNG">
