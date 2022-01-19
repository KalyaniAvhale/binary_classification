# binary_classification
Data Scientist assignment

Assignment was implemented following below steps,
### Step 1 : Explore Data set

### Step 2 : Data Visualizations 

### Step 3 : Feature Selection 
- Correlation Matrix
- Random Forest 

### Step 4 : Model Building and Evalution

## Summary 
1. Used 2 techniques for feature selection process - Correlation matrix and Random Forest
2. As part of preprocessing , StandardScaler was used to perform feature scaling
3. Model Comparion and Evaluation:
1. Logistic Regression : Model was getting overfitted slightly based on the AUC and ROC curve, results obtained we good and better compared to baseline model ( <31%).
2. KNN - Knn model performed well but tends to be overfitted and need more parameter tunning(k-value) to obtain best results
3. Random Forest : Random Forest performed good compared to LR and Knn and prevented model from overfitting. Here we can skip the process of scailing features. Correlation Feature selection gave slight 1% good results as compared to RF feature selection technique
4. XGB Classifier : XGB classifer with hyperparameter tunning performed better with .94 as f1 score and AUC equal to .99
Above AUC & ROC graph shows the compared results of different fitted models


## Files : 

Assignment_Data_Scientis.ipynb : Consist of all steps following EDA, Feature Selection and model building. This also includes predictions on test data
requirements.txt : Includes the required libraries
results.csv : Predicted results for test data
performance_results.json : Perfomance metrics for all models 
