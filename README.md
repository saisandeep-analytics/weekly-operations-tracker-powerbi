# Weekly Operations Tracker – Power BI Dashboard

## Project Overview

The **Weekly Operations Tracker** is an interactive Power BI dashboard designed to monitor and analyse the weekly operational performance of two restaurant locations:

- Port Severn (Store ID: 5349)
- Waubaushene (Store ID: 5201)

The dashboard provides a centralised view of key operational metrics, allowing management to compare store performance, monitor historical trends and identify areas that may require operational attention.

The project focuses on transforming weekly operational data into meaningful insights that support better decision-making and performance monitoring.

> **Note:** This project currently uses fictional sample data for demonstration purposes. It is designed to accommodate actual weekly operational data when available.

## Business Objectives

- Monitor weekly performance across two restaurant locations.
- Compare operational results between stores.
- Identify performance gaps and improvement opportunities.
- Track changes against previous reporting weeks.
- Analyse historical performance trends.
- Provide management with a simple and interactive reporting experience.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI | Dashboard development and visualisation |
| DAX | Measures, calculations and dynamic insights |
| Microsoft Excel | Data preparation and source dataset |
| Power BI Data Model | Data organisation and reporting structure |

## Key Performance Metrics

The dashboard supports five selectable operational metrics:

1. **Speed of Service (SOS)** – Monitors service times across five dayparts:
   - Weekday AM
   - Weekend AM
   - Brunch
   - Weekday PM
   - Weekend PM

2. **Guest Satisfaction (GSAT)** – Tracks guest satisfaction performance across both stores.

3. **Friendliness NPS** – Monitors customer feedback relating to friendliness.

4. **GPS Performance** – Tracks the selected GPS performance measure.

5. **Labour Performance** – Monitors labour percentage across both locations.

## Dashboard Features

### 1. Dynamic KPI Cards

Displays the selected reporting week's performance for both stores, including:

- Port Severn KPI
- Waubaushene KPI
- Difference between stores
- Dynamic performance interpretation

### 2. Store Comparison Chart

Provides a visual comparison between Port Severn and Waubaushene.

The chart dynamically responds to the selected metric. For Speed of Service, it displays all five dayparts.

### 3. Historical Trend Analysis

Displays the historical performance of both stores across all available reporting weeks.

The trend chart dynamically updates according to the selected metric while retaining the full historical timeline when a reporting week is selected.

### 4. Dynamic Key Takeaways

Provides three levels of operational insight:

- **Weekly Performance:** Identifies the difference in performance between the two stores for the selected week.
- **Week-over-Week Change:** Shows how each store's performance changed compared with its previous available reporting week.
- **Overall Trend:** Compares each store's first and latest available reporting weeks. For SOS, the insight focuses on daypart performance.

### 5. Interactive Filters

- Reporting Week selection
- Metric selection
- Dynamic KPI and chart updates
- Historical trend analysis

## Dashboard Screenshots

Add your dashboard screenshots to the `Screenshots` folder and use the following section to display them.

### Dashboard Overview

![Weekly Operations Tracker Dashboard](Screenshots/dashboard-overview.png)

### Speed of Service Analysis

![Speed of Service Analysis](Screenshots/sos-performance.png)

### Metric Performance Analysis

![Metric Performance Analysis](Screenshots/metric-analysis.png)

## Data Model & Calculations

The project uses a structured weekly operational dataset containing store information, reporting periods and performance metrics.

DAX measures were developed to support:

- Dynamic metric selection
- Store-level KPI calculations
- Store performance differences
- Conditional chart measures
- Historical trend calculations
- Week-over-week comparisons
- Dynamic performance interpretations
- Reporting-week validation

A disconnected metric selector and a separate trend-axis table support the dashboard's dynamic behaviour.

## Business Value

This dashboard demonstrates how restaurant operational data can be used to:

- Improve visibility into store performance.
- Identify differences between locations.
- Monitor service and guest satisfaction metrics.
- Understand changes in labour performance.
- Track operational progress over time.
- Support structured weekly management reviews.

## Future Enhancements

Potential future improvements include:

- Integration with actual restaurant reporting exports.
- Automated weekly data refresh.
- Labour scheduling and forecasting analysis.
- Operational corrective action tracking.
- Additional management reporting and performance indicators.

## Project Status

**Completed – Initial Dashboard Development**

The dashboard has been developed and tested using fictional sample data across both restaurant locations and all five performance metrics.

---

**Developed using:** Microsoft Power BI | DAX | Microsoft Excel

**Project Category:** Restaurant Operations Analytics | Business Intelligence | Data Analytics
