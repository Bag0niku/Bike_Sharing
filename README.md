# Bike_Sharing

## Purpose 
Client has requested Tableau visualizations of NYC CitiBike bikeshare trip data to pitch to investors on a similar product for Des Moines, Iowa. 

### Resources:
 - Tableau Public
 - NYC CitiBike August 2019 <a href="https://s3.amazonaws.com/tripdata/index.html"> Rideshare Data</a>.

## Deliverables 
 - Convert trip duration data to a datetime format with Python.
 - Atleast 7 graphs 
 - Create a Tableau Story for presentation.

## What is the idea?


## Presentation
- An interactive Tableau Story Board is available to play with and filter yourself on the <a href="https://public.tableau.com/app/profile/nick.patterson4200/viz/BikeSharinginNewYork/Story1?publish=yes">Tableau Public</a> Hosting service.

- The Dashbords are able to be filtered by Usertype, Gender and Week by clicking on the designated colored square.

## Summary 
CitiBike is a bicycle renting service powered by Lyft with stations throughout the city of New York. I'd like to start by defining a few terms first:
- Gender is broken into Male, Female, and Unknown because in addition to the people with non-binary genders that make up most of the category, there are people that refuse to answer the question. 
- CitiBike classifies their users into one of 2 categories: Annual Subscribers (Subscriber) and Everyone else (Customer). Subscribers are mostly commuters while Customers are casual riders, tourists, and new riders.
 
![](/Images/Who.png)

- With an inventory of 24,00+ bicycles and 1,500+ stations, 13,983 bicycles and 807 bike stations were active during the month of August 2019.
- 2,344,224 Rides dring the month of August 2019 with a total ride time of 41,030,675 minutes, equivalent to 78 years if you were to measure it as one continuous stream.

![](/Images/When.png)

- The most common riders during the month of Augaust 2019 were male subscribers during "rush hour" for an average ride time of 15 to 20 minutes.
- The best time of day to shuffle bikes around optimizing utilization will be Midnight to 5am.
- There are stations in 4 of the 5 buroughs but the ones in Manhattan are the most popular.

![](/Images/Where.png)

![](/Images/What.png)

- Bicycle maintenece will need performed most on the bicycles with a high ride count or High total ride time. Retrieving those bikes can be accomplished as apart of the nightly rotation of bicylces that need to change stations for best utilization.

![](/Images/How.png)

# Recommended Improvements to the Analysis
- Add the ability to filter the stations by burough/neighborhood.
- Find the typical radius a bicycle travels, do they tend to stay in their initial neighborhoods or traverse the borders?

Additional Data required to:
- Compare station locations with bus and train stops/routes.
- Compare station location and popularity to surrounding business types.
- Compare cost of living and incomes to ridership in neighborhoods and stations.
- Use more than one month, use the data for a financial quarter or a year. How does this affect the analysis?


# References:
 - Ride Sharing Data from <a href="https://ride.citibikenyc.com/homepage">CitiBike</a>'s historical data (August 2019), which they store <a href="https://s3.amazonaws.com/tripdata/index.html">here</a>.
