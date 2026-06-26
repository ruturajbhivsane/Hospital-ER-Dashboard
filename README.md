# Hospital ER Operations Dashboard

An interactive Excel dashboard analyzing emergency room operations, patient demographics, and cost metrics using Power Pivot, DAX, and PivotCharts.

## Overview

This dashboard answers a simple question for hospital ER stakeholders: *how is the ER actually performing, day to day and month to month — and who are we treating?* It pulls together patient volume, wait times, admission rates, satisfaction, and cost into a single view, with year/month slicers for drilling into specific periods.

## Features

- Dynamic Year and Month slicers powered by a custom Calendar table built in the Power Pivot Data Model
- KPI cards: total patients, average wait time, admission rate, patient satisfaction, estimated total cost
- Department-level visit volume breakdown
- Admission status and wait-time delay analysis (donut charts)
- Patient demographics by age group and race
- Monthly patient volume trend (area chart)

## Data model

- **Fact table:** Hospital Emergency Room Data (9,200+ records)
- **Lookup tables:** Department Lookup, Age Group Lookup
- **Calendar table:** built with DAX calculated columns, loaded into the Power Pivot Data Model
- Relationships managed in Power Pivot to support slicer-driven filtering across all visuals

## Tools used

Excel · Power Pivot · Power Query · PivotTables · PivotCharts · Slicers · DAX

## Screenshots

![Dashboard overview](dashboard-overview.png)

## Note on data

This dataset is synthetic, practice data created for portfolio/demonstration purposes only. No real patient information is included.
