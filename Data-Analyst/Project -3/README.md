# Flight Exploratory Data Analysis
## by Olawale Olushola


## Dataset

> This project investigates a dataset that reports flights in the United States from January 2007 to April 2008, including departure delays, and reasons for delays. So, a flight is also considered delayed if its arrival time is more than 15 minutes late.
The following are the sources of the data gathered:

- http://stat-computing.org/dataexpo/2009/the-data.html

The dataset for flight details contains approximately 4.6 million rows with 29 features.
The variables in the dataset include information about the origin, departure, date and time of the flight, duration, cancellation status, delay (and cause of delay), and so on.

## Data Wrangling
> We took the following steps in the wrangling process:
- combined the 2007 and 2008 data into a single csv file.
- Some variables, such as ArrTime and DepTime, were converted from hh:mm to datetime (min) format.
- Unnecessary columns were removed.
- Duplicate values were removed.

## Summary of Findings

> Among the data exploration findings are:
Carrier causes are the most common reason for flight cancellations, followed by weather and security.
The ACK (Nantucket) airport has the most departure and arrival delays.
ATL is the busiest airport, with a 26.7% flight delay.
Meanwhile, EWR has the highest proportion of delayed flights at approximately 32.2%.
Arrival and departure delays have a high correlation, which is to be expected.

## Key Insights for Presentation

> -The majority of flights were canceled due to Carrier and Weather reasons while Security concerns account for a negligible proportion of cancelled flights.
-The maximum average delay of approximately 21mins is also attributed to late arrival of the aircraft.

