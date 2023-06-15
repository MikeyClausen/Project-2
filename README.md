# Project-2
# Spanish Wine
## [Data Source](https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset)
### Description of data
* A list of 7000+ wines that describe their price, rating, and even some flavor description.
### Business Problem to solve.
* Our business problem is to find out how rating effects the price of wine. Stakeholders - Investors of the wine producers, farmers who are growing grapes.

## Analyticals Insights
![Alt text](https://github.com/MikeyClausen/Project-2/blob/main/pics/PBYOGH.png)
* The above bar plot shows that after the year 1969, almost no wine produced sold for over '1000'. This bit of information seems useful as it may be a grape quality issue, as discussed in our other trend of rating by year of the grape harvest.

![Alt text](https://github.com/MikeyClausen/Project-2/blob/main/pics/ROWBOHYOG.png)
*  Above line plot shows the drop in rating based on the year grapes were harvested. A significant decline can be seen from 1990 onward.

### Test Data Random Forest Regressor
* R2 Score: 0.9638
* Mean Absolute Error: 0.330771
* Mean Squared Error: 11.879550
* Root Mean Squared Error: 3.446672
* Explained Variance Score: 0.963791
* Max Error: 68.925469

### Training Data Random Forest Regressor
* R2 Score: 0.9799
* Mean Absolute Error: 0.201825
* Mean Squared Error: 7.426682
* Root Mean Squared Error: 2.725194
* Explained Variance Score: 0.979874
* Max Error: 104.330066

## Description of Model
* The Random Forest Regressor performs well on the model. Has a high R2 Score, High Explained Variance.

## Recommendations
* This model could be implemented to help look at the years grapes where harvested to see what factors provided a better rating.
* It can also help us understand other changes that may have occured, during certain years or during the processes involved in making the wine.

# Cirrhosis
## [Data Source](https://www.kaggle.com/datasets/fedesoriano/cirrhosis-prediction-dataset)
## Description of Data
* Several features to help predict if soneone's stage of cirrhosis of the liver.
## Business Problem to solve
* Can we predict stage of cirrohosis based on the provided data.

## Analyticals Insights
![Alt text](https://github.com/MikeyClausen/Project-2/blob/main/pics/bilirubin.png)
* This line plot shows us that when Bilirubin is above 7~mg/dl patients are at stage 2 or above of the disease

![Alt text](https://github.com/MikeyClausen/Project-2/blob/main/pics/albmuin.png)
* In this lineplot we can see that after 2.5 mg/dl or lower is found in the blood of Albumin we see many if not all patients at stage 3-4 of the disease.

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
