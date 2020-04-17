# Prediction-of-Traffic-Crash-Chicago




# Summary

traffic crashes are responsibles for more than 1 milion deaths every year worldwide and many more left injured. For that matter, Machine learning can help to analyze  the risks and reduce them. 
This project is based on the Chicago databases, divided by crashes, people and vehicles. From there, we will analyse and predict the primary cause of the traffic accident based on several features. We are aware that our target variable represents a multiclass classification problem for this reason we will use in our models classifiers such as Decisions Trees , Random Forest and Bagging classifiers.



# Data Source

Traffic crash data can be obtained at [Chicago Data Portal](https://data.cityofchicago.org/), exporting directly from the website. The links and descriptions of datasets are listed below:

--[Traffic Crashes - Crashes](https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if) - Crashes: Major dataset for this project.

--[Traffic Crashes - Vehicles](https://data.cityofchicago.org/Transportation/Traffic-Crashes-Vehicles/68nd-jvt3) - Vehicles: Information of related vehicles.

--[Traffic Crashes - People](https://data.cityofchicago.org/Transportation/Traffic-Crashes-People/u6pd-qa9d) - People:Information of related people.




# Language and Packages Used

--import pandas as pd
--import numpy as np
--import matplotlib.pyplot as plt
--%matplotlib inline
--from sklearn.model_selection import train_test_split
--from sklearn.preprocessing import StandardScaler 
--from sklearn.metrics import precision_score, recall_score, accuracy_score, f1_score, roc_auc_score
--from sklearn.ensemble import RandomForestClassifier
--from sklearn.datasets import make_classification



# Installing Sodapy, Shapely and Geopandas

For this project, sodapy, shapely and geopandas were used to plot all the police report ids in the Chicago area.
The links and descriptions of all libraries are listed below:

--[sodapy](https://pypi.org/project/sodapy/) - This library supports writing directly to datasets with the Socrata Open Data API.

--[shapely](https://pypi.org/project/Shapely/) - For manipulation and analysis of planar geometric objects.

--[geopandas](https://geopandas.org/) - GeoPandas is an open source project to make working with geospatial data in python.

