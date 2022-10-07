# Credit_Risk_Analysis

# Overview of the analysis: Explain the purpose of this analysis.

For this analysis I will need to employ different techniques to train and evaluate models with unbalanced classes. Mainly I will use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. 
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, I’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, I’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

# Results: 

The results for the six machine learning models (Naive Random Oversampling, SMOTE Oversampling, Undersampling, Combination (Over and Under) Sampling, Balanced Random Forest Classifier, and Easy Ensemble AdaBoost Classifier) shows the output for their respective balanced accuracy, precision, and recall scores.

The results are as follows:


* Naive Random Oversampling
!['Naive%20Random%20Oversampling](https://github.com/cbrito3/Credit_Risk_Analysis/blob/main/Naive%20Random%20Oversampling.png)

 The balanced accuracy score is 0.6348870972223508. 
 The precision for high and low risk are 0.01 and 1.00 respectively. 
 The recall scores for high and low risk are: 0.66 and 0.61 respectively. 
 

* SMOTE Oversampling
!['SMOTE%20Oversampling](https://github.com/cbrito3/Credit_Risk_Analysis/blob/main/SMOTE%20Oversampling.png)

The balanced accuracy score is 0.6591200367698136. 
The precision for high and low risk are 0.01 and 1.00 respectively. 
The recall scores for high and low risk are: 0.63 and 0.68 respectively. 
 
* Undersampling
!['Undersampling](https://github.com/cbrito3/Credit_Risk_Analysis/blob/main/Undersampling.png)

The balanced accuracy score is 0.6591200367698136. 
The precision for high and low risk are 0.01 and 1.00 respectively. 
The recall scores for high and low risk are: 0.69 and 0.40 respectively. 

* Combination (Over and Under) Sampling
!['Combination%20(Over%20and%20Under)%20Sampling](https://github.com/cbrito3/Credit_Risk_Analysis/blob/main/Combination%20(Over%20and%20Under)%20Sampling.png)

The balanced accuracy score is 0.5443246441108096. 
The precision for high and low risk are 0.01 and 1.00 respectively. 
The recall scores for high and low risk are: 0.72 and 0.57 respectively. 

* Balanced Random Forest Classifier
!['Balanced%20Random%20Forest%20Classifier](https://github.com/cbrito3/Credit_Risk_Analysis/blob/main/Balanced%20Random%20Forest%20Classifier.png)

The balanced accuracy score is 0.78776726253066. 
The precision for high and low risk are 0.04 and 1.00 respectively. 
The recall scores for high and low risk are: 0.67 and 0.91 respectively. 


* Easy Ensemble AdaBoost Classifier
!['Easy%20Ensemble%20AdaBoost%20Classifier](https://github.com/cbrito3/Credit_Risk_Analysis/blob/main/Easy%20Ensemble%20AdaBoost%20Classifier.png)

The balanced accuracy score is 0.925427358175101. 
The precision for high and low risk are 0.07 and 1.00 respectively. 
The recall scores for high and low risk are: 0.91 and 0.94 respectively. 

# Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.





