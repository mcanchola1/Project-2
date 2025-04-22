MIST 4610 – Group Project 2
<br>
Team Name
MIST 4610 11:10 Group 8

<br>
Team Members

Arnav Gupta,
Melanie Canchola,
Caroline Pitfield,
Ainsley Myers

<br>

Dataset Description
Dataset Name:
Average Salary by Job Classification

Source:
https://catalog.data.gov/dataset/average-salary-by-job-classification

Dimensions:
293 rows × 5 columns (after cleaning)

Columns Include:

Position Title – Name of the job role

Position Class Code – Job classification code

Grade – Job grade level

Average of Base Salary – Average base annual salary for the position

Number of Employees – Count of employees in that position

Data Types:

Text: Position Title

Numeric: Grade, Average of Base Salary, Number of Employees

Categorical/Numeric hybrid: Position Class Code

This dataset provides detailed salary information for various job positions and is suitable for examining patterns of compensation and workforce distribution.

<br><br>
Questions and Importance

Question 1

Is there a relationship between the average base salary of a position and the number of employees in that position?

Importance:
Examines how organizations invest in high-volume roles and whether those employees are fairly compensated. Socially relevant for understanding potential undervaluation of essential jobs.

Uses: Average of Base Salary and Number of Employees columns

<br>

Question 2

Is there a consistent correlation between job grade and average base salary across positions?

Importance:
Economically and organizationally important to ensure that salary progression aligns with increasing responsibility and expertise. Identifying inconsistencies may expose pay compression or outdated compensation structures.

Uses: Grade and Average of Base Salary columns


<br><br>

Data Manipulation

We removed all rows where the Grade column contained letters (e.g., "A1", "MGMT", etc.) instead of being a strictly numeric value. This was necessary to treat grade values as numerical data for correlation analysis and trend plotting. This step ensures that salary comparisons across grades are valid and interpretable in Tableau.

<br><be>

Analysis & Results
Visualizations Created in Tableau:

Is there a relationship between the average base salary of a position and the number of employees in that position?

<img width="607" alt="Screenshot 2025-04-17 at 12 11 11 PM" src="https://github.com/user-attachments/assets/ab717199-a6ab-473f-bd30-8a474c04a367" />

Key Findings:

Using a scatterplot, we are visualizing the average base salary in relation to the number of employees a person may have, using the data from Average Salary by Job Classification. We found that there is no significant correlation between the number of employees in a position and the compensation those employees recieve.

Is there a consistent correlation between job grade and average base salary across positions?   
<img width="564" alt="Screenshot 2025-04-17 at 12 13 30 PM" src="https://github.com/user-attachments/assets/bc942eab-2408-4752-86f5-6c5e7fe26369" />

Key Findings:

We are using the data from Average Salary by Job Classification to analyze how the job grade for a position is increasing or changing and has a correlation to the average salary using a line chart. We found that generally the higher the numeric grade of an individual employee, the greater their compensation would be.
   
<br>




<br><br>

Tableau Packaged Workbook
[Download Tableau Workbook](./Project2Tableau.twb) 

