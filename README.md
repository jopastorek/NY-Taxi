# CAUTION - This project is currently under construction
# New York City Taxi Ride Prediction
![](https://www.tripsavvy.com/thmb/oJts9MQYdhrt93nNu_y83XKt1PQ=/5125x3417/filters:fill%28auto,1%29/traffic-in-times-square--new-york-city-77817998-5c2e88c146e0fb00013a2772.jpg)

The goal of this project is to complete a full data science lifecycle including the following topics:

## Business Understanding 
The number of taxi pickups varies heavily depending on area, day, hour, season, weather and many more factors. Having more detailed information on future pickup numbers helps organise taxi companies to distribute their taxis more efficiently. 
## Data Mining
The data used for this project is available at https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page for 2009 until 2019. In 2017 the data format changes such that there are no pickup and drop off coordinates available anymore. Instead, rides are assigned one of around 250 pickup and drop off zones in order to specify location of start and end of a ride. Hence, data from 2017 till 2019 will be used. The provided data included every ride. In a first step all rides are goind to be aggregated to time-series bins of one hour. This also reduces the size of the data quite significantly from its original 25 GB size, which makes it easier to work with.
## Data Cleaning
Only the following taxi rides are to be included in the final dataset: taxi trips of 100 miles max, at least one passenger, a trip duration of at least one minute and two hours max. 
## Data Exploration
## Feature Engineering
## Predictive Modeling
## Data Visualization


## Future Work
There is a lot left to be done, e.g.
- [ ] first
