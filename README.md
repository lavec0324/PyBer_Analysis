# PyBer_Analysis
Module 5

## Overview of the Analysis

Purpose of this project was to look at ride share data across several city and city types and provide different views through tabes as well as different charts.  Initially two
sets of data were used which comprised of city data and individual ride data in that city for a specified period.  Using the common index of city we were able to combine and
further analyze the merged dataset.  A sample of that merged data can be seen here:

![](https://github.com/lavec0324/PyBer_Analysis/blob/main/analysis/merged_data.PNG)

Only three files are necessary for this analysis:

   * [PyBer_Challenge.ipynb](https://github.com/lavec0324/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb) - Jupyter Notbook created for analysis
   * [city_data.csv](https://github.com/lavec0324/PyBer_Analysis/blob/main/Resources/city_data.csv) - City Data
   * [ride_data.csv](https://github.com/lavec0324/PyBer_Analysis/blob/main/Resources/ride_data.csv) - Ride Data

This analysis could be used to determine what types of areas see more rides, the average cost of those rides, and the impact the time of the year has on those results.

## Results

Through analysis we can clearly see that urban areas have far more drivers, rides, and fares than rural and suburban areas.  This may suggest that cars are not prevelant in
those areas which could include unwillingness to drive in those areas, parking difficulties, or even cost of maintaining a vehicle in those areas (e.g. insurance, gas,
parking).

Additionally we can see that the average fare is higher in the rural areas.  This most likely has to do with the number of available drivers (supply and demand) as well as
probaby greater differences being covered.  The average fare per driver are also nearly 3.5 times larger from rural to urban.

We can also see for the 4 month view there appear to be spikes in late February for all types of cities.  The data is inconclusive for that aspect.

This can be seen in the below tables and graph.

##### Summary By Type Table

![](https://github.com/lavec0324/PyBer_Analysis/blob/main/analysis/summary_by_type.PNG)

##### Fare Summary for January 2019 (Jan-Apr)

![](https://github.com/lavec0324/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary

Per the analysis, we can make three business recommendations to reduce disparities among the city types:

  1. Increase the number of drivers in the rural areas
  2. Reduce the price of rides in the rural area
  3. Increase the price of rides in the urban areas
  
Items 1 & 2 would hopefully increase the demand for these types of services.  Item #3 would decrease the demand, bring the prices up and flatten out the demand a bit more.
That demand decrease could be used to increase the demand in the rural area.
