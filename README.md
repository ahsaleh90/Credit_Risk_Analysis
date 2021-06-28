# Credit_Risk_Analysis
## Overview of the Analysis:

The purpose of this analysis is to test different machine learning models ability to predict credit risk. This project will use the imbalanced-learn and scikit-learn libraries to build models and evalute them using resampling models. The following models where included:

RandomOverSampler
SMOTE
ClusterCentroids
SMOTEENN
BalancedRandomForestClassifier
EasyEnsembleClassifier


## Results

Naive Random Oversampling
![](https://github.com/ahsaleh90/Credit_Risk_Analysis/blob/main/img/naive_random_oversampling.png)

- Balanced Accuracy Score for the model is 0.6547.

For high risk performance:

- precision is very low at 1%
- recall is great at 72%

For low risk performance:

- Precision is high at 100%
- recall is fair at 59%


SMOTE Oversampling
![](https://github.com/ahsaleh90/Credit_Risk_Analysis/blob/main/img/SMOTE_oversampling.png)

- Balanced Accuracy Score for the model is 0.6620.

For high risk performance:

- precision is very low at 1%
- recall is goodat 63%

For low risk performance:

- Precision is high at 100%
- recall is good at 69%


Undersmapling
![](https://github.com/ahsaleh90/Credit_Risk_Analysis/blob/main/img/undersampling.png)

- Balanced Accuracy Score for the model is 0.5442.

For high risk performance:

- precision is very low at 1%
- recall is good at 69%

For low risk performance:

- Precision is high at 100%
- recall is bad at 40%

Combination (Over and under) sampling
![](https://github.com/ahsaleh90/Credit_Risk_Analysis/blob/main/img/combination_over_under_sampling.png)

- Balanced Accuracy Score for the model is 0.5442.

For high risk performance:

- precision is very low at 1%
- recall is very good at 72%

For low risk performance:

- Precision is high at 100%
- recall is fair at 57%

Balanced Random Forest Classifier
![](https://github.com/ahsaleh90/Credit_Risk_Analysis/blob/main/img/balanced_random_forest_classifier.png)
- Balanced Accuracy Score for the model is 0.7885.

For high risk performance:

- precision is very low at 3%
- recall is very good at 70%

For low risk performance:

- Precision is high at 100%
- recall is very good at 87%

Easy Ensemble adaBoost Classifier
![](https://github.com/ahsaleh90/Credit_Risk_Analysis/blob/main/img/easy_ensemble_adaboost_classifier.png)
- Balanced Accuracy Score for the model is 0.9316.

For high risk performance:

- precision is very low at 9%
- recall is excellent at 92%

For low risk performance:

- Precision is high at 100%
- recall is excellent at 94%

## Summary

The first four models used undersample, oversample and a combination of over and under sampling. All models are great at predicting high risk. The other two models were resampled and used ensemble classifiers (Balanced Random Forest anf Easy Ensemble Classifier) are better predicting low and high risk.
Based on performance the Easy Ensemble Classifier is recommended for assesing credit risk.







