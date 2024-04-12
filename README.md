# Prediction-of-Product-Sales

## Overview

- this project is dedicated to showcase my skills in my first stack of CodingDojo Data Sience Bootcamp, where i used a Sales dataset to Perform pre=processing tasks and Exploratory visualization. Here is two examples of the visuals that I created:
  - Data distribution of the item outlet sales feature:
![Data distribution of the Item outlet sales feature](https://github.com/YassinDhaya/Prediction-of-Product-Sales/assets/115571727/9858bac9-d341-4d65-b082-622d2035c8ad)
  - LM plot of the item MRP and the item outlet sales features grouped by the outlet size
 ![LM plot of the item MRP and](https://github.com/YassinDhaya/Prediction-of-Product-Sales/assets/115571727/94d580bf-e80b-4f74-85b2-5f193dc769f9)
# Author: Yassin Dhaya

# Business problem:
We are trying to predict sales for food items sold at various stores

# Data:
The data is a dataset that contains food item attributes of 8523 observations , the attributes are :          
 1   Item_Weight               
 2   Item_Fat_Content         
 3   Item_Visibility            
 4   Item_Type                 
 5   Item_MRP     
and 7 other features
# Methods
## Data preparation
we started by removing duplicates, the checking anf fixing inconsistencies in the data, then imputing missing values and removing outliers
## Column transformer
we scaled our numeric data , one-hot-encode our categorical data and encoded our ordinal data
## model implementation
we tried a linear regression model and a tuned Random forest model and we comparred the performance of the models based on performance metrics like r2 and RMSE
# Results
we found that the best performing model is the random forst model
## the most important metrics
RMSE = 1,057.559
R^2 = 0.595
