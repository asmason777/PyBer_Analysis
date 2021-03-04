# PyBer Rideshare Analysis
---
## Overview of Project

### Purpose

The objective is to assist management at PyBer to collect and process its raw rideshare data to help determine best practices going forward. Using Python, the results can then be displayed in both charts and graphs.

## Results

### Average Fare per Ride & Average Fare per Driver  

[![Ride-chart-summary.png](https://i.postimg.cc/wjymJQk8/Ride-chart-summary.png)](https://postimg.cc/FYvzXcqD)  

As seen in the above table, the results from the first breakdown that calculate the average fare per ride and average fare per driver per city type are fairly straight-forward. Not surprisingly, rural drivers made the most on average per ride. This makes sense as it can be assumed that the average length of a ride in a rural area is going to be longer. And, based on the same reasoning, urban rides, where the likelihood of shorter rides is to occur, have the lowest average per ride. Ultimately, the average fare per ride per city area is within the expected range. 

The average fare per driver is a bit more complex but mostly certainly is influenced by the number of drivers per city type. Rural drivers made over three times more on average per driver than urban drivers ($55.49 to $16.57). This difference is notable and is due to rural drivers completing significantly more rides per driver. For example, rural drivers accumulated a total of 125 rides with only 78 drivers which breaks down to 1.6 rides per driver. Conversely, urban drivers only received 0.675 rides per driver. From this data, it can be concluded that the number of drivers per city type has a great effect on the average driver’s income.

### Weekly Results

[![Py-Ber-fare-summary.png](https://i.postimg.cc/hP9jqZMG/Py-Ber-fare-summary.png)](https://postimg.cc/rKwc1JB6)  

The graph above compares fares by city type on a weekly basis over four months (January through April 2019). While a more in-depth investigation might uncover the variations for weekly fluctuations, overall the lines for all three city types remain relatively consistent throughout the period of analysis. This indicates that the demand in the different city areas is likely to stay the same as, again, there does not appear to be any major outliers in the data for any of the city types.


### Recommendations  

Based on the analysis of the chart and graph, the following recommendations should be considered:

1)	The income per driver is skewed in favor of rural drivers. As stated, this is due to there being an over-abundance of urban drivers and relatively few rural drivers. As demand is expected to stay consistent for each city type, PyBer should consider capping the number of urban drivers it allows. This would increase the income average for city drivers.  

2)	Another option would be to incentivize urban drivers to focus their efforts more in suburban or rural areas. PyBer could publish weekly earnings data based on city type thus allowing drivers to drive in more profitable areas.  

3)	Based on the data from the table, it appears that current ride fare rates are likely based more on ride distance rather than ride time. Urban rides, due to more traffic, are likely to be relatively longer in duration but shorter in distance. It may be possible that the algorithm that determines fare needs to be tweaked so that ride duration is compensated at a higher rate. This would help minimize the disparity between urban and rural driver incomes. 
