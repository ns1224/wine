# Wine Classification

## Introduction
This is a simple classification exercise using the famous wine dataset. In this ML project, I gained experienced using the Random Forest classifier as well as more experience using familiar algorithms: Decision Tree, SVC classifier, and KNN clusters. 

## Data
The data can be loaded through the following code:

    from sklearn.datasets import load_wine

    wine = load_wine(as_frame = True)
    
## Problem
The problem requires classification of different wines into one of three classes: 0,1 or 2. Using different features of the wine, e.g. alcohol, total phenols, etc., we must predict the wine's class. There are 178 unique wines, and 13 feature columns that describe each wine. 
  
## Tools
JupyterNotebooks were used for the EDA and ML model creations. Python is my favorite language for data analysis and Jupyter provides great presentation for output and chunk code output. Using the as_frame parameter returns a dataframe rather than a bunch type for easier pre-processing and data cleaning. 

## Conclusions

The best performing model was the RandomForestClassifier with a 98% accuracy. When the accuracy is so high, it could be a signal of overfitting. 

I was able to use a decision tree classifier to classify the target wine classes, and got an initial 85% accuracy. By tweaking some of the model parameters, I was able to increase accuracy, and by limiting the number of decisions made to classify the observations, decreased the models' overfit. 
