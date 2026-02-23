## India Tourism Revenue and Interest Analysis Dashboard

## Project Overview:
This project presents a comprehensive Tourism Revenue and Interest Analysis Dashboard for India, capturing tourism dynamics from 2015 to 2024. It integrates diverse data types including tourism revenue, visitor counts (domestic and international), and detailed segment revenues such as cultural, pilgrimage, heritage, nature, beaches, adventure, and medical tourism.

The dashboard is designed to provide actionable insights through interactive visuals and geospatial mapping, enabling stakeholders to understand tourism trends, revenue distribution, and visitor behavior across Indian states and regions.

## Problem Statement:

Tourism is a major contributor to India’s economy approximately 5.9% GDP contribution is providing from tourism to india, providing revenue and employment across diverse states and Union Territories. However, due to the vast geographical spread, varying visitor preferences, and multiple categories of tourism such as cultural, pilgrimage, heritage, nature, beaches, adventure, and medical, it becomes challenging to identify which states and categories drive the most value.

Policymakers, planners, and businesses often lack a consolidated, interactive, and visual representation of tourism data to make data-driven decisions. Without such insights, opportunities for focused investment, targeted marketing, and strategic development in tourism remain underutilized.

This project aims to analyze and visualize tourism revenue, visitor data, and category-wise contributions across all 36 states and Union Territories of India from 2015 to 2024. By leveraging Excel for preprocessing and Power BI for dashboard creation, the solution will highlight trends, top-performing states, domestic vs international visitor flow, and category-specific revenue distribution. The final outcome will be a dynamic dashboard that enables stakeholders to explore tourism performance interactively and make informed decisions for sustainable growth.



## Key Features
Total Revenue & Visitors Overview: Quick-glance cards summarizing total tourism revenue, domestic and international visitor numbers.

Yearly Revenue Trend: Line chart highlighting the annual growth of tourism revenue over a decade.

State-wise Revenue Distribution: Bar chart to compare tourism revenue across Indian states.

Visitor Trends: Visualization of domestic versus international visitors by year for comparative analysis.

Segmented Revenue Analysis: Multi-line charts showing revenue trends across different tourism segments such as pilgrimage, beaches, cultural, adventure, medical, and heritage tourism.

Interactive Filters: Select year(s) and state(s) to dynamically filter and explore the data.

Geo Mapping: Interactive map showcasing visitor interest and distribution geographically by state.

## Purpose and Benefits
Enables data-driven decision making for government and tourism authorities.

Identifies high-performing states and sectors within the tourism industry.

Tracks visitor growth and behavior patterns over time.

Supports targeted policy formulation and marketing efforts to boost tourism.

Enhances understanding of niche tourism segments to develop focused strategies.

## Technologies Used:
1.Excel data source containing extensive tourism metrics for India.

Excel Work
Excel was used for data collection, preprocessing, and calculation before visualizing in Power BI.

Tasks Done in Excel
Data Cleaning

Removed duplicates & blanks.

Standardized column names (e.g., "Domestic Visitors", "Revenue (₹ Crores)").

Fixed inconsistent percentage values for tourism categories.

Derived Columns

Total Visitors = Domestic Visitors + International Visitors

Category-wise Revenues = Total Revenue × Category %

Example (for Cultural Revenue):
=[[Tourism Revenue]] * ([[Cultural (%)]] / 100)
Repeated for Pilgrimage, Heritage, Nature, Beaches, Adventure, and Medical.


## Data Validation

Ensured category percentages per row ≈ 100%.
2.Power BI for data visualization and dashboard creation.
DAX Formulas 
1. Total Tourism Revenue
Total_Tourism_Revenue = SUM('TourismData'[Tourism Revenue])
2. Total Domestic Visitors
Total_Domestic_Visitors = SUM('TourismData'[Domestic_Visitors])
3. Total International Visitors
Total_International_Visitors = SUM('TourismData'[International_Visitors])
4. Total Visitors
Total_Visitors = SUM('TourismData'[Total_Visitors])
DAX for Segmented Revenues
5. Heritage Revenue
Heritage_Revenue = SUM('TourismData'[Heritage_Revenue])
6. Pilgrimage Revenue
Pilgrimage_Revenue = SUM('TourismData'[Pilgrimage_Revenue])
7. Beaches Revenue
Beaches_Revenue = SUM('TourismData'[Beaches_Revenue])
8. Nature Revenue
Nature_Revenue = SUM('TourismData'[Nature_Revenue])
9. Cultural Revenue
Cultural_Revenue = SUM('TourismData'[Cultural_Revenue])
10. Adventure Revenue
Adventure_Revenue = SUM('TourismData'[Adventure_Revenue])
11. Medical Revenue
Medical_Revenue = SUM('TourismData'[Medical_Revenue])

## Charts used for Visualization:
1.Total Tourism Revenue by Year (Line Chart)
2.Total Tourism Revenue by State (Bar Chart) top 10
3.Domestic vs International Visitors by Year (Stacked  Bar Chart)
4.Revenue by Segment Over Time (Linechart)
5.Geographical Distribution (Map)
6.Interactive Slicers (For Year, State)

Excel_file_link:https://github.com/yaswanthmucharla/Indian_Tourism_Revenue_Dashboard/blob/main/India_Tourism_2015_2024.xlsx
Powerbi_dashboard_link:https://github.com/yaswanthmucharla/Indian_Tourism_Revenue_Dashboard/blob/main/Tourism_Dashboard.png
