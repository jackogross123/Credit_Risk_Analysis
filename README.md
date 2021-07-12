# Credit_Risk_Analysis
## Resources
Juptyer Notebooks, Python 3.7.6

## Overview of the Analysis
Analyzing credit risk is a difficult challenge. There are many factors that play a role in shaping credit. In this analysis we will build and develop machine learning models to help predict if someone has high or low credit risk. Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then, I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

## Summary
### Use Resampling Models to Predict Credit Risk
 - Naive Random Oversampling: The balanced accuracy test it 67%, the precision for the high_risk has a very low positivity at 1% and the recall is 74%

![image_1](https://github.com/jackogross123/Credit_Risk_Analysis/blob/main/Resources/1.png)

 -Oversampling: The accuracy score is 66.2%, the precision for the high_risk loans has a low positvity again at 1% and recall is 69% overall

![image_2](https://github.com/jackogross123/Credit_Risk_Analysis/blob/main/Resources/2.png)

 - Undersampling: The balanced accuracy score is 66.2% overall, the precision is at 99% and the recall is 41%

![image_3](https://github.com/jackogross123/Credit_Risk_Analysis/blob/main/Resources/3.png)

### Use the SMOTEENN Algorithm to Predict Credit Risk
 - Combination: The balanced accuracy score is 54.7% the precision is 99% and the recall is 57% overall

![image_4](https://github.com/jackogross123/Credit_Risk_Analysis/blob/main/Resources/4.png)

### Use Ensemble Classifiers to Predict Credit Risk
 - Random Forest Classifier: The accuracy score is 77.2% the precision is 99% and the recall is 88%

![image_5](https://github.com/jackogross123/Credit_Risk_Analysis/blob/main/Resources/5.png)

 - Easy Ensemble AdaBoost Classifier: The accuracy score is 91.7% the precision is 99% and the recall is 94%

![image_6](https://github.com/jackogross123/Credit_Risk_Analysis/blob/main/Resources/6.png)

## Recommendation
In the first 4 models we oversampled, undersampled, and took a combination of both to predict loan ratings. The accuracy for the 4 models weren't that high which is probalamtic for our cases. In the next models we took ensemable factors to determine loan ratings.I reccomend the ensemble models to use because they bring the greatest combination of of accuracy and precision.
