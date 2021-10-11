# Credit_Risk_Analysis

# Overview:

Testing machine learning algorithms capabilities to accurately predict credit risk. One challenge to credit risk algorithms is unbalanced data, data in which the values the alorgithm are looking for is relatively small compared to the whole dataset. Credit risk algorthms must balance precision and recall to get accurate results from a population of data. In this analysis I look at six machine learning models and compare their results. 

# Results 

* ## RandomOverSampler
<img width="1189" alt="random_oversanpling_results" src="https://user-images.githubusercontent.com/84756166/136716779-9d1fa8ec-221b-4e00-b7f4-b9f039588842.png">

* ## SMOTE
<img width="1200" alt="SMOTE_results" src="https://user-images.githubusercontent.com/84756166/136716836-a055138a-5452-4d41-9c85-b010298c401d.png">

* ## ClusterCentroids
<img width="1226" alt="undersampling_results" src="https://user-images.githubusercontent.com/84756166/136716863-7d0606dd-e233-4e9c-afc5-d957391f38a3.png">

* ## SMOTEENN 
<img width="1211" alt="SMOTEENN" src="https://user-images.githubusercontent.com/84756166/136716928-c90b7425-6004-47d9-a679-8a279c0fc888.png">

* ## BalancedRandomForestClassifier
<img width="1250" alt="Bal_Random_Forest" src="https://user-images.githubusercontent.com/84756166/136716972-d055cccc-a1a0-4f1f-98dc-be736e52a586.png">

* ## EasyEnsembleClassifier
<img width="1246" alt="Easy_Ensemble_AdaBoost_Classfifier" src="https://user-images.githubusercontent.com/84756166/136717005-93e6d5bb-4a49-43ef-aa83-7ce351ac609f.png">

## Summary:

* The results are fairly consistent within oversampling and undersampling models. However, as we progress and move to reduce bias with the Balanced Random Forest Classifier and Easy Ensemble Adaboost Classifier the results improve greatly. Precision and recall climb into the >90% accuracy level. 

* I would recommend using the Easy Ensemble classifier based on its positive test results. Of course there's always improvement to be made. There are still a handful of false negatives but I think this tool can be used to save time in the loan approval process. All negative results should be reviewed for accuracy. 
