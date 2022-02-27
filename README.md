# Credit_Risk_Analysis
## Overview of the analysis 
The purpose of this project is to build up the skills to use in data preparation, statistical reasoning and machine learning to apply on the unbalanced classification problem by using oversampling, undersampling algorithms and the combination approach of over- and undersampling algorithm. 

## Results

- Naive Random Oversampling
<img width="751" alt="Naive Random Oversampling" src="https://user-images.githubusercontent.com/92502292/155835036-91c752a8-1c6c-41d6-a616-a524af291d6a.PNG">

- SMOTE Oversampling
<img width="709" alt="SMOTE oversampling" src="https://user-images.githubusercontent.com/92502292/155835068-5c0c61e7-39b6-47ad-950d-e1f37872ef4a.PNG">

- Undersampling 
<img width="743" alt="Undersampling" src="https://user-images.githubusercontent.com/92502292/155835097-f505a94d-eed5-412e-97ec-944931ff4b8c.PNG">

- SMOTEENN
<img width="743" alt="SMOTEENN" src="https://user-images.githubusercontent.com/92502292/155835112-784a1869-210b-4440-8548-91e64da71905.PNG">

- Balanced Random Forest Classifier 
<img width="889" alt="Balanced Random Forest Classifier" src="https://user-images.githubusercontent.com/92502292/155835127-de377f74-75d8-4309-a41b-285d403ae30e.PNG">

- Easy Ensemble AdaBoost Classifier
<img width="783" alt="Easy Ensemble AdaBoost Classifier" src="https://user-images.githubusercontent.com/92502292/155835143-6c2f6505-ca1a-4ca9-a835-910b07061d5d.PNG">

## Summary 
After testing supervised machine learning model, we were able to know which models has the best performance and gives the values of target column close to one of accurancy score. Model using resampling has low calculated accuracy score and none of the models are exceeded over 0.7. The highest score is 0.6623 accuracy score using SMOTE oversampling model. However, Ensemble classifier model gives better accuracy score. The model with BalancedRandomForestClassifier has 0.78776 accuracy score while EasyEnsemble AdaBoot Classifier has 0.9254 accuracy score which gives the highest of all the models that has been tested. 

Our supervised training shows that the most promising module to use is EasyEnsemble AdaBoot Classifier with and accuracry score 0.9254.  