# Concrete strength regression

This notebook contains a brief **Exploratory Data Analysis** of the ["Revisiting a Concrete Strength regression" Dataset](https://www.kaggle.com/maajdl/yeh-concret-data) and a selection of models trained to predict concrete mixture's compressive strength based on it's ingredients. 


### Github sometimes has problems rendering jupyter notebooks correctly, if that happens please visit 
https://www.kaggle.com/janzasadny/concrete-strength-regression-94-4-r2 

or 

https://nbviewer.jupyter.org/github/ZasadnyJan/Concrete_strength_regression/blob/main/Main_notebook.ipynb 

## Data

The ["Revisiting a Concrete Strength regression" Dataset](https://www.kaggle.com/maajdl/yeh-concret-data) contains information about different concrete recipes and compressive strength of each of them. 

## Objectives
**EDA**

The objective of this notebook is to perform a brief **data analysis** in order to identify properties of variables and relationships between them. 


**Data cleaning and variable engineering**

Acquired information will then be used to **clean the data** and **engineer variables** in a way that should improve model performance. 


**Model training**

Next, I will train **6 regression models**: 
- LinearRegression
- Ridge 
- Lasso
- RandomForestRegressor
- GradientBoostingRegressor
- XGBRegressor

using **GridSearchCV** and **RandomizedSearchCV** to optimize their parameters. This balanced selection of linear and non-linear models should hopefully provide us with an accurate solution for this problem.


**Model exploration**

Lastly, I will **analyze the information** provided by the best performing model to gain deeper insights about the data as well as the model and try to find out which variables have the largest impact on concrete's compressive strength.
