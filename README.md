# LOGISTICS DASHBOARD

The dashboard below is an interactive report focusing on shipment volumes, transit time, carrier status and country distribution. 
There are two more views specifically focusing on: delivered orders and orders in transit. 
The top charts of the dashboard contains the most important KPI’s. 
You can navigate through the dashboard using the menu on the right. 
Each chart shows the most important trends, figures and numbers.

<image src="/Dashboard_2.png" alt="Logistics Dashboard">
  
## GOAL

The purpose of a dashboard is to review the most important KPI’s and results on the one page. 
The dashboard should show the managers how the logistics process performs.  

## METRICS
Metrics focusing on **delivered orders**:
- OTP (On Time Performance - relation of orders delivered on time and total numbers of orders in the period)
- Transit Time - average transit time in a region (light blue area is a range between min and max transit time)
- Total Shipments - number of shipped orders in a period
- Top-10 Countries - the most demanded destination countries  

Metrics focusing on **orders in transit**:
- Current Delivery Status - Orders numbers by delivery status (easy way to find problem orders)
- Carrier Status - Orders numbers by carrier status (more details explanation of current delivery situation)
- Carrier Status by Order Number - the tool to check exact order for status


## PROJECT STEPS
- Collect row data from different sources (CRM, carriers shipment systems)
- Join tables and editing format using MS PowerQuery
- Add support columns and calculate required key performance indicators
- Create pivot table and related chart for each metric
- Join all required charts on the board
- Add timelines and filters

## RESULT
- The dashboard gives on-time delivery performance overview and current status of shipments in transit. Some filters can be applied to choose dates, regions or carriers to review the performance for the past period, provide root cause analysis and find weaknesses in process.
- Monitoring of current order status allows to prevent shipments delay in advance. Inadequate carrier status can be selected and delivery problems might be solved on time.
- Timeline on the charts can be group by weeks, months, years or region. The drill-dawn clearly groups information ranging from the big picture down to individual case.
- By using the dashboard, you will discover the right insights in an easy way. You can apply filters yourself and review different graphs. By immediately having the right information available, correct decisions can be made.


