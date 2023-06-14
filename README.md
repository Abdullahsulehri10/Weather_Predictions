# Weather_Predictions
## Linear Regression and ML flow
This dataset was sourced from Datacamp which consisted of 15341 rows and 10 variables. As climate change has become the hot topic these days, it has become imperative for climatologists to ameliorate their weather forecasting. Sklearn and Mlflow is used to predict london's mean weather temperature (target variable) against features that are classified as weather metrics. The following are the contents:
* Exploratory Data Analysis
* Data Visualization
* Feature Selection
* Preprocessing
* Machine Learning Training and Evaluation

The date column has been featured engineered in a datetime format by extracting the month and year out of it to analyze the mean weather temperature per month. This was visualized using lineplot and barplot following a heatmap of the correlation of all metrics. 
33% was the train-test-split ratio. Simple Imputer was used to replace null values with the mean values of variables. The values were scaled using standard scaler and the data was normalized. 
The accuracy was measured using three models: Linear Regression, Random Forest and Decision Tree.
These three models were experimented using mlflow where each model was suffixed and its experiment time and accuracy value was recorded.
