# Energy-Consumption-Dashboard
The Energy Consumption Dashboard is an interactive Power BI report designed to analyze building-level energy usage across multiple energy types (Water, Electricity, and Gas) in India. The dashboard provides insights into total consumption, cost analysis, energy distribution percentages, and comparative performance across buildings and energy categories. This project demonstrates data modeling, DAX calculations, relationship building, KPI design, and interactive dashboard development.

# Key KPIs

The dashboard highlights the following performance indicators:
1. Total Cost – Overall energy expenditure
2. Total Buildings – Number of buildings analyzed
3. Total Units Consumed – Combined energy usage
4. Energy Consumption % Distribution
5. % of Water Consumption
6. % of Electricity Consumption
7. % of Gas Consumption

# Dashboard Insights

* Water has the highest share of total consumption.
* Gas has the lowest overall consumption.
* Total Cost and Total Consumption are positively correlated.
* Energy usage varies significantly across buildings.
* Consumption and cost divergence is highest in Water category.

# Data Model Structure

The project uses a structured data model with:

1️. Energy Consumption Table
Date
Building
Energy Type
Consumption Units
Generated Relationship ID

2️. Rates Table
Year
Energy Type
Price per Unit (INR)
Unique ID (Year + Energy Type)

3️. Building Master Table
Building Name
State
Country (India)

Relationships were created using a composite key (Year + Energy Type) to calculate dynamic cost measures.

# DAX Measures Used

Examples of key measures:
Total Units Consumed
Total Cost (Consumption × Rate)
Percentage Contribution by Energy Type
Category-level Cost Calculation
Dynamic Insight Text Measures

# Tools & Technologies

Power BI Desktop
DAX (Data Analysis Expressions)
Power Query (Data Transformation)
Data Modeling & Relationships

# Requirements

To run this project:
Power BI Desktop (latest version recommended)
Basic understanding of:
Data modeling
DAX
Relationships
Power Query transformations

# How to Use

Download the .pbix file.
Open in Power BI Desktop.
Refresh data (if required).
Use the navigation buttons to filter energy types.
Explore KPI metrics and insights.

# Author

Madhavan Shanmugam
Power BI Developer | Data Analyst
