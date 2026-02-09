## Instagram User Analytics
Project Summary

This project performs an end-to-end analytical study of Instagram user engagement using SQL-driven data modeling, exploratory analysis, and business-focused visualization. The objective is to extract actionable insights from social media interaction data by evaluating engagement efficiency, posting behavior, and follower dynamics.

The workflow emphasizes relational database design, query optimization, and dashboard-driven insight delivery, mirroring real-world data analyst practices.

## Tools & Technologies

PostgreSQL – Data modeling, preprocessing, and analytical querying

Power BI – Interactive dashboards and KPI visualization

Microsoft Excel – Data validation and exploratory checks

Visual Studio Code – SQL development environment

Canva – Report and presentation design

Git & GitHub – Version control and project documentation

Markdown – Technical documentation

## Project Architecture
├── README.md
├── query
│   ├── query.sql
│   └── data_from_query
│       └── exported_query_results
│
├── reports
│   ├── SQL_Analysis_Report.pdf
│   └── pbi
│       └── Instagram_Analytics_Dashboard.pbix
│
├── src
│   ├── data
│   │   └── raw_and_processed_datasets
│   ├── database.sql
│   └── preprocessing.sql

## Business Problem

Social media engagement metrics are often evaluated at surface level (likes or followers), which can lead to misleading conclusions. This project addresses that gap by analyzing relative engagement efficiency and behavioral indicators rather than absolute counts.

## Key analytical objectives:

Measure engagement performance beyond follower volume

Identify behavioral patterns influencing engagement rate

Evaluate consistency and activity as predictors of interaction

Provide data-backed insights for content optimization strategies

## Dataset Overview

The dataset consists of structured engagement metrics derived from Instagram public profile activity. Core attributes include:

followers

following

posts

total_likes

total_comments

engagement_rate

post_frequency

days_active

Derived metrics were calculated using SQL to standardize engagement comparison across users.

## Data Processing & Modeling

Designed normalized relational tables in PostgreSQL

Applied preprocessing queries to handle missing values and inconsistencies

Created derived fields such as engagement rate and posting frequency

Optimized SQL queries for aggregation and performance analysis

Analytical Approach

Exploratory Data Analysis (EDA) using SQL aggregations and filters

Engagement Segmentation based on follower count and activity level

Trend Analysis to evaluate posting behavior versus interaction outcomes

Comparative Analysis between high-visibility and high-efficiency users

## Key Findings

High follower counts do not consistently correlate with high engagement rates

Accounts with moderate followers but consistent posting show stronger engagement efficiency

Engagement rate is a more reliable KPI than total likes or comments alone

Posting consistency contributes more to engagement than sheer posting volume

## Dashboard & Reporting

Developed an interactive Power BI dashboard highlighting:

Engagement rate distribution

User segmentation by activity level

Correlation between posting frequency and engagement

High-performing user profiles

Delivered insights through a structured SQL analysis report for stakeholders

Outcome & Learnings

This project demonstrates practical experience in:

SQL-based analytical problem solving

Translating raw social media data into business insights

Designing dashboards that support data-driven decision-making

Applying analytical thinking to engagement and performance metrics

The analysis framework can be extended to other social media platforms or integrated with time-series data for predictive modeling.
