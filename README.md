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
Hate Crimes 2017-2025

Source:
[https://catalog.data.gov/dataset/hate-crimes-2024](https://catalog.data.gov/dataset/hate-crimes-2024)

Dimensions:
293 rows × 5 columns (after cleaning)

Columns Include:



Data Types:



This dataset provides detailed salary information for various job positions and is suitable for examining patterns of compensation and workforce distribution.

<br><br>
Questions and Importance

Question 1

How does the age of offenders (under 18 vs. over 18) vary across different types of hate crime biases?
![image](https://github.com/user-attachments/assets/480592ea-8532-4dcf-bd3a-c7c3db989387)

Importance:
This graph compares the number of hate crimes by offenders over 18 and under 18 across different biases from 2017 to 2025. It shows that adults commit a majority of hate crimes, but certain biases, like Anti-Black and Anti-Gay (Male), have involvement from younger offenders. 

Uses: Target education and intervention efforts, especially among youth, to address bias-related violence early.

<br>

Question 2

During which years did hate crimes involving specific types of bias (e.g., Anti-Black, Anti-Gay, Anti-Jewish) peak, and what patterns emerge when comparing these spikes across time?
<img width="1131" alt="Screenshot 2025-04-27 at 7 37 52 PM" src="https://github.com/user-attachments/assets/5ca48e9d-233d-4cf1-b923-e4c30dc258a6" />
<img width="1108" alt="Screenshot 2025-04-27 at 7 44 48 PM" src="https://github.com/user-attachments/assets/fadea105-112e-4b6c-b43a-73a4c1e9236b" />


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

Using a scatterplot, we are visualizing the average base salary in relation to the number of employees with the same position in the county, using the data from Average Salary by Job Classification. We found that there is no significant correlation between the number of employees in a position and the compensation those employees recieve.

Is there a consistent correlation between job grade and average base salary across positions?   
<img width="564" alt="Screenshot 2025-04-17 at 12 13 30 PM" src="https://github.com/user-attachments/assets/bc942eab-2408-4752-86f5-6c5e7fe26369" />

Key Findings:

We are using the data from Average Salary by Job Classification to analyze how the job grade for a position is increasing or changing and has a correlation to the average salary using a line chart. We found that generally the higher the numeric grade of an individual employee, the greater their compensation would be.
   
<br>




<br><br>

Tableau Packaged Workbook
[Download Tableau Workbook](./Project2Tableau.twb) 

