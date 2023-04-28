# `puerto-rico-forest-transition`: Examining Puerto Rico’s Forest Transition with Tree Cover Prediction Models


This project was completed as a requirement for GIS 5572: Principles of Geocomputing at the University of Minnesota.

## About

The aim of this project was to determine the most significant factors contributing to forest transition (~1950s-2000s) and to find a model that best predicts forest cover based on the explanatory variables. The explanatory variables under consideration comprise slope, soil productivity, precipitation, poverty rate, population density, and land protection level. 

### Methods
- Exploratory Regression `arcpy`
- Spatial Autocorrelation (Global Moran's I) `arcpy`
- Hot Spot Analysis `scipy`
- Generalized Linear Regression (GLR) `statsmodels.api` `scikit-learn`
- Random Forest Model `scikit-learn`
- Linear Regression, Lasso, Ridge, Decision Tree Regression, Random Forest Regression, and XGBoost Regression `scikit-learn` `xgboost`


### Results 
The Random Forest Model was the best model in predicting forest cover in Puerto Rico, r2 = 0.83. 


<img src="https://user-images.githubusercontent.com/103837294/235193434-10daf91f-155f-469a-b870-7efb8535fb60.png" width=50% height=50%>


## Structure
* Data: `/data`

* IPYNB File(s): `/ipynb`


## Author(s)
Mattie Gisselbeck
