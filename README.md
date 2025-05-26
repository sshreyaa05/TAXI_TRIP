### NYC Taxi Trip Data Analysis: Insights on Ride Patterns and Potential Failures

### Overview:
This project analyzes NYC Taxi trip data to understand ride patterns, peak demand times, payment behaviors, and identify potential failed rides based on trip characteristics. Since the dataset lacks explicit cancellation info, trips with very short distances or low fares are flagged as possible aborted rides. The insights can help improve taxi operations and resource allocation.

### Steps:
1.	Data Preprocessing: Converted pickup and dropoff timestamps to datetime; extracted pickup hour and day.
   
2.	Trip Statistics: Calculated total trips, average trip distance, and fare amounts.
   
3.	Demand Analysis: Visualized trip counts by hour of day and day of week to find peak demand times.
	
4.	Trip Characteristics: Plotted distributions of trip distance, fare amount, and trip duration.
	
5.	Customer Behavior: Analyzed payment types and passenger counts.
	
6.	Failed Ride Proxy: Identified trips with distance < 0.1 miles or fare < $2 as potential failed rides and analyzed their occurrence by hour.

### Interpretations:
•	Peaked demand occurs during specific hours and days, guiding better driver allocation.

•	Most trips are within typical distance and fare ranges, but a small portion of very short or cheap trips may indicate failures or cancellations.

•	Payment types and passenger counts reflect user preferences and ride types.

•	Recognizing potential failed rides helps target operational improvements to reduce ride cancellations and enhance customer satisfaction.

