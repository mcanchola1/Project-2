# MIST 4610 – Group Project 2

## Team Name:
**MIST 4610 11:10 Group 8**

## Team Members:
1. Arnav Gupta [@ArnavGupta](https://www.github.com/akg93611)  
2. Ainsley Myers [@AinsleyMyers](https://www.github.com/anm00752)  
3. Caroline Pitfield [@CarolinePitfield](https://www.github.com/cgpitfield)  
4. Melanie Canchola [@MelanieCanchola](https://www.github.com/mcanchola1)

---

## Dataset Description

**Dataset Name:** Hate Crimes 2017–2025  
**Source:** [Data.gov – Hate Crimes Dataset (2024)](https://catalog.data.gov/dataset/hate-crimes-2024)  
**Dimensions:** 267 rows × 15 columns

**Key Columns:**
- Month (String)  
- Incident Number (Integer)  
- Date of Incident (Date/Time)  
- Day of Week (String)  
- Number of Victims under 18 (Integer)  
- Number of Victims Over 18 (Integer)  
- Number of Offenders under 18 (Integer)  
- Number of Offenders Over 18 (Integer)  
- Race/Ethnicity of Offenders (Categorical)  
- Offense(s) (String)  
- Offense Location (String)  
- Bias (Categorical)  
- Zip Code (Integer)  
- APD Sector (Categorical)  
- Council District (Integer)

This dataset provides detailed information about hate crimes reported in the Austin area between 2017 and 2025. It includes demographics of both offenders and victims, offense types, bias categories, and geographic information.

---

## Analytical Questions and Visual Insights

### **Question 1:**  
**How does the age of offenders (under 18 vs. over 18) vary across different types of hate crime biases?**

![Offender Age by Bias Type](https://github.com/user-attachments/assets/480592ea-8532-4dcf-bd3a-c7c3db989387)

**Importance:**  
This chart compares offender age groups across bias types. While most hate crimes are committed by adults, some categories—like *Anti-Black* and *Anti-Gay (Male)*—show notable youth involvement.

**Use Case:**  
This insight supports targeted early-intervention and educational outreach, especially in schools and youth-focused programs.

---

### **Question 2:**  
**During which years did hate crimes involving specific biases (e.g., Anti-Black, Anti-Gay, Anti-Jewish) peak, and what trends emerge over time?**

![Bias Trends 1](https://github.com/user-attachments/assets/5ca48e9d-233d-4cf1-b923-e4c30dc258a6)

![Bias Trends 2](https://github.com/user-attachments/assets/fadea105-112e-4b6c-b43a-73a4c1e9236b)

**Importance:**  
These graphs reveal temporal spikes in specific types of hate crimes. Notably, *Anti-Black* and *Anti-Jewish* incidents saw surges in certain years, often aligning with social or political events.

**Use Case:**  
Understanding these patterns enables better resource planning and helps advocacy groups or city officials respond proactively to emerging bias-related threats.

**Note:**
We showed both pre and post filtering for biases with consistent trends versus those which had very little frequency and therefore were unable to show trends over time.

---

## Tableau Packaged Workbook

📊 [**Download the Tableau Workbook**](./Project2Tableau.twb)

This workbook includes interactive dashboards used to answer the questions above.

---
