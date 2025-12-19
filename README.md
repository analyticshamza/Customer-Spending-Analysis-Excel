# Customer Spending Analysis – Excel

## Project Overview
This project focuses on analyzing retail customer purchase data to understand customer spending behavior, product category performance, and regional revenue trends using Microsoft Excel.

The analysis is performed using Excel formulas and conditional formatting, without using Pivot Tables or charts, to demonstrate strong fundamentals in data analysis and business reporting.

---

## Objectives
- Calculate overall average revenue and identify high-value transactions
- Improve date readability using custom date formats
- Categorize customers into age groups using conditional formatting
- Compare product categories based on average customer spending
- Analyze total revenue contribution by region

---

## Dataset
- **File:** `retail_customer_purchases.csv`
- **Key Columns:**
  - CustomerID
  - ProductCategory
  - PurchaseDate
  - Revenue
  - Age
  - Region
  - PurchaseFrequency

---

## Tools Used
- Microsoft Excel

---

## Techniques & Functions Applied
- **Formulas:**  
  - `AVERAGE`  
  - `AVERAGEIF`  
  - `SUMIF`
- **Conditional Formatting**
- **Custom Date Formatting (DD-MMM-YY)**
- **Table-based data analysis (no Pivot Tables)**

---

## Analysis Performed

### 1. Average Revenue & High-Value Transactions
- Calculated overall average revenue using `AVERAGE`
- Highlighted transactions above the average using conditional formatting and currency formatting

---

### 2. Purchase Date Formatting
- Converted purchase dates to a user-friendly format (`DD-MMM-YY`) for better readability

---

### 3. Age Group Categorization
Customers were categorized into the following age groups using conditional formatting formulas:
- Under 18
- 18–29
- 30–49
- 50 and above

Each age group was visually differentiated using distinct formatting styles.

---

### 4. Product Category Spending Analysis
- Created a summary table for product categories
- Used `AVERAGEIF` to calculate average revenue per category
- Highlighted:
  - **Highest average spending category** in green
  - **Lowest average spending category** in red

---

### 5. Regional Revenue Analysis
- Created a regional summary table
- Used `SUMIF` to calculate total revenue for each region
- Identified regions with the highest and lowest customer spending

---

## Key Insights
- Sports category generated the highest average revenue
- Electronics category showed the lowest average customer spending
- South region contributed the highest total revenue
- Conditional formatting made spending patterns easy to interpret at a glance

---

## Screenshots

### Above-Average Revenue Highlighting
<img src="https://github.com/user-attachments/assets/755b3417-110d-4d9d-9a0e-b08f0ef9b34d" width="700"/>

### Age Group Categorization
<img src="https://github.com/user-attachments/assets/7d5b453b-be70-47be-939e-ec4beec60a3d" width="700"/>

### Average Revenue by Product Category
<img src="https://github.com/user-attachments/assets/7b2e79ce-0a1c-4fdb-ad49-583f74813128" width="700"/>

### Total Revenue by Region
<img src="https://github.com/user-attachments/assets/b546aeba-e7cc-4393-846e-32782323d326" width="700"/>

---

## Author
**Ali Hamza Shaikh**
