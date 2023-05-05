# CitiBike Data Analysis with Tableau

## Overview of Analysis

The purpose of this project was to analyze the NYC CitiBike data to determine whether a bike-sharing program is beneficial in major metropolitian cities around the world. By analyzing the bike sharing data for New York City we uncover some key findings which help decision-makers at companies like CitiBike determine if they would like to invest in a bike-sharing program in a major city. Using Pandas, Jupyter , and Tableau we are able to create a interactive dashboard that produces visualizations that help us understand the types of customers using this service, the peak hours, the trips categorized by weekdays, etc. By using the Python program and the Pandas library we are able to change the data type for one of the coloumns in the raw data. This helps us calculate the Checkout Times of Users by their Gender. Using Tableau we are able to create an interactive dashboard that can help decision makers at bike sharing companies make data driven decision to help grow their business and better serve their communities.  


## Bike Sharing Data Analysis Results:

### Data Cleaning
Cleaned the raw data using Pandas library and changed the data type of the 'trip duration' coloum using the following steps from integer to datetime format.
![load_data](https://user-images.githubusercontent.com/100486461/179337941-d0e5dd86-b00b-4271-b690-fe949d02e586.PNG)
![2](https://user-images.githubusercontent.com/100486461/179337944-0d91edf7-1bfc-4031-997c-2a8034cf97e2.PNG)
With the following steps we can convert the 'tripduration' coloum to a datetime datatype from an integer datatype
![3](https://user-images.githubusercontent.com/100486461/179337999-92c06b4c-5bb0-4926-a2e8-aa4b773fa85e.PNG)

After uploading the new data into Tableau, we are able to create the following visualizations to help our analysis
1. Bike Rental Hours - This visualization helps us understand on average the hours where there are most and least amount of bike rentals during the day. This can also help companies decide the hours of operations for their bike sharing services, the hours where they might need more employees at certain locations to meet the business demands.
![Bike Rental Hours](https://user-images.githubusercontent.com/100486461/179338444-abe20d1f-44da-4f77-85af-8e16bdade91b.PNG)

2. Top Starting and Ending Locations - This visualization helps us understand the most preferred locations where users like to begin and end their bikeride
![top start and end locations](https://user-images.githubusercontent.com/100486461/179338439-cf253cac-dce1-455e-a970-11df39e51443.PNG)

3. Checkout Times for Users - This visualization helps us understand the average bike checkout durations for Users, as well as see that the majority of the bike sharing users are Males
![Checkout Times by Gender](https://user-images.githubusercontent.com/100486461/179338679-c766b1f2-a62c-4eff-a85a-1dec7d2fd82a.PNG)

4. We can also learn the number of trips, types of customers, customer age, trips by gender breakdown as follows
![number of trips](https://user-images.githubusercontent.com/100486461/179338848-3603123f-5d61-4d33-9cd2-e331d690845d.PNG)

5. Customer Type - This visualization helps us understand whether the subscription service is popular among users
![customer type](https://user-images.githubusercontent.com/100486461/179338893-6e2c26ae-48a1-4c9f-8e65-a0b5990b5a42.PNG)

6. Gender Breakdown - This visualization helps us understand who is using the bike sharing service the most and can help companies in decision making processes. In the raw dataset there was no category for different gender types. Through the following formula we can change the raw data for gender from interger to string datatype.
![Converting_Number_to_String](https://user-images.githubusercontent.com/100486461/179339176-3c309632-6b22-4d02-82fc-01894f31442f.PNG)


7.  Trips by Weekday - This visualization helps us understand the number of trips for each user types during different days of the week
![trips gender by weekdat](https://user-images.githubusercontent.com/100486461/179339197-74fabaa1-f4d2-44fa-ad04-4ff8eefd0282.PNG)

The following is the link to the Tableau Dashboard [link](https://public.tableau.com/app/profile/yesha4974/viz/BikeSharingDataAnalysis_16579395964070/Story1?publish=yes)
 
