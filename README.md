# Tableau 

 

Citi Bike is New York City's largest bike sharing system. This Assignment is about the network of bicycle rental
 stations intended for point-to-point transportation.

# The Data 

Citi published Citi Bike Trip Histories - downloadable files of Citi Bike trip data. I used the Citi Bike data 
for the whole year of 2017 (approximately 1 million observations). The data includes:

## Trip Duration (in seconds)
# Start Time and Date
# Stop Time and Date
Start Station Name
End Station Name
Station ID
Station Lat/Long
Bike ID
User Type (Customer = 24-hour pass or 7-day pass user; Subscriber = Annual Member)
Gender (Zero=unknown; 1=male; 2=female)
Year of Birth

I end up marging all the data file for each months of 2017 and cleaned the null data before using in the Tableau.


# Observation 

The number of famale rider is significantly lower than male rider. The most popular age for biking is about 20 years old!
The most demanding time to ride during weekday is about 8:00 AM in the morning and 5:00 to 6:00 PM in the afternoon. 
There are so many stations around city and some of them are more popular than others to start or end the rides. 
All the bikes wont be used at the same rate. As far as repair time, I have no data indicating any information about the 
last time each bike repaired or based on which conditions bikes need to be repaired. I made assumtion each bike will need 
to be repir every 25 miles. 
