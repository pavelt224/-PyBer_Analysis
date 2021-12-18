# PyBer_Analysis
UM Bootcamp - Module 5

## Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Python 3.6.9, Anaconda Navigator 1.9.7, Jupyter Notebook 6.0.1

# Overview of the analysis:
The goal of this written report is to compile a DataFrame that summarizes ride-sharing data by city type. This report will feature multiple-line graphs of total weekly fares for each city type, created with the Pandas and Matplotlib tools.



![Fig8](https://user-images.githubusercontent.com/93852380/145932760-b4f143b3-f798-4e62-90dd-88d5ae82e4ca.png)



## Results:
The distinction between rural, urban, and suburban city types may be seen in the graph above. Between the months of January and April, the fare in urban centres is the highest and most consistent. Rural city fares are the cheapest of the three city kinds, and unlike the Urban and Suburban city types, the fares never cross. Despite the fact that the tickets never cross, the Urban fares start at an average of $1,800 and rise to $2,300 as the months pass. The Suburban rates, on the other hand, began at $1,000; however, the pattern was not consistent, since the fare fell in March and even further in mid-April. Rural rates began at $200 and continued to rise and fall until the end of April. One thing the three city types have in common is a fare hike near the end of February.


## Summary:
 The ridesharing dataframe summary informs us a few things: 
  There are far more rides in metropolitan areas than in suburban or rural areas. Recomendation: In order to balance the tide beteween  this an option could be to increase time base fare for rural tides. The number of drivers follows a similar pattern, with more drivers concentrated in urban areas. The average fare per ride and the average fare per driver are both highest in rural areas and lowest in urban areas. This means that as a ride share service expands its driver pool, the cost of rides or fares decreases on average. However, it's worth noting that one essential piece of information is missing: the ride's duration. It's likely that the data is skewed by the length of the route, resulting in an increase in fares, because rural locations may require lengthier rides.
