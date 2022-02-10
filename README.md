# Credit_Risk_Analysis

## Overview of the analysis: 
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans\. Therefore, I employed different techniques to train and evaluate models with unbalanced classes: imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling\.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm\. Then, I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm\. Next, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk\. 

## Results: 
See the balanced accuracy scores and the precision and recall scores of all six machine learning models\. The following screenshots demonstrate the clissification reports generated for each method performance\.

### Oversampling: Naive Random Sampling
<p align="center">
  <img width="700" height="180" src="https://github.com/chkCreate/Credit_Risk_Analysis/blob/cda30c97b2d397e99e518b63226910f3932c49aa/Results/over_naive.PNG">
</p>

### Oversampling: SMOTE Oversampling
<p align="center">
  <img width="700" height="180" src="https://github.com/chkCreate/Credit_Risk_Analysis/blob/cda30c97b2d397e99e518b63226910f3932c49aa/Results/over_smote.PNG">
</p>

### Undersampling: ClusterCentroids
<p align="center">
  <img width="700" height="180" src="https://github.com/chkCreate/Credit_Risk_Analysis/blob/cda30c97b2d397e99e518b63226910f3932c49aa/Results/under.PNG">
</p>

### Combination (Over & Under) Samplings: SMOTEENN
<p align="center">
  <img width="700" height="180" src="https://github.com/chkCreate/Credit_Risk_Analysis/blob/cda30c97b2d397e99e518b63226910f3932c49aa/Results/combo.PNG">
</p>

### Ensemble Learners: Balanced Random Forest Classifier
<p align="center">
  <img width="700" height="180" src="https://github.com/chkCreate/Credit_Risk_Analysis/blob/cda30c97b2d397e99e518b63226910f3932c49aa/Results/balanced_ensemble.PNG">
</p>

### Ensemble Learners: Easy Ensemble AdaBoost Classifier
<p align="center">
  <img width="700" height="180" src="https://github.com/chkCreate/Credit_Risk_Analysis/blob/cda30c97b2d397e99e518b63226910f3932c49aa/Results/easy_ensemble.PNG">
</p>

## Summary: 
After reviewing the results from all six (6) different types of classifications report, Ensemble Learners: Easy Ensemble AdaBoost Classifier yielded the highest f1 score, which is the average accuacy of the tests calculated from the precision and accuracy statistics from the testing results\. 
