# Credit_Risk_Analysis


## Overview
In accessing credit risk, any data set in unbalanced. 
The code herein addresses this issue using a multiple of sampling techniques. 
The machine learning models used are listed below. 

### In credit_risk_resampling file
- Oversampling using RandomOverSampler
- Oversampling using SMOTE
- Undersampling using ClusterCentroids
- Comnination over and under sampling using SMOTEENN

### In credit_risk ensemble file
- RandomForest Classifier
- EasyEnsemble AdaBoost Classifier



## Results
#### Accuracy Scores From Highest to lowest

- Easy Ensemeble, 0.8976774758983348
- Random Forest, 0.6776024929399163
- SMOTEENN, 0.6659379477298553
- SMOTE, 0.6653944963193519
- RandomOverSampler, 0.6480197708521408
- ClusterCentroids, 0.5338680266425931


#### Recall scores of high_risk results
Having a higher sensitivity for high risk applicants is importing in accessing credit risk. 
Therefore, below, a ranking of high risk recall for the six models. 

- Easy Ensemeble, 0.83
- SMOTEENN, 0.76
- RandomOverSampler,0.67
- SMOTE, 0.65
- ClusterCentroids, 0.60
- Random Forest, 0.36



## Summary

Given the figures in the results, it is recommended to use the EasyEnsemble model to access credit risk. 

