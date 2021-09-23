# Car Selling Price Prediction
## Created a tool to predict selling prices of cars by using Data from cardekho.com available on Kaggle. 
### Step 1: Imported dataset : Cardekho.com via Kaggle.com https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho



### Step 2: Feature Engineering and Selection 
-- Out of the 8 total features present, used correlation and ExtraTreesClassifier to select important features and note their importance. Used One-Hot encoding on 'Transmission' and 'Fuel Type' to convert categorical feature into numerical features. 

 
### Step 3: Used RandomForestRegressor with Hyperparamter tuning to predict selling price and improve accuracy. 
-- Used RandomForestRegressor to predict selling price of cars. Random forest is a Supervised Learning algorithm which uses ensemble learning method for classification and regression.



