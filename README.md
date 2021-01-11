# Citi Bike NYC Challenge

## Overview

The purpose of this project was to pitch to investors that a bike-sharing program is worth investing in Des Moines. In order to do this, a bike trip analysis was conducted using Tableau Public software. From this analysis, visualizations were used to create a bike trip story. 

## Resources

Data sources: "201908-citibike-tripdata.csv" retrieved from https://s3.amazonaws.com/tripdata/index.html

Software: Python, Tableau Public

## Tableau Dashboard Story

[link to dashboard](https://public.tableau.com/profile/jason.masurovsky#!/vizhome/NYCCitiBikeChallenge_16102519452920/NYCCitiBikeStory)

## Results

![img_1](https://github.com/jmasurovsky/NYC_Citi_Bike/blob/main/images/Number_of_rides.png)

*Figure 1. Total number of rides.*

There were a total number of 2,344,224 trips taken using citi bike in New York City. 

![img_2](https://github.com/jmasurovsky/NYC_Citi_Bike/blob/main/images/Top_starting_locations.png)

*Figure 2. Top starting locations*

The map above displays the top starting locations for all citi bike trips. The larger the circle is equal to a higher count of where trips started. The darker the shading also means a higher density of where trips started.

![img_3](https://github.com/jmasurovsky/NYC_Citi_Bike/blob/main/images/Top_ending_locations.png)

*Figure 3. Top ending locations*

The map above displays the top ending locations for all citi bike trips. Same as top starting locations, the larger the circle and darker shading means a higher density count while smaller circles and lighter shading means a low density count.

![img_4](https://github.com/jmasurovsky/NYC_Citi_Bike/blob/main/images/Checkout_Times_for_Users.png)

*Figure 4. Checkout times for users*

The plots above show the count of checkout times for users. Checkout times peak during typical morning rush hour times of the day, and gradually decreases the day goes on.

![img_5](https://github.com/jmasurovsky/NYC_Citi_Bike/blob/main/images/Checkout_Times_by_Gender.png)

*Figure 5. Checkout times by Gender*

The plot above shows the count of checkout times by gender. Highlighting the peak hours of checkout times, the majority of trips are taken by men.

![img_6](https://github.com/jmasurovsky/NYC_Citi_Bike/blob/main/images/Trips_by_weekday_per_hour.png)

*Figure 6. Trips by weekday per hour*

The chart above shows a density heatmap of a breakdown of trips by weekday per hour. During the weekend most trips are taken late-morning and during the afternoon, whereas most trips during weekdays are taken during morning and afternoon rush hour. 

![img_7](https://github.com/jmasurovsky/NYC_Citi_Bike/blob/main/images/Trips_by_gender_weekday_per_hour.png)

*Figure 7. Trips by gender (weekday per hour)

The visualization above shows weekday trips per hour by gender. Weekday trips by gender show similar patterns as before with majority of weekay trips occurring around 7am-9am and 5pm-7pm. While weekend trips are taken from 11am-4pm.

![img_8](https://github.com/jmasurovsky/NYC_Citi_Bike/blob/main/images/User_trips_by_weekday.png)

*Figure 8. User trips by weekday*

This visualization displays that most of NYC citi bike subscribers are men. The distribution of gender for customers is fairly even. Customers are more likely to take trips on weekends instead of weekdays.

## Summary

Results of the analysis give context to the 2 million trips taken by citi bike users in New York City. It shows that most trips were taken from south and central Manhattan, in addition to small high density clusters of trips taken in Brooklyn. Most trips are taken during rush hour, especially commuters in the morning, majority being men. Breakdown of trips taken by weekday per hour showed a different story with weekend trips are typically taken later in the afternoon. Customers that are not subscribed to a citi bike membership are likely to take trips during weekends. An additional visualization to create would be maps of weekend trip starting and ending locations compared to weekday starting and ending locations. Another visualization that would be helpful would be creating bins of age groups by 'Birth Year' and creating charts of checkout times by age group. 
