# 🚗 Uber Ride Data Analysis

This repository contains an end-to-end data analysis project on Uber ride bookings in the NCR region. 
The goal is to derive meaningful business insights related to demand patterns, cancellations, revenue performance, and trip economics using Excel, Python, and Power BI.

## 📌 Project Overview

This project analyzes ride-booking data from Uber in the National Capital Region (NCR) to understand:
- How demand varies across different times of day  
- What factors contribute to ride cancellations  
- Which segments, distances, and vehicle types drive revenue  
- Key operational challenges and insights for business decisions

The analysis is performed using Python for data cleaning and exploratory data analysis, and Power BI for interactive reporting.

## 🧰 Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Data cleaning, preprocessing, and EDA |
| Jupyter Notebook | Code and exploratory analysis |
|Microsoft Excel | Initial data review and validation checks |
| Power BI | Dashboard creation and visualization |
| DAX | Measure calculation and analysis logic |

## 🧾 Dataset Description

The dataset used in this project is sourced from Kaggle and contains Uber ride booking records from the NCR region.
The ride dataset includes the following features:

| Feature | Description |
|---------|-------------|
| Booking_ID | Unique ride identifier |
| Ride_Date | Date of the ride booking |
| Ride_Time | Time of ride booking |
| Booking_Status | Status (Completed, Cancelled, Incomplete) |
| Ride_Distance | Distance of the ride |
| Booking_Value | Fare collected |
| Vehicle_Type | Type of vehicle used |
| Pickup_Location | Start of the trip |
| Drop_Location | End of the trip |
| Cancellation_Reason | Reason for cancellation |
| Driver_Rating | Rating given to driver (if completed) |
| Customer_Rating | Rating given by customer (if completed) |

_(Refer to the documentation folder for a full data dictionary.)_

## 🗂️ Project Workflow

### 1️⃣ Data Understanding & Initial Review (Excel)

- Reviewed raw dataset structure and column consistency
- Performed preliminary data inspection
- Checked basic summaries and data formatting
- Identified potential inconsistencies before analysis

### 2️⃣ Data Preprocessing & EDA (Python – Pandas)

- Checked for duplicate records and handled missing values
- Cleaned and standardized date & time variables
- Computed descriptive statistics for key numerical features
- Analyzed booking status distribution (Completed, Cancelled, etc.)
- Identified peak-hour demand patterns
- Performed revenue and distance-based trend analysis
- Conducted correlation analysis between numerical variables
- Visualized trends using histograms and time-series charts

### 3️⃣ Business Insights & Dashboard Development (Power BI)

- Loaded processed dataset into Power BI
- Created calculated measures (Total Rides, Revenue, Cancellation Rate)
- Built interactive dashboards with filters and slicers
- Visualized demand trends and cancellation patterns
- Analyzed revenue drivers and trip performance
- Used bar charts, line charts, donut charts, and KPI cards
- Highlighted key insights for operational and business decision-making

## 📈Dashboard Overview

### 🚗📊 RIDE PERFORMANCE OVERVIEW

<img width="1353" height="745" alt="image" src="https://github.com/user-attachments/assets/3268b765-d853-4ca1-83fe-bdceba340f14" />

- Displays total bookings, completed rides, cancellation rate, and average fare
- Shows hourly booking trends to identify peak demand periods
- Analyzes ride distribution across distance buckets
- Provides booking status breakdown for operational monitoring

### ⏰ Peak Hours & Cancellations

<img width="1352" height="746" alt="image" src="https://github.com/user-attachments/assets/b842f17d-387c-40cc-bd0f-a27dcf3cad1d" />

- Highlights total failed rides and cancellation split (driver vs customer)
- Visualizes hourly cancellation trends
- Identifies high-risk time slots with operational pressure
- Analyzes incomplete ride patterns by hour

### 💵 🛣Revenue & Distance Analysis

<img width="1345" height="742" alt="image" src="https://github.com/user-attachments/assets/a620f6a6-9af0-4ca8-854b-6f6cf1fc2918" />

- Displays total revenue, average fare, and average distance
- Analyzes fare distribution across booking value buckets
- Examines revenue efficiency by distance segments
- Compares revenue contribution by payment methods and vehicle types

## 📊 Key Insights

Here are some major findings from the analysis:

- 📉 **High Cancellation Rate**  
  Nearly **38% of total bookings are cancelled**, indicating operational inefficiencies.

- ⏰ **Peak Hour Cancellation Patterns**  
  Driver-initiated cancellations spike during evening peak hours (~7 PM), suggesting supply–demand imbalance.

- 💰 **Revenue Drivers**  
  Short-distance trips show higher revenue efficiency per ride, while long-distance rides contribute the largest booking volume overall.

- 🛣️ **Distance & Economics**  
  Distance segment analysis reveals that rides above 10 km dominate total booking volume.

- 📊 **Operational Pressure**  
  Peak-hour demand combined with high cancellation rates indicates a gap in driver availability affecting service reliability.

## ⭐ Future Enhancements

- Analyze driver allocation strategies during evening peak hours to reduce demand–supply gaps.
- Evaluate supply–demand imbalance during high-cancellation time slots using predictive modeling.
- Optimize in-app booking workflow to reduce cancellation friction and improve customer experience.

## Contact

Saranya K

saranyakrishnan6379@gmail.com
