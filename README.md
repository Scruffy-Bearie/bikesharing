# New York City CitiBike – The Where, When and Who of Bike Usage

## Overview
Tableau is a software package that allows users to access relational data bases and spreadsheets (amongst other data sources) and to, using drag and drop functionality, access multiple chart formats for producing data visualizations.  The client for this study, an entrepreneur introduced to bike sharing as a tourist in New York City, has an interest in starting a bike share business in Des Moines Iowa and has asked for analysis of Citi Bike data from New York to assist in presenting her business proposal to potential investors.  The purpose of this project was to use Tableau to prepare visualizations of the Citi Bike data for sake of assisting in said analysis. 

## Results

The first step of the analysis was to examine the most popular/frequently used starting locations for Citi Bike trips.  The latitude, longitude coordinates for all starting locations were plotted on a map of New York City with the size and colour of the respective markers adjusted so that the most popular/frequently used locations were given a larger marker with a dark green colour (see Figure 1).

### Figure 1: Top Trip Starting Locations for New York City CitiBike Program 
![]( https://github.com/Scruffy-Bearie/bikesharing/blob/main/IMAGES/Top%20Starting%20Locations.png)
Analysis of the results revealed that the highest density of bike share starting points was in Lower Manhattan.  

That said, it seemed reasonable to next determine at what time of day bike share trips were most likely to start. As such, a bar graph was produced that displayed the number of bike share trips started as a function of time of day (see Figure 2).

### Figure 2: Top Trip Starting Times for New York City CitiBike Program
![]( https://github.com/Scruffy-Bearie/bikesharing/blob/main/IMAGES/August%20Peak%20Hours.png)
Examination of the resultant visualization revealed that the most popular trip start times were from 7:00 a.m. to 9:00 a.m. and from 4:00 p.m. to 7:00 p.m.

Having determined where and when a bike trip was most likely to start, the next step was to determine when a bike trip was most likely to stop.  With this objective in mind, a heat map was produced that displayed stop times for bike trips on a colour scale such that the most likely/popular stop times were assigned a darker colour (see Figure 3).

### Figure 3: Top Trip Stop Times for New York City CitiBike Program Filtered by Weekday
![]( https://github.com/Scruffy-Bearie/bikesharing/blob/main/IMAGES/Trips%20by%20Weekday%20per%20Hour.png)

Examination of the heat map evidenced a high proportion of stop times within, or close to, the same intervals identified as popular start times.

With the analysis conducted to this point suggesting that most bike share trips were short trips in Lower Manhattan coinciding with “rush hour”, it seemed pertinent to examine “who” was using the bikes for these trips.  As such, the data used for the previous visualization was filtered by gender to produce a second heat map (see Figure 4).

### Figure 4: Top Trip Stop Times For New York City CitiBike Program Filtered by User Gender
![]( https://github.com/Scruffy-Bearie/bikesharing/blob/main/IMAGES/Trips%20by%20Gender%20(Weekday%20per%20Hour).png)
Examination of the resultant heat map demonstrated that the majority of bike trips were being taken by male users.  

Analysis conducted thus far was suggesting that most bike trips were being taken by male users for their commute to work but, further analysis was required to support this conclusion.  As such, two visualizations were produced: one displayed number of trips as a function of trip duration (See Figure 5) and the second displayed the same data filtered by gender (see Figure 6).

### Figure 5: Number of Bikes as a Function of Trip Duration
![]( https://github.com/Scruffy-Bearie/bikesharing/blob/main/IMAGES/Checkout%20Times%20for%20Users.png)
### Figure 6: Number of Bikes as a Function of Trip Duration Filtered by User Gender
![]( https://github.com/Scruffy-Bearie/bikesharing/blob/main/IMAGES/Checkout%20Times%20by%20Gender.png)
Analysis of the resultant plots provided further evidence in support of previously identified trends in that they demonstrated the majority of bike trips were being taken by male users and lasted for 20 minutes or less.

With the analysis to this point suggesting that most bike trips were being taken by male users in Lower Manhattan as a means of commuting to work, one additional piece of evidence was required to support the analysis.  With this objective in mind, a heat map was produced to examine trip starting times by weekday filtered by user type and gender with higher frequency results being assigned a darker colour (see Figure 7).

### Figure 7: Top Trip Starting Times For New York City CitiBike Program Filtered by User Gender, Customer Type and Weekday
![]( https://github.com/Scruffy-Bearie/bikesharing/blob/main/IMAGES/User%20Trips%20by%20Gender%20by%20Weekday.png)

The resultant visualization provided more evidence in support of identified trends, clearly indicating that most bike share trips were being taken by male subscribers on weekdays.

All images displayed as results, along with a “story” formatted presentation containing all images can be found at the following URL:
https://public.tableau.com/app/profile/sean.milligan4372/viz/UserTripsbyGender_16698458763820/NewYorkCityCitiBike-TheWhereWhenandWhoofBikeUsage

## Summary
The visualisations created and presented suggested that the majority of CitiBike bike trips taken in New York City in the month of August were taken by male subscribers on weekdays and lasted for 20 minutes or less.  Moreover, the visualisations suggested that the majority of bike trips started in lower Manhattan between 7:00 a.m. and 9:00 a.m. and 4:00 p.m. and 7:00 p.m.  As such, the results seemed to suggest that the majority of CitiBike bike trips were male subscribers using the bikes to commute to and from work.

Given the results and analysis presented, it is suggested that as much as the client enjoyed using CitiBike bikes as a tourist in New York, it is unlikely that tourist business alone would allow a business similar to CitiBike to flourish in Des Moines and that long term viability of such a business (and returns for investors) would depend on the following factors:

•	Population density in Des Moines

•	Proximity of residential neighborhoods/accommodations to places of work

All that said, the analysis and conclusions presented thus far would also benefit from/be supported by production and analysis of the following visualisations:

(i)	A heat map analysis of trip duration filtered by start time and day of week

(ii)	A graphical analysis of number of trips as a function of trip duration filtered by user type (subscriber and customer)
 

