# PowerBI Data Modelling Project

## Overview

This project focuses on designing and optimizing a scalable Power BI data model using 23 interconnected datasets. Instead of creating dashboards, the objective was to build a clean, high-performance semantic model that follows data modeling best practices and provides a reliable foundation for business reporting and analytics.

The project involved understanding the business context, transforming raw datasets into a structured Star Schema, optimizing table relationships, improving data quality, and implementing secure data access through Row-Level Security (RLS).

## Technologies Used

- Power BI Desktop
- Power Query
- DAX
- Star Schema Data Modeling
- Row-Level Security (RLS)

## Business Problem

The business data was spread across multiple datasets containing duplicate records, inconsistent values, unnecessary columns, and an unstructured data model. These issues made reporting difficult, increased model complexity, reduced performance, and created challenges in maintaining accurate business insights.

Additionally, the organization required controlled access to regional data so that users could only view information relevant to their assigned regions.

## Solution

To improve data quality and reporting performance, I transformed 23 raw datasets into a structured Star Schema by separating Fact and Dimension tables, cleaning inconsistent data, removing duplicates, and standardizing naming conventions. 
I optimized relationships using single-direction filtering, centralized DAX measures in a dedicated Measures table, and implemented Row-Level Security (RLS) to ensure users could only access data for their authorized regions. 
The resulting data model is cleaner, more scalable, secure, and better suited for efficient business reporting and analysis.

## Business Impact

This optimized data model provides a strong analytical foundation that enables faster, more reliable reporting and easier maintenance.

Key business benefits include:

- Improved report performance through an optimized Star Schema and efficient table relationships.
- Increased data quality by removing duplicate records and resolving inconsistencies before analysis.
- Reduced model complexity by eliminating redundant tables and organizing measures into a centralized structure.
- Enhanced scalability, making it easier to build future dashboards and analytical reports.
- Strengthened data governance by implementing Row-Level Security (RLS), ensuring users only access data relevant to their assigned regions.
- Improved maintainability through standardized naming conventions and a clean semantic model, allowing analysts and developers to work more efficiently.

