# Causes of death data set
objective: Find the leading cause of death overall within the US. From there we will try and cluster the leading causes and see if any specific sections of the nation are vunerable to specific problems.
* EDA
    - [X] Put data into pandas dataframe
    - [X] Find info, mean, medians, and datatypes for each column
        - [X] Examine typing, noise, and distribution     
    - [X] Deal with outliers or missing data
    - [X] Make some correlations for the data and create a heatmap 
    - [X] Write up the initial EDA discoveries

* Data Prep
    - [X] see if there are any functions needed for graphing purposes
    - [X] make copies of the data
    - [X] divide train, valid, and test sets
    - [X] feature engineering
        - [X] Feature selection (Not needed)
        - [X] Feature transformations
        - [X] feature scaling

* Classification Task
    - [X] Try some classifiers starting with log regression
    - [X] Cross-Validation test on the model
    - [X] Create Pipeline for the models with the best CVs
    - [X] hypertune model as needed
    - [X] Try to see if it can guess the model without `113 Cause Name` column
    - [X] Try more models 

# Top college dataset
* EDA
    - [X] Put data into pandas dataframe
    - [X] Find info, mean, medians, and datatypes for each column
        - [x] Examine typing, noise, and distribution     
    - [X] Deal with outliers or missing data
    - [X] Make some correlations for the data and create a heatmap 
    - [X] Write up the initial EDA discoveries

* Regression Task
    - [X] drop unnecessary columns for ranking regression
    - [x] Simple impute on numeric and category columns outlined in the EDA 
    - [X] One hot encode category columns
    - [X] Make traget column, and split the data for train and test set
    - [X] Pipelines
    - [X] try some regressors to find rank and feature importance associated with rank
    - [ ] draw up some general conclusions based on the dataset
* Classification Task
    - [ ] see if it's possible to guess the name of the univiersity 