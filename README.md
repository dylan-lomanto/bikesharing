# Bike Sharing in Des Moines

### Overview
This project aims to determine whether or not a bike sharingn program is viable for the city of Des Moines, Iowa.  This intial analysis examines data from New Yor City's Citi Bike program for August of 2019.  The following set of visualizations display the length of time that bikes are checked out for all riders and genders, the number of bike trips for all riders and genders for each day of the week, the number of bike trips for each type of user and gender for each day of the week, the total number of trips for each user type, and total number of bike trips for each user type and gender for each birth year.

### Analysis
##### Checkout Times for Users
![Checkout Times for Users](https://user-images.githubusercontent.com/86164867/134569647-6b2b12e4-7363-4be5-924f-399c6a3fcc1b.PNG)
The peak trip duration for all users is 5 minutes. The vast majority of rides are under 50 minutes, and are heavily clustered between 1 and 23 minutes.  This shows that the majority of users use the Citi Bikes for short trips, not full commutes.

##### Checkout Times by Gender
![Checkout Times by Gender](https://user-images.githubusercontent.com/86164867/134570487-a31ee32c-694e-42d9-8549-c5cc4af23f1d.PNG)
The male and female genders have very similar patterns, with a sharp peak at 5 minutes for men and 6 minutes for women.  The unknown gender observes a slightly different pattern, with an elongated peak of similar numbers of rides for trip durations of 8 through 25 minutes.

##### Trips by Weekday for Each Hour
![Trips by Weekday for Each Hour](https://user-images.githubusercontent.com/86164867/134572140-bed30088-8950-4070-aad0-d23f0ab83bdc.PNG)
The frequency of morning trips is relatively consistent for Monday through Fridays between 7 and 9am.  The frequency of evening trips between 5 and 7pm is consistent on Monday, Tuesday, and Thursday. There is a notable drop in the frequency of evening trips on Wednesdays, and the peak time for evening trips on Fridays is slightly earlier.

##### Trips by Gender (Weekday per Hour)
![Trips by Gender (weekday per hour)](https://user-images.githubusercontent.com/86164867/134574581-e7b57a4c-d1ec-44b4-b87d-9fd31f821024.PNG)
The male and female genders have consistent patterns of frequency.  The unkown gender, however, has more frequent trips on the weekends then on weekdays.

##### User Trips by Gender by Weekday
![User Trips by Gender by Weekday](https://user-images.githubusercontent.com/86164867/134575400-20df5b1b-3eab-477f-8f1a-5c8ac16bb312.PNG)
The male and female genders follow similar day of the week patterns. The majority of their trips are by subscribers. The unknown gender has more frequent trips on weekends than weekdays and has more customer trips than suscriber trips.

##### Total Trips by Usertype
![Total trips by Usertype](https://user-images.githubusercontent.com/86164867/134576466-1c02aba1-9cf5-4e1d-8c4a-04290fed03e3.PNG)
Roughly 81% of total trips are taken by subscribers while the remiaining 19% are taken by customers.

##### User Trips by Birth Year
![User Trips by Birth Year](https://user-images.githubusercontent.com/86164867/134576944-b95d8dca-38d5-4e6f-ad28-adb1eca6e4b0.PNG)
Total subscriber rides peak for the birth year 1990, with a significant rise for 1969. Total customer rides peaks substantially for the birth year 1969, with significantly smaller spikes for 1989 and 1995. The peak in 1969 is so significant that it is likely a data error for both types of customers

##### User Trips by Gender by Birth Year
![User Trips by Gender by Birth Year](https://user-images.githubusercontent.com/86164867/134577494-0862e7df-35d2-4bfa-9268-85ccfc85b9b4.PNG)
The male and femal genders observe similar patterns, with no peak in 1969.  Male ridership peaks for birth year 1990 while femal ridership peaks between birth years 1989 and 1992.  The unknown gender has a massive peak of ridership for birthyear 1969. This is almost certainly a data error as 9% of total rides are displayed as having been taken by a person with an unknown gender born in 1969.

### Summary


##### Additional Visualizations
1. Total Trips by Gender: In order to further explore the anomaly of the total number of rides by unkown gender with a birth year of 1969 the total numnber of trips by each gender should be displayed on a bar graph. 
2. Starting Location by Birthyear: This visualization should examine if their is any relationship between age of rider and starting location. Since the total ridership heavily trends towards younger riders it may be more cost effective to remove bikes from areas that are only frequented by older riders.
