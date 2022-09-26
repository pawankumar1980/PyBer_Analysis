# PyBer_Analysis

Pyber with Matplotlib

## **Background**

After completing a successful exploratory analysis for PyBer, a ride-sharing business, the CEO asked the Manager and me to deep dive into the data to understand ridership and fare metrics by the types of cities in which Pyber operates. The scope of work includes using Python, Pandas, and Matplotlb to create a summary DataFrame and a multi-line graph of the total weekly fares for each city type.

## **Results**

### **Summary DataFrame**

The two data frames were merged, and the groupby() function was used to calculate the total number of rides, drivers, and fares for each city type. In addition, the average fare per ride and fare per driver for each city was calculated. In addition, the average fare per ride and fare per driver for each city was calculated. Finally, this data was added to a summary data frame.

<img width="468" alt="Deliverable 1" src="https://user-images.githubusercontent.com/111800568/192164554-97983dc8-12b5-4d98-aaa0-01ed90b90aa6.png">


-  Urban cities have the highest ridership demand, while rural cities have the least. They had 4X+ more drivers than Suburban cities. There are more drivers than rides in urban cities, and shorter travel distances mean both average fare per driver and average fare per ride are on the lower side.
-  Rural cities had the least number of drivers and, as a result, had the average fare per driver even though the ratio of total rides to total drivers is equivalent to the Suburban city type.



### **Multiple line Chart**

The data was grouped into a new dataframe and then grouped by weeks to show the rleation between total fares and the different city types.


![PyBer_fare_summary](https://user-images.githubusercontent.com/111800568/192178643-631d1129-f975-414b-8a69-76ef24acb148.png)



- The fares across the different city types peaked by the end of February. From March-April, the fares kept oscillating, reaching Feb end levels in the case of Urban and Rural cities. Post-April, the fares in Urban and Rural cities dropped while they increased in Semi-urban cities.


