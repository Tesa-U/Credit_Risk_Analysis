# Credit_Risk_Analysis

## Overview of the analysis
Using imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling to predict credit risk. 

## Results

### •	Oversampling the data using the RandomOverSampler and SMOTE algorithms.

![plot](images/naive_random_oversampling.png)

### * Smote algorithm.
![plot](images/smote_oversampling.png)

### •	Undersampling the data using the ClusterCentroids algorithm. 

![plot](images/undersampling.png)

### •	Combinatorial approach of over- and undersampling using the SMOTEENN algorithm

![plot](images/combination.png)

### •	Compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier

![plot](images/balanced_random_forest_classifier.png)

![plot](images/ensemble_adaboost_classifier.png)




## Summary
Analysis shows that majority of the models have low balanced accuracy score. 
Easy Ensemble AdaBoost model shows better accuracy. Also, the precision for the high-risk profile is low, thus they have issue to detect risk. Therefore, financial institutions may combine these models with other analysis. 



