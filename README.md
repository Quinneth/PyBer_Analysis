# PyBer_Analysis

## Purpose

Business decisions are driven by detecting patterns, trends, correlations, and outliers. The purspose of this assignment is to create an analysis including visualizations using Python's two-dimensional plotting library Matplotlib. "Action" quality figures produced must tell a visual story by using visualizations that are informative and engaging. 

## Resources
- Software:  anacondaSciPy, Numpy, Pandas, Matplotlib, Jupyter Notebook
- Data Source: city_data.csv, Ride_Data.csv
 
## Overview
 
The PyBer project's goal was to create visualizations of rideshare data to help improve access to ride-sharing services and determine affordability for underserved neighborhoods. Visualization provided showcase the relationship between the type of city, number of dirvers/riders, and percentage of total fares, riders, and drivers by type of city. The analysis was conducted using data gathered between January and May 2019 from rural, suburban, and urban type-city ride-sharing activities. 

## Results
 
### Total Revenue by city type
Proportion of fares by ***city*** type
Approximate: 
- Urban: $40,000
  - Average Fare: $24.53
  - Standard Deviation: $11.74
  - Median: $24.64
- Suburban: $19,000
  - Average Fare: $30.97
  - Standard Deviation: $10.67
  - Median: $30.75
- Rural: $4,000
  - Average Fare: $34.62
  - Standard Deviation: $14.55
  - Median: $37.05

![Total Fares by City Type](https://github.com/Quinneth/PyBer_Analysis/blob/main/analysis.png/Fig5.png)

### Total rides by city type
Proporation of rides by ***city*** type
- Urban: 1,625
  - Average: 24.6
  - Standard Deviation: 5.4
  - Median: 24
  - ***At least 1 Outlier***
- Suburban: 625
  - Average: 17.4
  - Standard Deviation: 4.3
  - Median: 17
- Rural: 125
  - Average: 6.9
  - Standard Deviation: 2.5
  - Median: 6
 
![Total Rides by City Type](https://github.com/Quinneth/PyBer_Analysis/blob/main/analysis.png/Fig6.png)


### Total drivers by city type
Proportion of driver by ***city*** type
- Urban: 2,405
  - Average: 37.7
  - Standard Deviation: 20.1
  - Median: 37
- Surburban: 490
  - Average: 13.7
  - Standard Deviation: 8.0
  - Median: 16
- Rural: 78
  - Average: 4.3
  - Standard Deviation: 2.7
  - Median: 4

![Total Drivers by City Type](https://github.com/Quinneth/PyBer_Analysis/blob/main/analysis.png/Fig7.png)

### Revenue Trend by City Type

![Total Faire by City Type](https://github.com/Quinneth/PyBer_Analysis/blob/main/analysis.png/Fig8.png)



***Takeaways***
- Urban cities make up the majorioty of Pyber's revenue, but have the lowest average and median fare along with the most variation. 
- Suburban and rural cities have fewer drivers but the average fares are higher than urban cities.
- The fare trend remains fairly stable throughout the timeframe. There more inter-month variations seen in urban and rural city types. 
- All city types see a slight rise in fairs in mid-February possibly due to Valentines Day traditions. 
- Suburban city revenue sharply rises again in April possibly due to the change in seasonal weather. 

## Recommendations
1. Compute further analysis on on under-performing city types:
  - Is under performance related to lack of resources? 
  - Is the underperformance related to accessibility i.e variation in the type of transportation needs by city type?
  - Repeat analysis on subsequent timeframe.
2. Raise driver supply in suburban and rural cities. Longer distances may account for the higher average fare. Pursuing more drivers might expand the those respective markets because each ride occupies a driver for longer compared to urban cities. 
3. Strategically boost the the number of drivers based on weekend and holiday schedules through incentives like gas cards or quota bonuses. Bonuses could be tied to number of rides or miles driven. 
4. Increase marketing campaigns sin suburban and rural markets
