# PyBer_Analysis

## Overview of the analysis:
### Explain the purpose of the new analysis.
This project is an analysis of weekly ride-share fares utilizing python, pandas, and ride-share data. Firstly, data is broken down into the 3 different city types: Rural, Suburban, and Urban. This data created a summary of the rideshare data by showing the total rides, total fares, total drivers, average fare per ride, and average fares per driver for each city type. Next, a pivot table is utilzed to allow the base data be indexed by date and separated into the 3 city types. This pivot table was then summarized in a new dataframe to show the fares of each city type by date without null values. Finally, this new dataframe was utilized to creat a chart to demonstrate how each city type compared to eachother in total fares across the given date range.


## Results:
### Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
![Ride Share Summary](https://github.com/waciciarelli/PyBer_Analysis/blob/main/Screenshots/ride_share_summary.png?raw=true)

Firstly, as seen in the summary DataFrame above, Urban areas have significantly more rides and drivers than any other area. However, this does not necessarily mean that this is the best area for drivers to work in. Although the total fares are lower in Suburban and Rural areas, it is to be noted that the average fare per driver is significantly greater than in Rural areas.

![Total Fares By City Type Chart](https://github.com/waciciarelli/PyBer_Analysis/blob/main/Screenshots/fares_by_city_type_chart.png?raw=true)

The above chart demonstrates how each city type faired on a given day. As seen above, the rankings for each city type are consistent throughout the survey period and are as follows: 
1. Urban 
2. Suburban
3. Rural

Additionally, although most dates seem to be somewhat unrelated in fares, there is a spike across each of the city types during late February. This suggest that people from every city type are in greater need of ride-shares during this period.

## Summary:
### Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

In order to combat the disparities between each city type, I would firstly recommend that the CEO hire more drivers from rural areas. This would allow for more rural rides to be processed in a timely manner and increase the Rural area's total fares.

Secondly, because there is a surplus of drivers compared to rides in urban areas, there is not the need to hire more drivers in these areas. I would recommend that the number of drivers be slowly reduced such that the average fare per driver become more averaged out with the average fares of drivers in all city types and these drivers may have a more stable income without sacrifices to the company.

Finally, I would invest in Suburban areas as this seems to have great potential. Although the number of rides is not as great, the average fare per ride is high enough that an increase of business in this area would greatly increase revenue for the ride-share company. While this holds true in Rural areas as well, Suburban areas already have a foothold when it comes to ride-share and it would be a much more stable source of revenue than in rural areas.
