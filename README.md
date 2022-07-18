# PyBer_Analysis
## Purpose
The purpose of the project was to analyze data from a very large CSV file for a ridesharing App company called PyBer.  In this analysis we write python scripts using **Pandas library**, a **jupeter notebook** and **matplotlib** to create a variety of charts to show case the relationship between type of the city, number of drivers and rides and alsp percentage of total fares, riders and drivers by type of city. This analysis and visualization is going to help the ridesharing company Pyber to increase access and affortability for under serve neighbourhood.
## Overview of the Analysis
In this analysis total weekly fares for each city type is calculated. Datasets containing ride and city were used to calculate data such as total rides, total drivers, total fares, average fare per ride and driver for each of the city types.The Data sets were also used to create a new data frame to find the average fare per week from January 1st 2019 to April 29th 2019 for each of the city types. The dataframe from the analysis was used to create a multiple-line graph that visualized the total weekly fares for each city type for the above period. The data and visualization created was then analyzed to provide recommendations to the CEO of Pyber to address any disparities among the city types.
### Resources 
* CSV Files: `city_data.csv`, `ride_data.csv` in Resources file
* Jupyter Notebook Files:: `PyBer.ipynb`, `PyBer_Challenge.ipynb`
* Python: `Python v3.7.6`, Dependencies: `Pandas Library` and `Matplotlib Library`
## Results
### Summary of DataFrame
The following dataframe was created to observe and analyze data in each city types
<img width="620" alt="Screen Shot 2022-07-16 at 7 00 57 PM" src="https://user-images.githubusercontent.com/107584361/179380864-3bb19b9f-2fad-4d1f-8e99-8c5557ceff0b.png">

The above dataframe shows that 
* The Urban cities has the highest number of rides and drivers than the other two type of cities and the Rural cities have the least, As a result the city type Urban brings the most revenue as we can see in the Total Fares column and Rural cities bring the least amount of revenue. 
* The Average Fare per Ride for the Rural city types have the highest average fare per ride, meaning there is a chance of more revenue in this city type for every ride increase compared to Urban city types which has the lowest average fare per ride. 
* Also Urban city has more drivers than the rides meaning few drivers are not having any rides and rural city has less drivers than the rides this shows there is a demand for drivers.
### Total fare by city type
A multiple line chart was created to help us visualize and perform analysis of the Total Fares from January 1 2019 to April 29th 2019 for each of the city types.
<img width="1005" alt="Screen Shot 2022-07-16 at 7 13 08 PM" src="https://user-images.githubusercontent.com/107584361/179381124-365cd5c6-457c-41f2-8d14-c2b6e1eed9b4.png">

* During this time period the total fare for each of the ciy types we can observe that Urban city type had the highest total fares for all the weeks and rural areas had the least. 
* We can also observe that the 3rd week of February has the highest total fares for each of the city type showing increased demand at that time. 
* Urban cities aslo seem to bring a lot of revenue in the first and third week of March. 
* Towards the start of January 2019 and towards the end of April all Fares for each city type are showling decline.
## Summary
Based on the analysis following are the recommendation for addressing any disparities among the city types.
1. Increase the number of drivers availability in Rural and Suburban cities to meet the ride demand so the number of rides increases and can bring more revenue.
2. By making fares afforable in the Rural and Suburban cities, there will be chance of increased number of rides.
3. By offering discounts and also advertising in the month of february they can be more revenue as from the graph we can see there are more rides in the mid of february.
