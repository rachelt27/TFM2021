# TFM2021

In this thesis we explored the capabilities of machine learning for the detection of incipient cognitive dysfunction that occurs in the early stages (Preclinical) of Alzheimer’s disease.  In particular we provide a tool for clinicians to distinguish which tests are sensitive enough to classify healthy subjects to those with Preclinical Alzheimer’s Disease. 

**Datasets**
1. Battery tests
2. [Finger tapping tests](https://osf.io/2kje8/)

**Process**
⋅⋅* Conduct a data analysis on both data sets 
⋅⋅* Analyze the performance over different classification models and ensemble methods 
⋅⋅* Classify with the chosen Random Forest and compute the feature importance scores
⋅⋅* Analyze the use of Synthetic Minority Oversampling Technique (SMOTE) to deal with the imbalanced nature of the dataset 
⋅⋅* Fine Tuning model with grid search

**Models and ensemble methods tested**
⋅⋅* Random Forest 
⋅⋅* Logistic Regression
⋅⋅* SVM (Linear Kernel)
⋅⋅* SVM (Polynomial Kernel)
⋅⋅* SVM (Radial Basis Function Kernel)
⋅⋅* Naive Bayes
⋅⋅* XGBoost 
⋅⋅* Adaboost
⋅⋅* Hard Voting
⋅⋅* Stacking

**Functions**
The key custom function used throughout are located in the file *Functions.ipynb*

