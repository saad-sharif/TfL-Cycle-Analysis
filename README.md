# London Cycling Services – Usage & Operations Analysis

## Project Overview

This project analyzes **cycling service usage in London** to support **investment decision-making**.  
The analysis was conducted to help stakeholders better understand how customers use the service, identify operational challenges, and assess overall system reliability.

Following an initial stakeholder meeting, the key areas of interest were identified as:
- Expected patterns of usage
- Customer behavior and demand profiles
- Operational concerns related to **bike availability, reliability, and supply chain management**

---

## Objectives

- Perform exploratory data analysis on London cycling usage data
- Analyze **net inflows and outflows of bicycles** at docking stations
- Identify **cyclical usage patterns** using spectral analysis
- Highlight potential operational risks and inefficiencies
- Provide insights relevant for **investment evaluation**

---

## Data Sources

### Historical Usage Data
- Multiple CSV files located in the `Data` folder
- Data includes journey-level information across London cycle hire stations

### Live System Data
- Transport for London (TfL) live feed:
https://tfl.gov.uk/tfl/syndication/feeds/cycle-hire/livecyclehireupdates.xml


### Geographic Reference
- Static London map image used for visualization:
  - `london_map.png`

---

## Required Packages

The analysis was conducted in **Python** using the following libraries:

### Core Data Handling
- pandas
- numpy
- glob
- os

### Visualization
- matplotlib
- matplotlib.image

### External Data & APIs
- requests
- xml.etree.ElementTree
- io.BytesIO

### Signal Processing
- scipy.signal (periodogram)

### Utilities
- warnings
