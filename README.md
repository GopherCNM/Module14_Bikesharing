# NY Citi Bike with Tableau

## Overview of the project

In this project, I’ve used Tableau to visualize Citi Bike data from New York City, using CSV data available on the Citi Bike System Data page. Using the August 2019 dataset, I’ve visualized ride count and usage data, trip duration and time-of-day trends, and insights on customers who used the service. These understandings will be leveraged to better understand the bike-sharing business, and to make a pitch for possible expansion into other cities, such as Des Moines, IA.  

## Results

After building some visualizations in Tableau worksheets, and consolidating these into a few dashboards, I created a Tableau story to help summarize my findings.  

The full Tableau workbook (Module14_Challenge) can be found at my [Tableau Public profile]( https://public.tableau.com/app/profile/bryce.hutchins).  

**1. Citi Bikes are popular in New York City!**  

In the month of August 2019, there were more than 2.3 million Citi Bike rides in New York City. My Tableau visualizations indicated that these rides were concentrated in Manhattan, with usage also sprinkled across the Brooklyn and Queens boroughs.  
![Citi story 1](/Screenshots/Story1.PNG)  

**2. Usage patterns follow traditional work schedules.**  

I used heat maps to understand when Citi Bikes were used throughout the week and throughout the day. These indicated that rides most commonly took place during work commute times, such as 8 AM and 5-6 PM from Monday through Friday. Usage on the weekends was spread evenly across the day, from around 10 AM to 6 PM. These trends held consistent across genders. The heat map also shows that males are heavier users of Citi Bikes. Based on these findings, I suspect that much of the Citi Bike usage in NYC is related to commuting. Weekend usage is more even and spread through the day, so more likely related to leisure, sightseeing, and errands.  
![Citi story 2](/Screenshots/Story2.PNG)  

**3. Most trips are short in duration.**  

I used continuous line graphs to understand trip duration, in total and by gender. This revealed that most rides were under 30 minutes in length. In fact, the peak where most rides occurred were around 5 minutes in length. This also adds support to the idea that much of Citi Bike’s rider base uses the service for work commutes within the city. I would suspect sightseeing and leisure rides would be longer than 5 minutes. There weren’t any significant differences between males and females in terms of ride duration.  
![Citi story 3](/Screenshots/Story3.PNG)  

**4. 81% of customers are subscribers.**  

I plotted user types on a pie chart and found that 81% of rides in the month were by service subscribers, as opposed to “one-time” customers. Further, I created a heat map to show usage by day of the week, customer type, and gender. This again showed that most Citi Bike riders are male subscribers, and with usage spread across the week. As seen in the other heat maps, the heaviest periods of usage took place during the work week.  
![Citi story 4](/Screenshots/Story4.PNG)  

## Summary

My visualizations for the NYC Citi Bike dataset indicated that much of the program’s usage takes place during traditional work commute times with durations of short length. This is a testament to NYC, and the ability of people to live close to where they work. Success for future program expansion, including cities such as Des Moines, IA, is dependent on the layout of the city. Do people live close to where they work? Are there stores to carry out weekend errands in close proximity? Are there sights to see and leisure to be had on the weekends? Does the city have bike lanes or other dedicated paths to keep bikers and pedestrians safe? These are all important considerations.  

It would be interesting to see a few other visualizations on the given dataset. Other possibilities could include:  
- Ride duration on weekends vs weekdays. Our chart showed that most rides were around 5 minutes long, but much of this was probably weighted by weekday commuting. Seeing some segmentation specific to weekends might give some indication on how the bikes are being used on those days.  
- It would also be interesting to dig deeper on starting and ending locations to understand average distance of each ride, and any discernable trends.  
- I would also like to dig into the most heavily used station locations, and overlay landmarks or points of interest, to understand what might drive high usage.
