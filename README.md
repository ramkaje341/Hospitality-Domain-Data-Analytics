# 🏨 Hospitality Revenue Analytics – Power BI (CodeBasics)

<p align="center">
  <img src="https://img.shields.io/badge/Tool-Power%20BI-yellow" />
  <img src="https://img.shields.io/badge/Domain-Hospitality-blue" />
  <img src="https://img.shields.io/badge/Data%20Model-Star%20Schema-green" />
  <img src="https://img.shields.io/badge/Status-Completed-success" />
</p>

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/c/cf/New_Power_BI_Logo.svg" width="120"/>
</p>

A comprehensive **Power BI analytics solution** designed to deliver actionable insights for the **Revenue Team in the Hospitality domain**.  
This project analyzes **booking patterns, revenue metrics, and operational performance** across multiple hotel properties using an optimized **star schema data model**.

---

## 📊 Project Overview

This dashboard helps hospitality businesses:
- Understand **revenue performance**
- Track **booking trends**
- Measure **occupancy and capacity utilization**
- Compare **hotel-wise and category-wise performance**

Interactive visuals and KPIs enable **data-driven revenue decisions**.

---

## 📁 Dataset Structure

The project follows a **Star Schema** for efficient analytics and optimized query performance.

### ⭐ Dimension Tables

**dim_date.csv**
- `date` – Calendar dates (May, June, July)
- `mmm yy` – Month-Year format (e.g., May 25)
- `week no` – Week number
- `day_type` – Weekday / Weekend

**dim_hotels.csv**
- `property_id` – Unique hotel identifier
- `property_name` – Hotel name
- `category` – Luxury / Business
- `city` – Hotel location

**dim_rooms.csv**
- `room_id` – Room type (RT1, RT2, RT3, RT4)
- `room_class` – Standard, Elite, Premium, Presidential

---

### 📌 Fact Tables

**fact_aggregated_bookings.csv**
- `property_id`
- `check_in_date`
- `room_category`
- `successful_bookings`
- `capacity`

**fact_bookings.csv**
- `booking_id`
- `property_id`
- `booking_date`
- `check_in_date`
- `check_out_date`
- `no_guests`
- `room_category`
- `booking_platform`
- `ratings_given`
- `booking_status` (Cancelled, Checked Out, No Show)
- `revenue_generated`
- `revenue_realized` *(40% deduction for cancelled bookings)*

---

## 🎯 Key Features

- 📈 Revenue generated vs. revenue realized analysis  
- 📉 Booking performance tracking (success, cancellations, no-shows)  
- 🏨 Occupancy and capacity utilization metrics  
- 🗓️ Temporal trends (day, week, month)  
- 🏢 Property-wise and category-wise comparisons  
- ⭐ Customer ratings and booking platform insights  

---

## 🛠️ Tools & Technologies

<p align="left">
  <img src="https://upload.wikimedia.org/wikipedia/commons/c/cf/New_Power_BI_Logo.svg" width="60"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/8/87/CSV_Icon.svg" width="60"/>
</p>

- **Microsoft Power BI** – Data modeling & visualization  
- **CSV Datasets** – Historical booking data  
- **Star Schema** – Optimized analytics design  

---

## 📈 Analytics Capabilities

- Revenue trend analysis  
- Occupancy rate calculations  
- Booking platform performance comparison  
- Customer satisfaction analysis  
- Cancellation and no-show rate analysis  
- Weekend vs. weekday performance  
- Property-level and category-level insights  

---

## 📂 Repository Structure

