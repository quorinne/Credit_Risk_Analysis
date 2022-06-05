# Credit Risk Analysis
## Overview
Fast Lending is a peer-to-peer lending services company. 
They want to use Machine Learning to predict credit risk as they believe it could be more accurate. We have been asked to assist them in building and evaluating several Machine Learning models or algorithms to predict credit risk. We will be using resampling and boosting techniques to increase the accuracy of analysis. We will also evaluate the models to see how well they predict data

## Results 

We have used several models in our analysis, each with varying accuracy scores.

* The Naive Random Oversampling (NRO) accuracy score is 64.39%
* The NRO High Risk Precision is 0.01
* The NRO High Risk Recall is 0.69
* The NRO Low Risk Precision is 1.00
* The NRO Low Risk Recall is 0.59
* The NRO AVG Risk Precision is 0.99
* The NRO AVG Risk Recall is 0.60


![alt text](https://github.com/quorinne/Credit_Risk_Analysis/blob/main/Resources/NaiveRandomOversampling.png?raw=true)


* The SMOTE Oversampling(SO) balanced accuracy score is 64.39% 
* The SO High Risk Precision is 0.01
* The SO High Risk Recall is 0.72
* The SO Low Risk Precision is 1.00
* The SO Low Risk Recall is 0.57
* The SO AVG Risk Precision is 0.99
* The SO AVG Risk Recall is 0.57
![alt text](https://github.com/quorinne/Credit_Risk_Analysis/blob/main/Resources/SMOTEOversampling.png?raw=true)

* The ClusterCentroids resampler (CC) balanced accuracy score is 64.48% 
* The CC High Risk Precision is 0.01
* The CC High Risk Recall is 0.67
* The CC Low Risk Precision is 1.00
* The CC Low Risk Recall is 0.41
* The CC AVG Risk Precision is 0.99
* The CC AVG Risk Recall is 0.41
![alt text](https://github.com/quorinne/Credit_Risk_Analysis/blob/main/Resources/CCUndersampling.png?raw=true)

* The Combination Over and Under (OU) Sampling balanced accuracy score is 54.15% 
* The OU High Risk Precision is 0.01
* The OU High Risk Recall is 0.70
* The OU Low Risk Precision is 1.00
* The OU Low Risk Recall is 0.57
* The OU AVG Risk Precision is 0.99
* The OU AVG Risk Recall is 0.58
![alt text](https://github.com/quorinne/Credit_Risk_Analysis/blob/main/Resources/OverUnderSampling.png?raw=true)

* The Balanced Random Forest Classifier (BRF) balanced accuracy score is 44.21% 
* The BRF High Risk Precision is 0.01
* The BRF High Risk Recall is 0.78
* The BRF Low Risk Precision is 0.99
* The BRF Low Risk Recall is 0.10
* The BRF AVG Risk Precision is 0.98
* The BRF AVG Risk Recall is 0.11
![alt text](https://github.com/quorinne/Credit_Risk_Analysis/blob/main/Resources/BalancedRandomForestClassifier.png?raw=true)

* The Easy Ensemble AdaBoost Classifier (EEC) balanced accuracy score is 93.17 %
* The EEC High Risk Precision is 0.09
* The EEC High Risk Recall is 0.92
* The EEC Low Risk Precision is 1.00
* The EEC Low Risk Recall is 0.94
* The EEC AVG Risk Precision is 0.99
* The EEC AVG Risk Recall is 0.94
![alt text](https://github.com/quorinne/Credit_Risk_Analysis/blob/main/Resources/EasyEnsembleAdaBoostClassifier.png?raw=true)


## Summary

The best choice out of the six models we have used for this analysis is Easy Ensemble. The Average Recall for that model is 0.94 while the Precision is 0.99 and the balanced accuracy score is 93.17 %. While all six models had close High Risk and Low Risk Recall and Precision, the Average Precision and Recall was highest among Easy Ensemble. Among the other models the High-Risk precision was 0.01 while the Low-Risk precision was 1.00. This led to a rather dramatic difference in precision scores for High Risk, and Low Risk with the Average precision being 0.99 for all except Balanced Random Forest Classifier which was 0.98.  So, to determine the best model we turn to the Recall. The Recall varies from model to model being as low as 0.11 and as high as 0.72 for the other five models. Easy Ensemble having a recall of 0.94, a precision of 0.99 and a balanced accuracy score of 0.93 (93.17 %)  is therefore the best option. 

