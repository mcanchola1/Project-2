MIST 4610 – Group Project 2
Team Name & Members
Team Name: MIST 4610 11:10 Group 8
Team Members:

Arnav Gupta

Melanie Canchola

Caroline Pitfield

Ainsley Myers

📊 Dataset Description
Dataset Name: Average Salary by Job Classification

Source: https://catalog.data.gov/dataset

Dimensions: 293 rows × 5 columns (after cleaning)

Columns Include:

Position Title – Name of the job role

Position Class Code – Job classification code

Grade – Job grade level

Average of Base Salary – Average base annual salary for the position

Number of Employees – Count of employees in that position

Data Types:

Text (Position Title)

Numeric (Grade, Average of Base Salary, Number of Employees)

Categorical/Numeric hybrid (Position Class Code)

This dataset provides detailed salary information for various job positions and is suitable for examining patterns of compensation and workforce distribution.

❓ Questions and Importance
Question 1:
Is there a consistent correlation between job grade and average base salary across positions?

Importance: Economically and organizationally important to ensure that salary progression aligns with increasing responsibility and expertise. Identifying inconsistencies may expose pay compression or outdated compensation structures.

Data Link: Uses Grade and Average of Base Salary columns.

Question 2:
Is there a relationship between the average base salary of a position and the number of employees in that position?

Importance: Examines how organizations invest in high-volume roles and whether those employees are fairly compensated. Socially relevant for understanding potential undervaluation of essential jobs.

Data Link: Uses Average of Base Salary and Number of Employees columns.

🛠️ Data Manipulation
To ensure clean and accurate analysis:

We removed all rows where the Grade column contained letters (e.g., "A1", "MGMT", etc.) instead of being a strictly numeric value.

This was necessary to treat grade values as numerical data for correlation analysis and trend plotting.

This step ensures that salary comparisons across grades are valid and interpretable in Tableau.

Filtered out incomplete or null rows for salary and grade.

Created calculated fields in Tableau for:

Correlation

Salary bins

Employee volume categories

📈 Analysis & Results
Visualizations Created in Tableau:

Scatter plots to show salary trends by grade and employee volume

Histograms for salary distribution across grades

Heatmaps to identify clusters of underpaid high-volume roles

Key Findings:

A general positive trend exists between job grade and salary, though there are outliers.

Some high-volume positions fall below the median salary line, indicating potential undervaluation of common roles.

🧳 Tableau Packaged Workbook
📁 [Link to Tableau .twbx file uploaded in this repository]
Open this file in Tableau Desktop to explore the dashboards and calculated fields used in the analysis.

📚 References
Dataset Source: catalog.data.gov

Tableau Documentation: https://www.tableau.com/learn
