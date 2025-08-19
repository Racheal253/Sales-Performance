# Sales-Performance

## Table Of Contents

- [Project Overview](#project-overview)
- [Audience](#audience)
- [Data Sources](#data-sources)
- [Data Structure](#data-structure)
- [Tool used for the analysis](#tool-used-for-the-analysis)
- [Data Preparation](#data-preparation)

 
## Project Overview 

This project aims to deliver insights into sales performance for MavenTech Company across various teams. The analysis focuses on key performance indicators (KPIs) such as total sales, win rates, and sales trends over time. Data from different teams were consolidated and visualized using Power BI to provide a comprehensive view of each team's contribution to the company's overall performance. The project incorporates interactive elements such as buttons for easy navigation between reports, card visuals with reference labels for quick summaries, and up/down arrows to signal growth or decline in sales.

The project also includes in-depth DAX measures to analyze sales performance by individual team members, allowing sales managers to identify areas of improvement and make informed decisions.



<img width="608" height="338" alt="sales performance" src="https://github.com/user-attachments/assets/c84438c7-0a9b-4317-8a28-bc442f323e30" />   <img width="616" height="337" alt="sales performance2" src="https://github.com/user-attachments/assets/d49db95e-675d-4351-bc04-ac50914d0e89" />   <img width="602" height="335" alt="sales performance3" src="https://github.com/user-attachments/assets/0b540a25-733b-447e-a119-46a1b78b75ab" />


## Audience 

Sales Managers

## Data Sources 

- "products.csv" : details of products
- "sales team.csv" : information about the sales team 
- "sales pipeline.csv": details of sales and sales stages"
- "account.csv" : details of company name and employees

## Data Structure
- Multiple Tables: 4
- Number of Records: 200,000
- Number of Fields: 22
  
## Tool used for the analysis 
PowerBI- for cleaning, analyzing and building reports. 

## Data Preparation 

The data was mostly clean,so there was not much cleaning required. However, the following steps were taken to ensure data validity:
1. Data loading and inspection
2. Changed type of some columns
3. Removed unnecessary columns
4. Handled missing values: There were about 15% missing valus in the patient location data, but these missing values did not significantly affect the analysis, so they were left as it was.
5. Created a date table using Dax to facilitate time-based analysis.








