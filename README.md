# Hotel-Analytics-Dashboard-Using-Power-BI

## 📌 Project Overview

This project focuses on analyzing hotel data using **Microsoft Power BI**.

The main purpose of this project is to understand hotel booking and stay performance and present the information through interactive dashboards.

The project covers different areas such as **booking demand, guest behaviour, stay performance, staff and room performance, and booking or stay problems**.

---

## 🎯 Objectives

The main objectives of this project are:

* To understand hotel booking demand.
* To analyze guest booking behaviour.
* To evaluate stay performance.
* To understand staff and room usage.
* To identify booking and stay-related problems.
* To create an interactive dashboard for easy analysis.

---

## 📂 Dataset

The project uses multiple datasets related to hotel operations:

* **Guests** – Guest details and guest types.
* **Hotels** – Hotel information such as hotel name, city, and star rating.
* **Rooms** – Room types, prices, occupancy, and room status.
* **Bookings** – Booking details, booking channel, requested room type, nights booked, and booking amount.
* **Stays** – Check-in, check-out, stay status, nights stayed, and service requests.
* **Staff** – Staff details and staff information.

These tables were connected in Power BI using the relevant IDs.

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query** – for data cleaning and transformation
* **DAX** – for creating measures and calculations
* **Data Modelling** – for connecting the tables
* **Power BI Visualizations** – for creating interactive dashboards

---

## 📊 Dashboard Pages

### 1. Booking Demand

This page focuses on overall booking activity.

Key KPIs include:

* Total Bookings
* Total Booking Amount
* Average Booking Amount
* Average Nights Booked

The page also shows bookings by hotel, booking channel, and requested room type.

---

### 2. Guest Booking Behaviour

This page focuses on how guests interact with the hotel.

Key KPIs include:

* Total Guests
* Total Bookings
* Bookings per Guest
* Guest Booking Amount

The dashboard also compares guest types, guest activity, hotels, and booking trends.

---

### 3. Stay Performance

This page focuses on the performance of hotel stays.

Key KPIs include:

* Total Stays
* Completed Stays
* Cancelled Stays
* No-show Stays
* Average Nights Stayed
* Average Stay Duration

The visuals help understand stay outcomes and hotel-wise stay performance.

---

### 4. Staff and Room Performance

This page focuses on hotel resources.

Key KPIs include:

* Stays Handled
* Room Usage
* Average Stay Duration by Staff
* Average Nights Stayed by Room Type

It helps understand staff workload and room usage.

---

### 5. Booking and Stay Problems

This page focuses on identifying booking and stay-related problems.

Key KPIs include:

* Problem Stays
* Problem Rate
* Cancelled Stays
* No-show Stays
* Average Service Requests

The visuals help compare problems across hotels and understand service request levels.

---

### 6. Executive Summary

The final page provides an overall summary of the hotel data.

It includes important KPIs and visuals for:

* Booking activity
* Revenue
* Guests
* Stays
* Stay status
* Problem rate

This page provides a quick overview of the complete analysis.

---

## 📈 Key DAX Measures

Some of the important measures created in the project are:

* **Total Bookings**
* **Total Booking Amount**
* **Average Booking Amount**
* **Average Nights Booked**
* **Total Guests**
* **Bookings per Guest**
* **Total Stays**
* **Completed Stays**
* **Cancelled Stays**
* **No-show Stays**
* **Average Nights Stayed**
* **Average Stay Duration**
* **Stays Handled**
* **Room Usage**
* **Problem Stays**
* **Problem Rate**
* **Average Service Requests**

---

## 🧹 Data Preparation

Before creating the dashboards, the data was prepared using Power Query.

The main steps included:

* Checking column names and data types.
* Checking missing or blank values.
* Checking duplicate records.
* Cleaning unnecessary spaces.
* Checking consistency in categorical values.
* Creating relationships between the tables.

---

## 🔗 Data Model

The tables were connected using primary and foreign key relationships.

The main relationships include:

* Hotels → Rooms
* Hotels → Bookings
* Guests → Bookings
* Bookings → Stays
* Rooms → Stays
* Staff → Stays

This model allows the different datasets to work together for analysis.

---

## 💡 Conclusion

This project helped me understand how Power BI can be used to convert raw hotel data into meaningful dashboards.

Through this project, I gained practical experience in **data cleaning, data modelling, DAX, KPI creation, and dashboard design**.

The final dashboard provides an interactive way to understand hotel bookings, guests, stays, resources, and operational problems.
