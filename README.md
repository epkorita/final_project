# Final Project: GitCrash

## [NYPD Collision Data](https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions/h9gi-nx95)

### Purpose:

#### Understand the role of location, cause, time of day, and day of week as contributing factors to accidents resulting in injury/death of motorist(s).

### Questions to consider:

* Do specific contributing factor categories rise/fall based on time of day?
* What is the rate and projection of collisions based on vehicle type (Car vs Truck)?
* What is the frequency of injury/death for common contributing factors?
* What is the distribution of different accident types among the boroughs?
* Which machine learning model best predicts probability of accidents?

### Predictions:

* Alcohol and Drug related accidents are more likely to occur during late night/early morning hours (10PM-3AM)
* Most accidents occur during rush hour traffic (7-9AM & 4-6PM)


### Process:

Clean dataset to remove unnecessary columns and limit variability to accidents with two vehicles or less (Drop vehicles 3 and beyond, redundant location data, and unique key). Load csv into Python and begin grouping/breaking down data to categorize injury vs non, vehicle category (car/truck) and contributing factors. Use date/time to interpret time of day variable.

Create rate based visualizations by plotting data using Tableau. Add map visualization to illustrate rates between boroughs and distribution based on time of day. 

## **[Tableau Visualizations](https://public.tableau.com/profile/ellen.guerrero#!/vizhome/NYCTrafficData/Story1?publish=yes)**

Build machine learning models to determine if we can use them to determine likelihood of injury/death based on controllable factors, temperal factors, and vehicular factors.

### Machine Learning Models Attempted:

* Logistic Regression
* SVM

### Screenshots:

![](https://github.com/epkorita/final_project/blob/master/Screen%20Shot%20Features.png?raw=true)

![](https://github.com/epkorita/final_project/blob/master/Screen%20Shot%20SVM%20Results.png?raw=true)

### Assumptions made/Challenges encountered:

* Police entered data differently causing extra clean up for minor differences such as capitalization or phrasing. (ex: illness and Illness, SUV and Sport Utility Vehicle, etc)
* Assumed the first contributing factor was associated with the first vehicle and main cause (at fault). In some cases there were multiple vehicles with differing factors. 


### Questions to continue to explore:

* Do vehicle types have impact or correlaton with specific contributing factors?
* See how public transportation factors into accident data? For example, is there a higher probability of an accident with public transportation?
* Do places of interest have correlations with type of contributing factors? For example, does an area with several bars nearby have higher rates of alcohol related accidents?
* Can we compare accidents in specific locations to the traffic patterns present?
* Is the rate of death vs injury impacted when hospitals are within a specific radius?
* How does size of vehicles involved in the collision impact the rate of fatality vs injury?



# Any Questions?
![](https://upload.wikimedia.org/wikipedia/en/b/b5/David_S._Pumpkins_dance.jpg)
