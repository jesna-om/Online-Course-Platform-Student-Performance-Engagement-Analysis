# Online-Course-Platform-Student-Performance-Engagement-Analysis

Analysis of student performance on an online course platform with **Excel data cleaning** and an interactive **Power BI dashboard**. Includes **KPIs, course completion rates, enrollment trends, matrix tables, scatter plots**, and **DAX measures** to track progress, time spent, and top performers.

## Features
- **Data Cleaning (Excel):**
  - Standardize `Name`, `Gender`, `Country`
  - Convert `Time_Spent` to hours
  - Impute missing/invalid `Age`
  - Extract total sessions from `Session_Attendance`
  - Filter invalid emails and remove duplicates
  - Flag **High Performers** (`Completed = Yes` & `Feedback_Rating ≥ 4`)
  - Create `Experience_Level` based on Age
  - Calculate `Engagement Score` from Time Spent + Progress

- **Power BI Dashboard:**
  - Overview **KPIs**: Total Students, Avg Progress, Avg Rating, Completion %
  - **Category Analysis**: Students by Course Category, Completion Rate by Country
  - **Matrix Table**: Course vs Feedback Rating
  - **Line/Area Chart**: Enrollment trend by month
  - **Scatter Plot**: Correlation between Progress and Rating
  - **Custom DAX Measures**: Completion % by Category, Avg Time Spent per Category
  - **Slicers**: Filter by Course Category, Country, Experience Level
  - **Calculated Table**: Students who did not complete the course

## Technologies Used
- Microsoft Excel  
- Power BI Desktop  
- DAX (Data Analysis Expressions)

## How to Use
1. Open the cleaned dataset in Excel for reference or preprocessing.  
2. Open the Power BI `.pbix` file to explore the interactive dashboard.  
3. Use slicers to filter by Course Category, Country, or Experience Level.  
4. Hover over charts to see detailed tooltips.

