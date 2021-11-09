# Wine Classification

## Introduction
This is a simple classification exercise using the famous wine dataset. In this ML project, I gained experienced using the Random Forest classifier as well as more experience using familiar algorithms: Decision Tree, SVC classifier, and KNN clusters. 

## Data
The data can be loaded through the following code:

    from sklearn.datasets import load_wine

    wine = load_wine(as_frame = True)
    X = wine.data
    y = wine.target
  
## Tools
JupyterNotebooks were used for the EDA and ML model creations. Python is my favorite language for data analysis and Jupyter provides great presentation for output and chunk code output. Using the as_frame parameter returns a dataframe rather than a bunch type for easier pre-processing and data cleaning. 

## Conclusions
I was able to create really high performing models, scored both accuracy rate (98.41%) and cross-validated (98.41%). 
