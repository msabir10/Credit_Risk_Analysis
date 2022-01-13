# Credit_Risk_Analysis

## Project Overview
The purpose of this project is to employ different techniques to train and evaluate models with unbalanced classes. With the credit dataset from LendingClub, several different algorithms are used to predict credit risk. The performance of these different models are compared and recommendations are suggested based on the results.


## Software
Python 3.7
SciPy 1.6.2
Scikit-learn 0.24.1
imbalanced-learn 0.80


## Results
#### Oversampling-Native Random Oversampling
Balanced Accurracy Score: 0.674
High-Risk Precision: 0.01
High-Risk Recall: 0.74

#### Oversampling-SMOTE
Balanced Accurracy Score: 0.662
High-Risk Precision: 0.01
High-Risk Recall: 0.63

#### Undersampling: Random Undersampling
Balanced Accurracy Score: 0.662
High-Risk Precision: 0.01
High-Risk Recall: 0.63

#### Balanced Random Forest Classifier
Balanced Accurracy Score: 0.788
High-Risk Precision: 0.03
High-Risk Recall: 0.70

#### Easy Ensemble AdaBoost Classifier
Balanced Accurracy Score: 0.931
High-Risk Precision: 0.09
High-Risk Recall: 0.92


## Summary
For all models, utlizing EasyEnsembleClassifier is the most effective. Provides a highest Score for all Risk loans. The precision is low or none for all the models. In General, above the 90% of the current analysis, utlizing EasyEnsembleClassifier will perform a High-Risk loan precision as a great value for the overall analysis.