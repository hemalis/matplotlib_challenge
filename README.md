# Pyber Analysis
## Overview of the analysis
Purpose of the analysis is to create a summary of the ride service app Pyber which provides details about how it's being utilized by various types of cities that is Urban, Suburban and Rural. Also, provide a multiline chart which shows time series comparison of fares for different types of cities. 

## Results

Summary of the Pyber analysis is as show below: 

| City type     | total rides | total drivers | total fares | average fare per ride | average fare per driver |
|----------|-------------|---------------|-------------|-----------------------|-------------------------|
| Rural    | 125         | 78            | $4,327.93   | $34.62                | $55.49                  |
| Suburban | 625         | 490           | $19,356.33  | $30.97                | $39.50                  |
| Urban    | 1,625       | 2,405         | $39,854.38  | $24.53                | $16.57                  |

- It shows that Pyber is highly popular in Urban cities which has highest number of rides (1,625)
- Pyber's ~62% revenue ($39,854.38) comes from Urban cities. 
- Average fare per ride and average fare per driver is highest in Rural cities. 
- Average fare per driver is ~2.3x in Suburban and ~3.3x in Rural compared to Urban cities. This shows that there are more drivers required in Rural and suburban cities. 
- Drivers are less compared to rides in Rural and suburban cities that leads to having higher average fare per ride.

Comparison between fares is shown in below image. 
![alt text](https://github.com/hemalis/matplotlib_challenge/blob/main/analysis/PyBer_fare_summary.png?raw=true)

- There is a peak in time series happening in Feb 3rd week in all types of cities. 
- Line for rural series is relatively flat compared to other type of cities. 
- Urban cities are starting lower but it goes up as time progresses. There are ups and downs but still relatively on higher side. 
- Suburban cities have seen dropped fares through Feb and March but it's peaking at the end of the April. 

## Summary
Based on above results, here are the recommendations for CEO of Pyber. 

1. Urban cities have highest demands and highest rides, it's a great opporunity to market more in Urban cities. It's also due to the fact that it has higher drivers then rides. 
2. Rural and Suburban cities needs more drivers as there are higher # of rides happend compared to # of drivers. In Rural cities, riders are 1.6x more then drivers. 
3. There is an opportunities to expand in Rural and Suburban cities as revenues are less there. ~62.5% of revenues comes from Urban cities & there is huge market in Suburban and Rural cities that can be captured. 
