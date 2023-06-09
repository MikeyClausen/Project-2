# Project-2
## Spanish Wine
## [Data Source](https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset)
### Brief description of data
* A list of 7000+ wines that describe their price, rating, and even some flavor description.
### Business Problem to solve.
* Our business problem is to find out how rating effects the price of wine. Stakeholders - Investors of the wine producers, farmers who are growing grapes.

## Analyticals Insights
![Alt text](https://github.com/MikeyClausen/Project-2/blob/main/PBYOGH.png)

#### The above bar plot shows that after the year 1969, almost no wine produced sold for over '1000'. This bit of information seems useful as it may be a grape quality issue, as discussed in our other trend of rating by year of the grape harvest.

![Alt text](https://github.com/MikeyClausen/Project-2/blob/main/ROWBOHYOG.png)

####  Above line plot shows the drop in rating based on the year grapes were harvested. A significant decline can be seen from 1990 onward.

### Random Forest Regression w/o PCA Test Scores Tuned Scores
* MAE: 0.5911
* MSE: 0.5141
* RMSE: 0.7170
* R2: 0.3281

### Random Forest Regression w/o PCA Train Scores Tuned Scores
* MAE: 0.2414
* MSE: 0.0866
* RMSE: 0.2943
* R2: 0.8853


## Description of model.

* Random Forest Regression used to predict on the model performed the best. Without more data, or a subject matter expert to help with feature engineering I do not recommend using it.

## Recommendations

* I recommend first taking more time to collect data.
* Once this has been done, provide a subject matter expert to help with feature engineering.
