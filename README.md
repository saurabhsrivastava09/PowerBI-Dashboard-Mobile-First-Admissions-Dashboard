# Mobile-First Admissions Dashboard

## Project Overview

This Power BI dashboard, describes the creation of a mobile-optimized admissions dashboard for the University of New Haven's leadership, including the University President.

As a Graduate Data Analyst, the goal was to provide timely, actionable insights into Fall 2025 admissions data (both undergraduate and graduate) that could be easily accessed on a mobile device. The dashboard tracks various student segments (e.g., New First-Time, Full-Time Students; Transfer, Part-Time Students) and offers navigation at the college level, allowing drill-downs into specific academic units like the College of Arts & Sciences and Pompea College of Business.

Key Performance Indicators (KPIs) tracked include applications submitted, completed, accepted, denied, I-20 issued, visa approved, net deposits, and enrolled students, enabling instant year-over-year comparisons between Fall 2024 and Fall 2025.

## Design Strategy

The dashboard was designed with a mobile-first approach. To optimize for mobile devices with limited screen real estate, custom text labels were placed above KPI cards, saving space and maintaining a clean layout. Trend arrows were incorporated using DAX measures to visually indicate performance changes between 2024 and 2025, making significant shifts quickly noticeable. The dashboard also aligns with the university's brand identity by incorporating "Charger Blue and Yellow" colors and a "Powered by Charger" footer.

## Key Features & Visuals

Here are selected screens from the dashboard illustrating the mobile-first design and core functionality:

### Power BI Snapshot: What the President Sees

![Screenshot_20250506_142450](https://github.com/user-attachments/assets/dc29f639-6b58-4289-b081-4492064ea1ef)
*This snapshot shows the main navigation screen for the Undergraduate Admissions dashboard, allowing selection by classification type (e.g., New Students Full Time) and college name (e.g., CAS, PCOB).*

(https://github.com/user-attachments/assets/24e1ff5c-ece0-48f9-b8b8-6c4c652e72c4)![Screenshot_20250506_142707]
*This screen displays the year-over-year comparison for "New First Time - Full Time" students, showing KPIs like Submitted, Completed, Accepted, Denied, I-20, Visa, and Net Deposits for both 2024 and 2025, with clear trend arrows indicating performance changes.*

![Screenshot_20250506_142516](https://github.com/user-attachments/assets/c6edbb6a-3869-43f7-9234-acba04e6abb9)
*This view demonstrates the college-level drilldown, specifically for "Pompea College of Business," presenting the same set of KPIs with year-over-year comparisons and trend arrows.*


**Microsoft Power BI Desktop** (specifically Version 2.142.928.0) 

**DAX** (Data Analysis Expressions) for custom measures and conditional formatting 

**SQL Server** (for data connection) 

## How to Interact

This dashboard is designed to be interactive. The Power BI project file (.pbix) is available upon request.
