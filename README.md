🏨 Hospitality Revenue Analytics – Power BI (CodeBasics)

A comprehensive Power BI analytics solution built to deliver actionable insights for the Revenue Team in the Hospitality domain.
This project analyzes booking behavior, revenue performance, and operational efficiency across multiple hotel properties using an optimized star schema data model.

📊 Project Overview

This dashboard enables hospitality businesses to:

Track revenue performance

Monitor booking trends

Evaluate occupancy and capacity utilization

Compare property-wise and category-wise performance

Interactive visuals and KPIs help stakeholders make data-driven revenue decisions.

📁 Dataset Structure

The project follows a star schema for efficient analytics and performance optimization.

⭐ Dimension Tables
dim_date.csv

date – Calendar dates (May, June, July)

mmm yy – Month-Year format (e.g., May 25)

week no – Week number

day_type – Weekday / Weekend

dim_hotels.csv

property_id – Unique hotel identifier

property_name – Hotel name

category – Luxury / Business

city – Hotel location

dim_rooms.csv

room_id – Room type (RT1, RT2, RT3, RT4)

room_class – Standard, Elite, Premium, Presidential

📌 Fact Tables
fact_aggregated_bookings.csv

property_id

check_in_date

room_category

successful_bookings

capacity

fact_bookings.csv

booking_id

property_id

booking_date

check_in_date

check_out_date

no_guests

room_category

booking_platform

ratings_given

booking_status (Cancelled, Checked Out, No Show)

revenue_generated

revenue_realized
(Cancelled bookings incur a 40% revenue deduction)

🎯 Key Features

Revenue Analysis – Generated vs. realized revenue tracking

Booking Performance – Success, cancellation, and no-show insights

Occupancy Metrics – Capacity utilization across properties

Temporal Trends – Day, week, and month-based analysis

Property Comparison – Performance by hotel, city, and category

Customer Insights – Ratings analysis and booking platform effectiveness

🛠️ Tools & Technologies

Microsoft Power BI – Dashboard development & visualization

Data Sources – CSV-based historical booking data

Data Modeling – Star schema for optimized querying

📈 Analytics Capabilities

Revenue trends over time

Occupancy and utilization rate calculations

Booking platform performance comparison

Customer satisfaction analysis

Cancellation and no-show rate analysis

Weekend vs. weekday performance

Property-wise and category-wise breakdowns

📂 Repository Structure
├── dim_date.csv                      # Date dimension
├── dim_hotels.csv                   # Hotels dimension
├── dim_rooms.csv                    # Rooms dimension
├── fact_aggregated_bookings.csv     # Aggregated booking data
├── fact_bookings.csv                # Detailed booking records
├── meta_data_hospitality.txt        # Data dictionary
├── Problem_Statement_and_Tasks.docx # Project requirements
└── Hospitality-Revenue-Analytics.pbix # Power BI dashboard

🚀 Getting Started
Prerequisites

Microsoft Power BI Desktop (latest version recommended)

Installation
git clone https://github.com/suhaasd/Hospitality-Revenue-Analytics-PowerBI.git

Open the Dashboard

Launch Power BI Desktop

Open Hospitality-Revenue-Analytics.pbix

Explore interactive visuals and insights

📊 Data Dictionary

Detailed column descriptions and metadata are available in
meta_data_hospitality.txt

👤 Authors

Sriram K

Vaishnav P S

Samarth M

Suhaas D

📝 License

This project is intended for educational and analytical purposes.

Built with Power BI to drive data-driven decisions in Hospitality Revenue Analytics 📊🏨
