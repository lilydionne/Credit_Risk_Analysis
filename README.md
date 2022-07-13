# Credit Risk Analysis

## Objective

Given that the volume of good loan applicants outnumber risky loans applicants we are tasked with building and evaluating several machine learning models to predict credit risk. In this project we will: 
 - Use the RandomOverSampler and SMOTE algorithms to oversample the data
 - Use the ClusterCentroids algorithm to undersample the data
 - Use SMOTEEN to both oversample and undersample the data
 - And lastly, use BalancedRandomForestClassifier and EasyEnsembleClassifier to reduce bias
 
## Results

##### RandomOverSampler
  - Accuracy Score: 62.5%

![](https://github.com/lilydionne/Credit_Risk_Analysis/blob/main/RandomOverSampler.PNG)
  - Based on the precision score, that the model is great at predicting low risk loan applications (100%) but fails at predicting the high risk loan applications (1%)

##### SMOTE
  - Accuracy Score: 65.1%

![](https://github.com/lilydionne/Credit_Risk_Analysis/blob/main/SMOTE.PNG)
  - Based on the precision score, that the model is great at predicting low risk loan applications (100%) but fails at predicting the high risk loan applications (1%)


##### ClusterCentroids
  - Accuracy Score: 51.6%

![](https://github.com/lilydionne/Credit_Risk_Analysis/blob/main/ClusterCentroids.PNG)
  - Based on the precision score, that the model is great at predicting low risk loan applications (100%) but fails at predicting the high risk loan applications (1%)

##### SMOTTEN
  - Accuracy Score: 61.6%

![](https://github.com/lilydionne/Credit_Risk_Analysis/blob/main/SMOTEENN.PNG)
  - Based on the precision score, that the model is great at predicting low risk loan applications (100%) but fails at predicting the high risk loan applications (1%)


##### BalancedRandomForestClassifier
  - Accuracy Score: 

##### EasyEnsembleClassifier
  - Accuracy Score: 

## Summary
Unfortunately, all models used to perform the credit risk analysis show weak precision in determining if a credit risk is high. Due to the large volume of low risk applications, the model had better success at predicting those loans, but the precision was weak. Due to issues with my computer, I was unable to properly run BalancedRandomForestClassifer and EasysembleClassifer, but will troubleshoot this further to complete the analysis.

