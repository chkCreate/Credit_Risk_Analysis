# Credit_Risk_Analysis

## Overview of the analysis: 
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans\. Therefore, I employed different techniques to train and evaluate models with unbalanced classes: imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling\.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm\. Then, I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm\. Next, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk\. 

## Results: 
See the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

### Oversampling: Naive Random Sampling
<p align="center">
  <img width="400" height="180" src="https://github.com/chkCreate/stock-analysis/blob/a2213f63a02074ba7ccba883c664d54df4ad716f/Resources/Original%20_Code_2017.PNG" title "Original Code 2017 Time Execution">
</p>

### Oversampling: SMOTE Oversampling
<p align="center">
  <img width="500" height="180" src="https://github.com/chkCreate/stock-analysis/blob/a2213f63a02074ba7ccba883c664d54df4ad716f/Resources/Original%20_Code_2017.PNG" title "Original Code 2017 Time Execution">
</p>

### Undersampling: ClusterCentroids
<p align="center">
  <img width="600" height="180" src="https://github.com/chkCreate/stock-analysis/blob/a2213f63a02074ba7ccba883c664d54df4ad716f/Resources/Original%20_Code_2017.PNG" title "Original Code 2017 Time Execution">
</p>

### Combination (Over & Under) Samplings: SMOTEENN
<p align="center">
  <img width="700" height="180" src="https://github.com/chkCreate/stock-analysis/blob/a2213f63a02074ba7ccba883c664d54df4ad716f/Resources/Original%20_Code_2017.PNG" title "Original Code 2017 Time Execution">
</p>

### Ensemble Learners: Balanced Random Forest Classifier
<p align="center">
  <img width="800" height="180" src="https://github.com/chkCreate/stock-analysis/blob/a2213f63a02074ba7ccba883c664d54df4ad716f/Resources/Original%20_Code_2017.PNG" title "Original Code 2017 Time Execution">
</p>

### Ensemble Learners: Easy Ensemble AdaBoost Classifier
<p align="center">
  <img width="400" height="180" src="https://github.com/chkCreate/stock-analysis/blob/a2213f63a02074ba7ccba883c664d54df4ad716f/Resources/Original%20_Code_2017.PNG" title "Original Code 2017 Time Execution">
</p>

## Summary: 
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning\.

After reviewing the results from all six (6) different types of classifications report, Ensemble Learners: Easy Ensemble AdaBoost Classifier yielded the highest f1 score, which is the average accuacy of the tests calculated from the precision and accuracy statistics from the testing results\. 