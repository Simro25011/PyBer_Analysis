# PyBer_Analysis

## Purpose
The purpose of this exploratory data analysis is to identify key carpooling metrics by city type and generate a graphical representation of total weekly fares by city type, which will help improve carpooling accessibility and determine carpooling affordability.


## Resources:
Data Source: ride_data.csv & city_data.csv; Software: Python 3.7.6; Jupyter Notebook

## Analysis

We used the groupby function along with the sum and count functions to get the total passengers, total trips, total fares, the average fare per trip obtained by dividing the total fare for each city type by Total number of trips per city type , while the average fare per driver is obtained by dividing the total fare for each city type by Total number of drivers per city type. To obtain a data frame for plotting a multi-line chart, the following tasks were performed:

- Renaming main data column using rename column function
- Using date and time index functions to set index to date and time
- Creating a new dataframe with city type and tariff columns using the copy function
- The index of the new dataframe has been checked with the info function
- The groupby function is used to group rates by location and date and place them in a dataframe using the dataframe function

https://github.com/Simro25011/PyBer_Analysis/blob/main/Resources/pyber_summary_table.png

the dataframe above tells us the average fare per driver per trip is the highest in rural cities and the lowest in cities, and the high fares observed in rural cities are due to the lower number of trips and drivers across the city. 


lets Analyse therefore our  graphical representation of total weekly fares by city type below

https://github.com/Simro25011/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png

In the months from January to April 2019, the Urban cities had the highest total fares, followed by the Suburban cities , while the rural ones had the lowest fares.  In conclusion, the decline in ride share  usage in rural cities from January 2019 to April 2019 may be due to the lower number of rides opportunities and drivers available in these cities, as well as the allocation of more carpool opportunities and drivers to rural cities is  likely  going to lower the average fare per driver per trip.


## Summary

The decline in ride share  usage in rural cities from January 2019 to April 2019 may be due to the lower number of rides opportunities and drivers available in these cities, as well as the allocation of more carpool opportunities and drivers to rural cities is  likely  going to lower the average fare per driver per trip. If we had more data regarding the demographic population  for each city type,  we  will be able to group rates by population and city type. This information will provide a clearer picture of why certain city types have higher average prices per driver per trip.

