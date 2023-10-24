# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
 - Analyze the factors impacting the number of available bikes within Quebec bike stations
 - Build a statistical model which explores correlation between the number of free bike at any given bike station and its average distance from local gyms/restaurants

## Process
 1. Gather information on Quebec bike stations through the usage of the Citybikes API
 2. Collect information on restaurants, bars and gyms within a 1km radius of any given bikestation utilizing Foursquare API
 3. Explore, transform and clean data generated from API
 4. Repeat step 2 and 3 utilizing Yelp API 
 5. Compare information received from both Foursquare and Yelp APIs
 6. Join information from all prior steps into one cohesive DataFrame
 7. Utilize EDA and data visualization methods to explore data
 8. Create a SQLite database to store information collected
 9. Build a regression models to analyze relationship between number of free bike at a given station and its average distance from a gym
 10. Interpret results and present findings 



## Results
- In regards to Quebec, Foursquare provided better insight on local gyms whereas Yelp provided better quality data on restaurants

-The model proved insufficient at exploring variations in the number of available bikes a given station at the 95% confidence interval -- sufficient at the 90% confidence interval

- Granted a 90% confidence level, the number of available bikes at any given station is negatively correlated with said stations distance from a gym
    - On average, for every 100m a bike station nears a gym the number of bikes available decreases by 4

- The R-squared value indicates the model accounts for approximately 4.6% of the variation in the number available bikes

## Challenges 
- Request Constraints on Yelp API 

- Yelp outage 

Lack of information from project radius constraints
## Future Goals
- Recreate model with loosened radius constraints

- Investigate correlation utilizing larger cities/datasets

- Explore additional factors impacting the number of gyms and bike stations within a given city

- Analyze the consumer basis of CityBikes users 

