# London Cycling Services – Usage & Operations Analysis

## Project Overview

This project analyzes **cycling service usage in London** to support **investment decision-making**.  
The analysis was conducted to help stakeholders better understand how customers use the service, identify operational challenges, and assess overall system reliability.

Following an initial stakeholder meeting, the key areas of interest were identified as:
- Expected patterns of usage
- Customer behavior and demand profiles
- Operational concerns related to **bike availability, station imbalance, and supply chain reliability**

---

## Objectives

- Perform exploratory data analysis on London cycling usage data
- Analyze **net inflows and outflows of bicycles** at docking stations
- Identify **cyclical usage patterns** over time
- Highlight potential operational risks and inefficiencies
- Provide insights relevant for **investment evaluation**

---

## Data Sources

### 1. Historical Usage Data
- Multiple CSV files contained in the `Data.zip` folder
- Includes trip-level information such as:
  - Start and end stations
  - Timestamps
  - Journey durations

### 2. Live System Data
- Transport for London (TfL) live feed:
  
```text
https://tfl.gov.uk/tfl/syndication/feeds/cycle-hire/livecyclehireupdates.xml
