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
   6. A line graph that visualizes the total weekly fares for each city type. 

## Resources:
* Data sources: city_data.csv, ride_data.csv
* Software: Python 3.8.3, Jupyter Notebook (anaconda3)

## Results:

The results of the ride sharing analysis summary below show that ride sharing is much more common and quite a bit cheaper in urban areas than in suburban or rural areas.  For the time period of January 2019 to early May 2019 captured by the data, there were 1,625 total rides shared in urban cities and only 125 in rural cities.  When comparing the total number of drivers in each city type, the data showed that urban cities had far more drivers (2,405) than suburban (490) or rural (78) cities.  In fact, urban cities were the only city type that had more drivers than total rides for the time period analyzed.  Additionally, from the summary the data shows that urban cities brought in 2 times as much fare revenue as suburban cities and 9 times as much as rural cities, but the average fare per ride is actually lowest in urban cities.  Both the average fare per ride and per driver were highest in rural cities and lowest in urban cities.

![Ride_Sharing_Summary](Analysis/Summary.png)

The following bubble chart shows a comparison of the average fare versus the total number of rides for each city type.  The bubble sizes also provide a visual comparison of how the number of drivers in each city correlates to the data.  The chart below shows that cheaper fares correlate to a higher number of rides while higher fares typically have a lower number of rides.  

![Bubbble_chart](Analysis/Fig1.png)

Below are the mean, median and mode statistics for each city type for the ride count, fares and driver count metrics.  Again, the statistics show that urban cities had the highest average ride count and driver count but the lowest average fares.  Rural cities had the lowest average ride count and driver count, with several cities only having one driver in the neighborhood, but they had the highest average fare.

| Ride Count Statistics  | Fare Statistics |  Driver Count Statistics |
|:----|:----|:----|
| ![Ride_Count_stats](Analysis/Ride_Count_Stats.png) | ![Fares_stats](Analysis/Fare_Stats.png) | ![Drivers_stats](Analysis/Driver_Stats.png)

The box and whisker plots below were used to determine if there were any outliers in the data.  The first plot of the ride count data shows that there was one outlier in the data for urban cities.  The outlier had 39 rides over the time period that the data was collected.

|  |  |
|:----|:----|
| ![Total_Fares Stats](Analysis/Fig2.png) | ![Total_Rides_Stats](Analysis/Fig3.png) |
| ![Total_Drivers_Stats](Analysis/Fig4.png) | |

The pie charts below show the percentage of total fares, total rides and total drivers for each city type.  It is clear from the charts that urban areas hold the highest percentage of each metric while rural areas hold the lowest percentage.  A closer look, when comparing the total rides and total drivers charts, also reveals that the number of drivers could likely be better aligned with the number of rides for each city type.

|  |  |   |
|:----|:----|:----|
| ![Total_Fares Pie](Analysis/Fig5.png) | ![Total_Rides_Pie](Analysis/Fig6.png) | ![Total_Drivers_Pie](Analysis/Fig7.png) |

The following line graph shows a comparison of the weekly total fares per city type.  The graph shows that the city types tend to follow a somewhat similar pattern for the total fares from week to week, urban cities collect the highest volume of fares with suburban cities collecting the next highest volume and rural cities collecting the least amount of fares. 

![Weekly_Fares Chart](Analysis/Fig8.png)


## Summary:

Based on the data, I have four business recommendations which address disparities among the city types.  My recommendations are as follows:

  1. **Reduce the number of drivers in urban cities.** - There were more drivers in urban cities than there were total rides.  This makes ride sharing very accessible in urban neighborhoods but it could also be causing some negative effects.  Having too many drivers could potentially be leading to lower average fare prices and lower fares per driver.
  2. **Increase fares in urban cities.** - The data showed that the fares in urban cities were significantly lower than those in suburban or rual cities.  Increasing fares could bring in higher profits for PyBer.  A couple things to consider before making this change would be the reason for the lower fares and the demand for ride sharing in urban cities.  It is likely that the fares are lower becuase the average length of each ride is shorter but if the demand for ride sharing is high enough, customers may still be willing to pay a higher price for each ride.  A market study would be a good tool to use to determine if increasing fares would increase profits or decrease customers.
  3. **Add drivers in rural and urban neighborhoods.** - There were more total rides than drivers in suburban and rural cities.  Because of this, it's possible that there were other customers who wanted rides but were unable to get access to a driver.  Increasing the number of drivers would improve accessibility in suburban and rural areas, and could lead to more rides and an increase in total fares.  Additional data on customer interest in suburban and rural cities or data for how many customers were unable to get a driver would be useful in deciding how many drivers should be in each city.
  4. **Reduce fares in suburban and rural cities.** - Suburban and rural cities have higher average fare prices per ride than those in urban cities.  Making ride sharing more affordable to suburban and rural neighborhoods may widen the customer base, creating more riders who use the service.  This would lead to an increase in total rides and possibly an increase in total fares for suburban and rural neighborhoods.  However, one thing to consider when looking at fares is the distance of each ride.  It's possible that the fares in rural and suburban cities are higher because the average distances of the rides are longer.  Additional data would be needed to evaluate the cause of the higher fare and the feasibility of lowering fares.
  
