# (Flights Delay Exploration )
## by (Nyaradzo Majari)


## Dataset

> The dataset I used in this analysis is one of the datasets provided by Udacity. It consists information about flights from 1987 to 2020. Because it is a large data set I just took a portion of the data, that is 27 000 records only. The dataset can be found from this link [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7] 

>Replaced the null values in the delay columns.
>Dropped the columns that were not necessary for the analysis.
>Changing the 0.0 and 1.0 to no and yes respectively in Cancelled column.


## Summary of Findings

> In my exploration I found out that day 4 which is Thursday was the most travelled day but the difference with other days is not really signficant. 2007 was the most travelled year, 1987 and 2020 had the least flights. 2020 there was corona virus and too much travelling restrictions. Weather had the highest percent of CancellationCode. The following pairs had strong positive relationships, DepDelay and ArrDelay having the strongest.


> It clearly showed that DepDelay strongly affects ArrDelay, because the pattern of the line on the lineplot is clearly the same in both plots. February had the lowest delays and August had the most delays, respectively. 2007 was greatly affected by DepDelay and ArrDelay followed by 2020. There was a shrp decrease of Depature and Arrival delay from 2019. NASDelay had the highest effect in these following Origin ATL, ORD, DFW, LAX, ATL having the highest count. Over these years DepDelay had the highest effect followed by ArrDelay and sometimes LateAirCraftDelay. It clearly showed that these three had more effects compared to other delays. All these years Weather had been predominant of the flight cancellations followed by Carrier. Security was never an issue of cancellation until 2020 and it was very high and corona virus pandemic might have been the cause.




## Key Insights for Presentation

> My main focus is on the relationships between the delays and what mainly caused the flight cancellations.