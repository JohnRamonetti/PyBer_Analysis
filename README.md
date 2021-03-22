# PyBer_Analysis


## Overview
### Objective: The current analysis was carried out to explore and assess the access and affordability of PyBer ride sharing for different populations based on the types of city (urban, suburban or rural) in which the service is used.  Data was received for 120 cities in which the PyBer service is available, including the driver count and the city type for each of the cities.  Additionally, data was received for each ride provided for the first four months of the year 2019 in each of the noted cities, including the date, fare and ride ID, as well as the city, for each ride.  After reviewing and merging the data, exploratory analysis was carried out, then a summary of the data and a graph of the weekly fares by city type were prepared.

## Resources
  - Data Source: [ride_data.csv](Resources/ride_data.csv), [city_data.csv](Resources/city_data.csv)
  - Software: Python 3.7.7, Anaconda, Jupyter Notebook 6.1.4, Pandas, Matplotlib


## Results
#### A summary table shows the following results. [(summary table)](analysis/Ride_sharing_summary_by_city_type.png)

### [Total Rides](analysis/Fig6.png)
#### There were 2,375 rides included in the data. Urban cities accounted for 1,625 rides, or 68.4% of the total rides provided. Suburban and rural cities accounted for 625 and 125 rides respectively, or 26.3% and 5.3% of the total rides provided.
### [Total Drivers](analysis/Fig7.png)
#### The total number of drivers for all cities in the current data was 2,973. Urban cities had a total of 2,405 drivers, or almost 81% of the total driver count.  Suburban cities had 490 drivers (16.5% of the total).  Rural cities accounted for only 78 drivers, just 2.6% of the total driver count.
### [Total Fares](analysis/Fig5.png)
#### Total fares collected for the rides during time period considered were $63,539. Urban cities totaled fares of $39,854 for the time period viewed (62.7% of the total).  Suburban cities totaled fares of $19,356 for the same time period (30.5% of the total).  Rural city rides had fares totaling $4,328 for this period (6.8% of the total).
### [Average Fare per Ride](analysis/Fig3.png)
#### For urban, suburban and rural cities, the average fare per ride was [$24.52, $30.97 and $34.62](analysis/Ride_sharing_summary_by_city_type.png) respectively.
### [Average Fare by Driver](analysis/Ride_sharing_summary_by_city_type.png)
#### For urban, suburban and rural cities, the average fare per driver was $16.57, $39.50 and $55.49 respectively.

### [Total Fare by City Type (Weekly)](analysis/PyBer_fare_summary.png)
#### An annotated line chart was prepared showing the total weekly fares by city type for the period Jan 1, 2019 through April 29, 2019.  The chart clearly shows the consistently higher revenue produced by urban fares over both suburban and rural fares, and higher revenue produced by suburban fares over rural fares.  while revenues vary week to week for all city types, there appears to be more month to month variation for urban cities than both suburban and rural cities, and perhaps slightly more month to month variation for suburban cities than rural cities.

## Summary
### Firstly, it is important to note that over 60% of revenue is coming from urban fares, so the urban market is very important.  However, urban cities have a disproportionate number of drivers.  While there are more than 30 times the number of urban drivers as rural drivers, there are only 13 times as many urban city rides as rural city rides.  Likewise, there were 2.6 urban rides for every suburban ride, however, there are 5 urban drivers for every suburban driver. So, we would recommend thinking about and considering utilization rates of urban drivers.  Further study would be warranted to evaluate whether urban driver utilization can improve the company's bottom line.
### Although rural cities account for only 5.3% of the total rides and 2.6% of the total driver count, these cities provide almost 7% of the total fares.  Again, we would recommend further evaluation, in this case to determine whether increasing the number of rural drivers would increase revenue, or whether the ride demand is saturated.
### Both the average fare per ride and the average fare per driver increase significantly from urban to suburban to rural cities.  This is probably, in part, due to the greater distances drivers must travel as you mover from urban to suburban to rural settings.  It is also due, in part, to the disproportionately high number of drivers in urban cities. We should look at how drivers are engaged in the different city types (part-time, full-time, per diem, etc.) in order to make better sense of what these numbers mean.  If most drivers are full-time, then it is important to utilize them fully to ensure continued driver satisfaction and protect the company's bottom line.
### When we look at the weekly fare fluctuation in the "Total Fare by City Type" line chart, it is clear that we need to understand whether there is significant seasonal fluctuation in demand for rides (perhaps urban riders prefer to walk when the weather is nice).  We need to understand better how to anticipate the factors, like weather, that affect the demand for rides, again so that the company can better utilize drivers and adequately fill ride demand.

