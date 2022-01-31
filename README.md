# Des Moines - Bike Sharing NYC Citi Bike Data

## Overview of Statistical Analysis
- Our goal is to convince investors that a bike-sharing program in Des Moines is a solid business proposal. Using NYC Citi Bike Sharing data from August 2019, we analyzed the data by using Pandas to change the "tripduration" column from an integer to a datetime datatype to create our visualization that will be presented to our potential investors. 
- Our visualization will include the following:
  - The length of time that bikes are checked out for all riders and genders.
  - The number of bike trips for all riders and genders for each hour of each day of the week.
  - The number of bike trips for each type of user and gender for each day of the week.

### Data and Resources Utilized:
- NYC CitiBike starter code
- Pandas
- 201908-citibike-tripdata.csv
- Tableau

## Results

- Deliverable 1: Change Trip Duration to a Datetime Format using Pythons and Pandas
![image](https://user-images.githubusercontent.com/90146132/151722907-ba57a96a-c7ee-4117-8358-e9213a94a62d.png)
![image](https://user-images.githubusercontent.com/90146132/151722928-6ffc7791-7e67-40e5-aa61-732d29048662.png)

- Deliverable 2: Create Visualizations for the Trip Analysis
  - How long bikes are checked out for all riders and genders?
  ![image](https://user-images.githubusercontent.com/90146132/151723117-bd25882b-8f75-4fee-a209-66a73fc6f615.png)
  In the image above, we are visualizing the length of time the bikes are checked out by the total number of users.
  ![image](https://user-images.githubusercontent.com/90146132/151723177-d9675a10-8cca-4bd3-a423-9c82a60d71dd.png)
  In the image above, we are visualizing the length of time the bikes are checked out by each type of gender.
  
  - How many trips are taken by the hour for each day of the week, for all riders and genders?
  ![image](https://user-images.githubusercontent.com/90146132/151723214-03b08384-5138-4daa-9c2e-6d57653d0809.png)
  In the image above, we can observe the number of bike trips that are taken on the weekdays by each hour of the day displayed as a heatmap.
  ![image](https://user-images.githubusercontent.com/90146132/151723276-e80bf351-aa9e-4a16-b629-94503912d1f9.png)
  In the image above, we can observe the number of bike trips that are taken by each gender on the weekdays by each hour of the day displayed as a heatmap.
  
  - A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender?
  ![image](https://user-images.githubusercontent.com/90146132/151723378-dad288c2-6779-4077-a47b-da73551069eb.png)
  In the image above, we have diplayed the number of bike trips by gender for weekdays by each user type.
  
- Deliverable 3: Create a Story and Report for Final Presentation

[Final Story Analysis](https://public.tableau.com/shared/SFY957Y8M?:display_count=n&:origin=viz_share_link)
  
  ![image](https://user-images.githubusercontent.com/90146132/151724203-851020ed-1305-4489-b7ca-f61dc62f4a69.png)
  In the image above, we have presented the checkout trip duration for both user and each gender. On the Checkout Time for Users line graph, we can infer that the highest number of checkout times for bikes occurs within the first hour of checking our the bike where it appears that about 145K bikes are utilized in 0-50 mins. On the Checkout Times by Gender line graph, we can infer that the majority of bikes utilized are males which account for more than 100k bike checkouts within the first hour of trip duration. When looking at the Top Starting Locations map, it appears that most of the bikes checked out by these users are mostly in area in between and Empire State Building and Central Park or close to the Hudson River.
  
  ![image](https://user-images.githubusercontent.com/90146132/151724410-04bb67f7-da61-4d43-9472-835a94f6c429.png)
  In the following image above, we have presented the weekday trips per hour and customer. On the Trips by Weekday per Hour heatmap, we can infer that the majority of bikes are checked out at 8am and 5-6pm. We can also infer that out of all the weekdays, it appears that on Thursday at 8am and 5-6pm is the highest number of bikes checked out at the those times. On the User Trips by Gender by Weekday, we can conclude that male subscribers are the users and gender that utilize the bikes during any weekday. Looking at our Customer Type pie chart, the bike utilization is dominated by CitiBike subscribers. 
  
  ![image](https://user-images.githubusercontent.com/90146132/151725101-57f0596a-5771-46c4-8135-dc492e4c0de2.png)
  In the image above, we have presented the weekday trips per hour and gender. Looking at the Trips by Gender (Weekday per Hour) heatmap, we may conclude that males dominated by males at 8am and 5-6pm when the highest amount of bikes are checked out, with Thursday being the busiest. We also have displayed a pie chart of Gender Breakdown, where we can infer that the majority of bike riders are indeed males. 
  
## Summary
- In conclusion, we believe the a bike-sharing program will thrive in the city of Des Monies in locations where there is a high traffic of residents in the city that could aid in their everyday commutes in the city. Two additional visualizatons that will continue to analyze the future outcome of the business is a visualizaton of the bikes that are utilized the most as well as which bikes have needed the most repairs based on the number of trip durations the bike has been used. The images below describes the visualizations described.

![image](https://user-images.githubusercontent.com/90146132/151726516-703a8d64-7035-40e1-a5e0-6ee2c908df47.png)

![image](https://user-images.githubusercontent.com/90146132/151726541-99243df5-68ec-4660-acd6-3ac152e0b570.png)



