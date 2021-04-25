# Credit_Risk_Analysis
## Overview:
To use different algerithms to train and evaluate credit card risk with unbalanced classification problem.

## Results:
Evaluated six models:

![](images/NROver.PNG)
Naive Random Oversampling
* high_risk pre(0.01), rec(0.76), f1(0.02)
* low_risk pre(1.00), rec(0.59), f1(0.74). 
Not a good model for predicting high_risk because the f1 score shows a very low number( low precision is indicative of a large number of false positives)



![](images/SMOversampling.PNG)
SMOTE Oversampling
* high_risk pre(0.01), rec(0.63), f1(0.02)
* low_risk pre(1.00), rec(0.69), f1(0.82). 
Not a good model for predicting high_risk because the f1 score shows a very low number( low precision is indicative of a large number of false positives)

![](images/CSUndersampling.PNG)
Cluster Centroids Oversampling
* high_risk pre(0.01), rec(0.69), f1(0.01)
* low_risk pre(1.00), rec(0.40), f1(0.57).
Not a good model for predicting high_risk because the f1 score shows a very low number( low precision is indicative of a large number of false positives)
