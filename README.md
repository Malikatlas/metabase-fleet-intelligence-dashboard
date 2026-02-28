# Fleet Intelligence Dashboard (Metabase)

A dynamic analytics dashboard built using open-source Metabase, integrating Bolt, Uber Suppliers, and FMS data into a unified fleet performance monitoring platform.

---

## Overview

This project demonstrates a real-world Business Intelligence implementation using a locally deployed Metabase instance connected to multiple operational data sources.

The dashboard consolidates:

- Bolt Fleet Integration data
- Uber Suppliers transaction data
- FMS operational records

into a centralized Fleet Intelligence Platform.

---

## Key Features

### Dynamic Filtering
- Global date range filter
- Driver-level filtering
- Vehicle registration filtering
- Platform selection (Bolt / Uber / FMS)

### KPI Monitoring
- Total Revenue
- Total KM (Busy / Free)
- Acceptance Rate
- Working Hours
- Total Trips
- Commission & Earnings breakdown

### Performance Analytics
- Daily revenue trends
- Daily KM trends
- Trip distribution by hour
- Top drivers by revenue
- Top vehicles by revenue

### Operational Insights
- Fleet order status distribution
- Transaction-level reporting
- Platform earnings comparison
- Busy vs free KM analysis

### Geo Analytics
- Pickup and drop-off visualization
- Location-based operational mapping

---

## Architecture

- Open-source Metabase deployed locally
- Database connections configured for:
  - Bolt integration data
  - Uber Suppliers reporting data
  - FMS system database
- SQL-based questions used to build dynamic cards
- Interactive dashboard filters mapped to multiple datasets

---

## Dashboard File

The complete dashboard visualization is included as:

`Metabase - Fleet Intelligence Platform.pdf`

This file contains:
- KPI layout
- Filter configurations
- Trend charts
- Platform breakdowns
- Geo visualizations
- Transaction reporting tables

---

## Security & Privacy

- No production credentials included
- No raw database dumps shared
- Any identifiable data in screenshots is anonymized

---

## Skills Demonstrated

- Multi-source data integration
- BI dashboard design
- Metric engineering
- Operational analytics
- Performance monitoring
- Data modeling for reporting
- Interactive filter mapping
- Geo visualization
- Fleet performance intelligence

---

## Purpose

This project showcases analytics engineering and BI development capabilities, focusing on real-time operational monitoring for fleet-based platforms.
