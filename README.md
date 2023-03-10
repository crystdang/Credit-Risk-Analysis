# Module 18 Challenge: Credit Risk Analysis - Supervised Machine Learning
## by Crystina Dang using Jupyter Notebook, mlenv environment

### Overview of the analysis:

The purpose of this analysis is to evaluate which sampling technique performs best for the intended use of predicting credit risk.

### Results: 

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

#### Resampling Models (Deliverable 1):
(file: Notebooks/credit_risk_resampling.ipynb)


*Below is an image of the balanced accuracy score and imbalance classification report when RandomOverSampler is used:*
![This is an image](https://github.com/crystdang/Credit-Risk-Analysis/blob/main/Images/ROS_BAS.png)
![This is an image](https://github.com/crystdang/Credit-Risk-Analysis/blob/main/Images/ROS_imbalanced.png)


*Below is an image of the balanced accuracy score and imbalance classification report when SMOTE is used:*
![This is an image](https://github.com/crystdang/Credit-Risk-Analysis/blob/main/Images/SMOTE_BAS.png)
![This is an image](https://github.com/crystdang/Credit-Risk-Analysis/blob/main/Images/SMOTE_imbalanced.png)


*Below is an image of the balanced accuracy score and imbalance classification report when ClusterCentroids is used:*
![This is an image](https://github.com/crystdang/Credit-Risk-Analysis/blob/main/Images/CC_BAS.png)
![This is an image](https://github.com/crystdang/Credit-Risk-Analysis/blob/main/Images/CC_imbalanced.png)


#### Combination Models (Deliverable 2):
(file: Notebooks/credit_risk_resampling.ipynb)


*Below is an image of the balanced accuracy score and imbalance classification report when the combinatin sampling SMOTEENN is used:*
![This is an image](https://github.com/crystdang/Credit-Risk-Analysis/blob/main/Images/SMOTEENN_BAS.png)
![This is an image](https://github.com/crystdang/Credit-Risk-Analysis/blob/main/Images/SMOTEENN_imbalanced.png)

#### Ensemble Models (Deliverable 3): 
(file: Notebooks/credit_risk_ensemble.ipynb)


*Below is an image of the balanced accuracy score and imbalance classification report when the machine learning model BalancedRandomForestClassifier is used:*
![This is an image](https://github.com/crystdang/Credit-Risk-Analysis/blob/main/Images/Forest_BAS.png)
![This is an image](https://github.com/crystdang/Credit-Risk-Analysis/blob/main/Images/Forest_imbalanced.png)


*Below is an image of the balanced accuracy score and imbalance classification report when the machine learning model EasyEnsembleClassifier is used:*
![This is an image](https://github.com/crystdang/Credit-Risk-Analysis/blob/main/Images/Ensemble_BAS.png)
![This is an image](https://github.com/crystdang/Credit-Risk-Analysis/blob/main/Images/Ensemble_imbalanced.png)

### Summary: 

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
