# PyBer Analysis
## Overview
### Description:
V. Isualize has tasked myself and a colleague on creating a summary of the ride-share data. We are to create multiple line graphs that shows the total weekly fares per each city type. 

### Purpose:
My job is to clean up the data and place into readable graphs and statistic sheets. 

### Situation
We want to identify what city type performse best at what fare rate. We want to know what are the differences between Urban, Suburban and Rural citiy types. We will be looking at fare cost, how many riders per city type and how many drivers we have in each city type.

### Approach:
We will be looking at 3 different city types: Rural, Suburban and urban. In this exercise, we will be using Matplotlib, Pandas and Python in order to clean the data to look at the statistics.

## Analysis and Results
### Outcomes
In our data analysis, we have noticed that that there is an inverse correlation between size of city to cost of fare. With  more drivers available, cost of fares seems to be lower. As indicated in the following figure, we can identify that Urban city types will have more rides and drivers with a lower average cost per ride. We can also see that with Rural city types will have the least amount of drivers and will have the highest average fare per driver.

For the amount of drivers per city type, Urban has the most drivers by far with 2,405, followed by Suburban at 490, and Rural with onlu 78 drivers. 
The total number of rides done in Urban (1625) has 2.6X more rides more than Suburban(625), and 13 times more than Rural(125).
We can see that the average cost of fare for a ride is lower in the Urban setting, costing an average of $24.53 per ride and $16.57 for the driver. With this, we note that the total fares gained was $39,854.38, which is 2.05x more than Suburban. Suburban had an average cost of $30.97 per ride and a $39.50 per driver, which would be a 1.26x increase in cost per ride and 2.38x more per driver. At the most expensive side, Rural costs $34.62 on average per ride and the driver's fare is $55.49 on average. 

Figure 1:
![Totals](https://github.com/benlew3/PyBer_Analysis/blob/main/img/overall%20statistics.PNG)

### Analysis
![fare chart](https://github.com/benlew3/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)

On this chart, we are able to see the general cost of fares though a timeline from January 2019 to May 2019. We can see that on average, the Urban city type will generate more fare revenue that either Suburban or Rural. 


## Summary
From our findings, these would be my business recommendations:

1. We may want to consider a reduction in drivers for the Urban setting. We were shown that in the span from January to May 2019 that there were only 1625 riders for the 2405 drivers. Creating a more balanced rider to driver ratio can help improve average fare per driver. 

2. We see that Rural drivers generate the most fare per ride. If we were to capitalize on that market, we may be able to improve revenue. Further research into that market may be warrented. We would want to identify what the costs are per driver, time driving, and available market for riders.

3. In March, we notice that the Urban city type has a volitile month and starts to dip down before going into April, where as Suburban and Rural remain flat. We may want to see why March creates a rough patch for Urban settings and see how we can lower the volitility and improve our fare rates.
