# Hospitality Domain Project – Power BI Dashboard

## Overview

This project focuses on analyzing the business performance of AtliQ Grands, a luxury hotel chain operating across multiple cities in India.

The objective of this dashboard was to identify the reasons behind declining revenue and market share by analyzing hotel performance, pricing strategy, occupancy trends, booking platforms, and customer behavior.

Using Power BI, I created an interactive dashboard that helps management track key hospitality KPIs and make better revenue and operational decisions.

---

## Business Problem

AtliQ Grands was facing increasing competition from other hotel chains and was struggling with declining market share and revenue performance.

The company needed a centralized dashboard to:
- Track hotel performance across cities and properties
- Analyze occupancy and pricing trends
- Identify underperforming hotels
- Improve revenue management decisions
- Increase direct bookings and reduce dependency on third-party platforms

---

## Objective

The goal of this project was to:
- Build an interactive business intelligence dashboard
- Analyze hospitality KPIs across multiple properties
- Identify pricing and occupancy inefficiencies
- Generate actionable business insights for revenue optimization

---

## Tools & Technologies Used

- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- MySQL
- Excel

---

## Dataset Information

The project uses historical hospitality business data from AtliQ Grands.

### Tables Used

#### Dimension Tables
- `dim_date` → Date and time-based analysis
- `dim_hotels` → Hotel property details and locations
- `dim_rooms` → Room category and capacity details

#### Fact Tables
- `fact_bookings` → Booking transactions, cancellations, pricing, revenue
- `fact_aggregated_bookings` → Aggregated hotel performance metrics

The dataset contains hotel-level and booking-level information across multiple cities and properties.

---

## Dashboard Features

### 1. Executive Overview

Provides a high-level business summary including:
- Revenue
- Occupancy %
- ADR (Average Daily Rate)
- RevPAR (Revenue Per Available Room)
- Realisation %
- Cancellation %

This page helps leadership quickly evaluate overall hotel performance.

---

### 2. Property Performance Analysis

Analyzes individual hotel performance across cities.

Key insights included:
- Underperforming properties
- Revenue contribution by hotel
- Occupancy comparison across locations
- Guest rating trends

This helped identify hotels requiring operational or service improvements.

---

### 3. Pricing & Revenue Analysis

Focused on pricing strategy and booking behavior.

Main findings:
- Weekend occupancy increased significantly
- ADR remained almost constant despite higher demand
- Dynamic pricing opportunities were being missed

This suggested that hotels were not adjusting room pricing effectively during peak demand periods.

---

### 4. Booking Platform Analysis

Compared booking performance across different platforms.

Insights:
- Heavy dependency on third-party booking platforms
- Lower direct booking contribution
- Opportunity to improve profit margins through direct website bookings

Recommended strategies:
- Loyalty programs
- Exclusive website offers
- Direct booking discounts
- Personalized promotions

---

## Key Business Insights

### Dynamic Pricing Opportunity

Occupancy rates increased during weekends, but ADR remained mostly unchanged.

This indicated that hotels were not using demand-based pricing strategies effectively, resulting in lost revenue opportunities.

---

### Direct Booking Improvement

A large percentage of bookings came from third-party platforms that charge commissions.

Increasing direct bookings could improve profit margins and customer retention.

---

### Property-Level Performance Gaps

Some hotels consistently showed:
- Lower occupancy
- Lower guest ratings
- Lower revenue contribution

This highlighted operational and service quality issues at specific properties.

---

## Business Recommendations

Based on the analysis, the following recommendations were made:

- Implement dynamic pricing strategies
- Improve guest experience for low-rated hotels
- Increase focus on direct booking channels
- Use loyalty programs and targeted promotions
- Optimize pricing during high-demand periods

---

## Technical Work Performed

During this project, I worked on:
- Data cleaning using Power Query
- Building relationships between fact and dimension tables
- Creating calculated measures using DAX
- Designing interactive dashboards
- Creating filters and slicers for dynamic analysis
- KPI tracking and trend analysis
- Business storytelling through visualization

---

## Key KPIs Used

- Revenue
- RevPAR
- ADR
- Occupancy %
- Realisation %
- Cancellation Rate
- Booking Platform Contribution

---

## What I Learned

This project helped me understand:
- Hospitality business metrics
- Revenue management concepts
- Pricing strategy analysis
- Dashboard storytelling
- Data-driven business decision making
- End-to-end Power BI dashboard development

It also improved my ability to connect technical analysis with real business problems and actionable recommendations.

---

## Live Dashboard

You can explore the interactive Power BI dashboard here:

[View Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZTJjMDY5ZWQtYTg4MC00NGE2LTkxYzctNjM1ZGUyOWI4MGU4IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=3751830d01a40003dc5a)

### Dashboard Preview

[![Hospitality Dashboard](Hospitality%20Domain%20Project.png)](https://app.powerbi.com/view?r=eyJrIjoiZTJjMDY5ZWQtYTg4MC00NGE2LTkxYzctNjM1ZGUyOWI4MGU4IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=3751830d01a40003dc5a)

---

## Project Outcome

This dashboard transformed raw hospitality data into a structured business intelligence solution that can support:
- Revenue optimization
- Pricing decisions
- Operational improvements
- Customer strategy planning
- Hotel performance monitoring

The project demonstrates practical skills in Power BI, DAX, data modeling, and business analytics using a real-world hospitality scenario.
