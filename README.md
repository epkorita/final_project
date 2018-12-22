# Final Project: GitCrash

## NYPD Collision Data
#### Source: https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions/h9gi-nx95

### Purpose:
#### Understand if vehicle types and specific traffic violations or instances contribute more heavily to injury in a collision.

### Questions to consider:
#### What factors create injury to a motorist in a collision?
#### What is the impact of time of day?
#### What is the rate and projection of collisions based on vehicle type (Car vs Truck)?


### Predictions:
#### * Smaller vehicles(cars) involved in collisions with larger vehicles(trucks/suvs) have higher fatality and injury rates.
#### * Smaller vehicles have higher injury rates.

### Machine Learning Models Attempted:
#### * Linear Regression
#### * Logistic Regression
#### * K Mean
#### * SVM

### Process:
#### Clean dataset to remove unnecessary columns and limit variability to accidents with one vehicle or less (Drop vehicles 3 and beyond, redundant location data, and unique key). Load csv into Python and begin grouping/breaking down data to categorize injury vs non, vehicle category (car/truck) and contributing factors. Use date/time to interpret time of day variable.

#### Create rate based visualizations by plotting data using matplotlib and Tableau. Add map visualization to illustrate rates between boroughs. 

#### Build a machine learning model to start with likelihood of injury vs non. Add contributing factors to provide more accurate results. 