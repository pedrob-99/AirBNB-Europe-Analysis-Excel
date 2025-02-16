# Airbnb Europe Analysis in Excel: Power Query Basics & the Pitfalls of Generic Dashboards

## Executive Summary
This project serves a dual purpose: demonstrating technical proficiency with Excel and Power Query while critically examining the limitations of conventional dashboard design. Through analyzing AirBnB listings across ten European capitals, I created a traditional Excel dashboard that, while technically sound, intentionally highlights the pitfalls of generic visualization approaches that lack narrative focus. The project reveals how standard dashboard practices, despite their technical merit, often fail to transform data into actionable insights, emphasizing the importance of storytelling in data visualization.

## Business Problem
In the competitive travel and hospitality industry, property managers and travel companies often rely on dashboards to monitor market trends and set competitive pricing strategies. However, many dashboards—especially those created in Excel—focus solely on presenting data without contextualizing the insights into a meaningful narrative. This gap can result in dashboards that are visually appealing but fail to drive actionable insights. The business challenge addressed by this project was twofold:
1. Data Integration: Merge fragmented weekday and weekend datasets from multiple European cities into a cohesive dataset.
2. Insight Delivery: Create an Excel dashboard that, while technically robust, also exposes the pitfalls of generic dashboards that do not incorporate storytelling, ultimately highlighting the need for a narrative that transforms raw graphs into actionable insights.

## Methodology
To address these challenges, I followed these steps:
- Data Integration: Utilized Excel’s Power Query to merge weekday and weekend CSV files for each city, adding a “day” column to maintain context, and then consolidated all datasets with an additional “city” column.
- Data Cleaning: Removed duplicate entries, renamed columns for clarity (e.g., “biz” to “Business Purpose”), and converted Boolean values into user-friendly “Yes/No” indicators.
- Data Transformation: Categorized continuous distance data into four ranges (0-1 km, 1-2 km, 2-3 km, and 3+ km) for both city centre proximity and nearest metro station, to facilitate better segmentation.
- Dashboard Design: Built an interactive dashboard using pivot tables and a variety of dynamic charts, including:
  - Horizontal bar charts displaying average prices by city and room type.
  - Line charts showing price evolution based on accommodation capacity.
  - Pie charts illustrating the distribution of room types.
  - Stacked 100% bar charts highlighting distance ranges from the city centre and metro stations.

While these visualizations demonstrate technical prowess, the overall design intentionally lacks a guiding narrative. This approach is meant to showcase the limitations of a generic dashboard, where the absence of storytelling can lead to multiple, sometimes conflicting, interpretations of the data.

## Skills 
Technical Skills:
- Excel: PivotTables, PivotCharts, Dashboard Design.
- Power Query: M language, Data Transformation, Data Integration.
- Data Cleaning: Duplicate Removal, Data Type Conversion.
- Data Analysis: Descriptive Statistics, Categorical Analysis.

Critical Analysis Skills:
- Understanding dashboard limitations.
- Recognition of visualization best practices.
- Insight communication strategies.
- User experience considerations.

## Results & Business Recommendation
Key Findings:
- Pricing Dynamics: Although Amsterdam emerges as the most expensive market on average, Athens, with the highest maximum value, is the cheapest overall.
- Accommodation Trends: Nearly two-thirds of the listings are entire homes or apartments, suggesting a market preference for complete accommodations.
- Capacity Impact: The analysis shows that while prices for 2- and 3-person accommodations remain similar, there is a significant price increase for accommodations designed for groups of four.
- Location Insights: The data reveals a varied distribution of listings in relation to both city centres and metro stations.

Business Recommendation:
- Integrate Storytelling: While Excel dashboards are powerful for data analysis, integrating a narrative is essential to guide interpretation and drive actionable insights. I recommend that organizations enhance their dashboards with storytelling elements to ensure data leads to strategic business actions.
- Optimize Pricing Strategies: Stakeholders should focus on markets like Amsterdam for premium pricing strategies and tailor marketing efforts based on the observed trends.
- Targeted Operational Improvements: Use insights on accommodation composition and capacity to adjust resource allocation, thereby improving overall operational efficiency.

This project not only demonstrates the advanced capabilities of Excel and Power Query but also serves as a cautionary example of how a technically sound dashboard can fall short without a strong narrative to drive decision-making.
