# new_citibike_challenge

## Citi Bike Trip Analysis

Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena. 

1. Design 2-5 visualizations for each discovered phenomenon (4-10 total). You may work with a timespan of your choosing. Optionally, you can also merge multiple datasets
from different periods. 
2. Use your visualizations (not necessarily all of them) to design a dashboard for each phenomenon. The dashboards should be accompanied by an analysis explaining why the 
phenomenon may be occuring. 
3. Create one of the following visualizations for city officials:
   * Basic: A static map that plots all the bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top. 
   * Advanced: A dynamic map that shoes how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map. 
   * The map you choose shouls also be accompanied by a write-up describing any trends that were noticed during your analysis.
   
4. Create your final presentation:
   * Create a Tableau story that brings together the visualizations, requested maps and dashboards. 
   * Ensure your presentation is professional, logical and visually appealing. 
   
   
## Overview

New York City Citibike data from August 2019 was analyzed to show trends for times of day, days of the week, gender, starting locations and ending locations. Pandas was used to change the 'tripduration' column from an integer to a datetime datatype.
Using the converted datatype, visualizations were created to show the length of time the bikes were checked out for all riders and genders, as well as age. Visualizations were also created to show peak hours for August 2019 and the top and bottom starting and ending locations for riders. 

## Link to Tableau Dashboard

[NYC Citibike August Analysis]()

# Results

## August 2019 trends Dashboard

![image](https://user-images.githubusercontent.com/115905663/236079739-875edc85-740e-4a28-98f6-8ff4af3e70d0.png)

After graphing the total number of rides for August 2019 by the hour of start time, the peak hours were consistently between 8AM-10AM and 5PM-7PM. This is likely due to the need for transportation during work commutes. 

![image](https://user-images.githubusercontent.com/115905663/236078125-dce48208-4074-4e05-a6d9-a2f3bb7507a2.png)

The hours of 5PM and 6PM on Thursdays saw the highest usage of Citibike for August 2019. 

![image](https://user-images.githubusercontent.com/115905663/236079666-ca3f2a07-1aa6-4e52-9ca5-eebec9684f7f.png)

The top 3 starting and ending bike stations were Pershing Square North, E 17th St & Broadway, and West St and Chambers St., respectively, which are all high tourist areas and close to subway stations. Besides being popular sight-seeing/activity areas, being near other public transit options could have influenced riders' decision to use Citibike. 

![image](https://user-images.githubusercontent.com/115905663/236078247-ab930c3f-f382-42bf-b0a8-9cb0ce3e43db.png)

Less riders started and ended rides in residential areas (east of the river) during August 2019. This could be due to the distance from the main city center and other modes of transportation being faster/easier than Citibike. It should also be noted that there were ~10 ending stations located in New Jersey that all had rider counts of 1. These were filtered out of the Bottom 10 End Stations visual. 

![image](https://user-images.githubusercontent.com/115905663/236078422-62954fd0-2bf6-46cd-b8ee-1d7904736fc6.png)

When analyzing checkout time for users, the tripduration for NYC Citibike users peaked at 5 minutes. Most NYC Citibike trips were under 1 hour in length. While there were trips that lasted more than 1 hour, these times could be the result of user error when returning the bicycle or possible thefts. 

![image](https://user-images.githubusercontent.com/115905663/236079123-e8ef4f13-2cfa-4e6c-9026-30980f6ba932.png)

## Trends based on Gender Dashboard

![image](https://user-images.githubusercontent.com/115905663/236079240-2a8f0c02-e599-4357-a810-19e7c8fb82e5.png)

Males made up more than half of all daily riders each day in August 2019. Daily usage for females remained steady at about 24% of daily riders throughout the month. 

![image](https://user-images.githubusercontent.com/115905663/236079313-202cc229-78f0-486d-bdc4-6b993ff976b0.png)

Male riders between the ages of 30-39 make up the largest group of riders. The 20-29 age bracket make up the most number of female riders. There were likely errors in birth year input that were filtered out of this visual (born before 1940). While there could be individuals aged 80+ that may participate in Citibike usage, it is unlikely that these were valid birth years and most likely false data. 

![image](https://user-images.githubusercontent.com/115905663/236079365-a0193118-de9a-40e4-9b6e-bad980b47d61.png)

The trip length based on gender again shows that males and females both check out Citibikes for about 5-6 minutes, but many more males use Citibikes than females. 

![image](https://user-images.githubusercontent.com/115905663/236079427-265d3603-7073-4e47-a809-452891caab2b.png)

Overall, more males are riding Citibikes. 6PM is the most popular checkout time, with Thursdays seeing the most male riders. 

![image](https://user-images.githubusercontent.com/115905663/236079560-40f569da-e957-444e-bd38-4f6e2075d82c.png)

