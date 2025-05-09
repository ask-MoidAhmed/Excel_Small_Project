# 🗂 Excel Practice Data Analysis

**By Moid Ahmed**  
*Information Systems student at SNHU | Fulfillment & Data Analysis Specialist*

---

## 📋 Overview

This project is a **hands-on data cleaning, enhancement, and analysis exercise** using sample data from [Excel Practice Online](https://excel-practice-online.com/tools/practice-data-worksheet-excel-practice-online/). The aim was to transform raw sales data into actionable insights through structured cleaning, validation, and dynamic Excel formulas, charts, and dashboards.

---

## 🔧 Steps Completed

### 1️⃣ Data Preparation & Cleanup

- **Converted dataset to a structured table** for easier referencing.
- **Fixed inconsistencies:**
  - Standardized dates (numbers vs. text) using *Text to Columns*.
  - Corrected data types and formatting:
    - *List Price* & *Actual Price* → Currency format.
    - *Discount %* → Calculated field (relying on List & Actual Price).

![image](https://github.com/user-attachments/assets/55549f14-d3ff-425d-b4a0-89a874360767)
   
- **Validation:**
  - Ensured *Actual Price ≤ List Price*.
  - Verified dates (e.g., day ≤ 31).

![image](https://github.com/user-attachments/assets/94c74fdf-8878-4252-ac14-cd55f9f81788)

---

### 2️⃣ Adding Extra Data Fields

- **Sales Tax:**  
  `7.45%` of *Actual Price*.

![image](https://github.com/user-attachments/assets/2a1264c1-cce7-4f77-aea7-2cf227215c68)
  
- **Shipping Fee:**  
  - USA → `$0`  
  - Outside USA → `13.4%` of *Actual Price*.  
  *(Used named ranges for clarity & flexibility.)*

![image](https://github.com/user-attachments/assets/f7181d8b-de9d-479d-a8b7-8340bfbe2a10)

- **Revenue per Transaction:**  
  - `Actual Price + Sales Tax + Shipping Fee`
 
![image](https://github.com/user-attachments/assets/c3db4ee4-901e-4d0e-8c9f-d16c48e0a850)

- **Random Customer Rating:**  
  - Added a *randomized score* for customer service evaluation.
- **Value Paste:**
  - Converted formulas to static values to prevent unwanted changes on undo.
 
![image](https://github.com/user-attachments/assets/35abaa6f-85f1-4079-8616-ea9ed8703ea1)

- **Helper Row:**  
  - Extracted *Year* from each transaction’s date (hidden after setup).  

  ![image](https://github.com/user-attachments/assets/d4364938-de50-4284-9ed0-4dbfa7f3dc3b)

---

## 📈 Data Analysis & Visualization

- **Dynamic Total Revenue:**
  - Used `SUMIFS` to calculate revenue **by Region & Year**.
  - Created a **dropdown list** (years) to select and auto-update results.

![image](https://github.com/user-attachments/assets/68aa00ef-1cdb-4799-b049-23f30c011de8)
    
- **Pie Charts:**
  - *Revenue Distribution* by Region.
  - *Profit Distribution* (assuming 40% of Shipping Fee is profit).
 
![image](https://github.com/user-attachments/assets/6f49a8d1-a3ac-4aa4-9074-09da6486dfdd)

![image](https://github.com/user-attachments/assets/78f03b32-7b49-4c47-8cac-c715108e577a)

- **Bar Charts:**
  - Average Revenue per Region.
- **KPI Metrics:**
  - Avg. Rating.
  - Avg. Revenue.
  - Profit Margin %.

![image](https://github.com/user-attachments/assets/8eefc57d-9484-4928-ae7d-8fe345a30c25)

---

## 🤓 Advanced Formulas & Insights

- **Top Salesperson:**  
  Identified the *best performer* by **Region & Year**, showing total revenue generated.

  ![image](https://github.com/user-attachments/assets/e2059149-f6ca-49ef-ad11-215f03525bf3)

  ![image](https://github.com/user-attachments/assets/47332d75-32bf-4238-b033-a72938ccb886)

- **Average Discount per Item:**  
  Summary table of discounts across items.

![image](https://github.com/user-attachments/assets/4a39a631-46b2-49cb-9073-d97027185d21)

- **Top Country Analysis:**  
  - Found the country with the **highest revenue** for the selected Region & Year.
  - Identified the **top product** in that country & its revenue.
 
  ![image](https://github.com/user-attachments/assets/65ee3066-f782-442e-b3dd-9f811face55e)

- **Discount Adjustment Scenario:**
  - Located the item with the **highest discount %** (with its item code).
  - Allowed entry of a **new discount %** to recalculate:
    - Old & updated *List Price* and *Actual Price* (auto-updated by Region & Year).

  ![image](https://github.com/user-attachments/assets/5ba96fc3-1655-4f9c-b494-ce6e580d16c2)

---

## 🔮 Projections & Trend Analysis

- **Projected Revenue:**  
  Forecasted next year's revenue using growth assumptions.

  ![image](https://github.com/user-attachments/assets/88cb5f16-d76d-4428-acbf-95795a584b6f)

- **Trend to 2030:**  
  Created a **line chart** visualizing expected revenue growth through 2030.

  ![image](https://github.com/user-attachments/assets/4a5ff49a-d823-4e71-9b41-1c1b93014ada)

## 🚀 Why This Matters

This project demonstrates my capability to:

- Handle **real-world messy data**.
- Build **dynamic, automated dashboards**.
- Apply **advanced Excel techniques** (validation, named ranges, dynamic formulas).
- Use **data analysis** for actionable business insights.
- Deliver **visualizations** that enhance decision-making.

---

## 🛠 Tools & Skills Used

- Excel Tables & Structured References
- Text to Columns
- Data Validation & Error Checking
- Advanced Formulas (SUMIFS, INDEX-MATCH, dynamic arrays)
- Named Ranges
- Data Visualization (Pie, Bar, Line Charts)
- Dashboard Creation
- Scenario Modeling & Forecasting

---

## 👤 About Me

**Moid Ahmed**  
Information Systems Student at SNHU | Team Lead at Walmart Fulfillment | Excel & Data Analytics Enthusiast
