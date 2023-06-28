**Price Prediction Model on Housing Data Using Linear Regression**

*Description*
-Predicted the sale price of a house based on data about other similar houses & created an effective price prediction model. 
-Linear Regression can be used to predict value of dependent variable 'Sales' (i.e. Y) based on one or more independent variables(i.e. X). 



*Problem Solving Framework*
1. Imported data & necessary libraries                                                                    
   !pip install python
   !import numpy as np   
   !import matplotlib.pyplot as plt  
   !import pandas as pd  

2. Understand & explored the data 
   a.Investigated Sale Price by looking at statistics such as mean, std, min, max etc. Visualize histograms to better understand data
   b.Explored the data by using scatter plots to understand the relationship between SalePrice(i.e. dependent variable) & different independent variables

3. Data cleaning 
   a.Find nulls in numerical columns
   b.Took care of nulls by either replacing or dropping them
   
4. Finding correlation
   a. Calculated correlation with respect to Sale Price
   b. Created three groups of variables based of correlation
      i First Set of Variables with correlation of ~69% & above
      ii Second Set of Variables with correlation of 60% & above
      iii Third Set of Variables with correlation of ~50% & above

5. Created and analyzed Linear Regression Model
   a. Built Linear Regression Model 
   b. Checked model effectivenes using R²

6. Checked validity of price prediction model against test data
   
