# Customer-Visit-Management-Dashboard
Power BI dashboard for customer visit management, queue analysis, SLA compliance, service performance, and staff performance monitoring.

## Overview

The Customer Visit Management Dashboard is a Power BI project designed to provide a centralized view of customer visits, queue activity, service performance, SLA compliance, and staff performance across multiple service locations.

The dashboard transforms customer visit data into interactive insights that help monitor operational performance, identify service delays, analyze customer traffic patterns, and evaluate staff performance.

## Objectives

The main objectives of this project are to:

- Monitor customer visit volumes and visit statuses.
- Analyze waiting and service times.
- Track waiting-time and service-time SLA compliance.
- Identify peak visiting hours and visit trends.
- Analyze appointment, no-show, and abandonment patterns.
- Compare service categories and arrival channels.
- Monitor staff performance across different branches.
- Provide detailed visit-level analysis using drill-through functionality.

## Key KPIs

The dashboard includes the following KPIs:

- Total Visits
- Completed Visits
- Waiting Visits
- No-Show Visits
- Abandoned Visits
- Average Waiting Time
- Average Service Time
- Average Total Visit Time
- Abandonment Rate
- Waiting-Time SLA Compliance
- Service-Time SLA Compliance

## Dashboard Pages

### 1. Overview

Provides a high-level summary of customer visit operations, including:

- Main visit KPIs
- Visit volume by city
- Waiting-Time SLA Compliance
- Service-Time SLA Compliance
- Detailed visit records

### 2. Performance Trends

Provides time-based analysis of operational performance:

- Daily Visit Volume Trend
- Average Waiting-Time Trend
- Average Service-Time Trend
- Peak Visiting Hours
- No-Show and Abandonment Trend
- SLA Compliance Trend

### 3. Visit Analysis

Provides detailed analysis of customer visits:

- Service Volume by Category and Service
- Arrival Channel Comparison
- Appointment Status Analysis
- Hourly Queue-Volume Analysis
- Abandonment and No-Show Analysis

### 4. Staff Performance

Provides staff-level performance monitoring, including:

- Total Visits Handled
- Completed Visits
- Average Waiting Time
- Average Service Time
- Service SLA Compliance
- Abandoned Visits
- Staff Performance Comparison
- Branch-Level Staff Information

### 5. Staff Details

A drill-through page that allows users to select a staff member and view detailed information about their assigned customer visits.

## Interactive Features

The report includes:

- Synchronized slicers across report pages
- Search-enabled filters
- Drill-through functionality for staff details
- Interactive charts and tables
- Page navigation
- Geographic visit analysis
- Dynamic filtering by date, city, site, service, visit status, staff code, SLA status, and other dimensions

## Tools & Technologies

- **Power BI Desktop** – Dashboard development and data visualization
- **SQL Server** – Data storage and data preparation
- **SQL Server Management Studio (SSMS)** – Database management and SQL queries
- **DAX** – KPI and performance measure calculations
- **Power BI Service** – Dashboard publishing and scheduled refresh
- **GitHub** – Project documentation and version control

## Data

The project uses a synthetic customer visit dataset created for demonstration and analytical purposes.

The dataset contains information about:

- Customer visits
- Service locations
- Services and service categories
- Appointment status
- Arrival channels
- Waiting and service times
- SLA targets
- Staff assignments
- Visit outcomes

## Project Structure

```text
Customer-Visit-Management-Dashboard/
│
├── Dashboard/
│   └── Customer_Visit_Management_Dashboard.pbix
│
├── Data/
│   └── customer_visit_data.csv
│
├── SQL/
│   └── database_queries.sql
│
├── Screenshots/
│   ├── overview.png
│   ├── performance_trends.png
│   ├── visit_analysis.png
│   ├── staff_performance.png
│   └── staff_details.png
│
└── README.md
