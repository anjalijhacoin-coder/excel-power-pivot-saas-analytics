Markdown
# SaaS Business Performance Executive Dashboard

## Overview
I built this executive-level dashboard entirely in Microsoft Excel to bridge the gap between raw operational data and stakeholder-ready business insights. Instead of a flat, unstructured spreadsheet, this project treats data analysis with professional rigor—utilizing a relational data model, Power Pivot, and clean visual storytelling to track core subscription health, revenue distribution, and support load.

---

## The Data Architecture & Model
To ensure data integrity and smooth interactivity across all charts, I structured the workbook using a multi-table relational model rather than dumping everything onto a single sheet:
* **Core Tables:** Separate, clean tables managing Customer Profiles, Subscription Tiers, and Support Ticket logs.
* **Relational Modeling:** Connected the tables using `CustomerID` as the primary/foreign key relationship in Power Pivot, ensuring that every filter and metric synchronizes dynamically across the entire workbook.

---

## Executive Summary & Key Performance Indicators (KPIs)
The dashboard opens with a balanced, two-card executive summary banner designed for immediate, high-level stakeholder visibility:
* **Left Card (Revenue Focus):** Total Revenue of ₹1,09,500 and Active Revenue of ₹80,850.
* **Right Card (Support & Operations Focus):** Total Support Ticket Volume of 426.

---

## Dashboard Layout & Visual Design
I designed the interface using a structured grid layout to maintain visual symmetry and guide the viewer's eye logically:
* **Global Slicers:** Positioned cleanly on the left-hand dock (`Company_Size` and `City`), allowing users to instantly filter the entire data model by enterprise tier or geographic market.
* **Revenue Breakdown Chart:** A multi-tier column chart segmenting revenue performance by industry and subscription plan tier (Basic, Enterprise, Pro).
* **Concentration & Risk Chart:** A concentric donut chart mapping revenue concentration against support ticket volumes to highlight operational bottlenecks.
* **Trend Analysis:** A bottom area chart tracking subscription growth and monthly churn trends over time.

---

## Technical Skills & Tools Demonstrated
* **Advanced Excel & Power Pivot:** Relational data modeling, multi-table joins, and data structuring.
* **Interactive Filtering:** Global slicer integration linked across multiple pivot tables.
* **Custom Visual Design:** Modern shape-based KPI scorecards, custom number formatting, and polished chart layouts.
* **Business Analysis:** Translating raw multi-source data into actionable SaaS metrics and operational insights.

---

## How to Explore
1. Download the `SaaS_Business_Performance_Executive_Dashboard.xlsx` file from this repository.
2. Open it in Microsoft Excel (Microsoft 365 recommended).
3. Test the interactive data model by clicking through the `Company_Size` and `City` slicers on the lef
