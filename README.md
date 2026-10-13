# OLA Booking Data Analysis Project

## Project Overview

The **OLA Booking Data Analysis Project** focuses on analyzing cab booking data using MySQL and Power BI to understand ride booking patterns, customer behavior, booking outcomes, and revenue performance.

The project uses SQL to explore and analyze booking records, calculate key business metrics, and identify trends in ride activity. Power BI is used to transform the analysis into an interactive dashboard that presents important performance indicators and business insights in a clear, visual format.

The objective is to demonstrate practical data analytics skills, including SQL querying, data exploration, business metric analysis, and interactive data visualization.

## Business Objectives

The project aims to answer important business questions related to cab booking operations and revenue performance.

- Analyze total booking volume and ride trends.
- Understand booking statuses, including completed and cancelled rides.
- Evaluate revenue and fare distribution.
- Explore customer booking behavior.
- Identify daily and monthly booking patterns.
- Present key performance indicators through an interactive Power BI dashboard.

## Tools and Technologies

| Tool | Purpose |
|---|---|
| MySQL | Data exploration, SQL analysis, aggregations, and business queries |
| Power BI | Interactive dashboard development and data visualization |
| CSV | Source dataset containing booking records |
| GitHub | Version control, project documentation, and portfolio presentation |

## Dataset Description

The project uses a CSV dataset containing OLA booking information.

Depending on the fields available in the dataset, the analysis may include:

- Booking identifiers and booking dates
- Booking status
- Customer-related information
- Ride and vehicle details
- Ride distance and fare amount
- Payment information
- Cancellation details

The actual columns and their definitions should be documented according to the supplied dataset.

## Analysis Performed Using SQL

SQL is used to explore booking records, summarize business metrics, and answer operational questions.

### 1. Booking Performance Analysis

This analysis focuses on understanding overall booking activity.

Key questions:
- What is the total number of bookings?
- How many rides were completed successfully?
- How many bookings were cancelled?
- What percentage of bookings resulted in completed rides?
- How does booking volume change over time?

**Business value:** Helps evaluate overall booking activity and identify patterns in successful and unsuccessful rides.

### 2. Booking Status Analysis

This analysis examines the distribution of booking outcomes.

Key questions:
- What is the distribution of bookings by status?
- What percentage of bookings were completed versus cancelled?
- Which cancellation categories are most frequent, if cancellation reasons are available?
- How do booking outcomes vary over time?

**Business value:** Helps identify booking completion patterns and areas where operational improvements may be needed.

### 3. Revenue and Fare Analysis

This analysis explores revenue-related metrics available in the dataset.

Key questions:
- What is the total fare amount associated with completed rides?
- What is the average fare per completed ride?
- How does revenue change across different time periods?
- How does fare distribution vary across ride categories, if available?
- Which payment methods are most frequently used, if payment data is available?

**Business value:** Helps evaluate fare patterns and understand revenue performance.

*Revenue calculations should use an appropriate business definition. Total fare amount, collected revenue, and net revenue are not necessarily the same.*

### 4. Customer Booking Analysis

This analysis focuses on customer activity and booking behavior.

Key questions:
- How many unique customers booked rides?
- Which customers have the highest number of bookings, if customer identifiers are available?
- How frequently do customers book rides?
- How does customer activity vary across time periods?

**Business value:** Helps understand customer activity and identify opportunities to improve customer engagement.

### 5. Time-Based Trend Analysis

This analysis explores booking activity over different time periods.

Key questions:
- How many bookings occur each day or month?
- Which periods have the highest booking volume?
- How does completed ride volume change over time?
- Are there visible patterns in booking and revenue trends?

**Business value:** Helps identify demand patterns and supports operational planning.

The exact SQL questions and metrics should reflect the queries implemented in `ola_sql.sql`.

## Power BI Dashboard

Power BI is used to present the booking analysis through interactive visualizations.

### Dashboard Components

**Key Performance Indicators (KPIs)**

- Total Bookings
- Completed Rides
- Cancelled Bookings
- Completion Rate
- Revenue or Total Fare Amount, according to the selected metric

**Booking Status Analysis**

Visualizes the distribution of completed, cancelled, and other booking outcomes available in the dataset.

**Revenue Analysis**

Displays revenue or fare patterns using appropriate charts and comparisons.

