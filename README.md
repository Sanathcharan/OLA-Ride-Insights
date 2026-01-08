# OLA-Ride-Insights
Problem Statement:
The rise of ride-sharing platforms has transformed urban mobility, offering convenience and affordability to millions of users. OLA, a leading ride-hailing service, generates vast amounts of data related to ride bookings, driver availability, fare calculations, and customer preferences. However, deriving actionable insights from this data remains a challenge. To enhance operational efficiency, improve customer satisfaction, and optimize business strategies, this project focuses on analyzing OLA’s ride-sharing data. By leveraging data analytics, visualization techniques, and interactive applications, the goal is to extract meaningful insights that can drive data-informed decisions. The project will involve cleaning and processing raw ride data, performing exploratory data analysis (EDA), developing a dynamic Power BI dashboard, and creating a Streamlit-based web application to present key findings in an interactive and user-friendly manner.

Business Use Cases:
Identifying peak demand hours and optimizing driver allocation.
Analyzing customer behavior for personalized marketing strategies.
Understanding pricing patterns and surge pricing effectiveness.
Detecting anomalies or fraudulent activities in ride data.
Approach:
Data Understanding & Exploration
Load and examine the dataset structure.
Identify key variables like ride status, payment method, and ratings.
Perform initial exploratory data analysis (EDA).
Data Cleaning & Preprocessing
Handle missing or inconsistent values.
Convert data types and standardize formats.
Create derived features if necessary for better insights.
SQL Query Development
Write queries to extract insights (e.g., ride trends, cancellations, ratings).
Optimize queries for performance and accuracy.
Validate results against the dataset.
Power BI Dashboard Creation
Design interactive visualizations for ride trends, revenue, and cancellations.
Use filters and slicers for dynamic data exploration.
Integrate KPIs and metrics for business insights.
Streamlit Application Development
Create a user-friendly UI to display SQL query results.
Implement interactive filters and search options.
Embed Power BI visuals into the Streamlit app for a complete analytics experience.
Project Documentation & Deployment
Document insights, queries, and dashboard explanations.
Ensure the Streamlit app is deployed and accessible.
Present findings with business-oriented storytelling.

SQL Questions
1. Retrieve all successful bookings:
2. Find the average ride distance for each vehicle type:
3. Get the total number of cancelled rides by customers:
4. List the top 5 customers who booked the highest number of rides:
5. Get the number of rides cancelled by drivers due to personal and car-related issues:
6. Find the maximum and minimum driver ratings for Prime Sedan bookings:
7. Retrieve all rides where payment was made using UPI:
8. Find the average customer rating per vehicle type:
9. Calculate the total booking value of rides completed successfully:
10. List all incomplete rides along with the reason

Power BI Questions
1. Ride Volume Over Time
2. Booking Status Breakdown
3. Top 5 Vehicle Types by Ride Distance
4. Average Customer Ratings by Vehicle Type
5. Canceled Rides Reasons
6. Revenue by Payment Method
7. Top 5 Customers by Total Booking Value
8. Ride Distance Distribution Per Day
9. Driver Ratings Distribution
10. Customer vs. Driver Ratings

Segregation of the views
1. Overall 
- Ride Volume Over Time
 - Booking Status Breakdown 
2. Vehicle Type 
- Top 5 Vehicle Types by Ride Distance 
3. Revenue
 - Revenue by Payment Method
 - Top 5 Customers by Total Booking Value
 - Ride Distance Distribution Per Day
 4. Cancellation
- Cancelled Rides Reasons (Customer) 
- cancelled Rides Reasons(Drivers) 
5. Ratings 
- Driver Ratings 
- Customer Ratings 
