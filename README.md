
# Module 2 Final Project


## Introduction

This repo contains a multivariate linear regression for King's County Housing Dataset. The dataset can be found here: 
https://www.kaggle.com/harlfoxem/housesalesprediction

## Contents

kc_house_data.csv - King's County Housing Dataset 2014-2015
column_names.md   - column names for the dataset
student.ipynb     - jupyter notebook with code 



## Summary

The King's County Housing Dataset provides several variables that can be used to create a prediction model. The prediction model used was a multivariate linear regression. Log transformations were used for continuous variables, and a MinMax Scaler for for the positively skewed continuous variables. One hot encoding was performed for categorical variables. 

We pose 3 questions and answers given by the analysis:

1. What are the best predictors for the sale price of a house?
Location, amount of bathrooms or bedrooms, square footage above ground, square footage of the basement, condition of the house

2. Are there any changes we can make to increase the sale price of a house?
We can increase the amount of bathrooms or bedrooms of the property. We can renovate the property or help improve the condition of the house.
3. Can location impact sale price?
Yes. Some locations may negatively impact the sale price of a house. It may not be worth it to buy a house in a location that is negatively impacted by it's location if the the ROI is not substantial.

After data transformations, the result of the multivariate linear regression is detailed below:

![alt text](https://github.com/jefferyrosario/dsc-mod-2-project-v2-1-onl01-dtsc-pt-012120/blob/master/ols_house_price.png)



## Conclusion

Our findings suggest that if you increase the amount of bathrooms, improve the condition of the house, increase the square footage above ground, we can sell a house with a higher ROI. Using the cofficients provided in the analysis, we can determine the price of a house after modifications.
