# Excel Salary Dashboard

An interactive Excel dashboard that answers one question fast: **what should this job actually pay?** Filter by job title, country, and employment type to see median salary, job volume, and top hiring platforms update in real time.

<img width="2000" height="1474" alt="image" src="https://github.com/user-attachments/assets/39c18a6d-b716-40b6-b447-8e64041c3a35" />


## Overview

This dashboard lets job seekers and analysts benchmark compensation across data roles (Data Analyst, Data Scientist, Data Engineer, Machine Learning Engineer, and related titles) without digging through scattered job postings one at a time. Pick a job title, country, and employment type from the dropdowns and every chart and KPI card on the sheet updates instantly.

## Dataset

- **Source:** Job postings dataset provided in Luke Barousse's Data Analyst course
- **Size:** ~5,800 postings
- **Fields:** job title, company, country, salary, employment type (full-time / part-time / contractor / temp / internship), job platform, and required skills

## Features

- **Job Title filter** — dropdown covering Data Analyst, Data Scientist, Data Engineer, Senior variants, Business Analyst, Software Engineer, ML Engineer, Cloud Engineer, and more
- **Country filter** — narrows all charts and KPIs to a single country, with a world map visual highlighting posting activity
- **Employment Type filter** — Full-time, Part-time, Contractor, Temp work, Internship
- **Salary-by-title chart** — horizontal bar chart ranking median salary across roles
- **Job-type volume chart** — bar chart of posting counts by employment type
- **KPI cards** — Median Salary, Top Job Platform, and Job Count, all driven by the current filter selection

## Tools & Techniques Demonstrated

- PivotTables and PivotCharts for dynamic, filter-driven aggregation
- Slicers and form-control dropdowns for interactive filtering
- Power Query for data cleaning and shaping
- Geographic mapping (3D Map / Bing Maps chart) for country-level visualization
- Dynamic formulas (XLOOKUP / INDEX-MATCH) to drive the KPI cards off the active filter state
- Dashboard layout and design principles (single-screen, no scrolling, consistent visual hierarchy)

## How to Use

1. Download `excel-salary-dashboard.xlsx` and open it in Excel (enable content/macros if prompted).
2. Use the Job Title, Country, and Type dropdowns to filter the data.
3. Read the updated charts and KPI cards for the selected combination.

## Key Insights

> Fill this in once the dashboard is built — 2–3 concrete findings (e.g., which role/country combination pays best, which employment type dominates postings, salary spread across seniority levels). This section is what turns the project from "I followed a tutorial" into "I can extract a business insight," which is what a recruiter is actually screening for.

## Credit

Built as Project 1 of [Luke Barousse's Data Analyst course](https://www.lukebarousse.com/). Dataset and dashboard concept from the course; implementation and any additional analysis are my own.

## Connect

- LinkedIn: https://www.linkedin.com/in/amanubhi1/
- Portfolio: https://github.com/amanubhi/
