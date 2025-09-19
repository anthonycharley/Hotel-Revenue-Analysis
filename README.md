# Hotel Revenue Analysis Project

This project was made to provide stakeholders at a hotel answers to how the hotel was performing over the course of 3 years. The goal was to identify key trends, understand the hotel's revenue, and to inquire about increasing hotel parking.

Questions from our stakeholders:
  - "Is our hotel revenue growing (YoY)?"
  - "Should we increase the parking lot sizes of either hotel types?"
  - "What trends are we seeing over the course of these 3 years?"

Tools used:
  - Microsoft SQL Server
     - To filter and group data provided for dashboard
  - Power BI
     - To visualize data in a readable manner, show revenue growth, and show parking space usage over time

---
# SQL Server Query

<img width=100% height=auto alt="query_linked_to_hotel_dashboard" src="https://github.com/user-attachments/assets/b63dd19c-760f-4b12-ae2e-a142fcb69c33" />

---
A Common Table Expression (CTE) and Unions were used to combine hotel data from 2018, 2019, and 2020 to create a new temporary table called "Hotels".
After the temporary table was created, Joins were used to combine all extra data from the market segment and discount table to provide a larger picture of all hotel data.
This query was then uploaded into Power BI for further analysis.

---
## PowerBI Interactive Dashboard

<img width=100% height=auto alt="Hotel_Analysis_Dashboard" src="https://github.com/user-attachments/assets/775e5fd3-a1da-4890-88c7-c04a06ac6af5" />

This interactive dashboard covers KPIs such as average daily rate, average parking spaces required, average discount applied, and revenue over time. 


## Power BI Measures Used

<img width=100% height=auto alt="measures_used_in_hotel_analysis" src="https://github.com/user-attachments/assets/642bc2c4-9c5b-4865-aec5-385fd0119081" />

---
## Project Insights

From the data, we find that 2019 was the biggest year for revenue from both hotels. The end of 2019 and beginning of 2020 was likely lower due to the outbreak of COVID-19. 
The City Hotel is our largest growing hotel via revenue at this time.
We began to see revenue on the rise towards the end of 2020, which shows that the hotels had a strong recovery after such world events.
The Resort Hotel, on average, required more parking spaces than the City Hotel. Yet, an increase in parking spaces for either hotel is not required at this time. 
We believe that of all the parking space allocations that already exist, there is no need for more allocations.

---
