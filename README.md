# bikesharing
Create Bike-sharing proposal using Tableau

The Citibike sharing program has been successful in New York City.  It provides an affordable and healthy transportation alternative that aligns with the cities goals of improving the enviornment.  The buisiness has been profitable in New York city.  A group of investors would like to study the buisness to understand how to recreate a similar buisness in Des Moine Iowa.  Tableau is used for data analysis and visualization to help the investors better understand how to the success of the Citi bike sharing buisness in New York city could be translated to the Des Moine market.

## Overview of the statistical analysis:

<img width="1007" alt="Screen Shot 2022-02-06 at 6 42 01 PM" src="https://user-images.githubusercontent.com/37478490/152708962-743d2774-78cc-4cf8-a47f-1d22417ffe91.png">

### Deliverable 1: 

Python was used to import the tripdata into a Pandas dataframe to enable conversion of datetime datatype.

<img width="1043" alt="Screen Shot 2022-02-06 at 6 52 30 PM" src="https://user-images.githubusercontent.com/37478490/152709432-78a8f11b-7712-4a46-bccd-4da4885e9ce9.png">

Trip duration was orignally stored as in64 in seconds.  A new column was added to the dataframe with the trip duration converted to a datatime format.

<img width="1043" alt="Screen Shot 2022-02-06 at 6 57 08 PM" src="https://user-images.githubusercontent.com/37478490/152709585-a05c214d-3767-4d95-a865-88bbeb640036.png">

The dataframe was exported to a CSV file entitled "201908-citibike-tripdata_New.csv

### Deliverable 2: 


#### How long bikes are checked out for all riders and genders?
<img width="889" alt="Screen Shot 2022-02-08 at 3 09 12 AM" src="https://user-images.githubusercontent.com/37478490/152954765-de099e84-1bfa-4d4d-8957-586658ecc12e.png">
This graph shows how long bikes were checked out for all riders broken down by gender.  The most common trip duration for men is 5 minutes.  The most common trip duration for women was 6 minutes and the most common trip duration for unknown gender was 11 minutes.  We can also see that customers who identify as men rent significantly more bikes than those who identify as women or unknown.


#### How many trips are taken by the hour for each day of the week, for all riders and genders?
<img width="889" alt="Screen Shot 2022-02-08 at 3 21 56 AM" src="https://user-images.githubusercontent.com/37478490/152956731-86ae212a-2318-4467-a952-473d00b17f9d.png">
The heat map shows how many bikes were checked out each hour of each weekday broken down by gender.  The darker blue indicates more bike rentals.  Morning rush hour (6-9am) and afternoon rush hour (4-7pm) have increased bike rentals.  The highest bike rental count occurs by males on Thursday during afternoon rush hour.  Bike rentals are more evenly distributed throughout the day.


#### A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.
<img width="889" alt="Screen Shot 2022-02-08 at 3 32 59 AM" src="https://user-images.githubusercontent.com/37478490/152958772-4942a8e6-bfe2-47ee-ab28-1fd112478648.png">
The heat map shows how many bikes were checked bout each day of the week broken down by user type and by gender.  Suscribers rent significantly more bikes then one-time customers.  Suscribers who identify as male and female rent significantly more bikes than customers who identify as male or female.  However, customers who identify as unknow rent more bikes than suscribers who identify as unknow.  Again we can see that the highest bike rental occurs on Thursday by male suscribers.

#### A breakdown of most popular bike rental locations
<img width="889" alt="Screen Shot 2022-02-08 at 3 45 59 AM" src="https://user-images.githubusercontent.com/37478490/152961248-722692c5-2faa-4bd8-8069-6fbda88dbf9b.png">
This dots on the map show the number of bikes rented at that location.  The size and color help to visualize the bike rental count at each location.  The larger and darker the dots, the more bikes are rented.  Bike rental counts are higher in areas of manhattan that are more densly populated with better sidewalks and more car traffic.  Investors will need to consider the bike path infrastructure in DesMoines since it will have a direct impact on the number of bikes rented according to this map.

#### A breakdown of customer type
<img width="889" alt="Screen Shot 2022-02-08 at 3 58 39 AM" src="https://user-images.githubusercontent.com/37478490/152963755-72dac759-93df-47c7-9b04-c1e128065dea.png">
This pie graph shows that 81% of bike rentals are from suscribers while 19% of bike rentals are from one-time customers.  This is a helpful visualizations because it shows that even in a tourist destination like New York City, the majority of the Citibike revenue comes from local and regular suscribers.  DesMoines is not a major tourist destination but can still have a profitable Bike sharing buisness if this trend holds.

#### A breakdown of customer gender
<img width="889" alt="Screen Shot 2022-02-08 at 4 09 54 AM" src="https://user-images.githubusercontent.com/37478490/152965852-62f7f94d-266b-4288-babd-c7274781db77.png">
The pie chart shows that 65% of customers identify as male, 25% of customers identify as female and 10% of customers identify as unknown.  Significantly more bike rentals come from male customers.  Investors should study gender breakdown in DesMoines when considering a bikesharing buisness.  Investors should also explore ways to increase bike rental in female and uknown customers.  

#### A breakdown of bike utilization
<img width="889" alt="Screen Shot 2022-02-08 at 4 19 33 AM" src="https://user-images.githubusercontent.com/37478490/152967466-3024ebec-75f5-4939-9d44-1f036b5ab070.png">
This circle visualization displays the bike utilization.  Each circle is an indivisual bike showing the number of rides.  This helps to understand how much traffic a bike can have before repairs and replacment are necesary.  Bike maintenance is an important factor to consider when creating a bikesharing buisness.  We can see that the Citibikes can handle up to 479 rides before needing major repair or replacment.



## Summary:
<img width="1070" alt="Screen Shot 2022-02-08 at 4 35 49 AM" src="https://user-images.githubusercontent.com/37478490/152970705-ee7ae548-7d16-4716-8f54-9c161af80e0a.png">

By studying customer data using the Tableau visualizations, we see that bikes are mostly rented during rush hour by local males for transportation to and from work.  

