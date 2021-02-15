# Credit_Risk_Analysis

![image](https://github.com/nypasha1928/Credit_Risk_Analysis/blob/main/Image/Credit%20_Risk_Analysis%20.png)

## Overview

In this project I am going to use machine learning to create prediction models for this classification problem of credit risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. I will be using different techniques to train and evaluate models with unbalanced classes.

## Results
    . BACKGROUNG INFO: 
 
 ![image](https://github.com/nypasha1928/Credit_Risk_Analysis/blob/main/Image/Predicted%20Class.png)
    
    . Precision Score= (Predicted True/ (Predicted True + False Positive)
      -People that were positive, we want to know the likelihood of actually being positive.
      
    . Recall Score= (Predicted True/ Predicted True + False Negative)
      -Person knows has a good loan status, but wants to know what the loan officer will give.
      
  ## BalancedRandomForestClassifier
  ![image](https://github.com/nypasha1928/Credit_Risk_Analysis/blob/main/Image/Balanced%20Random%20Forest%20Classifier.png)
  
    .Accuracy_score (r_squared) = .786
    .Precision = .99
    .Recall =  .87
    
    
## Ensemble AdaBoost Classifier

![image]()
   
    .Accuracy_score (r_squared) = .91
    .Precision = .99
    .Recall =  .93
    
## Naive Random Oversampling w Logistic Regression

![image]()

    .Accuracy_score (r_squared) = .69
    .Precision = .99
    .Recall =  .66
    
## SMOTE Oversampling w/ Logistic Regression

![image]()    
    
    .Accuracy_score (r_squared) = .66
    .Precision = .99
    .Recall =  .68
    
 ## ClusterCentroids Undersampling w/ Logistic Regression
 
 ![image]()
 
    .Accuracy_score (r_squared) = .60
    .Precision = .99
    .Recall =  .50
    
 ## Combination (Over and Under) Sampling w/ Logistic Regression
 
 ![image]()
     
    .Accuracy_score (r_squared) = .67
    .Precision = .99
    .Recall =  .64
    
 ## Summary
 
Overall, the best model that was generated to predict the unbalanced classification problem of credit risk is the Ensemble AdaBoost Classifier as well as the Balanced Random Forest Classifier due to their high precision, recall, and accuracy scores being near 1 which is what we want in this prediction problem. But I would recommend the Ensemble AdaBoost Classifier due to its higher overall scores for a classification prediction.
 
    
 
    

    
    
    
