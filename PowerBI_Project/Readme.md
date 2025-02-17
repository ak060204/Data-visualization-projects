# Power BI Final Project
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
o	Job Titles:
Simplified and standardized by splitting the text at delimiters (e.g., parentheses) to reduce variation.

o	Favorite Programming Language:

Split free-text responses using a colon as a delimiter to consolidate similar answers (e.g., different ways of writing "SQL").

o	Salary Range:

Split the "current yearly salary" column into minimum and maximum values, then calculated an average salary. Removed extraneous characters (e.g., "K", dashes, plus signs) to convert text into numeric values.

o	Other Transformations:
Removed unnecessary columns and applied similar cleaning steps to country and other categorical fields.

## Dashboard Creation Process
###	Import & Transformation:
Imported the CSV file into Power BI and used Power Query to perform all cleaning and transformation steps.

### Building Visualizations: 
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

