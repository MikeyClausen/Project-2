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

### REGRESSION METRICS FOR: Test Data XGBoost Tuned
* R2 Score: 0.9467
* Mean Absolute Error: 1.868367
* Mean Squared Error: 17.491149
* Root Mean Squared Error: 4.182242
* Explained Variance Score: 0.954208
* Max Error: 81.715500

### REGRESSION METRICS FOR: Training Data XGBoost Tuend
* R2 Score: 0.9857
* Mean Absolute Error: 1.638309
* Mean Squared Error: 5.274667
* Root Mean Squared Error: 2.296664
* Explained Variance Score: 0.992968
* Max Error: 60.851318

## Description of Model
* XGBoost performed the best on the model with a high r2 score, of 98% of the variance being explained.

## Recommendations
* This model could be implemented to help look at the years grapes where harvested to see what factors provided a better rating.
* It can also help us understand other changes that may have occured, during certain years or during the processes involved in making the wine.

# Cirrhosis
## [Data Source](https://www.kaggle.com/datasets/fedesoriano/cirrhosis-prediction-dataset)
## Description of Data
* Several different variables related to the disease that can be used to help predict if someone is suffering from cirrhosis.
## Business Problem to solve
* Can we predict stage of cirrohosis based on the provided data.

## Analyticals Insights
![Alt text](https://github.com/MikeyClausen/Project-2/blob/main/pics/bilirubin.png)
* This line plot shows us that when Bilirubin is above 7~mg/dl patients are at stage 2 or above of the disease

![Alt text](https://github.com/MikeyClausen/Project-2/blob/main/pics/albmuin.png)
* In this lineplot we can see that after 2.5 mg/dl or lower is found in the blood of Albumin we see many if not all patients at stage 3-4 of the disease.

## CLASSIFICATION REPORT FOR: Random Forest Classifier w/o PCA Test
###              precision    recall  f1-score   support

*          0.0       0.84      0.84      0.84        63
*          1.0       0.73      0.73      0.73        37

*     accuracy                           0.80       100
*    macro avg       0.79      0.79      0.79       100
* weighted avg       0.80      0.80      0.80       100

## CLASSIFICATION REPORT FOR: Random Forest Classifier w/o PCA Train

 ###             precision    recall  f1-score   support

*'          0.0       1.00      1.00      1.00       195'
*'          1.0       1.00      1.00      1.00       104'

*'     accuracy                           1.00       299'
*'    macro avg       1.00      1.00      1.00       299'
*' weighted avg       1.00      1.00      1.00       299'


## Description of model.

* Random Forest Classifier used to predict on the model performed the best. Without more data, or a subject matter expert to help with feature engineering I do not recommend using it.

## Recommendations

* I recommend first taking more time to collect data.
* Once this has been done, provide a subject matter expert to help with feature engineering.
