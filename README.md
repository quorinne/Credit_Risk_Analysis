# Credit Risk Analysis
## Overview
Fast Lending is a peer-to-peer lending services company. 
They want to use Machine Learning to predict credit risk as they believe it could be more accurate. We have been asked to assist them in building and evaluating several Machine Learning models or algorithms to predict credit risk. We will be using resampling and boosting techniques to increase the accuracy of analysis. We will also evaluate the models to see how well they predict data

## Results 

We have used several models in our analysis, each with varying accuracy scores.

* The Naive Random Oversampling (NRO) accuracy score is 64.39%
* The NRO High Risk Precision is 0.01
* The NRO High Risk Recall is 0.69
![alt text](https://github.com/quorinne/Credit_Risk_Analysis/blob/main/Resources/NaiveRandomOversampling.png?raw=true)


* The SMOTE Oversampling(SO) balanced accuracy score is 64.39% 
* The SO High Risk Precision is 0.01
* The SO High Risk Recall is 0.72
![alt text](https://github.com/quorinne/Credit_Risk_Analysis/blob/main/Resources/SMOTEOversampling.png?raw=true)

* The ClusterCentroids resampler (CC) balanced accuracy score is 64.48% 
* The CC High Risk Precision is 0.01
* The CC High Risk Recall is 0.67
![alt text](https://github.com/quorinne/Credit_Risk_Analysis/blob/main/Resources/CCUndersampling.png?raw=true)

* The Combination Over and Under (OU) Sampling balanced accuracy score is 54.15% 
* The OU High Risk Precision is 0.01
* The OU High Risk Recall is 0.70
![alt text](https://github.com/quorinne/Credit_Risk_Analysis/blob/main/Resources/OverUnderSampling.png?raw=true)

* The Balanced Random Forest Classifier (BRF) balanced accuracy score is 44.21% 
* The BRF High Risk Precision is 0.01
* The BRF High Risk Recall is 0.78
![alt text](https://github.com/quorinne/Credit_Risk_Analysis/blob/main/Resources/BalancedRandomForestClassifier.png?raw=true)

* The Easy Ensemble AdaBoost Classifier(EEC) balanced accuracy score is 93.17 %
* The EEC High Risk Precision is 0.09
* The EEC High Risk Recall is 0.92
![alt text](https://github.com/quorinne/Credit_Risk_Analysis/blob/main/Resources/EasyEnsembleAdaBoostClassifier.png?raw=true)


## Summary
