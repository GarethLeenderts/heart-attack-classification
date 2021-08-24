# Heart Attack Prediction



## Overview

According to the CDC, about 805000 people in the United States have heart attacks every year. Heart disease is the leading cause of death in the U.S., with someone dying every 36 seconds from cardiovascular disease.<sup>1</sup>

**Project Goal:**

Predict whether a person is likely to have a heart attack or not based on a set of data points, such as maximum heart rate and cholesterol levels.



## Data

link to dataset: https://www.kaggle.com/rashikrahmanpritom/heart-attack-analysis-prediction-dataset

* Only 303 data points in total
* Fairly balanced(small difference between positive and negative sample numbers)



## Results

Metric: F1-score (weighted average)

|           Model           | F1-score |
| :-----------------------: | :------: |
| Support Vector Classifier |   0.85   |
|       Random Forest       |   0.84   |
|          XGBoost          |   0.81   |
|         AdaBoost          |   0.78   |
|    Logistic Regression    |   0.78   |



## Models Used

* Support Vector Classifier
* Logistic Regression (with L2 regularisation)
* Random Forest
* XGBoost
* AdaBoost



## Techniques Used

* Grid Search
* Data imputation
* A fair amount of Feature Engineering
* Feature Selection using Random Forest Feature Importance (only for engineered features)



## Potential Improvements

* Ensemble the trained models
* K-Fold ensemble
* Use a more advanced data imputation technique(eg. MICE)



##### References

1. https://www.cdc.gov/heartdisease/facts.htm 
