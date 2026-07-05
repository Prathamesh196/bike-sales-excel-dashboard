# 🚴 Bike Sales Dashboard — Excel Analytics Project

## 📊 Project Overview

The **Bike Sales Dashboard** is an interactive data analytics project built entirely in **Microsoft Excel** to analyze customer purchasing behavior for a bike retailer. Using a dataset of approximately 1,000 customer records, the dashboard transforms raw data into meaningful business insights through data cleaning, PivotTables, PivotCharts, and interactive slicers.

The dashboard enables users to explore relationships between customer demographics and bike purchase decisions, helping identify trends across gender, marital status, age groups, education levels, and geographic regions.

---

## 🎯 Objective

The primary objective of this project is to transform raw customer data into an interactive and decision-ready dashboard that helps uncover patterns in bike purchasing behavior and supports data-driven business decisions.

---

## 🗂️ Dataset Information

- **Dataset:** Bike Buyers Dataset
- **Source:** Kaggle
- **Records:** Approximately 1,000 customer records
- **File Type:** Excel Spreadsheet

### Dataset Features

- Customer ID
- Marital Status
- Gender
- Income
- Children
- Education
- Occupation
- Home Owner
- Number of Cars
- Commute Distance
- Region
- Age
- Purchased Bike

---

## 🛠️ Tools & Technologies Used

- Microsoft Excel
- PivotTables
- PivotCharts
- Slicers
- Conditional Formulas
- Report Connections
- Data Cleaning Techniques
- Dashboard Design Principles

---

## 🔧 Project Workflow

### 1️⃣ Data Cleaning & Preparation

The raw dataset was cleaned and standardized before analysis:

- Removed duplicate records using Excel's Remove Duplicates feature
- Standardized categorical values
  - `M` → Male
  - `F` → Female
  - `M` → Married
  - `S` → Single
- Validated missing and inconsistent values
- Created a new **Age Bracket** column using nested IF formulas

### Age Bracket Logic

| Age Range | Category |
|------------|------------|
| 0 – 30 | Youngster |
| 31 – 54 | Middle Age |
| 55+ | Old |

Example Formula:

```excel
=IF(L2<=30,"Youngster",IF(L2<=54,"Middle Age","Old"))
```

---

### 2️⃣ Pivot Table Analysis

Four PivotTables were created to summarize customer behavior:

#### Average Income by Gender

Analyzes average income across:

- Male Customers
- Female Customers

Further segmented by:

- Purchased Bike = Yes
- Purchased Bike = No

#### Customer Count by Marital Status

Analyzes purchase behavior among:

- Married Customers
- Single Customers

#### Customer Count by Region

Regional distribution of customers:

- Europe
- North America
- Pacific

#### Customer Count by Age Bracket

Segments customers into:

- Youngster
- Middle Age
- Old

and compares bike purchase outcomes.

---

### 3️⃣ Data Visualization

PivotTables were converted into interactive PivotCharts.

Chart types used:

| Analysis | Chart Type |
|-----------|------------|
| Income vs Gender | Clustered Column Chart |
| Marital Status Analysis | Clustered Column Chart |
| Regional Distribution | Clustered Column Chart |
| Age Bracket Analysis | Line Chart |

Additional enhancements:

- Chart Titles
- Axis Labels
- Data Labels
- Consistent Formatting
- Improved Readability

---

### 4️⃣ Interactive Dashboard Design

A professional single-page dashboard was created containing:

- Dashboard Title Banner
- Four Interactive Charts
- Multiple Slicers
- Consistent Layout Design

### Dashboard Filters (Slicers)

The following slicers were added:

- Purchased Bike
- Marital Status
- Region
- Education

Using **Report Connections**, each slicer controls all PivotTables simultaneously, allowing real-time dashboard interaction.

---

## 📈 Key Insights

### 💰 Income Analysis

- Male customers exhibit a higher average income than female customers across both buyer and non-buyer segments.

### 👥 Age Analysis

- Middle-aged customers (31–54 years) represent the largest customer segment.
- This age group also contributes the highest volume of bike purchases.

### 🌎 Regional Analysis

- North America records the highest customer volume.
- Purchase behavior varies significantly across different regions.

### 💍 Marital Status Analysis

- Single customers show a slightly higher bike purchase rate compared to married customers.

---



```text
Project Folder
│
├── Dashboard Screenshot.png
├── Bike Sales Dashboard.xlsx
└── README.md
```

Example:

```markdown
![Dashboard Preview](Dashboard%20Screenshot.png)
```

---

## 📊 Business Value

This dashboard helps businesses:

- Understand customer demographics
- Identify high-value customer segments
- Analyze regional demand patterns
- Support targeted marketing campaigns
- Improve data-driven decision making

---

## 🧠 Skills Demonstrated

### Data Analysis

- Data Cleaning
- Data Validation
- Data Transformation
- Data Aggregation

### Excel Skills

- PivotTables
- PivotCharts
- Slicers
- Report Connections
- Nested IF Functions
- Dashboard Design

### Business Intelligence Concepts

- Interactive Reporting
- KPI Visualization
- Data Storytelling
- User-Centric Dashboard Design

---

## 🚀 How to Use

1. Download the Excel file.
2. Open the workbook in Microsoft Excel.
3. Navigate to the **Dashboard** worksheet.
4. Use the slicers to filter data by:
   - Purchased Bike
   - Region
   - Marital Status
   - Education
5. Watch all charts update dynamically based on selected filters.

---

## 📚 Learning Outcomes

This project provided practical experience with the complete analytics workflow:

- Transforming raw data into analysis-ready datasets
- Building efficient PivotTable-based summaries
- Creating meaningful visualizations
- Designing interactive dashboards
- Applying data storytelling principles
- Developing business intelligence reporting skills

The project reinforced the importance of data preparation, visualization selection, dashboard usability, and stakeholder-focused reporting while demonstrating how Microsoft Excel can function as a lightweight Business Intelligence platform.

---

## 📂 Project Structure

```text
Bike-Sales-Dashboard/
│
├── Bike Sales Dashboard.xlsx
├── Dashboard Screenshot.png
└── README.md
```

---

## 👨‍💻 Author

**Prathamesh Gawali**

B.Tech Computer Science and Engineering  
D. Y. Patil International University, Pune

---

## ⭐ If you found this project useful, consider giving it a star!
