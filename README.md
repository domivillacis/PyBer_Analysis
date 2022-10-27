# PyBer Analysis

## Overview of the analysis 

In my second week as a data analyst at PyBer, I’ve been assigned by the CEO of the company to collaborate with the Ridesharing Data Analytics Project from January to May 2019 and I will do it together with my manager Omar.

The main idea of this analysis is to be able to offer recommendations to our CEO on how to improve service and fares in underserved areas; this will not only benefit PyBer users but also its drivers.

To achieve this analysis, we have received two very large csv files that we’re going to merge and finally create a chart that will help us visualise the results.

Let’s dive in!

## Results

The first part of our analysis is based on total rides, drivers, and fares for each type of city, such as: urban, suburban and rural, and the average fare per ride and per driver.

![](totals.png)

As we can see, rural cities have 10-13 times fewer drivers, rides and therefore the total amount of fares is also too low compared to urban and suburban cities.

With this information, our conclusion is that when the total of riders exceeds the total of drivers the fare per ride and per driver increase.  When the total of drivers exceeds the total of riders the fare per ride and per driver decrease. 

An important comment is that this affects the drivers more than the riders (larger drop in $).

We’re now going to analyse the total weekly of the fares for each type of city.

![](weekly.png)

We must understand that the fares will always change and this is due to supply and demand. However, based on our chart, fares were lower in suburban cities from March to April, this may be due to the increase in drivers. In the case of rural cities, it can be seen that the rates are usually higher for the user due to the lack of drivers.
## Summary

![](chart.png)

The success of a multi-sided platform business model such as Pyber depends heavily on the interaction between both the drivers and the riders.
The results in the table show clearly that: The average fare per ride and driver depends on the supply and demand of drivers and riders. 

Obviously, keeping the fare price down attracts more riders to the app, but in order for that situation to occur you need a high supply of drivers using the app, but drivers will be attracted to the app if the fare price per driver is high. This is the dependency mentioned above.

Another important take away is that the situation where the supply of drivers exceeds the riders is in urban areas.
In rural and suburban areas, the numbers of riders exceed the drivers. 

A recommendation for our CEO is to be aware of this that the current situation can lead to a drop of drivers since their average fare is relatively low. 
On the other hand, we also recommend our CEO to be aware that she can expect a drop of riders in rural and suburban areas because the average fare is relatively high.

### Resources
Data Source: city_data.csv, rie_data.csv

Software: Jupyter Notebook 

Chart: Matplotlib

