# PyBer_Analysis
*Analyzing ride share data*

## 1. Overview of Analysis
I have been asked to arrange the PyBer ride share data from a region that includes rural, suburban, and urban areas into a summary DataFrame that allows for an at-a-glance understanding of how rides and fares differ among the three types of areas (that is, "city types"). I have also been asked to create a three-line chart to illustrate total weekly fares for each city type during a particular range of dates, and to give some recommendations.

## 2. Results
There are stark differences among the three city types when it comes to how many rides were taken, how many drivers are available, and in the total amount of fares that were collected. Far more drivers are available in urban areas than in rural, and far more rides were taken in urban areas. But a look at the summary DataFrame ...
![PyBer_deliv_1_Summary_DataFrame.png](https://github.com/JGGall/PyBer_Analysis/blob/main/Resources/PyBer_deliv_1_Summary_DataFrame.png)

... reveals that in rural areas the average ride had a fare that was 41% higher than the average fare in urban areas. In suburban areas, the average fare was 26% higher than in urban areas. Rural areas had only 3% of the drivers of urban areas, but the average rural fare was 335% of the average urban fare--in other words, the average rural fare was more than triple the dollar amount of the average urban fare.

I was also asked to create a three-line chart in "fivethirtyeight" style that plots the sum of the fares per week for a five-month period in each city type: rural, suburban, and urban.
![Fig8.png](https://github.com/JGGall/PyBer_Analysis/blob/main/analysis/Fig8.png)

This chart clearly shows the much higher fare revenue of urban areas when compared to suburban areas (which lie in the middle) and rural areas (with the lowest weekly revenue). The three lines plot the rise and decline of weekly revenue over time. The three lines, while situated at different levels representing different fare revenue, are not wildly divergent: they rise and fall together, probably based on weather and holidays and special events that attract people from all three city types in the region.

## 3. Summary
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
