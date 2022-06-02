# Citibike NYC Analysis

## Overview of the Statistical Analysis
The purpose of this analysis is to determine trends in Citibike bicycle sharing usage from New York City, and apply those findings to possible enterprise in Des Moines. Analysis will be performed on data collected from [Citibike System Data](https://ride.citibikenyc.com/system-data), for the month of August 2019. 

The data analysis will be performed using Tableau Public and is available for review on the [Tableau Public Website](https://public.tableau.com/app/profile/jordan.merritt/viz/CitibikeNYCAnalysis-August2019/CitibikeAnalysis?publish=yes).
## Results
![NYC Citibike Dashboard](https://github.com/JorMerr/bikesharing/blob/main/img/NYC-dashboard.JPG)
The above dashboard shows initial results of analysis, including:
- average trip duration per age of user
- total number of rides in August 2019
- the breakdown of users by gender
- the most used starting locations for Citibike rides

![Checkout Times for Users](https://github.com/JorMerr/bikesharing/blob/main/img/checkouttimes.JPG)
The above image shows the length of time bikes were checked out by users. The peak of the curve is at approximately 5 minutes in trip duration.

![Checkout Times for Users by Gender](https://github.com/JorMerr/bikesharing/blob/main/img/checkouttimes.JPG)
The above image further breaks down the trip duration from the previous image into user stated gender categories. As can be seen, August 2019 shows predominantly male users of the Citibike service in New York City.

![Trips per Hour](https://github.com/JorMerr/bikesharing/blob/main/img/tripsperhour.JPG)
The above heatmap indicates the volume of trips for each hour of each weekday in August 2019. The darker red the colour, the more trips occured at that time. Weekends show fairly steady usage throughout daylight hours, while bikes are used significantly more during standard commute hours on weekdays.

![Trips per Hour - Gender](https://github.com/JorMerr/bikesharing/blob/main/img/tripsperhour-gender.JPG)
The above heatmap further analyzes the gender breakdown of the previous heatmap. The gender breakdown seems to coincide with the gender breakdown from the Checkout Times, with more used by male users.

![Trips per Hour - Gender + User Type](https://github.com/JorMerr/bikesharing/blob/main/img/tripsperday-gender-usertype.JPG)
Further analysis of the volume of trips per hour and gender is seen above to indicate User Types: Subscribers, or one-time Customers. The heatmap shows that the majority of users are Subscribers, meaning that Citibike users who opt for the subscription serivce model in order to secure and utilize bicycles are more likely to continue using Citibike services, while one-time users make up a smaller portion of client base.

## Summary
Initial findings of the statistical analysis show that the majority of trips are less than 30 minutes in duration. This suggests bicycle pick up and drop off locations must be created with length of trip duration in mind. 

The peak trip duration of all users is approximately 5 minutes. This means that many, smaller locations for start and end of bicycle trips will be preferable in order to effectively service users in Des Moines. 

It is recommended to create visualization of trip start and end locations, and total distance travelled between to determine the most optimal distances between pick up locations in Des Moines.

Additionally, plotting the total distance between start and end locations against the total time per trip may reveal that some users pick up from central Citibike locations, use the bicycle for errands, and return to the same location. 

It may be prudent to determine how many users pick up and drop off from the same location to assist in determining the recommended number of bicycles to have on hand at popular pick up locations in Des Moines.
