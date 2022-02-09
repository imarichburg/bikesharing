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
The dots on the map show the number of bikes rented at that location.  The size and color help to visualize the bike rental count at each location.  The larger and darker the dots, the more bikes are rented.  Bike rental counts are higher in areas of manhattan that are more densly populated with better sidewalks and more car traffic.  Investors will need to consider the bike path infrastructure in DesMoines since it will have a direct impact on the number of bikes rented according to this map.

#### A breakdown of customer type
<img width="889" alt="Screen Shot 2022-02-08 at 3 58 39 AM" src="https://user-images.githubusercontent.com/37478490/152963755-72dac759-93df-47c7-9b04-c1e128065dea.png">
This pie graph shows that 81% of bike rentals are from suscribers while 19% of bike rentals are from one-time customers.  This is a helpful visualizations because it shows that even in a tourist destination like New York City, the majority of the Citibike revenue comes from local and regular suscribers.  DesMoines is not a major tourist destination but can still have a profitable Bike sharing buisness if this trend holds.  They can find other ways to make up for the possible loss of tourism revenue by finding ways to attract more locals to rent the bikes.

#### A breakdown of customer gender
<img width="889" alt="Screen Shot 2022-02-08 at 4 09 54 AM" src="https://user-images.githubusercontent.com/37478490/152965852-62f7f94d-266b-4288-babd-c7274781db77.png">
The pie chart shows that 65% of customers identify as male, 25% of customers identify as female and 10% of customers identify as unknown.  Significantly more bike rentals come from male customers.  Investors should study gender breakdown in DesMoines when considering a bikesharing buisness.  Investors should also explore ways to increase bike rental in female and uknown customers.  

#### A breakdown of bike utilization
<img width="889" alt="Screen Shot 2022-02-08 at 4 19 33 AM" src="https://user-images.githubusercontent.com/37478490/152967466-3024ebec-75f5-4939-9d44-1f036b5ab070.png">
This circle visualization displays the bike utilization.  Each circle is an indivisual bike showing the number of rides.  This helps to understand how much traffic a bike can have before repairs and replacment are necesary.  Bike maintenance is an important factor to consider when creating a bikesharing buisness.  We can see that the Citibikes can handle up to 479 rides before needing major repair or replacment.



## Summary:
<img width="1070" alt="Screen Shot 2022-02-08 at 4 35 49 AM" src="https://user-images.githubusercontent.com/37478490/152970705-ee7ae548-7d16-4716-8f54-9c161af80e0a.png">
By studying customer data using the Tableau visualizations, we see that bikes are mostly rented during rush hour by local males for transportation to and from work.  

81% of bike rentals are from suscribers and 19% are from one-time customers.  Bike rental times are heaviest during the morning and afternoon commute to and from work.  This shows that most buisiness is generated by local New York City residents that are using bikes to commute to and from work.  The One-time customers most likely result from tourism.  DesMoine is not a major tourist desitination like New York City so they will have to replace the lower revenue expected from tourism.

The total population in New York city and the population broken down by gender can be seen below.
<img width="907" alt="Screen Shot 2022-02-08 at 5 48 00 PM" src="https://user-images.githubusercontent.com/37478490/153095103-01683230-a8c7-4069-9d12-a037af13ef01.png">
48% of New York City residents are male and 52% are female.  However, females only make up 25% of bike rentals for Citi bike.  There is a great amount of revenue growth potential in studying why female ridership is low in New York city.  If the investors in the DesMoine buisiness can solve this issue then they will not have to worry about the portion of buisiness in New York that comes from tourism.  The current female riders could be surveyed to understand their likes and what more they would want.  

The other data we looked at was bike utilization and most popular rental locations.  This helped understand the life span of bikes and when to expect costly repair or replacments.  Bikes in popular destinations can be rotated with bikes from locations with less traffic.  This will balance out the rides per bike to reduce the cost of maintanance and replacement.


