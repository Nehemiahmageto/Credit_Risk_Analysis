# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. In this project, I used different techniques to train and evaluate models with unbalanced classes. I used imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Machine learning algorithms used in this project:
- RandomOverSampler
- SMOTE
- ClusterCentroids
- SMOTEENN
- BalancedRandomForestClassifier
- EasyEnsembleClassifier

These models were also evaluated for performance and accuracy at predicting credit risk.

## Results

* Naive Random Oversampling

![alt text](https://github.com/Nehemiahmageto/Credit_Risk_Analysis/blob/main/images/Capture_1.png)

* SMOTE Oversampling

![alt text](https://github.com/Nehemiahmageto/Credit_Risk_Analysis/blob/main/images/Capture_2.png)

* Undersampling

![alt text](https://github.com/Nehemiahmageto/Credit_Risk_Analysis/blob/main/images/Capture_3.png)

* Combination (Over and Under) Sampling

![alt text](https://github.com/Nehemiahmageto/Credit_Risk_Analysis/blob/main/images/Capture_4.png)

* Balanced Random Forest Classifier

![alt text](https://github.com/Nehemiahmageto/Credit_Risk_Analysis/blob/main/images/Capture_5.png)

Ranked feature importances

![alt text](https://github.com/Nehemiahmageto/Credit_Risk_Analysis/blob/main/images/Capture_6.png)

* Easy Ensemble AdaBoost Classifier

![alt text](https://github.com/Nehemiahmageto/Credit_Risk_Analysis/blob/main/images/Capture_7.png)

## Summary
After ascessing all the results, I came to the conclusion that no machine learning algorithm is perfect in predicting credit-risk. THe highest accuracy was recorded from Easy Ensemble AdaBoost Classifier. However, this is not a perfect algorithm as the F-Score for high-risk protection was .Use of any algorithm noted will subject company to a high risk of errors in prediction.
