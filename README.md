# PyBer_Analysis
---
## Overview of Project
V.Isualize has given us a new assignment. We need to create a summary DataFrame showing the ride-sharing data by the city type and present a multiple-line graph with the weekly fares for each city type.

### Purpose
The purpose of this analysis is to create a report that shows a multiple-line graph demonstrating the weekly fares for each type of city as well as a data frame that summerizes the ride sharing data by the type of city. Using these we can generate a report showing how the data differs by city type and shows how this data can then be used by those making the decisions at PyBer.

## Analysis

The Jupyter Notbook used to complte this analysis is:

[PyBer_Challenge.ipynb](https://github.com/ClaudAMC/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb)

## PyBer Analysis Results

### Summary Ride-sharing Data

Below we can see the Ride-sharing DataFrame:

![Summary_DataFrame.PNG](https://github.com/ClaudAMC/PyBer_Analysis/blob/main/analysis/Summary_DataFrame.PNG)

1. From this we can see the rural cities have the lowest number of rides and drivers; this leads to the average fare per ride and average driver wage being the highest at $34.62 and $55.49, respectively, as the total fare for rural cities is the lowest at $4,327.93.

2. Conversely, urban cities have the highest amount of rides and drivers resulting in the highest total fares at $39,854.38; this results in the lowest avg fare per ride and driver at $24.53 and $16.57, respectively.

Below we can see the summary multiple-line graph showing the weekly fares for each type of city between Jan 2019 to the end of April 2019.

![PyBer_fare_summary.png](https://github.com/ClaudAMC/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

1. From this graph we can see that the total fares for all three types of cities increased and peaked on the third week of feb. After this the total fares for suburban and rural cities decreased and plateaued through March while the fares for urban cities oscillated then through April plateued at a peak slowly decline as the month ran on.

2. During the month of April the suburban and rural cities no longer followed the same pattern where rural cities reached a peak at the begining of the month and then decline in fares there after. Suburban cities on the other hand hit a low during the second week of April, the following weeks however, had a sharp increase in fares.

## PyBer Analysis Summary

Business recommendations adressing any disparities among the city types would include:

1. Create incentives for drivers in suburban and rural cities as it is possible that lack of avaliable drivers may be preventing more customers from looking for these services in these areas. With more drivers the average fare per ride may decrease incentivizing riders to use the service more often; this might prove particularly useful in suburban cities.

2. Conversely, in urban cities there are more drivers than riders. This means that it is possible some drivers do not always have work. It may be useful for the company to spend more on advertising or incentives for riders in rural cities to use the service more. This may even out the driver to rider ratio increasing overall profit.

3. Tracking miles traveled per ride may also prove fruitfull as it is posible that the disparity in average fares are due to distances travelled. Rural cities are more spread out therefore rides may be longer than un urban communities, this may be driving the fares to be higher per ride. It may also be good to try and track driver to rider ratio through out a 24 hr period. In doing this we can get a better idea of when riders outnumber drivers - this means loss of profit and a wait for the customer.
