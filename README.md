# ☕ Coffee Orders Data Analytics Dashboard (Excel)

Author: Devkumar Chhatriwala  
Project Type: Data Analytics | Excel Dashboard  
Tool Used: Microsoft Excel  
Dataset Type: Sales & Product Lookup Data  
Learning Source: Inspired by Mo Chen (Data Analytics YouTube Channel)

This project is an end-to-end Excel-based data analytics dashboard built using raw coffee sales order data combined with a structured product master table. The dashboard provides business insights into customer purchasing behavior, product performance, revenue trends, and regional sales distribution. The objective of this project is to demonstrate core Excel analytics skills including lookup formulas, pivot tables, and interactive dashboard design.

--------------------------------------------

DATASET DESCRIPTION

The workbook consists of the following key sheets:

Orders Sheet  
Contains transactional sales data including Customer ID, Product ID, Quantity, Customer Name, Email, Country and multiple derived attributes using lookup formulas such as Coffee Type, Roast Type, Size, Unit Price, and Sales.

Products Sheet  
Acts as the master lookup table containing Product ID, Coffee Type, Roast Type, Size, and Unit Price.

Dashboard Sheet  
The final interactive dashboard created using Pivot Tables, Pivot Charts, Slicers, and calculated fields.

--------------------------------------------

KEY CONCEPTS IMPLEMENTED

Data Cleaning and Structuring  
Relational Lookups using INDEX and MATCH  
Calculated Sales Columns  
Pivot Table Modeling  
Interactive Filters using Slicers  
Business KPI Visualization  
Dashboard Layout and Design Best Practices  

--------------------------------------------

CORE LOOKUP FORMULA USED

=INDEX(products!$A$1:$G$49, MATCH(orders!$D2, products!$A$1:$A$49, 0), MATCH(orders!$I$1, products!$1:$1, 0))

This formula dynamically finds the correct product row using the Product ID and the correct attribute column using the field header, then returns the exact matching value. It is used to automatically populate Coffee Type, Roast Type, Size, and Unit Price in the Orders sheet.

--------------------------------------------

DASHBOARD FEATURES

Total Sales Overview  
Sales by Country  
Sales by Coffee Type  
Sales by Roast Type  
Quantity Sold Trends  
Customer Order Distribution  
Interactive Slicers for Country, Coffee Type, and Roast Type  
All visuals update dynamically based on slicer selections.

--------------------------------------------

BUSINESS QUESTIONS ANSWERED

Which coffee type generates the highest revenue  
Which country has the most customers  
Which roast type is most popular  
Which product size sells the most  
How sales performance changes based on different filters  

--------------------------------------------

TOOLS AND SKILLS DEMONSTRATED

Microsoft Excel Advanced  
INDEX and MATCH  
Pivot Tables and Pivot Charts  
Data Modeling  
Business Reporting  
Dashboard Design  
Data Cleaning  
KPI Visualization  

--------------------------------------------

HOW TO USE THIS PROJECT

Download the Excel file from this repository  
Open it using Microsoft Excel Desktop  
Navigate to the Dashboard sheet  
Use the slicers to interact with the data  
Observe how all metrics and charts update dynamically  

--------------------------------------------

LEARNING CREDITS

This project was created as a hands-on learning implementation inspired by Mo Chen’s Data Analytics YouTube tutorial and fully built, customized, and structured by Devkumar Chhatriwala for the purpose of strengthening Excel Analytics, Business Intelligence fundamentals, and data storytelling skills.

--------------------------------------------

DISCLAIMER

This project is created strictly for learning and portfolio demonstration purposes only. All data used is simulated or educational and does not represent real commercial transactions.

--------------------------------------------

REPOSITORY STRUCTURE

Coffee-Orders-Data-Analytics-Dashboard-Excel  
│  
├── Finished_coffeeOrdersData.xlsx  
└── README.md  

--------------------------------------------

CONTACT

Author: Devkumar Chhatriwala  
GitHub: https://github.com/DevKC98  

If you find this project helpful, feel free to star the repository.
