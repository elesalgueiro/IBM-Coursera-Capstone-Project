# IBM DS Specialization-CAPSTONE-PROJECT---The-Battle-of-Neighborghoods
## OPENING A VEGAN RESTAURANT IN TORONTO



## Project Description

Veganism has emerged as one of the top food and lifestyle trends in the past few years. Moreover, people, especially in cosmopolitan cities like Toronto, are more open to trying and exploring vegetarian or vegan restaurants.
The purpose of this project is to find the best location in Toronto to open a Vegan/Vegetarian Restaurant.

## Data

**Wikipedia**.Toronto boroughs, neighborhoods and postal coded. Data scraped using Beautiful Soup library.

**Foursquare API**.Location related data. Catefory venues in each neighborhood.

**Geospatial Data**.Geographical coordinatesof all neighborhoods and venues.
related data.

## Workflow
Fetch the information and process all the data into clean data frames.
With  Foursquare API I investigate the settings in Neighborhoods of Toronto and using Folium I created a map of Toronto with neighborhoods superimposed on top and color-coded each Neighborhood depending on what borough they are located in. 

Applying the **K-Means clustering algorithm**, we got different clusters of Neighborhoods in Toronto according to the average of Vegan/Vegetarian Restaurants. After having analyzed the clusters one by one we chose the cluster with fewer Vegan/Restaurants on average, therefore with fewer competitors. Moreover, having assumed that the type of clients in a yoga studio can most likely be a potential customer of a vegan restaurant, it should be noted that this cluster is also the one with the highest number of Yoga Studios. 

## Conclusion

Taking all that into account I selected the most 4 suitable neighborhoods within the cluster. I analyzed each one according to the most common venues in them to be able to give the best recommendation to our stakeholders.
The final decision on optimal Vegan/Vegetarian location would be given to the stakeholders but they would be also encouraged to take into consideration additional factors such as accessibility or locals rent opportunities.


