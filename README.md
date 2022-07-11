# PyBer_Analysis

## Overview of the analysis:

The goal of this project is to take the ride-sharing data from the months of January to early May of 2019 found previously, a step farther by creating a multiple-line graph. In the original project we analyzed the ride count, average fare per ride, and average number of drivers, all categorized by the type of city. Additionally, we compared each city's metrics and the average ride fare to the total number of rides per city. In this new project, the graph displays the total weekly fares for each city type: urban, suburban, and rural and is done so by using Pandas and Matplotlib to create an easy to read representation of the summary data frame for the Pyber company.

## Results:

In the summary data frame there is a trend between the population of the city and the total number of rides. This in and of itself, directly affects the total fare, the number of drivers, and the averages of the two. The total number of fares, drivers, and rides decrease as the cities move from urban to suburban and rural. Following this trend however, it is interesting to note that the average of both the drivers and fares increases as we move outward towards rural cities. This happens because the amount of Pyber rides and drivers that are available decreases when moving towards rural areas. With less drivers available, it is easy to find the corrilation between increased pricing and lack of demand. 

![pyber_results](https://user-images.githubusercontent.com/106495685/178185666-933a9142-99e2-4de5-9799-8840a9906c9b.PNG)

The multiple-line chart allows us to compare the total fares by city type over the five month period (January to May). When viewing, it is easy to the increase and peak in the number of rides towards the latter part of February. Each line seems to follow a trend of peaking in February and having some fluctuation in March. The only line that deviates from the pattern is suburban cities, where there is an increase in April that is not seen in urban and rural.

![PyBer_fare_summary](https://user-images.githubusercontent.com/106495685/178185349-801a968b-e046-4647-8abe-987c64306925.png)

## Summary: 

The average fare per ride shows that there is an increase from urban to rural cities and in the same fashion, the average fare per drive increases significantly. This may suggest a lack in drivers in smaller cities and to optimize a profit, it would be a good idea for the company to consider increasing driver to rural city ratios.

Also, in the multiple-line chart, there is an odd spike in the suburban city line that does not occur in the other two catagories. With that in mind, it would be wise to fine what caused the spike.

Finally, the average fare per ride and per driver shows us that there increase in price when there is a smaller number of drivers. Following this trend, the company could potentially influence the pricings by adjusting the number of drivers in a certain time or place to increase profits.
