# Hotel Booking Demand

## Overview
This project is an *Excel-based* hotel-booking analysis dashboard.  
The goal of the project was to practice data cleaning, pivot table creation and dashboard creation using Microsoft Excel.

The result is an **interactive dashboard** that provides insights into number of cancellations, type of guest who cancelled (families or single person).

---

## Dataset
Source: Online Hotel Booking 

Link: https://www.kaggle.com/code/mohamedzayton/hotel-booking

**Note**: Only first 200 rows of the dataset were used for analysis. This was done to make handling data in Excel more manageable.


- The Dataset includes following information:
  - Hotel Type (City Hotel or Resort Hotel)
  - Cancellation (Guest cancelled the booking or not)
  - Arrival Date Year
  - Arrival Date Month
  - Number of Adults
  - Number of Children
  - Number of Babies
  - Country
  - Reserved Room Type
  - Assigned Room Type
  - Reservation Status
  - Reservation Status Date
  - Room status
  - Guest Type (Couple / Single / Family)
  

---

## Data Preparation 
Basic data cleaning was performed directly in Excel using Power Query Editor including:
- Filtering the dataset (keeping only required columns)
- Adding required columns
- Removing duplicate records
- Handling missing values 


---

## Analysis & Pivot Tables
An analysis was done using Excel pivot tables, which gave the following insights:
- guest_type vs Total Guests (Count of room_status) vs Canceled Bookings (Sum of is_canceled): Maximum bookings were by couples and max cancellations were also by couples.
- room_status vs Count of room_status vs Canceled Bookings(Sum of is_canceled): Number of cancellations are not much affected by whether guest got their desired room or not.
- arrival_date_month vs Total Guests(Count of arrival_date_month) vs Canceled Bookings(Sum of is_canceled): Maximum bumber of guests and maximum number of cancellations were in the month of August.
- hotel vs  No. of Reservations (Count of hotel) vs Canceled Bookings(Sum of is_canceled): Number of reservations were more in City Hotel and number of cancellations were also more in city hotel.


---

## Dashboard
The Excel dashboard provides detailed insights using:
- Pivot charts

A preview of the dashboard is shown below:

![Hotel Booking Demand Dashboard](HotelBookingDashboardImage.jpg)

---

## Tools Used
- Microsoft Excel
  - Power Query Editor
  - Formulas
  - Filters
  - Pivot Tables
  - Charts

  ---


  ## Project Structure
- Raw Data: HotelBookingsData.csv
- Cleaned Data: HotelBookingsCleaned.csv
- Pivot Tables: HotelBookingsPivot.csv
- Dashboard in Excel: HotelBookingsDashboard.xlsx
- Dashboard Image: HotelBookingsDashboardImage.jpg

