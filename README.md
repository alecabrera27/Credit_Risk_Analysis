# Credit_Risk_Analysis

## Overview
In this project we will apply machine learning to solve a credit card risk challenge.
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we will employ different techniques to train and evaluate models with unbalanced classes and use the ‘imbalanced-learn’ and ‘sickit-learn’ libraries to build and evaluate models using resampling.

---

## Results

## Oversampling

### RandomOverSampler
- balanced accuracy score: 0.6513903493398762
- precisión: 0.99
- recall: 0.64

![Naive Random Oversampling](https://user-images.githubusercontent.com/78781719/134265211-9990cb77-5eca-4d97-835f-367c26db7651.PNG)

### SMOTE
- balanced accuracy score: 0.626685561
- precision: 0.99
- recall: 0.64

![SMOTE oversampling](https://user-images.githubusercontent.com/78781719/134265261-7f47b57d-b8ff-400e-8177-b8d6fd84e3f4.PNG)

## Undersampling

### ClusterCentroids

- balanced accuracy score: 0.5442166
- precision: 0.99
- recall: 0.42

![Undersampling](https://user-images.githubusercontent.com/78781719/134265353-4add0e70-92aa-44c2-ae29-660b791e0ae1.PNG)


## Combination

### SMOTEENN


- balanced accuracy score: 0.6400726
- precision: 0.99
- recall: 0.58

![Combination](https://user-images.githubusercontent.com/78781719/134265461-51eb563f-65ba-4646-b7f2-429346da42fe.PNG)


## Ensamble Learners

### BalancedRandomForestClassifier

- balanced accuracy score: 0.778784
- precision: 0.99
- recall: 0.88

![RandomForest](https://user-images.githubusercontent.com/78781719/134265724-3ffa84cd-62d5-418f-b67c-8a801ea89a1a.PNG)

### EasyEnsembleClassifier

balanced accuracy score: 0.9292916
precision: 0.99
recall: 0.92

![EasyEnsemble](https://user-images.githubusercontent.com/78781719/134265745-d79191c3-8ee6-4121-8c9d-dc2250bd232d.PNG)
