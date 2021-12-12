# Bikesharing
## Overview of the Analysis
In this analysis, we were tasked with using Tableau to look into investing in a bikesharing venture in the city of Des Moines, Iowa. To aid us in our decision-making, we pulled data from the New York [Citi Bike System Data](https://ride.citibikenyc.com/system-data) page, which contains donwloadable files of Citi Bike tip data. For this analysis, we looked at data taken in August of 2019. We used python to put the data into the desired data types and then utilized Tableau for the visualization.
<br />
## Resources
VS Code<br />
Python version 3.7.6<br />
Tableau version 3.7.6 ([Tableau Workbook Link](https://public.tableau.com/app/profile/brian.moazen/viz/citibikeData_201908/TripsbyAgeandGender))<br />

## Results
### Concerns Regarding Data
An obvious concern for this study are the differences between New York City (where the citibike analysis data is from) and Des Moines, Iowa.  Specifically, would it be reasonable to assume trends in NYC could indicate anything similar in Des Moines?  One piece of valuable data we could look at it citibike usage broken down by age and gender.  Shown below is a breakdown of the proportion of NYC citibike riders by ages and gender.  The peaks for both female and male occur in the 25-35 year age range.  The median ages of Des Moines residents is currently 34.2 years (male) and 33.4 years (female) ([Source: World Population Review](https://worldpopulationreview.com/us-cities/des-moines-ia-population)), which translates well, especially considering the NYC median ages are 38.1 and 35.4 for females and males, respectively.  This suggests that the similarity bewteen the Des Moines and New York City age demographics make  comparisons between them reasonable.  Note that genders that were listed as "unknown" or not entered were ignored in these calculations.<br />  
![](/Plots/Trips%20by%20Age%20and%20Gender.png)

### Citibike Usage Map
A map of Citibike trips is shown below.  The location with the most originated trips (red circle) corresponds to the station nearest to Grand Central Terminal.
![](/Plots/Trips%20Map.png)

### Trip Duration
The length of bike usage by gender is shown in the plot below: <br /> 
![](/Plots/Trip%20Duration.png)
The majority of trips take roughly 5-10 minutes (regardless of gender) with very few taking more than 35 minutes.  This suggests that most rides are within a few blocks, probably used as transportation rather than for tourism or sight-seeing.  This is supported by the fact that roughly 80% of citibike users were regular subscribers, who would most likely live in the city rather than be visiting (see figure below).
![](/Plots/User%20Type.png) <br /> 
Looking at trip duration by user type (subscriber or customer) shows that while the peak for the subscribers is in the 5-10 minute range (expected since they are the overwhelming majority), the distribution for customers is relatively flat between 5 and 30 minutes. This supports the conclusion that subscribers tend to have shorter trip times than customers.
![](/Plots/Trip%20Duration%20by%20Type.png)<br /> 
<br />

### Trip Ending Times
Just as the trip duration analysis indicated, looking at trip ending times by weekday also suggests a focus on subscribers would be ideal.  Below is a plot of frequency of bike rides by time and weekday.  Peaks are located at the beginning and end of workdays, as well as Saturday afternoon.
![](/Plots/Trips%20by%20Weekday.png). <br /> 

## Summary of Data
A brief summary of the NYC Citibike data is given below:
- the largest number of trips originated from the station nearest to Grand Central Station
- Most trips range have a duration of roughly 5-10 minutes
- Subscribers make about 80% of trips
- Peak times include the morning and evening "rush hours" and Saturday afternoons
<br />

## Recommendations for Implementation
The analysis indicates that the best approach to implementing a succesful bikesharing program would be to focus on gaining subscribers rather than focusing on tourists, especially given the relatively few number of tourists in Des Moines, Iowa compared to that of New York City. Reasons supporting this conclusion imclude:
- the peak in trip data originating at Grand Central Station (commuters)
- the peak in trip duration (for both genders) of 5-10 minutes
- the peaks in trip times at the beginning and end of each weekday
Furthermore, placing stations so that commuters would have an easier time utilizing the bikes would be good.  Some examples would be near parking garages, train and bus stops, and near places with many employees.<br />

## Recommendations for Further Study
A next step in this study should include data on Des Moines, Iowa.  A map of the city's parking garages and bus and train stops would be invaluable in helping to determine optimum bike station locations.  Surveys of downtown employees on their thoughts about a bikesharing program should be performed, as well as studies on the commutes of residents (are they parking in a garage right next to their places of business or is there a walk?).


