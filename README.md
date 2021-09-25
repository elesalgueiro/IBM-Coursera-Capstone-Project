# IBM Data Science Capstone Project 
## OPENING A VEGAN RESTAURANT IN TORONTO
![](https://github.com/elesalgueiro/IBM-COURSERA-CAPSTONE-PROJECT---The-Battle-of-Neighborghoods/blob/main/Vegan%20Image%20RM.jpg)

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

Taking all this into account, I selected the most 4 suitable neighborhoods within the cluster. I analyzed each one according to the most common venues in them to be able to give the best recommendation to our stakeholders.
The final decision on optimal Vegan/Vegetarian location would be given to the stakeholders but they would be also encouraged to take into consideration additional factors such as accessibility or locals rent opportunities.

## Links

This repository contains a complete [project report](https://github.com/elesalgueiro/IBM-COURSERA-CAPSTONE-PROJECT---The-Battle-of-Neighborghoods/blob/main/APPLIED%20DATA%20SCIENCE%20CAPSTONE%20%20-%20Final%20Report.pdf), a [pdf presentation]( https://github.com/elesalgueiro/IBM-COURSERA-CAPSTONE-PROJECT---The-Battle-of-Neighborghoods/blob/main/Applied%20Data%20Science%20Capstone%20PRESENTATION%20-IBM%20Coursera.pdf) and the [python codes]( https://github.com/elesalgueiro/IBM-COURSERA-CAPSTONE-PROJECT---The-Battle-of-Neighborghoods/blob/main/IBM%20DS%20CAPSTONE%20PROJECT%20-%20A%20New%20Vegan%20Restaurant%20in%20Toronto.ipynb). 
