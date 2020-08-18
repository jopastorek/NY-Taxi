# CAUTION - This project is currently under construction
# New York City Taxi Ride Prediction
![](https://www.tripsavvy.com/thmb/oJts9MQYdhrt93nNu_y83XKt1PQ=/5125x3417/filters:fill%28auto,1%29/traffic-in-times-square--new-york-city-77817998-5c2e88c146e0fb00013a2772.jpg)

## Business Understanding 
The yellow cabs are the embodiment of New York City as we see it every day. More than 100,000 taxi rides take place in the most populated area of the US every single day. Being able to make predictions about the number of rides at different times and places helps taxi companies to distribute their taxis more efficiently to where they are needed the most. The number of rides mostly depends on location: the data not only provides the pickup borough (Manhattan, Queens, Brooklyn, Bronx, Staten Island), but also a so called zone, which divides NYC into 265 spatial areas. Next, calendar features have a strong effect on the number of rides: time, day of the week, month, year, public holiday. Using external data, the impact of weather features on the number of rides, as well as big events happening in NYC will be examined. 

## Data Mining
The data used for this project is available at https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page for 2009 until 2019. In 2017 the data format changes such that there are no pickup and drop off coordinates available anymore. Instead, rides are assigned one of around 250 pickup and drop off zones in order to specify location of start and end of a ride. Hence, data from 2017 until 2019 will be used. The provided data includes every ride. In a first step all rides in one zone are aggregated to bins of one hour. This also reduces the size of the data quite significantly from its original 25 GB size, which makes it easier to work with.
The external weather data is UTC formatted and hence needs to be transformed to NYC time in order for them to be merged correctly.

## Data Cleaning
Only the following taxi rides are included in the final dataset: taxi trips of 100 miles max, at least one passenger, a trip duration of at least one minute and two hours max. 

## Data Exploration
The data has strong seasonal effects with a downward trend. First, rides are trending on an hourly level: less rides at night and early, more rides in the afternoon and evening. The busiest hour is on average 8 p.m. 3 a.m. is the most inactive time. Next, there is seasonality on a weekly level: Tuesday to Thursday are on average the busiest days, with Monday and Friday slightly behind. Weekends are significantly less busy (caution: this heavily depends on the zone). Third, seasonality on a monthly level: the are less rides taking place in Summer than in Winter which is most likely due to weather conditions. From 2017 until 2019 the number of taxi rides in NCY is affected by a strong downward trend. This is most likely due to the increase in popularity of ride sharing companies like Uber or Lyft. As stated previously, the number of rides is mainly dependent on the location. Manhattan alone makes up around 90 % of all rides, followed by the airports JFK and LaGuardia. Zones in Queens and Brooklyn close to Manhattan spike at some hours of the day but stay insignificant compared to Manhattan traffic. Bronx and Staten Island make only around 1% of all rides in NYC.
## Feature Engineering
## Predictive Modeling
## Data Visualization


## Future Work
There is a lot left to be done, e.g.
- [ ] first
