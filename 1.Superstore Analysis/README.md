# 🏪 Superstore Sales and Shipping Performance Analysis (Excel Project)

### 🧠 Overview
This project analyzes sales and shipping performance using the **Superstore dataset** in Excel.  
It explores trends in sales, shipping, and customer behavior across different regions and segments — all **without a profit column**.

The project demonstrates a complete end-to-end Excel analysis workflow:  
**data cleaning → calculated columns → PivotTables → charts → customer insights.**

---

### 📁 Folder Contents
| File / Folder | Description |
|----------------|-------------|
| **Raw Data.csv** | Original dataset used for analysis. |
| **Superstore Analysis.xlsx** | Cleaned and processed version with all derived columns, PivotTables, and charts. |
| **README.md** | Project documentation (this file). |
| **/Images/** | Contains chart snapshots for reference. |

---

### 🧹 Data Cleaning Steps
Data cleaning was performed in Excel (and partially with Power Query):
- Removed duplicates (`Order ID` + `Product ID`).
- Standardized date formats (`Order Date`, `Ship Date`).
- Added calculated columns:
  - `Shipping Days = [Ship Date] - [Order Date]`
  - `Order Month = TEXT([Order Date],"MMM")`
  - `Order Year = YEAR([Order Date])`
- Fixed missing or inconsistent Region / Postal Code values.
- Standardized text case for Category and Segment.

---

### 📊 Analyses Performed
**Sales Analysis**
- Total and average sales
- Top-performing categories and subcategories
- Regional and state-level contribution
- Customer segment spending patterns

**Shipping Analysis**
- Average shipping days
- Most used ship mode
- Region-wise delivery performance
- Orders delivered within 3 days

**Customer Insights**
- Number of unique customers
- Customers who purchased across multiple categories
- Top customers by sales volume
- Average order value per customer

---

### 📈 Key Findings
- **Top Regions:** West and East dominate overall sales.  
- **Shipping Time:** Average delivery time around *X days*.  
- **Top Segment:** Corporate customers show higher purchase frequency.  
- **Multi-Category Customers:** ~X% of customers bought from 2+ categories.

---

### 🧰 Tools & Techniques
| Tool | Purpose |
|------|----------|
| **Excel (Power Query)** | Data cleaning and formatting |
| **PivotTables & Charts** | Analytical summaries and trend visualization |
| **Slicers** | Interactive filtering (Dashboard-ready design) |
| **GitHub** | Version control & portfolio showcase |


---

### 🧑‍💻 Author
**Utkarsh Naik**  
Tech Professional | Data Analytics Enthusiast 
Contact: utkarsh.un@gmail.com