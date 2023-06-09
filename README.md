# Project-2
## Spanish Wine
## [Data Source](https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset)
### Description of data
* A list of 7000+ wines that describe their price, rating, and even some flavor description.
### Business Problem to solve.
* Our business problem is to find out how rating effects the price of wine. Stakeholders - Investors of the wine producers, farmers who are growing grapes.

## Analyticals Insights
![Alt text](https://github.com/MikeyClausen/Project-2/blob/main/PBYOGH.png)

* The above bar plot shows that after the year 1969, almost no wine produced sold for over '1000'. This bit of information seems useful as it may be a grape quality issue, as discussed in our other trend of rating by year of the grape harvest.

![Alt text](https://github.com/MikeyClausen/Project-2/blob/main/ROWBOHYOG.png)
*  Above line plot shows the drop in rating based on the year grapes were harvested. A significant decline can be seen from 1990 onward.

### Test Data Random Forest Regressor
* R2 Score: 0.7953
* Mean Absolute Error: 0.001128
* Mean Squared Error: 0.000088
* Root Mean Squared Error: 0.009403
* Explained Variance Score: 0.795340
* Max Error: 0.142000

### Training Data Random Forest Regressor
* R2 Score: 0.9642
* Mean Absolute Error: 0.000443
* Mean Squared Error: 0.000020
* Root Mean Squared Error: 0.004420
* Explained Variance Score: 0.964161
* Max Error: 0.110500

## Description of Model
* The Random Forest Regressor performs well on the model. Has a high R2 Score, High Explained Variance.

## Recommendations
* This model could be implemented to help look at the years grapes where harvested to see what factors provided a better rating.
* It can also help us understand other changes that may have occured, during certain years or during the processes involved in making the wine.

# Cirrhosis
