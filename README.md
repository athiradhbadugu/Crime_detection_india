# crime-dashboard-for-India
## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Features](#features)
* [Features to be added](#features-to-be-added)
* [Setup](#setup)


## General info
This website is a dashboard for crimes in India displaying and predicting different crimes in different states and districts.

## Technologies:
1. python3.8
2. matplotlib-3.4.2
3. Flask-2.0.1
4. Flask_SQLAlchemy-2.5.1
5. geopandas-0.9.0
6. pandas-1.3.0
7. numpy-1.21.1
8. scikit_learn-0.24.2

## Features:
1. Heatmaps for country and states. (country map for 21 crimes and state maps for 28 states for 4 dfferent crime)
2. Plots for multiple selected crimes in districts. (718 districts and 21 crimes)
3. Interactive plot for crime against children vs literacy rate in country.
4. Prediction of 7 different crimes against women and 10 different crimes against children in 28 states and 9 union territories.

## Features to be added:
1. Accessing data from database instead of reading csv files.
2. Update and delete for records in database.

## Setup
To run this project, install libraries given above:

```
$ cd crime-dashboard-for-India/
$ flask run
```