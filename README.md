# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
We have big network of city bike. City bike is spread across the globe. It has multiple bike stations in the city. We need to use various APIs to analyse the station for a city and based on that we need to identify the restaurants based on the ratings.

Additionly We need to identify if there is any relation between restaurants and distance from bike staion.

## Process
#### 1.Explore the data with City_bike API based on the city
#### 2.Find out the list of stations,bikes, location 
#### 3.Explore Foursquare API and find out the Restaurant near by the bike station.
#### 4.Explore Yelp API and find out the Restaurant near by the bike station.
#### 5. Create the combine data frame from both API.
#### 6.Mearge the data with list of stations,total bikes
#### 7.Perform the Model building

## Results
1. For bike station Toronto bike -station is selected.
2. It has total 12429 bikes in Toronto
3. By Exploring Foursquare API,total 6530 restaurants are there
4. There are 653 rows after merging the data with bike-station data
5. For total bike - mean =19.033691, std =6.323010 
6. P vaule for (total-bike vs distance) is 0.43 > 0.05 so it fails to reject H0
7. P vaule for (total-bike vs rating ) is 0.736 > 0.05 so it fails to reject H0

## Challenges 
 1. To get data from Yelp API to CSV file.
 2. To iterate for loop for both the API
 3. Model building and converting it tnto a classification.

## Future Goals
Find out easy way to use looping for iteration.Do some more research about models and how to perform Regression into classification. 
