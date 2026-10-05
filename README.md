# Customer Support Ticket & Service Quality Analytics
## Project Overview

This project analyzes customer support ticket data to evaluate service quality, SLA performance, resolution efficiency, and customer satisfaction. An interactive Power BI dashboard was developed to identify operational patterns, service bottlenecks, and areas for improvement.

## Business Problem

Customer support teams need to resolve issues efficiently while maintaining service quality and meeting agreed service-level commitments. This project analyzes ticket volume, priorities, support performance, resolution times, SLA compliance, and customer satisfaction to identify key problem areas and provide data-driven recommendations for improving support operations.

## Objective

* Analyze customer support ticket volume and status.
* Evaluate first-response and resolution SLA performance.
* Identify factors affecting resolution time and customer satisfaction.
* Analyze support team and agent workload.
* Identify key service bottlenecks and improvement opportunities.
* Provide actionable business recommendations.

## Dataset

The project uses a customer support interaction dataset containing **2,330 unique support tickets**.

Key information includes:

* Ticket status and priority
* Support topic and product group
* Agent and support group
* Ticket creation, response, resolution, and closing times
* Expected and actual SLA performance
* Customer satisfaction

* ## Tools & Technologies

* **Power BI** — Data modeling, DAX, interactive dashboards, and reporting
* **Power Query** — Data cleaning and transformation
* **DAX** — KPI and SLA performance calculations
* **Excel** — Initial data review and validation

## Data Preparation

The dataset was prepared in Power Query before analysis.

Key preparation steps included:

* Verified unique Ticket IDs and checked for duplicate records.
* Standardized column names and data types.
* Converted date/time fields and duration fields to appropriate formats.
* Created date and duration fields for response and resolution analysis.
* Created calculated SLA status fields: **Within SLA** and **SLA Violated**.
* Preserved legitimate missing values associated with unresolved tickets.
* Validated the data for negative durations and inconsistencies.

## Analysis & Power BI Dashboard

The analysis was performed using Power BI to evaluate customer support performance across four key areas:

### 1. Executive Overview

* Ticket volume and status distribution
* Monthly ticket trends
* Ticket priority and topic analysis
* SLA compliance by priority
* Customer satisfaction by priority

### 2. SLA & Service Quality Analysis

* First-response SLA compliance
* Resolution SLA compliance
* Average first-response time
* Average resolution time
* Customer satisfaction by support group

### 3. Operations & Agent Performance

* Daily ticket volume
* Agent workload
* Average resolution time by agent
* First-response SLA compliance by agent
* In-progress tickets by support group
* Customer satisfaction by agent

### 4. Ticket Insights & Root Cause Analysis

* Ticket distribution by topic and priority
* Resolution SLA compliance by topic
* Average resolution time by topic
* Customer satisfaction by topic

The dashboard provides an interactive view of support operations and helps identify service bottlenecks and areas requiring operational attention.


* Agent interactions
* Country and location information
