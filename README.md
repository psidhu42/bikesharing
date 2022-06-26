# NYC Citibike Analysis

## Overview of Project

An analysis of NYC CitiBike data for the month of August.

### Purpose

Using NYC Citibike data from August 2019 and Tableau Public perform an analysis to determine how long the bikes are checked out by all riders and then by gender. Also find the total number of rides and show the busiest hours and days by usertype (Subscribers or Customers) and by gender. The graphs and charts will help determine if a similar business plan would be successful in Des Moines, IA.

## Results of Analysis

To view an interactive page with the charts shown in the following images, click the link below.

[Link to NYC CitiBike Story](https://public.tableau.com/app/profile/pritpal.sidhu/viz/NYC-Citibike-Challenge_16557627335780/CitibikeUseageinNYC)

### August Peak Hours
!["August Peak Hours"](https://github.com/psidhu42/bikesharing/blob/main/resources/01-August-Peak-Hours.png)
This horizontal bar graph shows that the peak hours are aroud 8-9 AM and 5-6 PM, this could be due to work/school morning and evening commute times.

### Busiest Hours by Weekday
!["Busiest Hours by Weekday"](https://github.com/psidhu42/bikesharing/blob/main/resources/02-Trips-by-Weekday-per-Hour.png)
Similar to the bar chart above, this chart also shows the busiest hours of bike use, although here the data is broken down by each day. Monday to Friday shows heavier use during morning and evening hours, where Saturday and Sunday peak hours are focused around midday.

### Trip Duration by Number of Users
!["Trip Duration by Users"](https://github.com/psidhu42/bikesharing/blob/main/resources/03-Checkout-Times-for-Users.png)
This graph shows the duration of rides and the amount of rides that last that long. For example, looking at this graph we can see the peak is roughly 145,000 rides that last for around 5 minutes.

### Busiest Time of Day by Gender
!["Busiest Time of Day by Gender"](https://github.com/psidhu42/bikesharing/blob/main/resources/04-Trips-by-Gender-(Weekday-per-Hour).png)
Here we see the busiest times of day but broken down by gender. Using this chart we can also infer that more men use CitiBikes than women.

### Trip Duration by Gender
!["Trip Duration by Gender"](https://github.com/psidhu42/bikesharing/blob/main/resources/05-Checkout-Times-by-Gender.png)
This line graph shows that although more men ride the bikes, as the trip duration gets longer the number of users declines at a relative rate to the peak users.

### Busiest Days by User Type and Gender
!["Busiest Days by User Type and Gender"](https://github.com/psidhu42/bikesharing/blob/main/resources/06-User-Trips-by-Gender-by-Weekday.png)
More subscribers use the bike service than one time customers, and out of those subscribers there are more males than female riders, the busiest day being Thursday.

### Map of Top Starting Locations
!["Top Starting Locations Map"](https://github.com/psidhu42/bikesharing/blob/main/resources/07-Top-Starting-Locations.png)
Looking at this map we can see that a majority of the top starting locations are in Manhattan south of Central Park. There are a few popular locations the are along the outside edge of Central Park as well.

### Most Popular Destinations
!["Most Popular Destinations"](https://github.com/psidhu42/bikesharing/blob/main/resources/08-Most-Popular-Destination.png)
This circle chart shows the most popular destinations, the larger and more green the circle the popular the location. Using the [interactive chart](https://public.tableau.com/app/profile/pritpal.sidhu/viz/NYC-Citibike-Challenge_16557627335780/CitibikeUseageinNYC) on Tableau Public we can see that "Pershing Square North" is the most popular end point, which is located nearest to Grand Central Station.


## Summary

Using these charts and graphs, firstly it can be determined that the majority of the users are subscribers rather than single use customers. The first two charts give a good indication of the avaerage peak hours and busiest days by hour, form these two it could be said the busiest hours are around 5 to 6 PM with Thursday being the busiest day. Males are the majority users and thus have majority of the ride time within this dataset. One other conclusion that could be drawn from the last two charts is that the majority of the rides take place in southern Manhattan.

Although these charts provide a great deal of visual information, two others come to mind that might be useful in this analysis. The first being a chart or map that could possibly show the most common route taken, from starting to ending point. Another useful chart could be one that shows the most used bikes by ID number, to better help keep all bikes in working order.
