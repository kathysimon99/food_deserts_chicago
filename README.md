<img src ='images/chicagoimg.jpg' width = 300>
-downtown Chicago

#  Food Deserts In Chicago
___
### Alonzo Mays, Kathy Simon, and Mark Harris
___
# Table of Contents
| Topic | Description | Link |
| --- | --- | --- |
| Preliminary EDA | EDA that was performed in a Geopandas Environment |[eda_in_geopandas.ipynb](./eda_in_geopandas.ipynb) |
| Merge Food and Health Data |Merge Food and Health Data and Perform a Preliminary Clean | [food_health_clean_merge.ipynb](./food_health_clean_merge.ipynb) |
| Health Outcome Prediction | Predict Health Outcomes Using Low Access| [health_outcome_prediction.ipynb](./health_outcome_prediction.ipynb) |
| Food Desert Prediction | Predict Food Desert Using Health Outcomes | [predict_food_desert.ipynb](./predict_food_desert.ipynb)
| Demographic Visuals | Visuals created in Plotly About the Demographics | [create_visuals.ipynb](./create_visuals.ipynb) |
| Geographical Visuals | Geographical Visuals created in Geopandas| [create_visuals_geopandas.ipynb](./create_visuals_geopandas.ipynb)|
| Data | Folder Containing Data Files| [data](./data/) |
|Visuals | Folder Containing Visuals| [visuals](./visuals/)|

## Outline
___
### I. Problem Statement
### II. Description of Data
### III. Modeling
### IV. Summary
___

### I. Problem Statement

37 million people, including 11 million children, lacked consistent access to healthy food In 2018. That translates to 1 in 9 people having food insecurities in the United States. With so many people experiencing food insecurities, why is approximately $161 million of food wasted?

One reason that so many people in the United States experience food insecurities is that access to healthy food is scarce. There are communities, called food deserts, that have limited access to healthy foods. Our goal is to provide access to healthy foods within these deserts by means of local markets or mobile food trucks.  We will identify food deserts in Chicago using a binary classification model. Once we have identified the food deserts, we will identify optimal locations to provide these neighborhoods with access to healthy foods.


* need background information
___
### II. Description of Data
* Need information about the data and links to where the original data can be found.
 
* Summary of what the data looks like including a few important visuals

<img src = 'visuals/bar_pop_age_low_food_access.png'> 

[link to data dictionary for original low access data](./data/food_data_dictionary.csv)

####  Description of Important Features
| Feature | Type | Dataset | Description |
| --- | --- | --- | --- |
| LowIncomeTracts | int | [food_obesity.csv](./data/food_obesity.csv) | Flag for low income tract |
| HUNVFlag | int | [food_obesity.csv](./data/food_obesity.csv)| Flag for tract where >= 100 of households do not have a vehicle, and beyond 1/2 mile from supermarket |
| LATracts1 | int | [food_obesity.csv](./data/food_obesity.csv)| Flag for low access tract when considering 1 mile distance |
| LATracts_half | int |[food_obesity.csv](./data/food_obesity.csv) | Flag for low access tract when considering 1/2 mile distance |
| TractSNAP_percent | float |  [food_obesity.csv](./data/food_obesity.csv)| Percentage of housing units receiving SNAP benefits in tract |
| HCSOBP_2016-2018 | float |[food_obesity.csv](./data/food_obesity.csv) | Percentage of obesity in tract |
| HCSDIAP_2016-2018 | float |[food_diabetes.csv](./data/food_diabetes.csv)  | Percentage of diabetes in tract

___
### III. Modeling


___
### IV. Summary


