# PyBer-analysis
Python analysis for ride-sharing app

## Overview of the analysis

 We will use the Pandas library to create a summary of the ride-sharing data by city type. With Pandas and Matplotlib, we will create a Multiple-line graph showing each city type's total weekly fares. Finally, we will summarize the relationship between the type of city and the number of drivers and riders and present the summary to decision-makers at PyBer.

## Results

Using the Pandas' *groupby()* function, we get the total number of rides, the total number of drivers, and the total fares for each city type. Then, calculate the average fare per ride and per driver for each city type.
![PyBer_Summary.png](https://github.com/NadzeyaAudzeichuk/PyBer-analysis/blob/main/Analysis/PyBer_Summary.png)

If we compare the average fare per ride between each city type, we'll notice that the average fare per ride in rural cities is about 10% and 40% higher than in suburban and urban cities, respectively.

From the average fare per driver and total drivers, we see that the more drivers in the city, the smaller the average fare.

 Using your Pandas and *pivot()* and *resample()* functions, we create a multiple-line graph showing each week's total fares by city type.
 


![PyBer_fare_summary.png](https://github.com/NadzeyaAudzeichuk/PyBer-analysis/blob/main/Analysis/PyBer_fare_summary.png)



The total fare in urban cities is two and eight times greater than in suburban and rural towns. 

## Summary

Based on the findings, three recommendations on how to address disparities among the cities:
- Increasing the number of drivers in rural towns will make the rides more affordable for those neighborhoods.
- Reducing drivers in urban areas will increase drivers' average fares, which will positively impact their earnings.
- Balancing out urban, suburban and rural areas can improve revenue for the company 
