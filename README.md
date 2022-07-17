# PyBer Analysis

## Overview 
Working with an existing client PyBer to provide additional data analysis to their ride share program of three city types (Urban, Suburban, Rural).  The additional analysis requested was to present a line graph showing total weekly fares for each of the afore mentioned city types.  As well as how the new data gathered differes by city type and how those differences can be used by decision-makers at PyBer.

## Resources
- Jupyter Notebook
- pandas
- matplot lib libraries
- client provided .csv files

## Results
Working with the two .csv files I merged datasets based on the city columns which was the only value in both data sets.  This resulted in a new combined data set, which allowed me to complete my analysis.  The first aspect which stood out was there are drastically fewer drivers in rural cities, as compared to urban cities.  I also noted that the average fare per ride in Urban cities was approx $10 more then then that of the average ride of Urban Cities.  Lastly I noted that the average fare per driver was $55.49 in Rural cities, and only $16.57 in Urban cities.  In looking at the total riders and drivers, one can see that if the total riders is greater then total riders then the average fare per driver will be increased (less drivers + more riders = higher fare per driver overall), where as if the total riders was less then total drivers, then the average fare per driver will be decreased (more drivers + less riders = lower fare per driver overall.

- Put simply, if you have a surpluss of riders to drivers then the drivers make more in fare as there is less competition with other drivers.

<img width="700" alt="PyBer Summary DataFrame" src="https://user-images.githubusercontent.com/104927745/179375233-133c4887-b4e9-45b1-a070-96447ae50f0e.PNG">

Next I creded a multipleline plot which would show the client the total weekly value of the fares for each type of city (Urban, Suburban, Rural).  
- This plot showed that there are drastically higher total fares in Urban cities as compared to Suburban and lastly to Rural.
- Most of PyBer's total fares and revenue is being gained from Urban cities.

<img width="700" alt="Total Fare by City Type" src="https://user-images.githubusercontent.com/104927745/179375173-52907ba4-186d-441a-8e84-3858578326e7.PNG">

## Summary
While the data showed that Urban cities had the greatest revenue in Total Fares per Driver, it was the city type with the least profitibility per driver (and as such PyBer).  Where as Rural cities has the least revenue in Total Fares per Driver, but the highest profitibility per driver.  My recommendations to PyBer would be to look to the ratio of drivers to riders in Urban cities, specifically decreasing the number of drivers.  In Urban cities there were 2,405 drivers and only 1,625 riders, meaning that many drivers did not complete at least one ride.  Reducing the number of drivers in Urban cities will increase the average fare per driver (and revenue for PyBer).  Lastly, I would recomend PyBer to conduct additional analysis of ride duration and what the average fare per shorter amount of time (such as per mile), and compare that among the city types.  This could show that Rural drivers are making more per mile then that of their Urban counterparts, allowing PyBer to update their fare appropriately for more profitabilitly.
