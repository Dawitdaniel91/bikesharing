# bikesharing

## Overview

The purpose of project is to analysis the New York City Citibike data from August 2019 in order to determine if Citibikes would be a good fit for Des Moines, Iowa. The analysis was based on user time, time by gender, Trips by Gender(Weekday per hour),Trips by Weekday per hour and user trip by gender per weekday.Before the begun of the analysis it was required to used Pandas to change the 'tripduration' column from an integer to a datetime datatype. 

The report consists of two technical analysis deliverables and a written report to present my results. 

  Deliverable 1: Change Trip Duration to a Datetime Format

  Deliverable 2: Create Visualizations for the Trip Analysis

  Deliverable 3: Create a Story and Report for the Final Presentation


## Resources Used

. Python v3.x

   . Pandas
. Jupyter notebook
   
. 201908-citibike-tripdata

.Tableau Public Link to Tableau Dashboard(https://public.tableau.com/app/profile/dawit.alaro/viz/UserTripbyGenderbyWeekday/NYC_CitiBike_Challenge_Citybike_Analysis)

## Results

###   Deliverable 1: Change Trip Duration to a Datetime Format

By using Python and Pandas functions, I converted the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). 

![image](https://user-images.githubusercontent.com/80365882/122129997-cfaa8680-cdeb-11eb-91f1-461f2ea355e9.png)
  
            
 ### Deliverable 2: Create Visualizations for the Trip Analysis
 
 Using Tableau, create visualizations that show:
 
. How long bikes are checked out for all riders and genders.

. How many trips are taken by the hour for each day of the week, for all riders and genders.

. A breakdown of what days of the week a user might be more likely to check out a bike, by typeof user and gender.


 ### Checkout Times for Users
 
 In this visualization, The graph shows us the length of time that bikes are checked out for all riders.
 
 Tableau public link:https://public.tableau.com/app/profile/dawit.alaro/viz/CheckoutTimesforUsers_16234665352630/CheckoutTimesforUsers
 
 ![image](https://user-images.githubusercontent.com/80365882/122130595-b9e99100-cdec-11eb-9c61-bc8e8a42f6a6.png)

 ### Checkout Times by Gender
 
  We can understand from the table most of the general usertypes are male (90,357), but both the female and unknown gender usertypes are below the half number of the general number of usertype(41,838 Both bumber of usertype)
 
 
 Tableau public link : https://public.tableau.com/app/profile/dawit.alaro/viz/CheckoutTimesByGender_16237826859620/CheckoutTimesByGender
 
 ![image](https://user-images.githubusercontent.com/80365882/122131065-79d6de00-cded-11eb-8af9-e05a84f5fd26.png)

### Trips by Weekday for Each Hour

Tableau public link: https://public.tableau.com/app/profile/dawit.alaro/viz/TripsbyWeekdayperHour_16237831787440/TripsbyWeekdayperHour

![image](https://user-images.githubusercontent.com/80365882/122131246-bc001f80-cded-11eb-918f-dab8aa58a824.png)


### Trips by Gender (Weekday per Hour)

This graph shows the total number of trips by weekday and hour. We understood from the grepgh , most of the usertype demanded to use biking on the morning time.We can see that the highest demand times are the morning hours on weekdays from 6am till 9am and in the evening hours on weekdays between 5 pm and 7 pm. Most of the users used the high demand for weekend hours are middle of the day between 10 am and 6 pm.

Tableu public ling: https://public.tableau.com/app/profile/dawit.alaro/viz/TripsbyGenderWeekdayperHour_16237850118820/TripsbyGenderWeekdayperHour

![image](https://user-images.githubusercontent.com/80365882/122131490-15684e80-cdee-11eb-9dbf-c58966f774eb.png)

### User Trips by Gender by Weekday

From the graph we could understand that Thursday is the most popular day for bike rentals among male and females for weekdays whereas others most popular days are weekend which ard Saturday and Sunday.

Tableau public link: https://public.tableau.com/app/profile/dawit.alaro/viz/UserTripbyGenderbyWeekday/UserTripbyGenderbyWeekday

![image](https://user-images.githubusercontent.com/80365882/122131793-90316980-cdee-11eb-8ce8-d35fb9b9ebba.png)

### Number of Usertype based non gender

Tableau public link :https://public.tableau.com/profile/dawit.alaro#!/

The bar chart shows us  almost no singifcant diffrence change betwen the gender but hughe difference in the subscriber. Amost morethan 80000  subscriber are male.

![image](https://user-images.githubusercontent.com/80365882/122506286-e18a5600-cfb2-11eb-8d12-d9ac6f2dacf2.png)


### Top ten stations

The chart shows us almost most of the top ten starting and ending stations are from the same zone.

![image](https://user-images.githubusercontent.com/80365882/122506218-b7d12f00-cfb2-11eb-81ce-273afb7181eb.png)

## Summery

  Based the chart analysis the males are the primary users of City bikes in New York City if we see the general usertype, but if we see only the customers usertype, the difference is not significant because we do not have any information regarding the unknown customers. If we see the subscribers’ numbers, we can conclude the overall males are most of the usertype of the city bikes in the New York City. But Additional analysis is needed in order to determine if City bikes is a great fit for Des Moines, Iowa.
  
  
  In order to determine if city bikes are good fit for Des Moines, there is still some more visualization needed to convince investors that a bike-sharing program in Des Moines is a solid business proposal. There are two additional visualizations are suggested for future analysis
  
  
  The first one, it is better to visualize population growths between Des Moines and New York City. Publicly available census data could be used to look at population totals and growth rates between the two cities. The other one is visualization  based on the weather data between Des Moines and New York City. 
