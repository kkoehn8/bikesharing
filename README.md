# bikesharing

## Overview of the Analysis
The purpose of this analysis is to determine if it's feasible to start a bike-share program in the City of Des Moines, Iowa. We have obtained bike-share data from New York City and are performing analysis on the data to extract key metrics. Using this we will meet with Angel Investors to see if they will invest in our bike-shre program.

## Methodology
To perform the analysis we were provided with some initial data:
 - Bike Share Trip data from New York City for August 2019
 - Starter Code to perform Pandas data transformation

The software used for the analysis is:
 - Python/Pandas to prepare the data
 - Tableau Public to create the data visualizations

## Results
Following the completion of the preparation of the data using Pandas a new data file in .csv format was created. A series of Tableau Public worksheets were created to visualize different questions we asked of the data. These worksheets were combined into a Tableau Public Story. The Tableau Public story can be found following the link below: 

[Link to Tableau Public Visualization](https://public.tableau.com/views/Module14Challenge_16635200420150/CitibikeAnalysis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

The visualizations that were created for the analysis are detailed below.

### Number of Trips by Gender and Usertype
![01_TripsGenderUsertype](https://github.com/kkoehn8/bikesharing/blob/main/Images/01_NumberOfTripsByGenderAndUsertype.png)

The number of trips by Gender and Usertyps is a good visualation to start with. This will provide our investor with general information about the anticipated useage of our bike-share program. While we know that Des Moines does not have the populatation, or tourists, that are found in New York City we can get an idea of the total breakdown of trips. The image above shows us that the total number of trips by males is quite high, with the trips by male subscribers being a much higher percentage than by women subscribers. 

### Start Location
![02_StartLocation](https://github.com/kkoehn8/bikesharing/blob/main/Images/02_StartLocationOfTrips.png)

The start location visualization shows us the geographic distribution of where the trips start. We can see that a greater amount of trips start in the Manhattan area. This could also be influced in a higher number of tourists in that part of New York City. This will be useful as we analyze Des Moines and may lead us to determine if we anticipate certain areas where more rides would start.  

### Checkout Time of Users
![03_CheckoutTimeUsers](https://github.com/kkoehn8/bikesharing/blob/main/Images/03_CheckoutTimeOfUsers.png)

This visualization shows us the amount of time a bike is checked out for all users. From this we can see that the majority of trips are relatively short in duration with the peak being a 5 minute duration and very few lasting more than 50 minutes.

### Checkout Times by Gender
![04_CheckoutTimeGender](https://github.com/kkoehn8/bikesharing/blob/main/Images/04_CheckoutTimeByGender.png)

This visualization takes our analysis above a step further to help us determine if there is a difference in trip duration between men and women. The visualization shows us that the average trip duration for men and women are virutally identical. 

### Trips by Weekday by Gender
![05_TripsWeekdayGender](https://github.com/kkoehn8/bikesharing/blob/main/Images/05_TripsByWeekdayByGender.png)

When we analyzed the trips by Gender by Weekday we can see that there is not too much variation for the Customer usertype which may be because Customers are more likely to be tourists. However the visualization does show for the subscribers showes that while the number of trips on the weekend are higher, the highest number of trips for both males and females is on Thursday. 

### Trips by Weekday by Hour
![06_TripsWeekdayHour](https://github.com/kkoehn8/bikesharing/blob/main/Images/06_TripsByWeekdayByHour.png)

The analysis of Trips by Weekday by Hour shows us that more trips occur around 8am and 5pm to 6pm on the weekdays. Since this correlates with many employees work start and end times we could assume they are using the bike-share to commute to work. This may be a visualization that is not as applicable to Des Moines. In New York City may individuals work and live in the city so bike-shares are a useful method of transportation, if Des Moines also has a high proportion of employees working and living in the city this would be a useful comparison, however if more employees live outside the city this may not be as useful as other types of analysis. 

### Trips by Weekday and Hour by Gender
![07_TripsWeekdayHourGender](https://github.com/kkoehn8/bikesharing/blob/main/Images/07_TripsByWeekdayByGenderAndHour.png)

This visualization is an extension of the previous visualization to help us determine if there are hourly differences between males and females. The patterns that we see between males and females are similar implying that both males and females may be using bike-shares for commuting to their place of employment. 

## Summary

This analysis of the bike-share data from New York City has provided some useful insights. By reviewing the trip duration and hours of usage it appears that many of the trips are short - the peak is between 5 and 6 minutes and many of the trips are occurring during traditional rush hour traffic times. The timing and duration would suggest that many of the trips may be by employees as a method of commuting to their place of employment. 

Two additional visualizations that may be useful for our Angel Investor are:
 - Trip duration during weekday vs weekend. If our weekday riders are using bike-shares for commuting short distances, are weekend riders using them for longer trips?
  - Trip duration by age. Are the trips longer for younger users who may not being using bike-shares for commuting to work? 


