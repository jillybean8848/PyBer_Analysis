# PyBer_Analysis

## Overview
The primary goal of this analysis was to provide ridesharing data visualizations for PyBer in order gain access to ride-sharing services and determine affordability for underprivileged neighborhoods.

The study is based on the data provided in a CSV file from PyBer. The data has been processed using Python Pandas in Visual Studio Code in order to produce dataframes and a chart generated to visualize the data.

## Results

Once we merged the two data sets and used the groupby() function, the fare per ride and fare per driver averages were calculated and we wer able to show the summary DataFrame by city type.

![Pyber Summary DF](https://user-images.githubusercontent.com/110632671/191178712-c2b6c07c-8596-4f25-af86-ab52bd61411d.png)

This dataframe easily shows that urban cities had more total drivers than total rides which results in a direct impact on the average fare per ride and average fare per driver. Urban cities showed the lowest average fare per ride and earned significantly less than rural cities.

Alternatively, rural cities had the lowest number of total drivers which resulted in the highest average fare per driver. Even with the ratio of total rides to total drivers being equivalent to the suburban cities. 

Therefore, we can draw the conclusion that the number of drivers compared to the number of total rides has a significant impact on the average fare per driver overall. 

A multiline chart was also created in this analysis to help visualize the Total Fares from January 1, 2019 to April 29th, 2019 for each of the city types.

![total fare by city type](https://user-images.githubusercontent.com/110632671/191181509-6b1c611b-a34f-48e0-ba01-b00ca82dc882.png)

This chart visualizes the total fare for each of the ciy types during the months of January through April of 2019. We can easily see that Urban city types had the highest total fares during this time frame and rural areas showed the lowest. It also shows us that during the third week of February there was an increased demand for rides because of the high total fares for each of the city types at that time. Urban cities aslo seem to bring a lot of revenue in the first and third week of March. Also at the beginning of January and at the end of April all Fares for each city type showed some decline.

## Summary

The results of this analysis shows that the number of drivers versus the number of rides has a direct impact on the average fare. However, Urban city types have more people within a smaller area which results in a lower average fare per ride. Whereas, Rural city types are more spread out meaning they have fewer drivers compared to rides which would collect a higher average fare per ride but this could also be due to distance per ride. To further test this theory, PyBer should complete another analysis that would include distance as part of the data analysis.

Pyber executives may want to increase fares on shorter rides to help combat this issue. Alternatively, they could also hire fewer drivers in cities that are oversaturated. 
