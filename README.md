# Supplier Quality and Performance Dashboard
## Overview

This repository hosts a Power BI project designed to monitor and analyze supplier quality and performance across various dimensions, including vendors, plants, materials, and defect categories. The dashboard offers a holistic view of defects, production downtime, and related financial impacts, enabling manufacturers to pinpoint problem areas and take corrective actions to enhance supplier quality and operational efficiency.

The case study showcased here was developed for a manufacturing company struggling to track and improve supplier performance. By leveraging business intelligence, the company consolidated procurement data and generated actionable insights to tackle issues like material defects, vendor reliability, and production delays.

## Key Features

Defect Tracking: Visualizes the quantity and types of defects across vendors, materials, and plants.

Downtime Analysis: Highlights hours of downtime and their financial implications, helping stakeholders understand cost drivers.

Top/Bottom Performers: Identifies vendors, plants, and materials contributing most to defects and downtime.

Trend Analysis: Shows monthly trends in defects and downtime to reveal patterns over time.

Vendor-Material/Plant Relationships: Evaluates combinations of vendors and plants or materials to identify high-risk areas.

Financial Impact: Estimates losses due to downtime, supporting data-driven decisions for supplier quality improvement.

## Data Model

The dashboard uses a Star Schema data model to ensure efficient performance and simplified analysis.

Fact Table: Captures key metrics like total defect quantities and downtime hours.

Dimension Tables: Separate tables for Vendor, Plant Location, Material Type, Defect Type, and related attributes.

Date Table: Enables time-based analysis for trend tracking and filtering reports by periods.

## Getting Started
1. Prerequisites

Power BI Desktop: Download and install from the Microsoft website
.
2. Usage Instructions

3. Clone this repository to your local machine:

git clone https://github.com/yourusername/supplier-quality-dashboard.git

4. Open the .pbix file in Power BI Desktop.

5. Connect the dashboard to your dataset by importing relevant CSV or database files.

6. Refresh the data to update the visuals with your own data.

## Reports and Visualizations

The dashboard includes several key pages focusing on different aspects of supplier quality:

- Overview: Key metrics such as total defects, downtime hours, and financial impact.

- Vendor Performance: Shows best- and worst-performing vendors based on defects and downtime.

- Plant Performance: Identifies plants with the highest defect rates or downtime.

- Material Performance: Breaks down defects and downtime by material type.

- Downtime Impact: Quantifies the cost of downtime and highlights periods with the highest impact.
