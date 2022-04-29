# Surfs Up

## Overview of Project

### Purpose
The purpose of this project was to explore the temperatures in the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round. We will do this by using SQLlite, Python 3.9.2, Flask, and Jupyter Notebook to explore the hawaii.sqlite data source provided for this.

## Results
•	Summary Statistics for June temperatures.

![June_Temp.png](https://github.com/SZapata4/surfs_up/blob/main/June_Temp.png?raw=true)

•	Summary Statistics for December temperatures.

![Dec_Temp.png](https://github.com/SZapata4/surfs_up/blob/main/Dec_Temp.png?raw=true)

_Differences in Weather Summer and winter in Oahu, Hawaii_

•	The first major difference I see after looking at the above summary statistics is that it is about 4 degrees warmer in June than December on average in Oahu.
•	The second difference I see is that the minimum temperature in June is 8 degrees higher than in December.
•	The last thing that stands out to me in these summary statistics is how large the difference is in number of temperatures taken. In June there were 1700 and in December only 1517.


## Summary

When I look at the fact that there the average temperatures in June and December are approximately 74 and 71 degrees, I believe those typ of temperatures can sustain a surf and ice cream shop business is sustainable year-round. Also, when looking at the percentile temperatures and see that the lowest number there is 69 degrees further encourages me to agree with my assessment above.

However, I do have 2 things I would look further into before officially starting this venture.

1.	I would run a query to groupby stations to see which station has the warmest temperatures during June and December and then consider building the shop near that station
2.	I would also run a query to find the number of days there are under the temperature that W. Avy deems too cold for ice cream or surf. This will give you us an idea of how many slow days to expect in the months of June and December. This will give you a data point to extrapolate over summer and winter months.

