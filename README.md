# Atliq Hospitality Analysis — Power BI Project

This is a professional Power BI dashboard built to analyze performance metrics of **Atliq Hotels**. The dashboard provides insights into occupancy, revenue, booking trends, room categories, and more, helping stakeholders make informed business decisions.

---

## Project Highlights

- **High-Level KPIs:**
  - Occupancy Rate
  - Total Successful Bookings
  - Average Revenue
  - Total Revenue
  - Total Capacity
  - Average Rating
  - Successful Booking %

- **Visual Breakdown:**
  - Revenue by City & Property
  - Average Rating by City
  - Booking Percentage by City
  - Revenue by Room Class and Category
  - Revenue by City and Hotel Category

- **Interactivity:**
  - Slicers for filtering by:
    - Booking Platform
    - Day Type
    - Room
    - Category
    - City

- **Clean and Modern Design:** 
  - Business-friendly layout with branded visuals and consistent color scheme.

---

## Folder Structure

| File | Description |
|------|-------------|
| ![Dashboard1](/Dashboard/Dashboard1.png) | Primary dashboard with city- and property-wise revenue views |
| ![Dashboard2](/Dashboard/Dashboard2.png) | Extended dashboard with room and category insights |
| ![/Relationship](/Dashboard/Relationship.png) | Power BI data model schema (ERD) |

---

## Tools Used

- **Power BI Desktop** – Data modeling & visualization
- **Microsoft Excel** – Data pre-processing
- **DAX (Data Analysis Expressions)** – KPI calculations and filtering

---

## Dataset Details

The dataset consists of fact and dimension tables related to hotel bookings:

### Fact Tables
- `fact_bookings`: Contains details like booking status, check-in/check-out, revenue, guests, ratings
- `fact_aggregated_bookings`: Aggregated data with successful bookings and capacity

### Dimension Tables
- `dim_hotels`: Hotel property metadata (name, city, category)
- `dim_rooms`: Room classifications
- `dim_date`: Calendar details

---

## Business Insights

- Identify top-performing cities and properties based on revenue
- Analyze room class performance to optimize offerings
- Measure occupancy efficiency and booking trends
- Compare customer satisfaction using average ratings

---

## About Me

Made with by **Kesar Bareliwala**  
[LinkedIn Profile](https://www.linkedin.com/in/kesar-bareliwala-467b472a8)

---




