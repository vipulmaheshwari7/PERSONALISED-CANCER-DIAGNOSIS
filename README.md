# PERSONALISED-CANCER-DIAGNOSIS
1.Business Problem

1.1. Description

Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/
Data: Memorial Sloan Kettering Cancer Center (MSKCC)
Download training_variants.zip and training_text.zip from Kaggle.

We understand that analyzing text represents a difficult challenge, but believe it or not is the current state of the art when it comes to interpretation of genetic variants.

The workflow is as follows

A molecular pathologist selects a list of genetic variations of interest that he/she want to analyze
The molecular pathologist searches for evidence in the medical literature that somehow are relevant to the genetic variations of interest
Finally this molecular pathologist spends a huge amount of time analyzing the evidence related to each of the variations to classify them
Our goal here is to replace step 3 by a machine learning model. The molecular pathologist will still have to decide which variations are of interest, and also collect the relevant evidence for them. But the last step, which is also the most time consuming, will be fully automated.



Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/discussion/35336#198462

 we performed
 -Exploratory data analysis
 -Preprocessing of text
 -univariate analysis
 -Machine learning models like naive bayes, KNN ,Logistic regression,linear support vector machines,Random forest classifier
 -feature engineering
 
 #observations
1. Best model: liner model(logistic regression) with class balancing
2. Best featuriser: tfidf bigram on Text feature
3. Model interpretability: good
4. model complexity : good
5. Best Result using best model with optimum hyperparameter: train loss=0.38, CV loss=0.94,
   test_loss=0.95.




