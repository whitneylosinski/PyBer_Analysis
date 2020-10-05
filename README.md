# PyBer Analysis

## Overview of the analysis:

The purpose of this project is to perform an exploratory analysis and create compelling visualizations of rideshare data from January to early May 2019 for PyBer, to help improve access to ride sharing services and determine affordability in underserved neighborhoods.  Specifically, the analysis is to compare the relationship between the type of city and the number of drivers and riders as well as calcuate the total fares, drivers and riders per city type.  The deliverables from the analysis are as follows:

   1. Summary of ride sharing data by city type.
   2. A bubble chart that visualizes the average fare versus the total number of rides with bubble size based on the total number of drivers for each city type.
   3. Mean, median, and mode for each city type for the following:
        1. Number of rides
        2. Fare prices
        3. Number of drivers
   4. Box-and-whisker plots that visualize each of the following for each city type to determine if there are any outliers:
        1. Number of rides
        2. Fare prices
        3. Number of drivers
   5. Pie charts that visualizes each of the following data for each city type:
        1. Percent of total fares
        2. Percent of total rides
        3. Percent of total drivers
   6. A line chart that visualizes the total weekly fares for each city type. 

## Resources:
* Data sorces: city_data.csv, ride_data.csv
* Software: Python 3.8.3, Jupyter Notebook (anaconda3)

## Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

The results of the ride sharing analysis summary below show that ride sharing is much more common and quite a bit cheaper in urban areas than in suburban or rural areas.  For the time period of January 2019 to early May 2019 captured by the data, there were 1,625 total rides shared in urban cities and only 125 in rural cities.  When comparing the total number of drivers in each city type, the data showed that urban cities had far more drivers (2,405) than suburban (490) or rural (78) cities.  In fact, urban cities were the only city type that had more drivers than total rides for the time period analyzed.  Additionally, from the summary the data shows that urban cities brought in 2 times as much fare revenue as suburban cities and 9 times as much as rural cities, but the average fare per ride is actually lowest in urban cities.  Both the average fare per ride and per driver were highest in rural cities and lowest in urban cities.

![Ride_Sharing_Summary](Analysis/summary.png)

The following bubble chart shows a comparison of the average fare versus the total number of rides for each city type.  The bubble size also provides a visual comparison of how the number of drivers in each city correlates to the data.  The chart below shows that cheaper fares correlate to a higher number of rides while higher fares typically have a lower number of rides.  

![Bubbble_chart](Analysis/Fig1.png)

| a | b |
|:----|:----|
| ![Total_Fares Stats](Analysis/Fig2.png) | ![Total_Rides_Stats](Analysis/Fig3.png) |
| ![Total_Drivers_Stats](Analysis/Fig4.png) | |


| a | b |
|:----|:----|
| ![Total_Fares Pie](Analysis/Fig5.png) | ![Total_Rides_Pie](Analysis/Fig6.png) |
| ![Total_Drivers_Pie](Analysis/Fig7.png) | |

![Weekly_Fares Chart](Analysis/Fig8.png)


## Summary:

Based on the data, I have three business recommendations which address disparities among the city types.  My recommendations are as follows:

  1. **Reduce the number of drivers in urban cities.** - There were more drivers in urban cities than there were total rides.  This makes ride sharing very accessible in urban neighborhoods but it is driving down the average fare per driver.
  2. **Add drivers in rural and urban neighborhoods.** - There were more rides than drivers in suburban and rural cities.  Because of this, it's possible that there were other customers who wanted rides but were unable to gain access to a driver.  Increasing the number of drivers would improve accessibility in suburban and rural areas, leading to more rides and an increase in total fares.
  3. **Reduce fares in suburban and rural cities.** - Suburban and rural cities have higher average fare prices per ride than those in urban cities.  Making ride sharing more affordable to suburban and rural neighborhoods may widen the customer base, creating more riders who use the service.  This would lead to an increase in total rides and possibly an increase in total fares for suburban and rural neighborhoods.
  
