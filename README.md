# Hospitality Revenue Analytics – Power BI (CodeBasics)

A comprehensive Power BI analytics solution designed to deliver actionable insights for the Revenue Team in the Hospitality domain. This project analyzes booking patterns, revenue metrics, and operational performance across multiple hotel properties using an optimized star schema data model.

---

## Project Overview

This dashboard helps hospitality businesses understand revenue performance, booking trends, and operational efficiency through interactive visualizations and key performance indicators (KPIs).

---

## Dataset Structure

The project follows a star schema data model for efficient analytics and performance optimization.

### Dimension Tables

**dim_date.csv**
- date: Calendar dates (May, June, July)
- mmm yy: Month-Year format (e.g., May 25)
- week no: Week number
- day_type: Weekday or Weekend

**dim_hotels.csv**
- property_id: Unique hotel identifier
- property_name: Hotel name
- category: Luxury or Business
- city: Hotel location

**dim_rooms.csv**
- room_id: Room type (RT1, RT2, RT3, RT4)
- room_class: Standard, Elite, Premium, Presidential

### Fact Tables

**fact_aggregated_bookings.csv**
- property_id: Hotel identifier
- check_in_date: Customer check-in date
- room_category: Room type
- successful_bookings: Number of successful bookings
- capacity: Maximum available rooms

**fact_bookings.csv**
- booking_id: Unique booking identifier
- property_id: Hotel identifier
- booking_date: Booking creation date
- check_in_date: Check-in date
- check_out_date: Check-out date
- no_guests: Number of guests
- room_category: Room type
- booking_platform: Booking channel
- ratings_given: Customer rating
- booking_status: Cancelled, Checked Out, No Show
- revenue_generated: Total booking revenue
- revenue_realized: Actual revenue after cancellations (40% deduction)

---

## Key Features

- Revenue generated vs. revenue realized analysis
- Booking performance tracking (success, cancellation, no-shows)
- Occupancy and capacity utilization metrics
- Time-based trend analysis (day, week, month)
- Property-wise and category-wise performance comparison
- Customer ratings and booking platform insights

---

## Tools & Technologies

- Microsoft Power BI
- CSV-based historical booking datasets
- Star schema data modeling

---

## Analytics Capabilities

- Revenue trend analysis
- Occupancy rate calculations
- Booking platform performance comparison
- Customer satisfaction metrics
- Cancellation rate analysis
- Weekend vs. weekday performance
- Property-level and category-level insights

---

## Repository Structure

