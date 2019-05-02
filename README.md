# Capstone_project

## Background:

Back in early 2012, The Los Angeles Fire Department admitted to the [Los Angeles Times](https://latimesblogs.latimes.com/lanow/2012/03/la-fire-department-admits-exaggerating-response-times.html) that they exaggerated the data to make it appear that firefighters were responding to emergencies quicker than they actually were. The false data reported that in 2008 the department responded to emergencies within five minutes about 86 percent of the time. It turns out the LAFD categorized 6 minute responses the same as 5 minute responses. Apparently the corrected data shows that the department actually met the five-minute benchmark only 64 percent of the time in 2008. In the LA Times report mentioned above, it mentions the "Federal guidelines call for first responders to arrive on scene in under five minutes 90% of the time."

According to the city wide response metrics from January to March of 2019, found on the [LAFD's website](https://www.lafd.org/fsla/stations-map), the average EMS (emergency medical service) response time is 6 minutes 36 seconds. 


## Problem Statement:

We will use two datas from the Los Angeles City [website](https://data.lacity.org/A-Safe-City/All-Stations-Response-Metrics/kszm-sdw4), LAFD's response metric and Census Data of Los Angeles neighborhoods, in order to explore the emergency metrics and census data for each of the LA neighborhoods. The main objectives for this project are listed as follows:

**1) We want to analyze if certain locations (districts/neighborhoods) within the Los Angeles City has any affect on the time it takes for the LAFD respondents to arrive at the scene. In this project we strive to investigate whether certain factors such as, the poverty rate, average income, or a majority ethnic group of a location in LA has any correlation to the average response time from the LAFD.**

**2) We will build a regression model to predict the response time of the LAFD when it comes to EMS reports for a particular location in the City of Los Angeles. Model performance will be guided by RMSE, and the model should improve the baseline by as much as it can.** 
 
 
 
### Dataset:

[Source](https://data.lacity.org/A-Safe-City/LAFD-Response-Metrics-Raw-Data/n44u-wxe4)
* LAFD Response Metrics - Raw Data
    - Data last updated in April 8, 2019

[Source](https://data.lacity.org/A-Safe-City/All-Stations-Response-Metrics/kszm-sdw4)
* Archived response Time metrics for all LAFD stations
    - Contains all stations response metrics from 2011 to 2017
    
[Source](
  
[Source](https://data.lacity.org/A-Livable-and-Sustainable-City/Census-Data-by-Neighborhood-Council/nwj3-ufba)
* Census 2010 population/demographic data approximated from block groups to LA Neighborhood Councils
    - Data last updated in April 2018