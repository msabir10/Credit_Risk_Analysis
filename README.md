# Credit_Risk_Analysis

## Project Overview
The purpose of this project is to employ different techniques to train and evaluate models with unbalanced classes. With the credit dataset from LendingClub, several different algorithms are used to predict credit risk. The performance of these different models are compared and recommendations are suggested based on the results.


## Software
- Python 3.7
- SciPy 1.6.2
- Scikit-learn 0.24.1
- imbalanced-learn 0.80


## Results
#### Oversampling-Native Random Oversampling
- Balanced Accurracy Score: 0.674
- High-Risk Precision: 0.01
- High-Risk Recall: 0.74

#### Oversampling-SMOTE
- Balanced Accurracy Score: 0.662
- High-Risk Precision: 0.01
- High-Risk Recall: 0.63

#### Undersampling: Random Undersampling
- Balanced Accurracy Score: 0.662
- High-Risk Precision: 0.01
- High-Risk Recall: 0.63

#### Balanced Random Forest Classifier
- Balanced Accurracy Score: 0.788
- High-Risk Precision: 0.03
- High-Risk Recall: 0.70

#### Easy Ensemble AdaBoost Classifier
- Balanced Accurracy Score: 0.931
- High-Risk Precision: 0.09
- High-Risk Recall: 0.92


## Summary
For all models, utlizing Easy Ensemble Classifier is the most effective. Easy Ensemble also has the highest precision, recall, and F1 scores as proven by the imbalanced classification reports. 
If one of the models in this project must be used to predict credit risk, it is recommended to use Easy Ensemble AdaBoost Classifier. However, if given the option, it is not suggested to use any of these models. Further research and development are required to create a more robust model that can predict credit risk.
