# An Integrated Project 2 - Gold mining

### The company name is Zyfra

The company develops efficiency solutions for heavy industry.  They are a business to business company and aims to solve problems for industry makers.  The goal is to predict how much gold ore will be extracted from a gold site.  We want to discover what is inefficient/efficient and optimize profitable parameters.   
 
### Details of Linear Algebra

Cleaned data and performed EDA.  Ensured no data leakage for our models to be created, by assuring certain features are not made available for test set.  Outliers are present in the data so this must be accounted for in data manipulation. Ploted histograms in analysis for chemical changes in process. Used functions and pipelines to build models for cross-validation, and tuned the model's hyperparameters using a cross-validated grid search.  Used Smape for scoring method of models. 

#### The Data

The data is on the extraction and purification process.  Data set came in different sets; all information is available in the full data set. 
  


### Results

Throughout the purification stages the mean changes in the stages dramatically for gold in a positive amount.  Also lead has increased in the purification stages, while silver has a small negative change in its mean.
My recovery was calculated correctly.  I measured the spread of data using intersquartile range and calculated the outliers. By multiplying the difference between the 75th and 25th percentiles by 1.5. Out of over 16,000 observations of data, a small number of outliers cause the mean absolute error to go from 69.163 to 1.0875.  The recovery is calculated correctly.