**Booking Trend Analysis**

Shows changes in booking volume over daily or monthly periods.

**Interactive Filters**

Allows users to explore the available data by relevant dimensions, such as date, booking status, vehicle type, or payment method, depending on the dashboard design.

### Dashboard Objective

The dashboard is designed to make booking performance easier to understand by combining key metrics, trend analysis, and visual comparisons in a single reporting interface.

## Key Business Insights

The analysis is intended to identify findings such as:

- The proportion of bookings that result in completed rides.
- Changes in booking volume across time periods.
- Revenue distribution and average fare patterns.
- Common booking cancellation patterns, where the required data is available.
- Differences in booking behavior across customer or ride categories.

**Actual findings:** Add the most important results from your SQL queries and Power BI dashboard here. Include verified figures or screenshots rather than assuming a trend before analyzing the data.

## Project Workflow

The project follows a structured data analytics workflow:

1. **Data Exploration:** Review the CSV dataset, understand its structure, and identify the available fields.
2. **Data Preparation:** Check for missing values, duplicate records, inconsistent formats, and invalid values where relevant.
3. **SQL Analysis:** Write queries to calculate booking metrics and analyze business performance.
4. **Metric Validation:** Verify important calculations and ensure that the SQL results are consistent with the underlying data.
5. **Dashboard Development:** Import the data or analytical results into Power BI and build relevant visualizations.
6. **Insight Generation:** Interpret the results and document findings that can support business decisions.
7. **Documentation:** Maintain the SQL scripts, dashboard file, and project README in GitHub.

## Repository Structure

```text
OLA-Booking-Analysis/
│
├── booking_ola.csv    # Source booking dataset
├── ola_sql.sql        # SQL queries for booking analysis
├── ola.pbix           # Power BI dashboard
└── README.md          # Project documentation
```

### File Description

- `booking_ola.csv` — Contains the source booking records used for analysis.
- `ola_sql.sql` — Contains SQL queries for data exploration, business metric calculations, and booking analysis.
- `ola.pbix` — Power BI report file containing the dashboard and associated data model.
- `README.md` — Documents the project objectives, tools, analysis areas, workflow, and findings.

## How to Run the Project

### Prerequisites

- MySQL Server and a compatible SQL client, such as MySQL Workbench.
- Microsoft Power BI Desktop.
- The project CSV dataset.
- The SQL scripts and Power BI report file.

### Step 1: Download the Repository

Clone the repository using Git:

```bash
git clone <your-github-repository-url>
cd OLA-Booking-Analysis
```

Alternatively, download the repository as a ZIP file from GitHub.

### Step 2: Import the Dataset into MySQL

Create a database and import `booking_ola.csv` into a table.

Ensure that the table name, column names, and data types match the SQL queries in `ola_sql.sql`.

### Step 3: Execute the SQL Queries

Open `ola_sql.sql` in MySQL Workbench or another compatible SQL client.

Execute the queries to explore booking records, calculate business metrics, and analyze booking performance.

### Step 4: Open the Power BI Dashboard

Open `ola.pbix` using Power BI Desktop.

If prompted, configure the appropriate data source or refresh the data connection according to the original setup.

### Step 5: Explore the Dashboard

Use the available visuals and filters to explore booking activity, booking outcomes, fare patterns, and time-based trends.

*Note: Exact setup steps may vary depending on how the SQL database and Power BI report were originally configured.*

## Skills Demonstrated

This project demonstrates practical application of:

- SQL and relational database querying
- Data exploration and validation
- Data cleaning concepts
- Aggregations and business metric calculations
- Booking and revenue analysis
- Time-based trend analysis
- Power BI dashboard development
- Data visualization
- Business problem-solving
- GitHub project documentation

## Conclusion

The OLA Booking Data Analysis Project demonstrates how SQL and Power BI can be used together to examine transportation booking data and present business performance in an accessible format.

SQL supports structured data analysis and metric calculation, while Power BI helps communicate the results through interactive visualizations.

The project provides a practical example of applying data analytics techniques to a business-oriented dataset and converting raw booking records into information that can support operational and business decisions.

## Author

**Priyanka Barman**

Aspiring Data Analyst | SQL | Excel | Power BI | Python

This project is part of my data analytics portfolio, showcasing practical learning in SQL-based analysis, business metrics, and interactive dashboard development.
