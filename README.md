# Flight Delays Analytics (Interactive Dashboard using Power BI)
## Project Objectives
The project aims to help airlines, airport authorities, and operational teams analyze flight delays to improve efficiency and passenger experience. By exploring flight patterns, delays, and their causes, the dashboard provides actionable insights to reduce delays and optimize scheduling.
# DataSet
-<a href="https://www.kaggle.com/code/adveros/flight-delay-eda-exploratory-data-analysis/input">DataSet</a>

## Key Questions / KPIs
•	Total flights vs delayed flights
•	Delayed rate (%) overall and by origin airport
•	Total carrier delays and average departure delays
•	Delay trends over months and days of the week
•	Main reasons for flight delays
•	Correlation between flight distance and delay
•	Airports and destinations with the highest delays


## Dashboard Pages
1.	Overview Page:
o	Shows total flights, delayed rate, average departure delay, and total carrier delay.
o	Pie chart of delay reasons.
o	Monthly trends in departure delay.
Dashboard Interaction<a href="https://github.com/HusseinSanad/DealyedFlights/blob/main/1.png">View Dashboard</a>
2.	Origin & Delay Analysis:
o	Breaks down delays by origin airport.
o	Highlights total weather, carrier, and NAS delays by origin.
o	Scatter plot showing relation between delay count and flight distance.
Dashboard Interaction<a href="https://github.com/HusseinSanad/DealyedFlights/blob/main/2.png">View Dashboard</a>

3.	Destination & Temporal Trends:
o	Delays by destination airport.
o	Average departure delay by origin.
o	Delays broken down by day of week and month for temporal insights.
Dashboard Interaction<a href="https://github.com/HusseinSanad/DealyedFlights/blob/main/3.png">View Dashboard</a>


## Process
•	Data Cleaning: Verified for missing values, corrected inconsistencies, ensured correct data types.
•	Data Modeling: Created relationships between tables for dynamic analysis.
•	Visualizations: Designed charts (bar, line, scatter, and donut) for each KPI.
•	Dashboard Design: Built three interactive pages with slicers to filter by origin, destination, month, or carrier.
•	Interactivity: All pages update dynamically based on slicer selection, allowing detailed drill-down analysis.
## Dashboards
<img width="908" height="504" alt="1" src="https://github.com/user-attachments/assets/b53492a2-c88f-4413-ac95-f84a16dfe21b" />

<img width="889" height="498" alt="2" src="https://github.com/user-attachments/assets/6cb4ac6b-aeaf-4716-84cb-48d1b92b3b62" />
<img width="892" height="499" alt="3" src="https://github.com/user-attachments/assets/7b64fbdb-e481-4d99-a7e6-bb3bb69061c2" />

## Project Insights
•	Delay Rate: Only 1% of total flights experienced delays, but significant for operational planning.
•	Top Delay Causes: Carrier delays (~30%) and Late Aircraft delays (~40%) are the main contributors.
•	High-Risk Airports: CMX, PLN, and SPI airports show consistently higher delays.
•	Distance vs Delay: Longer flights tend to have more cumulative delays.
•	Monthly Trends: December has the highest average departure delays (~50 minutes).
•	Day-of-Week Trends: Delays vary across weekdays, helping optimize staffing and scheduling.

## Conclusion
This interactive Power BI dashboard enables a comprehensive understanding of flight delays across multiple dimensions: origin, destination, month, and carrier. It provides operational teams with actionable insights to reduce delays, optimize routes, and enhance passenger satisfaction.
