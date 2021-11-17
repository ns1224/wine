# Wine Classification

## Introduction
This is a simple classification exercise using the famous wine dataset. In this ML project, I gained experienced using the Random Forest classifier as well as more experience using familiar algorithms: Decision Tree, SVC classifier, and KNN clusters. Further, by tweaking model parameters, the models were able to increase in their accuracy, even to a perfect classification. 

## Tools
JupyterNotebooks were used for the EDA and ML model creations. Python is my favorite language for data analysis and Jupyter provides great presentation for output and chunk code output. Using the as_frame parameter returns a dataframe rather than a bunch type for easier pre-processing and data cleaning. 

## Data
The data can be loaded through the following code:

    from sklearn.datasets import load_wine

    wine = load_wine(as_frame = True)
    
## Problem
The problem requires classification of different wines into one of three classes: 0,1 or 2. Using different features of the wine, e.g. alcohol, total phenols, etc., we must predict the wine's class. There are 178 unique wines, and 13 feature columns that describe each wine. Being a classification problem, are options are limited to classification algorithms, such as decision trees, support-vector classifiers, or clustering. 
  
## Conclusions

I was able to gain valuable experience with sklearn's machine learning packages, and explore some of the model object attributes for each. In doing so, and visualizing the decision trees, its easier to comprehend the logic behind the classifications.

For future projects, I think code reusability is key. For example, creating visualization functions to use cross-program would save time for many future projects. Many aspects that went into the intial analysis and exploration could be functionizable. 
