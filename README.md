Hotel Revenue Insights


📌 Problem Statement

AtliQ Grand, a luxury five-star hotel chain in India, has been facing declining market share and revenue due to competitive strategies and ineffective decision-making. This project aims to provide data-driven insights and strategic recommendations to help AtliQ Grand regain its market position.


🎯 Objective

To analyze hotel revenue data and derive actionable insights to optimize pricing, improve occupancy rates, and enhance revenue management strategies.


📂 Data Overview

The dataset consists of five CSV files:

dim_hotels - Hotel details (name, location, category)

dim_rooms - Room types

dim_dates - Dates, months, week numbers, and day types

fact_bookings - Booking details, check-in/check-out dates, number of guests, etc.

fact_aggregated_bookings - Booking capacity by room category and date


🔹 Dataset Insights

Total records in fact_bookings: 134,590 rows

Total columns in fact_bookings: 12 columns


📊 Key Metrics

ADR (Average Daily Rate)
RevPar (Revenue Per Available Room) = Total Revenue / Total Rooms Available

SRN (Sellable Room Nights)

DSRN (Daily Sellable Room Nights)

URN (Utilized Room Nights)

BRN (Booked Room Nights)

Realization (%) = URN / BRN

📌 In the hotel industry, Fridays and Saturdays are considered weekends, while Monday to Thursday are weekdays.


🧹 Data Cleaning

✔ Checked for missing values (None found)

✔ Removed redundant columns (e.g., day_type from dim_dates as weekends were predefined)


🔄 Data Processing

✅ Established Star Schema with one-to-many and many-to-one relationships:

Dimension Tables: dim_rooms, dim_hotels, dim_dates

Fact Tables: fact_bookings, fact_aggregated_bookings

✅ Used Power Query, DAX functions, and ETL processes for data transformation.


📈 Dashboarding

🔹 Created 26 key measures using DAX functions.

🔹Implemented interactive filters (city, room type, etc.).

🔹 Key KPI visualizations: ADR, Occupancy %, Revenue, RevPar, Realization (using KPI Cards)

- Weekday vs. Weekend Splits for ADR, Realization, Occupancy %, and RevPar

- Line & Column Chart - Realization % & ADR by platforms

- Donut Chart - Revenue by category

- Trend Analysis - Key metrics using Line Charts


🛠️ Technical & Soft Skills


🔧 Technical Skills

Power BI

DAX (Data Analysis Expressions)

Data Visualization

Report Building


🗣️ Soft Skills

Effective Presentation

Presenting Insights

Decision Making

Pricing Strategy

Strategic Planning


📌 Conclusion

This project provides a structured approach to hotel revenue analysis using Power BI. By leveraging interactive dashboards and key performance metrics, AtliQ Grand can make informed decisions to optimize revenue, improve occupancy, and regain market share.

🚀 Let's turn data into actionable insights!


📜 Author

Piyush Jadhav
📧 piyushdj1810@gmail.com
🔗 LinkedIn

Feel free to ⭐ this repository if you found it useful! 😊
