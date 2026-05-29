# Solar Panel Performance Analytics Project

## Project Overview
This project focuses on analysing solar panel performance data using SQL to uncover operational insights, identify performance patterns, and support data-driven decision-making. The analysis explores energy production, efficiency ratings, maintenance behaviour, and model-level performance trends across a fleet of solar panels.

The goal is to simulate a real-world analytics workflow by transforming raw operational data into meaningful insights that can help optimise energy output and improve maintenance strategies.

## Dataset: `SolarPanelMetrics`
The dataset contains operational records of solar panels, including:
- **Panel ID**: Unique identifier for each panel.
- **Model Name**: The specific solar panel model.
- **Energy Output (kWh)**: Total energy produced by the panel.
- **Efficiency Rating**: Percentage rating of panel efficiency.
- **Last Maintenance Date**: The date the panel last underwent maintenance.

## Tools & Technologies
- **SQL (Structured Query Language)**
- **Window Functions**
- **Aggregate Functions**
- **CTEs & Subqueries**
- **Time Series Analysis techniques**

## Project Objectives
The analysis was designed to answer key business questions:
1. Which solar panels generate the highest energy output?
2. How does performance vary across different models?
3. What are the trends in maintenance activity over time?
4. Are there any underperforming or abnormal panels?
5. How does each panel compare to fleet-wide averages?

## Key Analyses Performed

### 1. Exploratory Data Analysis (EDA)
- Dataset overview and structure inspection.
- Identification of missing values and duplicates.
- Distribution of model types.
- Summary statistics for energy output and efficiency.

### 2. Performance Analysis
- Ranking of panels by energy output.
- Identification of top and bottom performers.
- Model-level efficiency comparison.
- Detection of performance tiers.

### 3. Time-Based Analysis
- Maintenance trends over time.
- Running total of energy output.
- Month-over-month energy growth analysis.
- First and last maintenance tracking per panel.

### 4. Statistical Insights
- Average and median efficiency calculations.
- Outlier detection using standard deviation rules.
- Comparison against fleet-wide averages.

### 5. Advanced SQL Techniques
- Window functions for ranking and comparisons.
- Partitioning for model-based analysis.
- Rolling averages for performance smoothing.
- Trend comparison.
- Subqueries for dynamic analysis windows.

## Key Insights
- **Model Disparities**: Certain solar panel models consistently outperformed others in energy output and efficiency.
- **Maintenance Impact**: Maintenance timing has a noticeable impact on the energy performance trends.
- **Performance Distribution**: A small subset of panels contributes disproportionately to total energy production.
- **Optimisation Opportunities**: Performance variability exists both within and across panel models, indicating clear opportunities for operational optimisation.

---
*This project serves as a demonstration of SQL proficiency in handling time-series, performance, and operational data.*
*Created by Jonathan Ogana*
