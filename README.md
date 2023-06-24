# Cardiovascular-Disease-Classification-using-Logistic-Regression
In this project we have done the following steps to classify the Cardiovascular Disease
- We use the dataset from UCI website
- Exploratory Data Analysis
   - Data Quality Report for both continuous and categorical features
- Data Pre-processing:
  1) Remove entries that contain missing values. Remove entries with ? or NaN in them and replace with the mode for categorical features
  2) Replace outliers in data when applicable
  3) Check cardinality of features to check for categorical and continuous features
- Feature selection
  - We choose the features to train the model on by calculating the correlation between the feature and the target, then choosing the features with highest correlation
- Splitting dataset
  - 50/50, 60/40, 70/30, 80/20, 90/10
- Classification
  - Apply standard scalling
  - Use logistic regression model
  - GridSearchCV to find best hyperparameters
- Test the model
- Evaluation
  - Confusion matrix
  - Receiver Operating Characteristic (ROC)
  - Accuracy, Precision, Recall
    
