# PyBer Ride Sharing Analysis
Using python and jupyter notebook anualize and visualize PyBer ridesharing data.

## Resoures
Software:
- Jupyter notebook 6.4.8
- Python 3.10 (64-bit)

## Overview
This projecte required me to create a summary DataFrame of the ride-sharing data by city type. Using Pandas and Matplotlib, I then created a multiple-line graph that shows the total weekly fares for each city type.  Based on results summarize the findings. The PyBer results could help determine affordability and improve access to additional neighborhoods in need of a ride sharing service.

## Analysis Results
The first deliverable required me to obtain the following pieces of information:
- The total number of rides for each city type
- The total number of drivers for each city type
- The sum of the fares for each city type
- Calculate the average fare per ride for each city type
- Calculate the average fare per driver for each city type

Based on the information retrieved and calculated the below summary dataframe was created.  This shows there were significantly more urban rides given and urban drivers than rural and suburban areas.  On the other hand, the average fare per rural driver and suburban driver is significantly higher than urban.  This aligns with expectations since urban areas are more densly populated and individuals commute shorter distances, compared to less densly populated areas where individuals generally commute longer distances in suburban and even more so in rural areas.

![PyBer Challenge Dataframe Summary](https://github.com/Jahill17/PyBer_Analysis/blob/main/PyBer%20Challenge/PyBer_summary_dataframe.png)


The second deliverable ultimately required me to create a chart showing the total fares by city type.  The chart helps visualize and support the story of the average fare price and number of rides by city type.

![Total Fares by City Type](https://github.com/Jahill17/PyBer_Analysis/blob/main/PyBer%20Challenge/PyBer_fare_summary.png)

## Summary
The summary data shows a relationship exists between city type and average driver fare.  The more drivers there are to meet demand (number of rides) results in more overall revenue, additionally more populated areas (urban) generally result in lower average driver fare compared to less populates areas (rural).  This largely can be attributed to rural areas usually requiring longer trips compared to short distance travel within the city for urban areas.  Ultimately my recommendation would be to try to get more drivers in rural and suburban areas to match the demand since the driver average fare is higher.
