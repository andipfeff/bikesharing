# NYC CitiBike with Tableau

## Overview
This analysis on the Citibike business in New York City was prepared to assist in showing the viability of a bike-sharing program in Des Moines to a potential investor. Citibike data for the month of August 2019 was downloaded into a csv file and transformed using Pandas and Tableau calculations. The presentation was then created using a Tableau visualization story.

## Results

The following visualizations were created using Tableau worksheets, and combined using dashboards to create a Tableau Story for the presentation to the potential investor.

***[Link to NYC CitiBike Tableau Story Dashboard](https://public.tableau.com/app/profile/andrea.pfeffer/viz/NYC_CitiBike_Challenge_16402264327910/NYCCitiBikeChallenge)***

- ### **Checkout Times for Users** 

![User_Checkout_Times](https://user-images.githubusercontent.com/90863226/147290511-59026033-2e5f-4ac1-ab18-a89cacc004b2.png)

###### This line graph visualization shows how many bikes are checked out and for how long. The tooltip shows the hours and minutes of the trip length along with the ride count. It defaults to show trips in length between 0-3 hours, however there is an hour filter that the user can use to filter to any length of trip(s).

- ### **Checkout Times by Gender**

![Gender_Checkout_Times](https://user-images.githubusercontent.com/90863226/147290544-49a8107b-9ff5-4d28-b012-a75bd1392ea3.png)

###### Similar to the first vizualization, this line graph also shows the length of time that bikes are checked out only this time broken down by gender. The tool tip shows the hours/minutes of the trip duration along with the gender value and ride count. There are also filters for both hour length of trip duration and gender, with the default view showing trips between 0-3 hours for all genders.

- ### **Trips by Weekday per Hour**

![Hrly_Weekday_Trips](https://user-images.githubusercontent.com/90863226/147290601-5cad9d34-29e2-432d-8589-8c5d5d092d45.png)

###### This heatmap visualization shows total ride count broken down by weekday and hour of the day, with the lighter orange showing the less busy times and the darker orange showing the busier times. The tooltip contains the hour of the ride start time, the weekday, and the ride count.

- ### **Trips by Gender (Weekday per Hour)**

![Weekday_Hrly_by_Gender](https://user-images.githubusercontent.com/90863226/147290635-ba9995c3-f896-4c29-b326-82d3dd83abe9.png)

###### Similar to the previous visualization, this heatmap also shows ridership broken down by weekday by hour, however it also breaks down the data by gender. The lighter orange shows the less busy times and the darker orange is showing the peak ridership times. The tooltip contains the hour of the ride start time, weekday, ride count, and gender. There is also a filter that can be used to filter down to only one gender.

- ### **User Trips by Gender by Weekday**

![Gender_Weekday_Trips](https://user-images.githubusercontent.com/90863226/147290675-6f42bdff-47b9-444c-915d-d5d15d5ffd27.png)

###### This heatmap visualization shows the breakdown of ridership by day and gender broken out between subscribers and general customers. The lighter the blue, the lower the ride count, and the darker the blue being for the busiest days.  The tooltip shows the gender, user type, weekday, and ride count.  There are also filters for both gender and user type.

- ### **August Peak Hours**

![Aug_Peak_Hrs](https://user-images.githubusercontent.com/90863226/147290719-b62c6515-9f83-4a2c-ad6d-4677df51fb67.png)

###### This bar chart visualization shows the total rides for the month broken down by the hour of day the ride was taken. The tooltip shows the hour of day along with the ride count for that hour.

- ### **Start and End Locations**

![Start_End_Locations](https://user-images.githubusercontent.com/90863226/147290736-232fe245-2fad-4016-ada9-981bb094bb8b.png)

###### viz description

## Summary
Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset.
1. create a route map that contains both filters and color changing paramaters for the following dimenstions: day/time, gender, customer, type, and/or bike ID
2. create a station heat map for both starting stations & destination points segmented by user type to see the difference in subscribers vs customers 
3. create a bar chart showing ride counts by birth year by customer type
