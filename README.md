# Exploring-Wage-and-Employment-Trends Across U.S. Industries

**Target Audience**: High School Seniors  
**Purpose**: To help students understand the U.S. job landscape and make informed decisions about future career paths by examining wage and employment trends across industries.

---

## **Introduction**

Choosing the right career path is one of the most important decisions students make as they prepare for their futures. A key factor in this decision is understanding wage and employment trends in different industries. This report uses wage and employment data to provide insights into various sectors, helping students weigh options in terms of salary potential and job availability.

---
## **Key Metrics in the Dashboard**

1. **Average Annual Wage by Industry** (Bar Chart)
    - This bar chart displays the average wages across different industries, with the **Information** sector leading with a yearly average wage of $94K. Other sectors, such as Finance, Business Services, and Manufacturing, offer competitive wages, whereas industries like Leisure & Hospitality tend to offer lower average wages.
2. **Wage and Employee Trends Over Time** (Line Chart)
    - This trend line shows the progression of average wages over the years (2017-2020) and the total number of employees in the Information sector. Over time, wages have steadily increased from $76K in 2017 to $94K in 2020, while employee numbers have remained relatively consistent around 2.7M.
3. **Share of Total Employees by Industry** (Pie Chart)
    - The Information industry comprises just **2%** of the total workforce, which highlights that while the wages are high, the sector is not as large as others in terms of employment.
4. **Average Wage and Employees Per 1,000 Capita by State** (Map)
    - This map highlights wage disparities and employment concentration by state. Darker colors indicate higher average wages in those states, providing a geographical perspective on job opportunities in the Information sector.
---
## **Insights**

- **High Wages in Information and Finance**: Students interested in higher-paying fields should consider industries like Information and Finance, both of which offer competitive wages.
- **Leisure & Hospitality**: Although this industry offers lower wages, it may be an entry point for students looking for more accessible, service-based jobs.
- **Geographical Influence**: Employment and wage opportunities vary by state, with some regions offering better compensation for workers in high-demand industries. For example, the West Coast shows higher wage averages in the Information sector compared to other regions.
---
## **Techniques & Tools Used**

1. **Statistical & Lookup Formula**:  
    To calculate average wages and employee counts, formulas like **AVERAGEIFS()**, **SUMIFS()** and **VLOOKUP()** were used to dynamically pull relevant data from the dataset.
2. **Inserting and Formatting Custom Charts**:  
    Various chart types were utilized to best display the data, such as bar charts for wage comparison and pie charts for employee share representation. These charts were customized with specific colors and labels to enhance readability.
3. **Dynamically Highlighting Series**:  
    Conditional formatting was applied to the map section of the dashboard to differentiate between two types of information. When the map shows **Employee per 1,000 Capita**, the regions are highlighted in **orange**, while for **Average Wage**, the regions appear in **green**. This dynamic color change helps the end user quickly distinguish between the metrics being visualized, making the dashboard more intuitive and user-friendly.
4. **Adding Form Controls**:  
    A drop-down list was added to allow users to select different industries, making the dashboard interactive and customizable based on user preference.
5. **Protecting Workbooks and Worksheets**:  
    To ensure data integrity and prevent accidental edits, the workbook and specific sheets were protected. This helps maintain the dashboard’s accuracy for end users.
---
## **Conclusion**

This dashboard and report provide an insightful look at wage and employment trends, particularly for high school seniors exploring career options. By understanding the U.S. job landscape, students can better align their career aspirations with industries offering growth potential, competitive wages, and job availability.

![](https://github.com/KunLinTsai24/Excel--Exploring-Wage-and-Employment-Trends/blob/main/img/Dashboard.png)
