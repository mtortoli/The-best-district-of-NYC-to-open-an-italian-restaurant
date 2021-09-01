# Battle of Neighborhoods in New York City

## Warning
Github does not allow to display the map of New York. To visualize it correctly, please click on the following link:
https://nbviewer.jupyter.org/github/mtortoli/Battle-of-Neighborhoods-in-New-York-City/blob/master/battle_of_neighborhoods_nyc.ipynb.

## Introduction
New York is a famous city, which attracts many tourists and workers from all over the world.

Opening a business activity in this city can be very profitable but also very risky, as it is necessary to know well the neighborhoods and the commercial businesses. Not all neighborhoods in New York City are the same, and for each of them there can be advantages and disadvantages, for example, a less famous neighborhood can attract less tourists and workers, but there should be less competition from competing businesses.

## Business Problem
In this project the main goal is to find the best neighborhood/area to open an italian restaurant or pizzeria. Specifically, this report will be targeted to stakeholders interested in opening an **Italian restaurant/pizzeria** in **New York**, USA.

It's important to understand which is the right neighborhood to open this kind of activity, because in NYC there are already many italian restaurant/pizzeria activities, and therefore opening it in the right neighborhood can make the difference.

We will try to detect **locations that are not already crowded with restaurants**, especially we are particularly interested in **areas with no Italian restaurants/pizzeria in vicinity**. We would also prefer locations **as close to the biggest borough as possible**, assuming that first two conditions are met.

## Data
Based on the business problem defined above, fist of all we must find the biggest borough in New York, or the most densely populated borough. After that, the factors on which we will base our choice are the following:
* number of restaurants in each neighborhood
* number of Italian restaurants or pizzeria in the neighborhood, if any
* Population density in each neighborhood
* Latitude and longitude of each neighborhood

Following data sources will be needed to extract/generate the required information:
* New York City boroughs are taken from wikipedia page [NYC Boroughs](https://en.wikipedia.org/wiki/New_York_City#Boroughs). We will use this table to determine which is the "target borough".
* Neighborhoods, latitudes and longitudes are taken here: [NYC neighborhoods, latitudes and longitudes](https://geo.nyu.edu/catalog/nyu_2451_34572)
* Neighborhoods population density are taken here: [NYC Population Density](https://data.cityofnewyork.us/City-Government/New-York-City-Population-By-Neighborhood-Tabulatio/swpk-hqdp)
* Foursquare API for find restaurants in each neighbohood, especially italian restaurant and pizzeria.

