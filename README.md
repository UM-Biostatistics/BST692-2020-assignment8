

# BST692 2020 Assignment 8

# Goal: Predict Late Stage (3 or 4) Breast Cancer
You want to predict which women have advanced (Stage 3) and metastatic (Stage 4) breast cancer.  Cancer is staged clinically (before surgery) and pathologically (using details seen durring surgery).    Here you will be predicting the clinical staging using all variables that were known before surgery.

# Methods
## Subjcts

+ Take the data from the analysis_city20200601 dataset and split it so that 80% will be used for training and 20% for testing.  Do the split in a way that will be reproducible using a technique to make sure that the percentage of late stage are the same in both groups.  
+ Describe the percentage with late stage in the two samples

## Data processing

+ Dummy code variables that should be treated as categorical (but keep age and income as numeric).

## Use KNN

+ Find a good value of k.
+ Predict late stage.
+ Build a confusion matrix showing the actual vs predicted results in the test data.  Comment on the accuracy and kappa.

## Use logistic regression

+ Build a predictive logistic regression model.  
+ Examine the overall model
+ Examine the betas/p-values
+ Comment on the overall model and the predictors.
+ Build a confusion matrix showing the actual vs predicted results in the test data.  Comment on the accuracy and kappa.
