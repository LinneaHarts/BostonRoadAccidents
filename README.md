# BostonRoadAccidents

Many drivers hate sharing the road with bicyclists, but perhaps they could become allies, if road improvements for bikes made the road safer for cars as well and vice versa.

This exploration looks for commonalities between what causes bike and car accidents in the Boston Area. I found models to predict bike and car accidents, and identified the key features for predicting them, and bike accidents are a predictor of car accidents and vice versa, among many other road attributes.

## Data Sources
The data sets for this project come from:
- A database of Boston bike accidents from 2009 to 2012, constructed from police reports during this time: https://dataverse.harvard.edu/dataverse/BARI 
- Accident/crash data: US accident data 2017 https://www.kaggle.com/sobhanmoosavi/us-accidents
- The Massachusetts Department of Transportation (Mass DOT) road inventory https://geo-massdot.opendata.arcgis.com/datasets/road-inventory-2018
- The Mass DOT road inventory has a data dictionary: https://github.com/LinneaHarts/BostonRoadAccidents/blob/master/RI-DataDictionary.pdf

## Data Wrangling
- Create clusters of accidents within 50m of one another using shapely and geopandas packages
- Associate road data with those clusters
- Create areas without accidents and associate road data with those

This image shows all the accident clusters I identified


To Get Started:
* Overview presentation: https://github.com/LinneaHarts/BostonRoadAccidents/blob/master/reports/Bike%20and%20Car%20Accident%20Prediction.pdf
* Milestone report: https://github.com/LinneaHarts/BostonRoadAccidents/blob/master/reports/Bike%20and%20Car%20Accident%20Prediction%20Milestone%20Report.pdf
* Machine learning report: https://github.com/LinneaHarts/BostonRoadAccidents/blob/master/reports/Bike%20and%20Car%20Accident%20Machine%20Learning%20Report.pdf
* Final Report: https://github.com/LinneaHarts/BostonRoadAccidents/blob/master/reports/Bike%20and%20Car%20Accident%20Final%20Report.pdf


