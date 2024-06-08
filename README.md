
# Telangana Growth Analysis

Welcome to the "Telangana Growth Analysis" project, part of the Codebasics Challenge #7. This project aims to extract impactful insights and create data-driven storytelling from the data provided by the Telangana government. Project Link : https://app.powerbi.com/view?r=eyJrIjoiYjM2ODU5MTQtOTg3ZC00ODUzLTk1YWMtODVjYzVjYjhkNzlkIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9

## Objectives

- **Explore Datasets:** Stamp Registration, Transportation, and Ts-Ipass Datasets. Understand their attributes, categories, and time period.
- **Analyzing Trends:** Identify trends and patterns within each department.
- **Identify Growth Opportunities:** Highlight growth opportunities and areas needing attention.

### Stamps
- **Objective:** Analyze Telangana's Stamp Registration Revenue, count, E-Stamp Revenue Count, and the changes in E-Stamp Count compared to Stamp Registration across Telangana's diverse districts.
- **Dashboard:** This dynamic dashboard empowers users to uncover revenue trends, compare E-Stamp and Stamp Registration counts, and understand their implications for Telangana's fiscal landscape.

### Transportation
- **Objective:** Analyze Telangana's transportation datasets and examine seasonal trends patterns by vehicle class. Identify correlations among specific months between vehicle sales and create relevant visuals, such as shape maps.

### Ts-Ipass
- **Objective:** Analyze the Ts-Ipass datasets to investigate the investment trends for specific sectors across districts. Examine the relationship trend between district investments, vehicle sales, and stamp revenue. Identify substantial and cyclicality in investment trends across multiple districts.

### Insights & Recommendations
- **Objective:** Provide 5 Insights & 5 Recommendations for Telangana's Future Growth.

## Telangana Growth Analysis Data Description

This file contains metadata regarding the columns described in the CSV files provided for the Telangana Growth Analysis project.

## 1. dim_districts
The table contains information about districts.

- **dist_code:** District code or identifier for each district.
- **district:** Name of the district.

## 2. dim_date
This table contains dates at the monthly level. Telangana's fiscal year spans from April to March.

- **month:** Starting date of each month.
- **Mmm:** Name of the month.
- **quarter:** Associated quarter for each particular month.
- **fiscal_year:** Corresponding fiscal year of each month.

## 3. fact_stamps
Provides data on revenue generated from document registrations and e-stamp challan payments aggregated at the district and monthly level.

- **dist_code:** District code.
- **month:** Starting date of each month.
- **documents_registered_cnt:** Total count of documents registered.
- **documents_registered_rev:** Total revenue generated from registered documents.
- **estamps_challans_cnt:** Count of e-stamps challans.
- **estamps_challans_rev:** Revenue generated from e-stamps challans.

## 4. fact_transport
Provides information about individual vehicle sales data from the RTA(Regional Transport Authority) of Telangana, categorized by fuel type, vehicle class, seating capacity, and other general categories aggregated at the district and monthly level.

- **dist_code:** District code.
- **month:** Starting date of each month.
- **Fuel types:** Petrol, Diesel, Electric, Others.
- **Vehicle classes:** Motorcycles, Motorcars, Auto rickshaws, Agriculture, Others.
- **Seating capacity categories:** 1 to 3, 4 to 6, Above 6.
- **Other categories:** Brand new vehicles, Pre-owned vehicles, Non-Transport, Transport.

## 5. fact_TS_iPASS
Comprises data concerning units or businesses established within Telangana under the "Industrial Project Approval and Self-Certification System" (TS-iPASS).

- **dist_code:** District code.
- **month:** Starting date of each month.
- **sector:** Industry category.
- **investment in cr:** Investment made in the specific sector, measured in crores.
- **number_of_employees:** Number of employees associated with that sector.

