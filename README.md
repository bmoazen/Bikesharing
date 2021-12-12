# Bikesharing
## Overview of the Analysis
In this analysis, we were tasked with using Tableau to look into investing in a bikesharing venture in the city of Des Moines, Iowa. To aid us in our decision-making, we pulled data from the New York [Citi Bike System Data](https://ride.citibikenyc.com/system-data) page, which contains donwloadable files of Citi Bike trip data. For this analysis, we looked at data taken in August of 2019. We used python to put the data into the desired data types and then utilized Tableau for the visualization.
<br />
## Resources
VS Code<br />
Python version 3.7.6<br />
Tableau version 3.7.6 ([Tableau Workbook Link](https://public.tableau.com/app/profile/brian.moazen/viz/citibikeData_201908/TripsbyAgeandGender))<br />

## Results of the Analysis
### Concerns Regarding Data
An obvious concern for this study are the differences between New York City (where the citibike analysis data is from) and Des Moines, Iowa.  Specifically, would it be reasonable to assume trends in NYC could indicate anything similar in Des Moines?  One piece of valuable data we could look at it citibike usage broken down by age and gender.  Shown below is a breakdown of the proportion of NYC citibike riders by ages and gender.  The peaks for both female and male occur in the 25-35 year age range.  The median ages of Des Moines residents is currently 34.2 years (male) and 33.4 years (female) ([Source: World Population Review](https://worldpopulationreview.com/us-cities/des-moines-ia-population)), which translates well, especially considering the NYC median ages are 38.1 and 35.4 for females and males, respectively.  This suggests that the similarity bewteen the Des Moines and New York City age demographics make  comparisons between them reasonable.  Note that genders that were listed as "unknown" or not entered were ignored in these calculations.<br />  
![](/Plots/Trips%20by%20Age%20and%20Gender.png)

### Trip Duration
The length of bike usage by gender is shown in the plot below <br /> 
![](/Plots/Trip%20Duration.png)
The majority of trips take roughly 5-10 minutes (regardless of gender) with very few taking more than 35 minutes.  This suggests that most rides are within a few blocks, probably used as transportation rather than for tourism or sight-seeing.  This is supported by the fact that roughly 80% of citibike users were regular subscribers, who would most likely live in the city rather than be visiting (see figure below).
![](/Plots/User%20Type.png). <br /> 
With the duration of trips rather short and the majority of users being residents, it would most likely be wise to focus on gathering subscribers rather than targeting tourists or visitors.


## Summary
