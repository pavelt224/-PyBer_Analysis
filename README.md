# PyBer_Analysis
Pyber Analysis Report - Module 5

## Purpose
This is a summary DataFrame of the key metrics for ride-sharing data by city type, with a multiple-line graph showing the total fares for each week by city type. The results of the analysis are presented in the following report.

## Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Python 3.6.9, Anaconda Navigator 1.9.7, Jupyter Notebook 6.0.1

## Overview of the analysis
The goal of this written report is to compile a DataFrame that summarizes ride-sharing data by city type. This report will feature multiple-line graphs of total weekly fares for each city type, created with the Pandas and Matplotlib tools.


## Results
The table below shows a summary of ride-sharing data by city type. For each city type, it displays the average fare per ride and the average fare per driver.

![Pyber_Date](https://user-images.githubusercontent.com/93852380/146655764-27c709fd-7232-469e-ad2f-b0cfbbcb6a03.png)


From January to April 2019, this graph depicts the total fare by city type every week.

![Fig8](https://user-images.githubusercontent.com/93852380/145932760-b4f143b3-f798-4e62-90dd-88d5ae82e4ca.png)


## Summary:
 The ridesharing dataframe summary informs us a few things: 
  There are far more rides in metropolitan areas than in suburban or rural areas. Recomendation: 
  
  * In order to balance the tide beteween  them an option could be to increase time base fare for rural tides. 
  * The number of drivers follows a similar pattern, with more drivers concentrated in urban areas. 
  * The average fare per ride and the average fare per driver are both highest in rural areas and lowest in urban areas. 

This means that as a ride share service expands its driver pool, the cost of rides or fares decreases on average. However, it's worth noting that one essential piece of information is missing: the ride's duration. It's likely that the data is skewed by the length of the route, resulting in an increase in fares, because rural locations may require lengthier rides.


## Challenges and Difficulties Encountered

* Programming The following components of the programming were difficult: chain functions. Anyone conducting this study for the first time might need a quick guide to chain the functions.

* Analyzing data The data analysis was straightforward.

* Graphing, for example The graphing was difficult in the following ways: Object oriented plotting properties and attributes can be accessed. For quick reference, a brief guide or cheat-sheet may be required.

## Recommendations and Next Steps

* I advise the next individual who works on this analysis to avoid utilizing Google to find the information they need for programming. Only a few people can recall all of the code options required for each analysis. Making cheat sheets for such programming tips is also something I encourage.

* Approach Analyzing the distance traveled each ride could add another dimension to the analysis and help to clarify the distinctions between city types even further.

* Technical Procedures Open the notebook file with Python 3.7.6 and Jupyter Notebook 6.0.3, and continue the analysis with PyBer.ipynb. Numpy, scipy.stats, pandas, and matplotlib.pyplot are examples of statistical packages. Merge the distance data into the consolidated dataframe and plot the distances per ride and per city type to compare.

