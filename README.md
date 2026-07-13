# Vehicle Insurance Analytics Dashboard

An interactive Power BI dashboard analyzing vehicle insurance customer data — built to explore customer demographics, premium distribution, and vehicle-related risk patterns.

## Overview
This project involved cleaning and transforming a raw dataset of ~147,000 vehicle insurance records, then building a dynamic, filterable dashboard to surface key business insights around customer segmentation and premium trends.

## Data Cleaning & Transformation
- Removed null values and duplicate records using Power Query
- Binned continuous variables (Age, Premium) into categorical ranges for clearer visualization
- Structured the dataset for multi-dimensional filtering across Gender, Vehicle Age, Vehicle Damage, and Age range

## DAX Measures
- Built custom DAX measures to calculate key metrics including Average Premium and Median Premium, used across KPI cards and visualizations

## Dashboard Features
- **Dynamic filters:** Gender, Vehicle_Age, Vehicle_Damage, and an Age range slider
- **Visualizations:** Bar charts (Total Customers by Premium bins, Total Customers by Age bins, Avg Premium by Vehicle Age) and donut charts (Gender split, Vehicle Age split, Vehicle Damage split)
- **KPI cards:** Total Customers (147K), Median Premium (32K), Sum of Previously Insured (8K), Avg Premium (30K)

## Key Insights
- 62% of customers own vehicles aged 1–2 years, the largest segment in the dataset
- Average premium increases with vehicle age, with vehicles over 2 years old showing the highest average premium
- Gender split skews toward male customers (57%) vs female (43%)

## Tools Used
Power BI, Power Query, DAX


