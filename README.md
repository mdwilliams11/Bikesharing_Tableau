# bikesharing
Module 14 with Tableau


## Overview of Analysis

In this module I used Tableau and the Pandas Python library to conduct analysis on bike sharing data. The data comes from a bike sharing program in New York City over the month of August 2018.


## Results

[Link to Tableau Public Story](https://public.tableau.com/views/Mod14Challenge_16382517045240/CitiBikeStory)

This Tableau dashboards and sheets were created with data from a New York City bikesharing program with the hopes of gaining insight before starting a similar bikesharing program in another city.

![Any_title](https://raw.githubusercontent.com/mdwilliams11/bikesharing/main/checkout_time.png)

This dashboard shows the elapsed time that a bike was checked out for. The top chart shows all users while the bottom has checkout time broken out by gender. Most bikes are checked out around 10 minutes, with almost all rides falling under 45 minutes.


![Any_title](https://raw.githubusercontent.com/mdwilliams11/bikesharing/main/customer.png)

This pie graph of the customer usertype shows 81% of users are subscribers, with the remaining 19% being one-time customers. Repeat business is likely going to be key for any city with a potential bikeshare program.


![Any_title](https://raw.githubusercontent.com/mdwilliams11/bikesharing/main/peak_hours.png)

This graph shows the peak hours that bikes are used by the ride starttime. Peak bike share hours fall around the expected morning and evening commute. The slow period, in the early morning, may be an ideal window of time where bikes could be relocated or have maintenance performed on them.


![Any_title](https://raw.githubusercontent.com/mdwilliams11/bikesharing/main/trips_gender_weekday.png)

This graph shows the breakdown of rides by gender, weekday, and usertype. There are more subscribers than customers and more male riders than female. For subscribers, the distribution of rides seems fairly consistent throughout the week, with there being more Saturday rides for both male and female riders than there are Wednesday rides. For customers, the peak days are Saturday and Sunday, suggesting their bike usage is not tied to a work commute as much as the subscriber usertypes.


![Any_title](https://raw.githubusercontent.com/mdwilliams11/bikesharing/main/weekday_per_hour.png)

This heatmap of rides throughout the weekdays shows that a large portion of rides are likely being used for weekday commutes. The Saturday heatmap is more evenly distributed as riders are likely using the bikes for non-commute-related leisure or travel.


![Any_title](https://raw.githubusercontent.com/mdwilliams11/bikesharing/main/weekday_per_hour_gender.png)

The heatmap of rides throughout the weekdays broken out by gender shows the ride patterns are consistent between male and female riders.



## Summary

In addition to the analysis performed, we could continue the bikeshare analysis by comparing different fields within Tableau

* We could use the birth year field to look at the demographics of the bike share customers and subscribers

* We could use "usertype" and "starttime" to see when customers vs subscribers tend to ride the bikes. This could be useful when considering offering flexible prices during different hours or on different weekdays.
