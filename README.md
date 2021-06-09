# car_price_prediction
# Overview
this is machine learning based end to end developed model which help us to predict true car price on the basis of past data.

# steps followed to build this project
1)Data acquisition : data is gether from cardekho.com

2)Data preprosessing and feature engineering : in this step i have done data preprocessing tasks like missing value treatement , outlier detection , created new feature from existing feature , converted categorical data into continuous data using various encoding techniques and made data ready for further analysis.
 
3)Exploratory Data analysis : in this step i have done some EDA task to understand the behavior of data using on multivariate ananlysis with matplotlib and seaborn library.

4)feature selection : in this step i had been checked which feature is give more inpact on target variable(most importanat feature) with the help of ExtraTreesRegressor method of sklearn. 

5)model development(predictive modelling): in this step i have use RandomforestRegressor algorithm for train my model and make predictions , i have also done hyperparameter tuning for findning best parameter to build my machine learning model.

6)model deployment : i have been deployed my whole machine learning based application which is made using flask on heroku plateform. 
you can watch the working app or model on this link :- 
just put required data and you will get your correct car price 

# Technology used
made with - Python programming language

scikit learn

flask
