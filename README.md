# Flights-Exercises
## In this code, data from flights.csv, airlines.csv, and airports.csv is imported, and using Spark SQL, departure delays are analyzed, along with the number of airports by U.S. state, displayed on a choropleth map. A daily flight and delay summary is also created, followed by bar and pie charts showing flight counts per airline.
### Assignment from SGH
Find out which airports when treated as Origin have the smallest and the largest Departure delays.
Create a list of U.S. States with the number of airports that each of them has in descending order. Show this on a map of the U.S. (Hint: Use: a choropleth map. States are listed as USPS Abbreviations)
Create a list containing: DATE, NUM_OF_FLIGHTS, MAX_ARRIVAL_DELAY, AVG_ARRIVAL_DELAY. Please provide the date (from FlightDate) in the following format i.e. 2018-01-10. The maximum and Average delays should be provided in minutes but rounded to 2 digits after the decimal point.
Show on a bar chart the number of flights per Carrier. Use the full name of the airline (from airlines.csv).
Show on a pie chart the number of flights per Carrier but this time only show the individual results for the top 10 Carriers (measured by number of flights) and the rest show as one OTHER element. This will probably require the use of Temporary Views (Create or Replace Temporary View new_view as Select * from XXX). If it is done correctly OTHER should account for 16% of all flights.
