# Flight Data Exploration

## Dataset 

The data contains information for approx 7 million American based flights, for American airlines in 2008. The dataset includes flight delay information, as well as many other factors such as air time, origin, destination, delay types, etc. The csv file used as my dataset can be found here (click the 2008 link at the top): 

http://stat-computing.org/dataexpo/2009/the-data.html

**Note: I've renamed the dataset to flight_data.csv (this is imported into my jupyter notebooks) but have not made any changes to the dataset at the csv level, so the code should also run by downloading the 2008 file at the link above. 

## Summary of Findings

In the exploration, I found that the distributions of the arrival delays and departure delays differed. I also found that no delayed flights resulted in a cancelled flight. This must mean the flight delay is not recorded if the flight is eventually cancelled. Of the total dataset, can see that only 1.96 percent of flights were cancelled. 

I observed some interesting relationships between frequency and length of delays and factors such as the carrier, cause of delay, airtime, departure times, distance, destination and origin of the flights. Through this analysis it became obvious which airports and airlines are notorious for delays. I also investigated relationships between delays and the time of year (month) and day of the week. 

I was surprised to see that the majority of delays occured in February and April. February is not outrageous, but I would have expected more delays to happen during another winter month other than April. 

## Key Insights for Presentation

For my presentation, I focused on my analysis of originating and destination airports. I found that the worst airports to fly in and out of are Orlando and Atlanta in terms of delays. There were also clear carriers that should be avoided. 

The most common source of delays was found to be late aircraft delays by ten-fold, while the longest delays are attributed to carrier delays. 

In terms of frequency and duration of delays, the airlines to avoid are United Airlines, American Airlines and Southwest Airlines. 