# bikesharing

## Overview 

The purpose of this analysis was to create visualizations to evaluate Citibike usage to present the Des Moines Citibike program to investors. Specifically, we wanted to present on the following: 

- The length of time that bikes are checked out for all riders and genders
- The number of bike trips for all riders and genders for each hour of each day of the week
- The number of bike trips for each type of user and gender for each day of the week.

I began my analysis by converting the  "tripduration" column from an integer to a datetime datatype to get the time in hours. I did in this using Pandas in Python. 

## Results:

Linked below is my Tableau Public workbook that contains a Citibike Tableau Story. There are seven different visualizations in the story and each one has an added textbox with an explanation and takeaways. 
- [Link to dashboard](https://public.tableau.com/app/profile/charlotte.rotner/viz/CitibikeStory_16568740934880/CitibikeStory?publish=yes)

## Summary:

From the analysis done in the visualization we can make three major assumptions:
- Men use citibike's more frequently than women
- The most common time to ride bikes is around the early evenings 
- Citibike's are used most frequently in high density and 'touristy' areas of town. 

We need to ensure that these assumptions are taken into consideration when starting Citibike in Des Moines. 

There are a number of other visualizations we could create to help us make a business case to our investors. To name a couple 
- We could create a map showing ride starts and then add a color mark to show whether the rider was a subscriber or customer. This would help us see which parts of the city where there are more subscribers vs users and where we could target advertising.
- We could also create a heatmap showing which bike id's have had the greatest number of rides to know which bikes we will likely have to repair sooner. 
