# Google Data Analytics Capstone Case Study: Cyclistic Bike-Share Analysis

This project is part of the **Google Data Analytics Professional Certificate** capstone course. 
The goal of the case study is to analyze data from Cyclistic, a fictional bike-share company, to understand how casual riders and annual members use Cyclistic bikes differently.
Insights from this analysis will guide marketing strategies to convert casual riders into annual members.

---

## Table of Contents
- [Overview](#overview)
- [Business Task](#business-task)
- [Dataset](#dataset)
- [Tools Used](#tools-used)
- [Process](#process)
- [Key Insights](#key-insights)
- [How to View the Project](#how-to-view-the-project)
- [Contact](#contact)

---

## Overview
Cyclistic is a bike-share company offering bikes for rent across the city. The marketing team wants to design strategies to convert casual riders into annual members.
This case study applies the **six Phases of data analysis**: **Ask, Prepare, Process, Analyze, Share, and Act** to derive actionable insights.

---

## Business Task
The primary business task is: 
 - Analyze Cyclistic's historical data to understand differences between annual members and casual riders.
 - Identify patterns that can inform marketinf strategies to convert casual riders into annual members.

---

## Dataset
- **Source**: Cyclistic's publicly available trip data (provided by the course).
- **Timeframe**: The first 2 months of trip data from 2023.
- **Size**: Almost 400,000 rows
- **Features**: Trip start/end times, locations, use types (casual vs. member), bike types, and ride duration.

**Note** Data has been anonymized to protect user privacy.

---

## Process
The analysis followed these six phases:

1. **Ask**
   - Define the business task and key questions.
   - Identify stakeholders and objectives.

2. **Prepare**
   - Import Cyclistic trip data and validate its structure.
   - Assess for errors, missing values, and inconsistencies.
  
3. **Process**
   - Clean the data using Google Spreadsheet (I Chose spreadshhets because of the small amound of data).
   - Removed duplicates, missing values and filter out erroneous data (e.g., negative ride times, test rides, and zero ride_lengths)
  
4. **Analyze**
   - Compare usage patterns (e.g., ride duration, popular days) between casual riders and members.
   - I did not explore seasonal trends because I worked only for two months of the year (January/February) but i explored weekdays and weekends and bike type preferences.
  
5. **Share**
   - Create visualizations in Tableau and R.
   - Highlight key differences in usage behavior.
  
6. **Act**
   - Provide actionable recommendations for the marketing team.
  
---

## Key Insights
1. **Ride Duration**: Casual riders tend to take longer rides than annual members.
2. **Peak Times**: Casual riders primarily use bikes on weekends, while members use them consistently throughout the week.
3. **Bike Preferences**: Members prefer docked bikes, whereas casual riders favor electric bikes.
4. **Seasonality**: Casual rider activity peaks in summer, suggesting a preference for leisure use.

### Recommendations:
 - Launch weekend promotional campaigns targeting casual riders.
 - Offer discounted annual memberships for electric bike users.
 - Promote membership benefits (e.g., cost savings, flexibility) through targeted ads during peak seasons.

---

## How to view the project
1. **R Script**: The full R script for data cleaning, analysis, and visualization can be found in this repository:
   - [cyclistic_analysis.R]( cyclistic_analysis.R)
2. **Tableau Dashboard**: View the interactive dashboard here:
   - [Cyclistic Bike-Share Analysis Dashboard](#)
3. **Project Report**:The final report summarizing the analysis and recommendations is available as a PDF:
   - [Cyclistic_Case_Study_Report.pdf](#)
  
---

## Contact
Craeted by **Carlos Coreas** as part of the Google Data Analytics Professional Certificate.

- **Portfolio**: [](#)
- **LinkedIn**: [Carlos Coreas LinkedIn](#)
- **Email**: carloscoreas2015@gmail.com

Feel free to contact me or reach out with any questions!
<!---
CarlosCoreas/CarlosCoreas is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
