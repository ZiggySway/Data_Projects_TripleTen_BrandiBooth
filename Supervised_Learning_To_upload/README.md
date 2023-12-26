# Supervised Learning - Training Machine Learning

### The company name is Beta Bank

Beta Bank customers are leaving on a monthly basis. The bankers want to save the existing customers rather than attract new ones. I will predict whether a customer will leave the bank soon. This will allow the bankers to target suspected leaving customers with enticing offers, generating loyalty. 

 
### Details of Supervised Learning

After cleaning and EDA; I used one-hot encoding to feature prep for machine learning in non-numeric features.  Observed class imbalance, and used hyperparameters to weight the data for proper calculations and no overfitting. 
I have data on clients’ past behavior and termination of contracts with the bank to use. I used StandardScaler function to make all the data features even for evaluation.  I fitted the model using the training set, then transformed the training set, validations set, and testing set; using the same mean and standard deviation obtained from the training set.  This occured during the `scaler.fit(X_train[normalize])` portion of the code. Then I used `scaler.transform`, calling it on all the sets.  This ensures consistency in the scaling process across all sets.
  

#### The Data

I have data on clients’ past behavior and termination of contracts with the bank to use.    


### Results

I will build a model with F1 score, of at least 0.59 and check the F1 for the test set. Also, I will measure the AUC-ROC metric and compare it with the F1. Training a model Random Forest Classifier is the best model. Final model F1 score is .62; above expectation. AUC-ROC is depicted in visualization tools. The model works better than moving by chance. 


