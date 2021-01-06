# Bikesharing - Citi Bike in Tableau

## Overview
* This analysis was performed to gain understanding of trends and patterns in the bike rental market using data from Citi Bike in Des Moines, IA.

## Results

### Rentals by Gender
* The majority of bike rentals are conducted with male customers, at 65.28%.
![alt text](https://github.com/XZandermarsh/Bikesharing/blob/main/Rentals_by_Gender.png "Rentals by Gender")

### Rentals by User Type
* The majority of bike rental agreements are via subscription, at 81.07%, vs 18.93% of agreements as single use customers.
![alt text](https://github.com/XZandermarsh/Bikesharing/blob/main/Rentals_by_UserType.png "Rentals by User Type")

### Trip Duration by Age
* Ignoring some outliers in early birth years (higher age) due to low sample density, the general trend is that younger customers tend to rent the bikes for longer trips.
![alt text](https://github.com/XZandermarsh/Bikesharing/blob/main/Trip_Duration_by_Age.png "Trip Duration by Age")

### Checkout Times
* The most common checkout (mode) duration is 5 hours.
![alt text](https://github.com/XZandermarsh/Bikesharing/blob/main/Checkout_Times_For_Users.png "Checkout Times for Users")

### Checkout Times by Gender
* Overall, there are more male renters than female especially at a checkout duration above 4 hours
![alt text](https://github.com/XZandermarsh/Bikesharing/blob/main/Checkout_Times_by_Gender.png "Checkout Times by Gender")

### Trips by Weekday
* 8AM and 5PM are peak checkout times on weekdays (Mon-Fri), and times are more evenly distributed on weekends.
![alt text](https://github.com/XZandermarsh/Bikesharing/blob/main/Trips_by_Weekday.png "Trips by Weekday")

### Trips by Weekday by Gender by Hour
* Splitting the same visual by gender, the same peak times exist during the week. Again, it is apparent that there are more male users.
![alt text](https://github.com/XZandermarsh/Bikesharing/blob/main/Trips_by_Weekday_by_Gender_by_Hour.png "Trips by Weekday by Gender by Hour")

### Trips by Weekday by Gender and Type
* Peak days for single use customers are Saturday and Sunday. Peak days for subscribers are Monday, Tuesday, Thursday, and Friday.
![alt text](https://github.com/XZandermarsh/Bikesharing/blob/main/Trips_by_Weekday_by_Gender.png "Trips by Weekday by Gender")

## Summary
* In summary, male subscribers are the core customer demographic for the business. It is likely that these are mostly commuters who are using the service as their transportation to and from work. This is also apparent from the peak checkout times of 8AM and 5PM. 
* Additional visuals that may be informative would be the delta between check-outs and check-ins by location. This would aid in planning logistics for re-distributing the bikes periodically. Another would be to analyze common routes taken by rental bikes (path from check-out to check-in), as there may be additional opportunities to expand the network for more convenient locations to the customer base.

[link to Citi Bike dashboard](https://public.tableau.com/profile/alexander4965#!/vizhome/CitibikeAnalysis_16098958275720/CitibikeAnalysis)
