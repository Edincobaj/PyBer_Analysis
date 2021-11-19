# PyBer_Analysis
## Overview of the Analysis

As a data analyst at PyBer, you've been asked by the CEO, V. Isualize, to analyze all the rideshare data from January to early May 2019 and create a compelling visualization. Using our Python skill and knowledge of Pandas we'll create dataframes to allow us see the data by city type. We'll then create a multiple-line graph to show the weekly fares for each city type then submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Results

Taking a look at the summary dataframe we created in deliverable 1, we can see several differences between each city type.
![city_type_df_challenge](https://user-images.githubusercontent.com/41974323/142675518-dc6ae278-1127-44d0-9d45-b956b03d5ba6.PNG)
- Urban cities have the highest total rides, total drivers, and total fares followed by Suburban and Rural.
- Rural cities have the highest average fare per ride and average fare per driver followed by Suburban and Urban.
- Uban cities are the only ones that have a higher number of drivers then they do actual rides.

Taking a look at the multiple-line chart we created in deliverable 2, we can see how each city type did over the course of a few months.
![Total_Fare_by_city_Type](https://user-images.githubusercontent.com/41974323/142677275-beadeb90-d2ed-4358-90e9-65d17908e671.png)
- Rural cities had the lowest fares followed by Suburban and Rural city types.
- We see an interesting uptick of fares from all city types in the middle of February going into late February.
- In March there seems to be very inconsistent fares throughout the month in Urban cities while Suburban and Rural cities are mor consistent. 
- Going into the end of March into April there is a significant uptick of fares in Urban and Rural cities while Suburban cities suffered more of a downtrend.
- The first few weeks in January sees a large increase in fares from Urban and Suburban cities while Rural cities see a decrease.

## Summary
Based on the above results we can offer three business recommendations for addressing any disparities among city types.

1. We see that there are vastly more drivers than there are rides in Urban cities but given the fact that they have the lowest average fare per ride and average fare per driver, we may want to incentivize drivers to get more rides outside of the Urban areas to capitalize on higher averages in Suburban and Rural areas.
2. Urban cities have the highest total rides/fares out of the three city types while having the lowest average fare per ride/driver. An increase in prices for Urban areas would be a good boost to both PyBer and Urban drivers.
3. Given that Rural cities have the highest average fare per ride and lowest total rides, running promotions and/or discounts in those areas to increase total rides would give a boost the companies income. 
