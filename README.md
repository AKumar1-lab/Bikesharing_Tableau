### Bikesharing_Tableau

Module 14 NYC Citi Bike Sharing with Tableau

Completed by Angela Kumar

[Tableau Link for Angela Kumar](https://public.tableau.com/app/profile/angelakumar/viz/bikesharing_challenge_16331578231930/Dashboard2?publish=yes)

### Overview

Explore bike-sharing data with Tableau to create worksheets, dashboards and stories New York City bike-sharing data

### Purpose

Work with data visualization software called Tableau to present a business proposal for a bike-sharing company. First, you'll learn how to import, style, and portray data accurately. Then, you'll create worksheets, dashboards, and stories to visualize key data from a New York Citi Bike dataset.  After the analysis, the purpose is to create a proposal to expand the bike-sharing program to Des Moines, IA.

### Resources

Data: 201908-citibike-tripdata.csv; 2019-citibike-tripdata-uptd.csv(updated with the correct tripduration column); NYC_CitiBike_starter_code.ipynb (converted to NYC_CitiBike_Challenge.ipynb)

Software: Tableau Desktop and Public; Jupyter Notebook; Pandas, Python;

Other resources: https://www.bestplaces.net/compare-cities/new_york_ny/des_moines_ia/people

### Background

Now that we've gotten a good idea of how to create our story, there is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

For this analysis, you’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

* Show the length of time that bikes are checked out for all riders and genders
* Show the number of bike trips for all riders and genders for each hour of each day of the week
* Show the number of bike trips for each type of user and gender for each day of the week.

Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.

### Deliverables

* Deliverable 1: Change Trip Duration to a Datetime Format

Using Python and Pandas functions, you’ll convert the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). After you convert the "tripduration" column to a datetime dataytpe, you’ll export the DataFrame as a CSV file to use for the trip analysis in Deliverable 2.

![tripcolumn_datetime_datatype](https://user-images.githubusercontent.com/85860367/135740649-cd7e7fb9-5726-40b6-9195-96914ca19b82.png)

* Deliverable 2: Create Visualizations for the Trip Analysis

Using Tableau, create visualizations that show:

How long bikes are checked out for all riders and genders.
How many trips are taken by the hour for each day of the week, for all riders and genders.
A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

### Results

### 1. Checkout Times for Users
![Checkout times for users](https://user-images.githubusercontent.com/85860367/135742955-61fe94db-ba82-4d16-bdec-ec897f529547.png)
In this visualization, this shows the length of time that bikes are checked out for all riders.
The checkout time was for 20 minutes or less.
### 2. Checkout Times by Gender
![Checkout time by Gender](https://user-images.githubusercontent.com/85860367/135743003-185aa5af-842f-4357-8c53-0417b3568388.png)
In this visualization, this shows the length of time that bikes are checked out for each gender.
The checkout time was for 20 minutes or less; however there were more men using the bike-sharing program, ~4x the number of women.
### 3. Trips by Weekday for each Hour
![Trips by Weekday for Hr](https://user-images.githubusercontent.com/85860367/135743260-770faa0e-a1ed-4e3d-9ec6-1666a14ac5fc.png)
In this visualization, this shows the number of bike trips by weekday for each hour of the day as a heatmap.
Heavy commuting hours daily were between 6 a.m - 9 a.m; and 4 p.m. - 8 p.m.  Thursdays, Fridays, Saturdays, and Sundays were relatively busy.  
This may be workers, students, and tourists who are visiting the city for various events.
### 4. Trips by Gender (Weekday per hour)
![Trips by Gender Weekday and Hr](https://user-images.githubusercontent.com/85860367/135743645-9baf365f-d6cb-4e06-be21-5ada56170d9f.png)
In this visualization, you’ll graph the number of bike trips by gender for each hour of each day of the week as a heatmap
Gender did not matter much, as Thursdays, Fridays, Saturdays and Sundays were relatively busy.  
One observation is that there were more men using the bike-sharing service.
### 5. User Trips by Gender and Weekday
![User Trips by Gender and Weekday](https://user-images.githubusercontent.com/85860367/135743693-431ec7b1-8dfc-45d6-a148-c3ec8a0d9109.png)
In this visualization, this shows the number of bike trips by gender for each hour of each day of the week as a heatmap.
Most men were subscribers, and every day was busy, especially Thursdays.  

* Deliverable 3: Create a Story and Report for the Final Presentation

1. Added an Introduction page that includes the gender breakdown, user type, and the August Peak Hours.

![Introduction Page](https://user-images.githubusercontent.com/85860367/135747280-948d58fe-b101-4043-91d6-43f4b0c625ba.png)

2. Included the top starting and ending locations

![top starting locations](https://user-images.githubusercontent.com/85860367/135746698-577b8583-bf02-4ea4-aa87-05c83f98d840.png)

![top ending locations](https://user-images.githubusercontent.com/85860367/135746683-2aca5095-7aaf-476b-8443-101f09bbe7c1.png)

There wasn't an opportunity to add the following images forthe comparison of DesMoines, IA and NY, NY

<img width="384" alt="NY_IA comparison pop" src="https://user-images.githubusercontent.com/85860367/135746909-c71dfff9-16f8-4559-adb7-9926dab04022.PNG">

<img width="389" alt="age" src="https://user-images.githubusercontent.com/85860367/135746997-a0b6c5ed-5eae-4d64-926b-2f1f9a4f1421.PNG">

<img width="398" alt="Commute to work" src="https://user-images.githubusercontent.com/85860367/135746854-04bde15d-58fa-4dd0-a344-b6672506f474.PNG">

<img width="394" alt="IA_NY Commute" src="https://user-images.githubusercontent.com/85860367/135746869-4d9976d4-fad6-4aa7-959c-2cf81efed224.PNG">

<img width="388" alt="weather" src="https://user-images.githubusercontent.com/85860367/135746885-6977694d-4f18-4068-9c24-5d80bc13a3f2.PNG">


## Summary

The data visualization and analysis of the CitiBike program leads to to conclude that expansion to DesMoines, IA would be a sound and strategic move.  The average age is between 25 to 45 which also aligns with our data analysis in the "Avg Trip Duration by Birth Year"  The younger generation used the bike for a longer duration.

The percentage between male and female is also similar between the two cities.  Actually there are more men in DesMoines, the service will appeal to this group.

The weather between DesMoines and NY is very similar; temperatures were also comparable.

The average commute time is ~19 minutes for DesMoines, and ~41 minutes for NY.  There are more people using a car in DesMoines while NY has more people using mass transit or alternative modes.  In order to reduce the carbon footprint, DesMoines appears to benefit a bike-sharing program.

It would have been nice to be able to put this information on the storyboard, and also it would be a few things that were not analyzed that should be is the cost to rent the bike and what is the unit measure(by minute, hour,etc)

This project was very interesting. I learned a lot from this experience.
