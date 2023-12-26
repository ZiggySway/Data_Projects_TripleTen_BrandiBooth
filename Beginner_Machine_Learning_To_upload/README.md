# Beginner Machine Learning - ML execution

### The company name is Megaline

Megaline is a mobile phone carrier.  I am to automate a process of which customers to offer the updated phone plan to. It checks out to be a classification task, to help the company automatically determine offer the new product to the best selected customers.  

 
### Details of Beginner Machine Learning

I cleaned the data and gave a thorough EDA. Visualize the data using a heatmap.  This showcases correlations of features of the data. Then I begin to split the data into features known as (x) and targets, known as (y).  I use the train_test_split function to  create training and test sets.  I use a random_state, and make a test size sample.  

#### The Data

I have access to behavior data about subscribers who have already switched to the new plans (from the project for the Statistical Data Analysis).   


### Results

We can see more than half the customers have chosen the Smart Plan.  Two of the training datasets accuracy scored higher than the test set.  Which shows overfitting in the models. 
As we can see RandomForestClassifier has the highest accuracy percentage of 81%.  Which is above 75% threshold and far above the 50% chance rate if our data was balanced, and more than 75% chance rate if data mostly chose toward skewed data.


