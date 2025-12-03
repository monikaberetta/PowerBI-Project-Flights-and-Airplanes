**Airline Performance \& Operations Dashboard (Power BI)**

This project presents an interactive Power BI dashboard analyzing multiple aspects of airline performance.

The report covers operational efficiency, punctuality, route performance, financial metrics, geography insights, and scenario-based revenue simulations.


It demonstrates skills in data cleaning, data modeling, DAX, visual design, and business analysis.



* Project Overview
  
The dashboard provides a multi-page analytical view of airline operations, including:

Key operational KPIs

Airline and route performance

Passenger and revenue trends

Global route network mapping

Delay analysis

Detailed flight-level data

What-If simulation for pricing strategy

Executive summary

The goal is to offer a comprehensive yet intuitive view of airline performance for managers, analysts, and strategic decision-makers.

* Data Sources
The dataset includes simulated flight and operational records:
Airlines
Flight schedules
Passenger counts
Revenue \& pricies
Departure \& arrival delays
Geographical information (countries, airports)
Prepared manually for training and BI portfolio purposes

* Data Model
Main tables:
Flights – core fact table
Airlines – dimension
Calendar – date dimension
Routes – airport/route dimension
Edges – geographic connections
What-If parameters – scenario simulation
Relationships follow a star-schema design, optimizing filtering and model performance.

1\. Overview (Main KPIs)
Provides a snapshot of airline performance, including:
On-Time Performance %
Cancel Rate %
Avg Arrival Delay
Total Passengers
Total Revenue
Revenue trends and delay patterns
This page serves as a high-level executive view.

2\. Routes \& Airlines
Deep-dive comparison of:
Total passengers per airline
Performance by route
Matrix view with KPIs
Conditional formatting to highlight strengths/weaknesses
Helps identify profitable and underperforming routes.

3\. Geography
World map showing:
Passenger volumes per country
Arrivals vs departured
Route distribution
Supports a geographical understanding of the airline network.

4\. Operations
Operational performance metrics:
Departure delay
Arrival delay
Seasonal patterns
Hour-of-day analysis
Top/bottom performing carriers
Useful for identifying operational bottlenecks.

5\. Financials
Revenue-focused insights:
Total revenue per route
Fare vs distance relationship
Yield (USD per km)
Trend analysis
Cost per kilometer comparisons
Shows financial health and revenue drivers.

6\. Flight Details
A detailed table including:
Flight number
Airline
Origin–Destination
Delays
Revenue
Passengers
Includes Drillthrough from other pages for deeper analysis.

7\. Tooltip Page
Custom tooltip with flight KPIs appearing when hovering over visuals.
Improves data readability and user experience.

8\. What-If Analysis
Interactive pricing simulation:
User controls fare change (slider)
Dashboard recalculates revenue in real time
Shows revenue sensitivity to price adjustments
Useful for strategic decision-making.

9\. Summary Page
xecutive-level overview of the most important insights from the report.

**How to Use the Report**

1. Download .pbix file
2. Open in Power BI Desktop
3. Interact with slicers (Airline, Route, Year)
4. Use drillthrough to explore flight-level details
5.Experiment with What-If price scenarios




