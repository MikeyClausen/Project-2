# Project-2 - Spanish Wine
Create a README.md file in your GitHub repository. This README should include:
Your business problem and stakeholders
The source of your data
A description of your data
2 analytical insights from your data analysis.
You can use the 2 plots from Project 2, part 3 for this!
They should include visualizations AND written interpretations
The metrics for your best model
A description of how well your model would solve your business problem
A summary with at least 2 recommendations for your stakeholders, based on your model performance AND analytical findings.
## Business Problem to solve.
* Our business problem is to find out how rating effects the price of wine. Stakeholders - Investors of the wine producers, farmers who are growing grapes.

## Source : https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset

## A list of 7000+ wines that describe their price, rating, and even some flavor description.

## Harvest year and quality of harvest Greatly effect the rating. Rating effects price directly in most cases.

##  Above line plot shows the drop in rating based on the year grapes were harvested. A significant decline can be seen from 1990 onward.

## The above bar plot shows that after the year 1969, almost no wine produced sold for over '1000'. This bit of information seems useful as it may be a grape quality issue, as discussed in our other trend of rating by year of the grape harvest.

### ------------------------------------------------------------
[i] REGRESSION METRICS FOR: Test Data Random Forest Regressor
------------------------------------------------------------
R2 Score: 0.7953
Mean Absolute Error: 0.001128
Mean Squared Error: 0.000088
Root Mean Squared Error: 0.009403
Explained Variance Score: 0.795340
Max Error: 0.142000
------------------------------------------------------------
[i] REGRESSION METRICS FOR: Training Data Random Forest Regressor
------------------------------------------------------------
R2 Score: 0.9642
Mean Absolute Error: 0.000443
Mean Squared Error: 0.000020
Root Mean Squared Error: 0.004420
Explained Variance Score: 0.964161
Max Error: 0.110500