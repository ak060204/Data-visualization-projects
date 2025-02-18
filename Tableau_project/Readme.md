# Tableau Project: British Airways Reviews Dashboard Ratings & Insights 

This project is an end-to-end interactive dashboard built in Tableau using British Airways review data. I designed the dashboard to allow end users to dynamically select metrics and apply filters to explore various service ratings and trends.
<a href="[https://github.com/ak060204/Data-visualization-projects/blob/main/Tableau_project/Tableau_Project.png](https://public.tableau.com/app/profile/asveen.krishnan.n/viz/BritishAirwaysReviewsDashboardRatingsInsightsinTableau/Dashboard1)"> View Dashboard </a>
## Project Overview

### What I’m Doing:
I created an interactive Tableau dashboard that aggregates and visualizes British Airways review data.

### Project Focus:
The dashboard enables users to toggle between different service metrics (overall rating, cabin staff service, food, entertainment, ground service, seat comfort, and value for money) and apply filters such as date, seat type, traveler type, aircraft, and continent.

### Key Questions Addressed: 
o	How do average ratings for different service categories vary by country, month, and aircraft?

o	What insights can be drawn about customer feedback from the reviews?

o	Which metrics stand out and how do they trend over time?

## Datasets Used

### BA Reviews CSV:
Contains individual reviews with fields including author, date, place, and multiple rating metrics (e.g., overall rating, cabin staff, food, ground service, etc.).

### Countries CSV:
A country mapping table used to link review locations with geographic information (continent, region) for enhanced filtering.

## Dashboard Creation Process

### Data Connection & Preparation
•	Connecting Data:
Imported two CSV files (BA Reviews and Countries) and established a relationship between the place field in BA Reviews and the country field in Countries.

•	Geographical Role Assignment:
Converted the place field to a geographic role (Country/Region) to enable map visualizations.

### Dynamic Metric Selection
•	Parameter Setup:
Created a parameter, "Pick a Metric," as a single-value list with options such as overall rating, cabin staff service, entertainment, food, ground service, seat comfort, and value for money.

•	Calculated Field:
Developed a calculated field using a CASE statement that returns the selected metric's rating based on the parameter choice.

### Visualizations
#### Interactive Map (Average Custom Metric by Country): 
o	Plotted the map using the place field.

o	Colored the map based on the average value of the selected metric.

o	Customized tooltips to display the country, selected metric value, and number of reviews.

o	Applied a custom green color (hex: #013220) for consistency.

#### Line Chart (Average Custom Metric by Month): 
o	Created a line chart showing the trend of the average selected metric over continuous months.

o	Formatted the chart by removing gridlines and excessive decimal places, and aligning the text for clarity.

#### Dual Bar Chart (Average Custom Metric by Aircraft): 
o	Built a dual bar chart comparing the average selected metric and the count of reviews for each aircraft group.

o	Grouped aircraft with low review counts into a single “Various” category.

o	Adjusted axis titles and formatted colors (using a contrasting pink for review count) for better visual differentiation.

#### Summary Metrics Sheet: 
o	Developed a text-based summary showing key measures (average overall rating, average cabin staff service, average food, etc.).

o	Reformatted the values (one decimal place) and rearranged them with average overall rating as the primary metric.

## Filters & Interactivity
### Filters Implemented: 
o	Date Filter: Set as a continuous month filter to allow time-based analysis.

o	Traveler Type & Seat Type Filters: Configured as single-value dropdowns for streamlined user experience.

o	Aircraft Filter: Grouped less common aircraft into “Various” and set as a single-value dropdown.

o	Continent Filter: Added as a single-value dropdown to filter the map by region.

### Interactivity:
Configured visual elements (e.g., maps and charts) to act as filters when clicked, enabling users to drill down into specific data segments.

## Dashboard Assembly & Formatting

![Tableau_Project](https://github.com/user-attachments/assets/a20dae89-6067-4253-afd0-2c80b1de524b)

### Layout & Design: 
o	Employed a floating layout for greater flexibility in spacing and alignment.

o	Added a dashboard title ("British Airways Reviews") and positioned summary metrics at the top.

o	Organized filters in a vertical container and arranged visualizations (map, line chart, dual bar chart) in a clean, cohesive layout.

o	Included a separation line between filters and dashboard content for visual clarity.

### Final Touches: 
o	Adjusted tooltips to display only necessary information (e.g., actual metric values, number of reviews).

o	Standardized font sizes, alignment, and color schemes across the dashboard.

o	Published the dashboard to Tableau Public for easy sharing and portfolio display.

## Insights & Findings
### Country & Service Ratings:
The map visualization shows how different countries rate various service categories, revealing regional variations in customer satisfaction.
### Trend Analysis:
The line chart displays the fluctuation of average ratings over time, helping identify periods with higher or lower customer satisfaction.
### Aircraft Performance:
The dual bar chart provides insights into which aircraft groups receive higher ratings and how many reviews each group has, highlighting performance differences.
### Overall Discoveries:
The dashboard clearly demonstrates that customer ratings vary significantly across different dimensions (country, time, aircraft), and it offers a powerful tool for exploring these variations interactively.

## Final Thoughts
### Project Value:
This project showcases my ability to build a dynamic, interactive Tableau dashboard that combines multiple data sources and visualizations.
### Learning Outcomes:
I gained practical experience in parameter creation, calculated fields, and advanced filtering techniques in Tableau.
### Future Improvements:
While the dashboard is fully functional, further data cleaning and additional customizations could enhance its precision and visual appeal.
### Portfolio Impact:
This project is a strong addition to my portfolio, demonstrating my proficiency in data visualization and my ability to turn raw data into actionable insights.


