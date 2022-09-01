# Credit_Risk_Analysis

## Overview

The purpose of this analysis was to evaluate the dataset to to predict credit risk using several different machine learning models. The models can then be assessed and used to predict risk status for credit applications. 

## Results

The results of each analysis is listed below: 

### Naive Random Oversampling
![naive_random](https://user-images.githubusercontent.com/104689576/188027923-078e9685-486a-40a2-b7ae-d7448c5b754f.png)

      -Balanced Accuracy: 0.6293939430565123
      -Precision (high risk/low risk): 0.01/1.00
      -Recall (high risk/low risk): 0.57/0.68

### SMOTE Oversampling
![SMOTE](https://user-images.githubusercontent.com/104689576/188027952-6ce9572c-9969-4c9e-921a-35fc894fb4ba.png)

      -Balanced Accuracy: 0.6277008271188627
      -Precision (high risk/low risk): 0.01/1.00
      -Recall (high risk/low risk): 0.62/0.63
      
### Undersampling (Cluster Centroids)
![CC_undersampling](https://user-images.githubusercontent.com/104689576/188027894-5aad795a-94d8-4f0b-95f6-e4622933354b.png)

      -Balanced Accuracy:0.6277008271188627
      -Precision (high risk/low risk): 0.01/1.00
      -Recall (high risk/low risk): 0.61/0.45
      
### Combination (Over and Under) Sampling (SMOTEENN)
![SMOTEENN](https://user-images.githubusercontent.com/104689576/188027969-fa288d51-ec2b-4eb9-8edf-68dfc4ac3289.png)

      -Balanced Accuracy: 0.5295655712277054
      -Precision (high risk/low risk):  0.01/1.00
      -Recall (high risk/low risk): 0.70/0.58
      
### Balanced Random Forest Classifier
![Balanced_random](https://user-images.githubusercontent.com/104689576/188027876-bb102196-ca87-43c9-b169-d80ddbf13b4f.png)

      -Balanced Accuracy: 0.7877672625306695
      -Precision (high risk/low risk): 0.04/1.00
      -Recall (high risk/low risk): 0.67/0.91
      
### Easy Ensemble AdaBoost Classifier
![Easy_ensemble](https://user-images.githubusercontent.com/104689576/188027907-f9c0e5e9-7ae8-4829-a1cd-16d5b98d6c81.png)

      -Balanced Accuracy: 0.925427358175101
      -Precision (high risk/low risk): 0.07/1.00
      -Recall (high risk/low risk): 0.91/0.94
      
## Summary

The Easy Ensemble AdaBoost Classifer seemed to be the best of the models used with a a balanced accuracy score of about 93%. It should be noted if it is used though, that it still has a low precision score in detecting high risk creditees so false positives in that aspect should still be expected. 
