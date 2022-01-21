# (201902-fordgobike-tripdata)
## by (MAHMOUD WAEL HAMDY)


## Dataset

This project is divided into two main parts. In the first part, you will perform an exploratory data analysis on the Ford GoBike System Data set. I will use the data science and data visualization Python libraries to explore data set variables and understand data structure, anomalies, patterns, and relationships. The analysis in this part should be structured, from simple univariate relationships to multivariate ones.


> In Part Two, I'll take the main findings from my exploration and pass them on to others through an illustrative analysis. To this end, I will be creating a slide deck that uses polished illustrations to communicate my findings.

> This document explores a dataset containing approximately 183,412 Ford gobike trip data with 16 features (duration_second, start time, end time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude_bicycle_share_to). Most variables are 9 scalar, others are 2 date/time, 4 object type and 1 boolean type.

> To get clean data include:
> 1- Change the data type of start and end time to be datetime64.
> 2- Change the data type of bike_share_for_all_trip to be Boolean.

## Summary of Findings
 >in exploratory data analysis, I have done a lot of visualizations to reach my results such as the most duration of trips is 10 min , most popular 10 start and end stations and I have found that Market St at 10th St and San Caltrain Francisco station2(townsend St at 4th St) are the most common start station, while San Caltrain Francisco station2(townsend St at 4th St )and Market St at 10th St are the most common end station, bikes with id 4794 and 4814 are most in this data , 10.83% of the riders are Customers while  89.16% are Subscribers, Thursday andTuesday  are the most common days, while Sunday and saturday is the least day,Saturday and Sunday are the weekend in the United States of America.
 , tI think the hours are those from 7 to 9 in the morning and from 4 to 6 in the evening,This may be related to the time workers and students go to and leave work and school , the average time which riders (customers) take type is higher than the average of Subscribers, the riders (customers) have longer trips, whereas Subscribers have shorter trips,the average of all days is around 10 minutes , but the average duration of Saturday and Sunday is more necessary bit than the others day,the hours for both user types are those from 7 - 9 am and from 4 - 6 pm. This might be related to the time when employees and students go to and leave work and school,the frequency of the Subscriber type on weekdays is almost equal too and their trips are almost on weekdays but the frequency of the Customer type on weekdays is almost equal, but they prefer doing trips on weekends ,Customers have consistently higher trips across all hours of the day. However, customer trips are much longer at midnight and midday
## Key Insights for Presentation
>For the presentation, I'm trying to illustrate What is the duration of most rides? most popular start and end stations, the most common user type in the dataset , then the most popular day 

after all of these single relationships, I'm showing some relationships between two variables by showing the relation between user type and the hours they ride bikes , then the number of each type per day, and finally the number of trips for each day 
In the end, I am going to finish the presentation by showing a multi relationship, What are the most common hours for each user in each day?
