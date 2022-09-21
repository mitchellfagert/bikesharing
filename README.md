# bikesharing Project

## Overview
The framework for this project was to analyze New York CitiBike data for a presentation to potential investors who would be interested in starting a similar bikesharing business in Des Moines, Iowa.

In a calculated effort to explore the viability of starting a similair bike sharing business, I created an analysis that answers a few key questions:

    - Who uses the CitiBike program?
    - What area of the city sees the most usage?
    - What time of day are the bikes used the most and the least?
    - How much are the bikes used and by whom?

## Results
A Tableau story has been created and can be seen [at this link.](https://public.tableau.com/app/profile/mitchell.fagert/viz/BootcampProject_16637118321880/NYCCitiBikeAnalysis?publish=yes)

Although Des Moines demographics differ from New York Citie's, analyzing Citibike's August 2019 data providded much needed insight.

![Customer_breakdown](https://user-images.githubusercontent.com/107579508/191620466-201429f8-ac1b-4e10-9cbb-4d19d6b70118.png)

 - There were approximately 2,344,224 total rides completed in August 2019.
 - **81%** of the users were *subscribers* while the remaining **19%** of users were *customers*
 - **65%** of the users were identified as *MALE*, **25%** were *FEMALE*, and the remaining **10%** of users are labeled *UNKNOWN*.

<img width="514" alt="Top_starting_locations" src="https://user-images.githubusercontent.com/107579508/191621607-a7421b8d-02a7-43c3-b96c-d7d630293317.png">

The above image displays the count of rideshares started in a given area. The size of the circles and darkness indicate the relative number of trips started in that area. Data suggests a large majortiy of all rideshares started in Manhattan. This makes sense given its population density, tourist/entertainment value, and concentration of commercial activity.

<img width="711" alt="Peak_hours" src="https://user-images.githubusercontent.com/107579508/191622094-22fc23ca-0e40-495c-a9d4-8c413ed560b8.png">

This chart displays the total riders per hour of the day. We can see peak usuage is during typical "commuting" times of **7am-8am** & **5pm-6pm**. This chart also identifies optimal times on when to perform routine maintenance on the bikes so that revenue opportunites are not missed.

<img width="485" alt="Checkout_Time_for_Users" src="https://user-images.githubusercontent.com/107579508/191622232-d9ce0f08-d971-408d-987c-3d758dd3beca.png">

This graph shows the number of rides by duration and it shows a majority of trips taken are under an hour in length.

<img width="502" alt="Trips_by_Weekday_per_Hour" src="https://user-images.githubusercontent.com/107579508/191622404-5fd1b9be-b1d1-4c8d-b5e9-ccc7624eb714.png">

Above is a heatmap that shows weekly usage patterns. It supports earlier data that suggests heavy bike usage during weekday commute times.

![Trips_by_Gender_wkperhour](https://user-images.githubusercontent.com/107579508/191622423-87515812-a926-4903-a3f0-b7b813d04996.png)

This heatmap is similar to the one above it however it provides an additional layer of analysis by showing the weekly usage patterns by gender.

![User_Trips_by_Gender_by_Weekday](https://user-images.githubusercontent.com/107579508/191622447-1c49d88e-4fbe-49bf-b088-07b482c8151d.png)

Lastly, this heatmap further reinforces the trend and higher demand of of **MALE** users.

## Summary
In conclusion, bikeshare services like CitiBike are very popular and meet a strong demand of convienent and cheap transportation in a large metropolitan area. The user base is made primarily of male subscribers. CitiBike has a large growth opportunity infront of them if they can grow their **FEMALE** user base.

Lastly, additional analysis could be beneficial by:
    - comparing data from different months such as May & July.
    - including weather data to find a correlation of ride demand based on weather performance.
