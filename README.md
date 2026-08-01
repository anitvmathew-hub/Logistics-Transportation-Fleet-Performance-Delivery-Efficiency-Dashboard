# Logistics_Transportation_Fleet_Performance_Delivery_Efficiency_Dashboard


## Project Overview

The Logistics & Transportation Analytics Dashboard is an interactive Business Intelligence solution developed entirely in Power BI to analyze fleet performance, delivery efficiency, route optimization, and operational productivity.

The dashboard transforms raw transportation data into meaningful visual insights through data modeling, DAX calculations, and interactive reports. It enables logistics managers to monitor key operational metrics, identify performance gaps, and make informed business decisions that improve delivery efficiency while reducing operational costs.


## Business Problem

Transportation companies often face challenges such as:

 * Increasing delivery delays
 * Rising fuel consumption
 * Uneven fleet utilization
 * Poor visibility into vehicle performance 
 * Difficulty tracking delivery efficiency
 * Inefficient route planning
 * High operational costs

This dashboard addresses these challenges by providing real-time analytics and interactive visualizations to improve operational performance.

## Project Objectives
 * Monitor overall fleet performance
 * Measure delivery efficiency across routes
 * Analyze vehicle utilization
 * Track fuel efficiency
 * Identify delayed deliveries
 * Evaluate route performance
 * Enable data-driven operational decisions
   
## Dataset Overview

The dataset contains transportation operational information including:
Dataset Fields: 

 ●	***Trip Data***: Trip ID, Vehicle ID, Driver ID, Origin, Destination, Distance (km), Fuel Consumed (liters), Delivery Status (On-Time/Late), Delivery Date.
 
 ●	***Vehicle Master***: Vehicle ID, Vehicle Type, Capacity, Maintenance Cost.

### Tools & Technologies
 * Microsoft Power BI
 * Power Query
 * DAX 
 * Data Modeling
 * Data Visualization


## Power BI Development Process

### Data Preparation

The dataset was imported into Power BI and transformed using Power Query.

#### Tasks performed:

 * Checked duplicate records
 * Handled missing value in Distance column
 * Corrected data types
 * Standardized date formats
 * Extracted Month and Time from Delivery Date Column.
 * Created calculated column Route.
 * Built relationships between tables Trip_Data and Vehicle_Master

### DAX Measures Used
  * Total Cost
  * Total Fuel
  * Total Trips
  * Total Distance
  * On-Time Delivery %
  * Fuel cost
  * Maintenance Cost
  * Delivery performance %
  * Cost per km
  * Fuel efficiency
    
### Dashboard Features

#### KPIs

 * Total Trips
 * On-Time Delivery %
 * Average Delivery Time
 * Total Distance 
 * Cost per Km
 * Total Fuel

#### Visualizations

 * Delivery Performance % by Route and Delivery_Status
 * Fuel Efficiency by Month
 * Total Trips by Delivery Status
 * On-Time Delivery % by Route
 * Fuel Efficiency, Cost per km and Total Distance by Vehicle_ID and Vehicle_Type



### Key Business Insights

 * Total Trips: **50**
 * Total Distance Covered: **53.61K km**
 * Total Fuel Consumed: **4.63K L**
 * Cost per km: **$10.05**
 * Some vehicles incur relatively high costs despite average fuel efficiency, suggesting maintenance or operational inefficiencies.
 * Fuel efficiency **decreased** from approximately **11.93 km/L in January to 11.39 km/L in February**.
 * Out of 50 total trips, 30 trips **(60%)** were completed **On-Time**, while 20 trips **(40%)** experienced **delays**.
 * Several routes such as **Bangalore–Pune, Chennai–Delhi, Delhi–Pune, and Mumbai–Pune achieved a 100% on-time delivery rate**, demonstrating consistently strong
   operational performance. A few routes show only 50–75% on-time delivery, indicating recurring delays that require operational review.

### Business Recommendations
 * Increase On-Time Delivery from 60% to a target of 85–90% by optimizing routes and schedules.
 * Reduce the 40% delay rate through proactive monitoring and real-time operational interventions.
 * Improve fleet profitability by assigning the most fuel-efficient vehicles to long-distance routes.
 * Monitor route and vehicle KPIs continuously to identify underperforming assets and improve overall logistics efficiency.


### Conclusion

This Power BI project demonstrates how logistics and transportation data can be transformed into actionable business insights through interactive dashboards and advanced analytics. By monitoring fleet utilization, delivery efficiency, route performance, and fuel consumption, the solution empowers logistics teams to improve operational efficiency, reduce costs, and enhance customer satisfaction through data-driven decision-making.



### Dashboard Preview

![Logistics_Transportation_Fleet_Performance_Delivery_Efficiency_Dashboard](image/logistics_project_screenshot.png)



