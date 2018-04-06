## Problem / Question
Urban heat island is leading to the prevalence of extreme heat events in cities.
This can result in negative effects on citizens' health, such as heat stroke.
Some neighborhoods can be more vulnerable toward extreme heat events than others.
And the municipal government can act to direct resources to those vulnerable
neighborhoods for aids.

I would like to develop a heat vulnerability index for each census tract in Philadelphia, using Principal Component Analysis (PCA). And the analysis outcome will be shown on the webpage. Also, routes for getting to the nearest existing facilities in case of extreme heat events (such as, cooling center, library, outdoor pools, and parks) will be provided.


## The data
I will use the temperature data, census data, and environment conditions data for the PCA to build the index. And the existing facilities can be easily got from open data Philly.


## Technologies used
a. Filter and plot data
b. Showing information with events
c. Route finding applying Mapbox
d. Showing information by map color


## Design spec

#### User experience
I expect Philadelphia residents to use the application.
They can have an idea of the risks of being impacted by extreme heat events of a specific census tract, the environment conditions, as well as how to get to the nearest facilities in case of extreme hear events. The user can type in an address, or a census tract number to search information.
I think this might be similar to the trulia real estate website.


#### Layouts and visual design
I would add a search box on the top.
And information can be shown at the bottom of the page.
In the middle, the map is placed for showing the routes, mapping the colors, as well as providing information on events.
On the left side, user can choose to show environment information, risk information, or route to a facility.



## Anticipated difficulties
I think how to direct an address to the census tract it is located in can be difficult, especially when an address may result in different locations in Mapbox.


## Missing pieces
How to search for the nearest facility can be troublesome for me.
