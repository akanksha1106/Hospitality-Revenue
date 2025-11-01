# Hospitality-Revenue
# Hospitality Revenue Insights Dashboard
 #  Project Overview

The Hospitality Revenue Insights Dashboard is a data analysis project built using Python, Pandas, and Matplotlib.
It demonstrates how revenue performance in the hospitality industry can be analyzed using Key Performance Indicators (KPIs) such as:

- Occupancy Rate

- Average Daily Rate (ADR)

- Revenue per Available Room (RevPAR)

- Total Revenue

This project provides visual insights into daily trends and revenue distribution across different sources — Room, F&B, and Other revenue.

 # Objectives

Analyze and calculate key hospitality performance metrics.

Visualize occupancy and revenue trends over time.

Understand the relationship between room sales and revenue performance.

Provide data-driven insights for better revenue management.

# Tools & Technologies

Python – Main programming language

Pandas – Data manipulation and KPI calculations

Matplotlib – Data visualization and chart generation

Jupyter Notebook / VS Code – For development and analysis

#  Key Metrics Explained
Metric	Formula	Description
Occupancy Rate (%)	(Rooms Sold / Rooms Available) × 100	Measures the percentage of rooms occupied
ADR (Average Daily Rate)	Room Revenue / Rooms Sold	Indicates the average room rate per night
RevPAR (Revenue per Available Room)	Room Revenue / Rooms Available	Shows how much revenue is generated per available room
Total Revenue	Room + F&B + Other Revenue	Represents overall revenue across departments
# Dataset Description

The dataset is sample-generated using Pandas for 10 days of hotel operations.

Column	Description
Date	Day of operation
Rooms_Available	Total rooms available per day
Rooms_Sold	Number of rooms sold per day
Room_Revenue	Revenue earned from room sales
F&B_Revenue	Revenue from food & beverage services
Other_Revenue	Revenue from other sources (spa, parking, etc.)
# Features in Code

Data Creation:
Synthetic dataset created using pandas.DataFrame().

KPI Calculation:
Calculates Occupancy Rate, ADR, RevPAR, and Total Revenue.

Summary Display:
Prints overall average metrics and total revenue for 10 days.

# Visualizations:

Line chart showing Occupancy Rate and ADR trend.

Stacked bar chart for Revenue Breakdown by Source.

Line chart for RevPAR trend.

 Output Example

Console Summary:

--- Hospitality Revenue Insights Summary ---
Average Occupancy (%): 85.5
Average ADR: 1064.12
Average RevPAR: 910.0
Total Revenue (10 days): 947500


# Visual Outputs:

 Occupancy & ADR trend chart

 Stacked revenue breakdown chart

 RevPAR trend chart
