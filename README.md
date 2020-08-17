# PyBer_Analysis
## Overview
The CEO of Pyber has given us a dataset of rideshare data for the year 2019 and wants us to create a summary DataFrame of the ride sharing data by city type. We will submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Results
![image](https://user-images.githubusercontent.com/67936161/90367153-41c00c80-e01d-11ea-9194-9acf01c23eb2.png)

* The image above is the summary of the 2019 ride sharing data for each city type:
    1. Total Rides - Urban cities had the highest amount of rides for the year.  The amount of rides was 13x and 2.5x higher than rural cities and suburban cites respectively.
    2. Total Drivers - Urban cities had the highest amount of drivers for the year. The amount of drivers was 30x and 5x higher than rural cities and suburban cites respectively.
    3. Total Fares - Urban cities had the highest amount of total fares for the year. Urban cities collected 9x and 2x more in fares than rural cities and suburban cites respectively.
    4. Average Fare Per Ride - Urban cities had the lowest average fare per ride for the year. Urban cities' average fare per ride was about $10.00 and $6.00 less than rural cities and suburban cites respectively. It looks like the higher the supply of drivers brings down the average fare per ride. 
    5. Average Fare Per Driver - Urban cities had the lowest average fare per driver for the year. Urban cities' average fare per driver was about $39.00 and $23.00 less than rural cities and suburban cites respectively. It looks like the higher the supply of drivers brings down the average fare per driver. 

* Overall Urban cities had the best performance overall, based on the metrics above. The trend seems to be as the number of drivers increase the number of rides increases as well. In turn as the number of rides increase the total fares increases, average fare per ride decreases, and average fare per dirver decreases.

![image](https://user-images.githubusercontent.com/67936161/90368978-ca3fac80-e01f-11ea-9daf-ee327dc10b9a.png)

* The image above is a more indepth look at the total fares by city type from January 2019 to May 2019
    1. The data shows that the amount of fares collected by each city from January 2019 to May 2019 is pretty uniform and doesnt change too much over that period of time.
    2. We can see peaks of total fares collected for each city type towards the end of February.
    3. The total amount in fares drop dramatically for all city types going into May.

* Overall the total amount of fares collected between January 2019 to May 2019 does not fluctuate too much for each city type. However, it does appear that the end of February is when the most fares were collected for each city type. 

## Summary
* Business recommendations based on the results of the analysis:
    1. Because we see that having more drivers correlates to a more successful business I would recommend implenting that same model to rural and urban cities in order to boost ouput from those city types. The higher the supply of drivers could bring the average fare per ride & driver which could entice consumers to use ride sharing services more. 
    2. Ride sharing services are particulary successful in urban cities so you should look to increase production in those types of cities.
    3. If you want to reduce cost you could do away with ride sharing services in rural cities all together and shift the focus towards suburban and urban cities. Urban and suburban cities are consistant performers and increasing focus on those city types could yield higher rewards.