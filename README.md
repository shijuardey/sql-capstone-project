# sql-capstone-project
Project Overview

A SQL-based data analysis project designed to evaluate donor behavior, donation patterns, and fundraising performance to support data-driven decision-making for non-profit organizations.

Business Problem Statement

Non-profit organizations depend heavily on donor contributions to sustain operations and achieve fundraising goals. However, understanding donor behavior, donation frequency, demographic trends, and geographic performance can be challenging without structured data analysis.

This project aims to transform raw donor and donation records into actionable insights that help organizations:

Identify high-value donor segments.
Understand donation behavior patterns.
Improve donor retention strategies.
Support targeted fundraising campaigns.
Enhance overall fundraising effectiveness.
Dataset Description
Data Source

The dataset consists of donor and donation records provided for analytical purposes.

Tables Used
1. Donation_Data

Contains donor demographic information and donation-related metrics.

Key Columns:

ID
First_Name
Last_Name
Gender
State
Job_Field
Donation
2. Donor_Data

Contains donor profile and behavioral information.

Key Columns:

ID
Donation_Frequency
University
Car
Movie_Genre
Second_Language
Relationship

The two tables are connected using a common ID field in a one-to-one relationship.

Time Range

The dataset represents historical donor records. No specific date field or reporting period was provided in the source data.

Tools & Technologies Used
Database Management System (DBMS)
PostgreSQL
Query Language
SQL
Data Analysis Techniques
Data Cleaning
Data Validation
Data Integration
Aggregation Analysis
Segmentation Analysis
Descriptive Statistics
Key Findings
Total donations recorded amounted to $249,085.
Average donation value was $249.09 per donor.
Donation frequency is strongly associated with overall fundraising performance.
California, Texas, and Florida generated the highest donation values among all states.
Human Resources, Research & Development, and Product Management were the highest-contributing professional groups.
Data quality was generally suitable for analysis, although some demographic fields contained missing values.
Top Recommendations
Implement donor retention programs focused on recurring contributors to maximize long-term fundraising revenue.
Develop geographically targeted fundraising campaigns in high-performing states.
Improve data collection processes to reduce missing demographic information and support more advanced analytics.
# Donor and Donation Data Analysis using SQL

## Project Overview

A SQL-based data analysis project designed to evaluate donor behavior, donation patterns, and fundraising performance to support data-driven decision-making for non-profit organizations.

---

## Business Problem Statement

Non-profit organizations depend heavily on donor contributions to sustain operations and achieve fundraising goals. However, understanding donor behavior, donation frequency, demographic trends, and geographic performance can be challenging without structured data analysis.

This project aims to transform raw donor and donation records into actionable insights that help organizations:

* Identify high-value donor segments.
* Understand donation behavior patterns.
* Improve donor retention strategies.
* Support targeted fundraising campaigns.
* Enhance overall fundraising effectiveness.

---

## Dataset Description

### Data Source

The dataset consists of donor and donation records provided for analytical purposes.

### Tables Used

#### 1. Donation_Data

Contains donor demographic information and donation-related metrics.

**Key Columns:**

* ID
* First_Name
* Last_Name
* Gender
* State
* Job_Field
* Donation

#### 2. Donor_Data

Contains donor profile and behavioral information.

**Key Columns:**

* ID
* Donation_Frequency
* University
* Car
* Movie_Genre
* Second_Language

### Relationship

The two tables are connected using a common **ID** field in a one-to-one relationship.

### Time Range

The dataset represents historical donor records. No specific date field or reporting period was provided in the source data.

---

## Tools & Technologies Used

### Database Management System (DBMS)

* PostgreSQL

### Query Language

* SQL

### Data Analysis Techniques

* Data Cleaning
* Data Validation
* Data Integration
* Aggregation Analysis
* Segmentation Analysis
* Descriptive Statistics

### Visualization Tools

* Power BI (recommended for dashboard development and reporting)

---

## Key Findings

* Total donations recorded amounted to **$249,085**.
* Average donation value was **$249.09** per donor.
* Donation frequency is strongly associated with overall fundraising performance.
* California, Texas, and Florida generated the highest donation values among all states.
* Human Resources, Research & Development, and Product Management were the highest-contributing professional groups.
* Data quality was generally suitable for analysis, although some demographic fields contained missing values.

---

## Top Recommendations

* Implement donor retention programs focused on recurring contributors to maximize long-term fundraising revenue.
* Develop geographically targeted fundraising campaigns in high-performing states.
* Improve data collection processes to reduce missing demographic information and support more advanced analytics.

---

## Repository Structure

```text
donor-donation-sql-analysis/
│
├── README.md
├── SQL/
│   ├── schema_creation.sql
│   ├── data_cleaning.sql
│   ├── exploratory_analysis.sql
│   └── business_queries.sql
│
├── Dataset/
│   ├── Donation_Data.csv
│   └── Donor_Data.csv
│
├── Reports/
│   └── Donor_Donation_SQL_Report.pdf
│
├── Dashboards/
│   └── PowerBI_Dashboard.pbix
│
└── Documentation/
    └── Data_Dictionary.md
```

---

## How to Reproduce the Analysis

### Prerequisites

* PostgreSQL installed
* SQL client (pgAdmin, DBeaver, or similar)
* Power BI Desktop (optional for visualization)

### Setup Instructions

#### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/donor-donation-sql-analysis.git
cd donor-donation-sql-analysis
```

#### Step 2: Create the Database

```sql
CREATE DATABASE donor_analysis;
```

#### Step 3: Import the Datasets

Load:

* Donation_Data
* Donor_Data

into PostgreSQL.

#### Step 4: Execute SQL Scripts

Run scripts in the following order:

```text
1. schema_creation.sql
2. data_cleaning.sql
3. exploratory_analysis.sql
4. business_queries.sql
```

#### Step 5: Review Results

Analyze:

* Donation totals
* Donor segmentation
* Geographic performance
* Donation frequency patterns

#### Step 6: Build Dashboard (Optional)

Import query outputs into Power BI to create interactive visualizations and KPI dashboards.

### Live Repository

```text
https://github.com/shijuardey/sql-capstone-project.git
```

---

## License

This project is licensed under the MIT License.

```text
MIT License

Copyright (c) 2026

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files to deal in the Software
without restriction, including without limitation the rights to use, copy,
modify, merge, publish, distribute, sublicense, and/or sell copies of the
Software.
```
