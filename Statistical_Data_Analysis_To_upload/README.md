# Statistical Data Analysis - SDA

### The company name is Megaline

I determine which plan is a better plan as I work as an analyst for the telecom operator Megaline. The company offers its clients two prepaid plans, Surf and Ultimate. The commercial department wants to know which of the plans brings in more revenue in order to adjust the advertising budget.


### Details of SDA

Here I carry out a preliminary analysis of the plans based on a relatively small client selection.  I have the data on 500 Megaline clients: who the clients are, where they're from, which plan they use, and the number of calls they made and text messages they sent in 2018.  I analyze the clients' behavior and determine which prepaid plan brings in more revenue.
I load the data in using pandas.  I inspect the data for duplicates, consistency with casing/ spacing, check for missing data and other cleaning techniques.  There are 5 datasets so I inspect them all. I reset the index to the plan name for simplicity. I feature engineer a column to the plans dataframe; I fix and enrich the data. I use groupby function and aggregate to pull insights from the data. I also build pivot tables.  Created visualizations to display the data.  I create a hypothesis and test it using ttest, and p-value. 

#### The Data

I am provided with 5 datsets to work with.      


### Results

In general, Surf users clearly require more minutes.  I calculate the mean and the variable of the call duration to consider whether users on the different plans have different behaviours for their calls. Behavior is similar as far usage on the different plans.  Which tends to make the surf users use the upper limits of their plan, and Ultimate users, use the lower limits/ or amounts of their plan package.
On average; half of the surf user population goes over package limits monthly.  
