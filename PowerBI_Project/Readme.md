# Power BI Project: Data Pro Insight - Survey Breakdown
This project showcases my work using Power BI to transform, analyze, and visualize real survey data from data professionals. The dataset has around 600–700 respondents, and I used it to build an interactive dashboard that provides insights into job roles, salaries, programming language preferences, and more. <a href = "https://github.com/ak060204/Data-visualization-projects/blob/main/PowerBI_Project/PowerBI_Dashboard_screenshot.png"> View Dashboard </a>

## Project Objectives
### What I'm Doing:
Transforming raw survey data in Power BI, cleaning and standardizing key columns, and building a comprehensive dashboard.
### Project Focus:
Analyzing real-world data from data professionals to answer questions about job titles, salary ranges, programming language usage, work satisfaction, and entry difficulty into data science.
### Key Questions: 
o	What are the common job titles and how do they correlate with salary ranges?

o	Which programming languages are most favored by data professionals?

o	How do factors like country and gender affect average salaries?

o	What are the satisfaction levels regarding work-life balance and salary?

o	How difficult is it perceived to break into data science?

## Dataset & Data Cleaning
### Dataset Description:
The raw data is a CSV file from an online survey and includes: 

o	Unique ID, job title, current yearly salary (as a range), industry, favorite programming language, job satisfaction ratings, difficulty in breaking into data science, demographics (age, gender, country), and more.
### Data Cleaning Process: 
#### Job Titles:
Simplified and standardized by splitting the text at delimiters (e.g., parentheses) to reduce variation.

#### Favorite Programming Language:

Split free-text responses using a colon as a delimiter to consolidate similar answers (e.g., different ways of writing "SQL").

#### Salary Range:

Split the "current yearly salary" column into minimum and maximum values, then calculated an average salary. Removed extraneous characters (e.g., "K", dashes, plus signs) to convert text into numeric values.

#### Other Transformations:
Removed unnecessary columns and applied similar cleaning steps to country and other categorical fields.

## Dashboard Creation Process
###	Import & Transformation:
Imported the CSV file into Power BI and used Power Query to perform all cleaning and transformation steps.

### Building Visualizations: 

![PowerBI_Dashboard_screenshot](https://github.com/user-attachments/assets/f18e3c58-f40e-4f59-9777-3fbcdd315960)

#### Cards: 
	Count of Survey Takers: Displayed the total number of unique respondents.

	Average Age of Survey Takers: Shown as a high-level metric.

#### Bar Charts & Column Charts: 
	Average Salary by Job Title: Visualized using a stacked bar chart to compare roles like Data Scientists, Data Engineers, Data Architects, and Data Analysts.

	Favorite Programming Languages: Used a clustered column chart to show the count of votes per language.

#### Tree Map: 
	Country Breakdown: Displayed the distribution of survey takers by country, highlighting how salary differences can be influenced by geographic location.
#### Gauge Charts: 
	Difficulty in Breaking into Data Science: Showed the average difficulty rating (with proper min/max values) for entering the field.
#### Donut Chart: 
	Average Salary by Gender: Compared average salaries between males and females.
#### Dashboard Layout & Formatting: 
o	Added a title ("Data Professional Survey Breakdown") at the top.

o	Rearranged and resized visualizations for clarity.

o	Applied custom themes and adjusted colors for a clean, professional look.

## Insights & Findings
### Job Titles & Salaries: 
o	Data Scientists were found to have the highest average salary, followed by Data Engineers and Data Architects. Data Analysts had a lower median salary.
### Programming Languages: 
o	Python emerged as the most popular programming language among survey respondents.
### Country & Salary Impact: 
o	Salary averages varied by country, reflecting differences in cost of living.
### Gender Comparison: 
o	The average salary for female respondents was slightly higher than that for males.
### Job Satisfaction: 
o	Ratings for work-life balance and salary satisfaction were moderate, with respondents indicating room for improvement.
### Difficulty in Breaking Into Data Science: 
o	The gauge chart revealed varied perceptions of difficulty, with many rating it around the middle of the scale.

## Final Thoughts
•	This project provided a hands-on opportunity to work with real survey data using Power BI.

•	While the data cleaning was kept at a basic level for this project, it highlighted the importance of standardizing free-text responses and numeric ranges.

•	The dashboard delivers actionable insights into the professional landscape of data practitioners and can be further enhanced with more in-depth cleaning and additional analysis.

•	I am confident this project adds value to my portfolio and demonstrates my ability to work with real-world data and build interactive dashboards in Power BI.
