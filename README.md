Power BI Sales & Returns Analysis

Project Overview

This project is a Power BI data modelling and reporting exercise built around sales, product and returns data.

The report demonstrates the use of Power BI data modelling, relationships, DAX measures, visualisations, KPI reporting and geographic analysis to turn transactional data into an interactive analytical report.

Tools & Technologies

Microsoft Power BI

Power Query

DAX (Data Analysis Expressions)

Power BI Data Model & Relationships

Interactive data visualisation

Geographic mapping

Data Model

The model contains the following core tables:

Sales

The main transactional dataset containing fields such as:

Category

City

Country/Region

Coupon Code

Custom States

Customer ID

Customer Name

Experience Rating

Order Date

Order ID

This table provides the primary customer, geographic and transaction-level information used for analysis.

Products Master

A product reference table containing fields including:

Category

Cost

Loss Percent

Loss Percent (DAX)

Negative Profit

This table provides product-level information used for profitability and loss analysis.

Returns

The returns dataset contains fields including:

Customer ID

Order ID

Product

Product ID

Quantity

Return Date

Return ID

This table supports analysis of returned products and quantities.

Measures

A dedicated measures table is used to organise the report's DAX calculations, including:

Sum of Quantity

Total Sales

Gauge Gap to Target

Gauge Target

Gauge Maximum

Keeping measures in a dedicated table helps separate calculations from the underlying data tables and keeps the model organised.

Data Modelling & Relationships

The model uses relationships between the product master and transactional datasets.

The Products Master table acts as a reference table, connecting product-related information with the sales and returns data.

The model demonstrates the use of one-to-many relationships within Power BI and provides a foundation for analysing sales, profitability and returns across different dimensions.

DAX & Calculations

The project includes DAX calculations used to support analytical reporting and KPI visualisations.

Examples include:

Total Sales

Sum of Quantity

Gauge Gap to Target

Gauge Target

Gauge Maximum

Loss Percent

Negative Profit

These calculations allow the report to compare actual performance against targets and analyse profitability and loss.

Report Visualisations

The report includes several types of Power BI visualisations, including:

Customer information tables

Column charts

Geographic maps

KPI/gauge visualisations

Interactive navigation elements

Geographic Analysis

Map visualisations are used to analyse sales/loss information geographically using fields such as State, City and Country/Region.

KPI & Target Analysis

Gauge visualisations provide a visual comparison between actual sales performance and defined targets.

Key Power BI Skills Demonstrated

This project demonstrates practical experience with:

Data modelling

Table relationships

One-to-many relationships

DAX measures

Calculated fields

KPI reporting

Target analysis

Sales analysis

Profit/loss analysis

Returns analysis

Customer analysis

Geographic analysis

Data visualisation

Interactive report navigation

Dedicated measures tables

Power Query/data preparation

Analytical Questions

The report can be used to investigate questions such as:

What are the total sales?

How many units have been sold?

How are sales distributed geographically?

Which categories contribute most to sales?

Where are losses occurring?

What is the relationship between sales performance and the target?

What is the gap between actual sales and the target?

Which products or transactions are associated with returns?

How can customer information be analysed alongside sales performance?

Project Structure

Power-BI-Sales-Analysis/
│
├── Power bi test file (1).pbix
└── README.md

How to Use

Download or clone the repository.

Open Power bi test file (1).pbix using Microsoft Power BI Desktop.

Explore the report visualisations.

Open Model view to examine the data relationships.

Review the tables and fields in the Data pane.

Review the DAX measures used to generate the KPIs and visualisations.

Project Purpose

This project was created as a practical demonstration of Power BI data analysis, data modelling, DAX and business intelligence skills.

It can form part of a data analytics portfolio demonstrating experience in Power BI, data modelling, KPI reporting, data visualisation and business intelligence.

Author
