```markdown
# Bike Sales Dashboard — Excel Analytics Project

## 📊 Project Overview

An interactive Excel dashboard built to analyze customer purchasing behavior for a bike retailer. The dashboard visualizes key customer demographics — gender, marital status, region, age bracket — against bike purchase outcomes, enabling quick, filterable insights through dynamic slicers. Designed to demonstrate end-to-end data analytics skills: data cleaning, pivot table construction, data visualization, and dashboard design.

## 🎯 Objective

To transform raw, unclean customer transaction data into a clean, interactive, single-page dashboard that helps identify patterns in who purchases bikes — by demographic segment — to support data-driven marketing and sales decisions.

## 🗂️ Dataset

- **Source:** Bike Buyers dataset (Kaggle)
- **Size:** ~1,000 customer records
- **Fields:** Customer ID, Marital Status, Gender, Income, Children, Education, Occupation, Home Owner, Cars, Commute Distance, Region, Age, Purchased Bike

## 🛠️ Tools Used

- Microsoft Excel (PivotTables, PivotCharts, Slicers, Conditional Formulas, Report Connections)

## 🔧 Process & Methodology

### 1. Data Cleaning
- Removed duplicate records using Excel's built-in Remove Duplicates tool
- Standardized categorical codes (e.g., `M`/`S` → "Married"/"Single", `M`/`F` → "Male"/"Female") using Find & Replace
- Engineered a new **Age Bracket** column using nested IF formulas to segment customers into "Youngster" (0–30), "Middle Age" (31–54), and "Old" (55+)

### 2. Pivot Table Analysis
Built four PivotTables to summarize the cleaned dataset:
- **Average Income by Gender**, segmented by Purchase status
- **Customer Count by Marital Status**, segmented by Purchase status
- **Customer Count by Region**, segmented by Purchase status
- **Customer Count by Age Bracket**, segmented by Purchase status

### 3. Data Visualization
- Created PivotCharts linked directly to each PivotTable for live data updates
- Used a mix of chart types (clustered column and line charts) to suit each data story and avoid visual repetition
- Added data labels, chart titles, and axis titles to each chart for clarity and readability

### 4. Interactive Dashboard Assembly
- Consolidated all charts onto a single Dashboard sheet with a clean 2×2 grid layout
- Added a styled title banner for a polished, presentation-ready look
- Inserted multiple slicers (Purchased Bike, Marital Status, Region, Education) connected via Report Connections to all four PivotTables simultaneously
- Enables real-time cross-filtering — selecting any slicer value updates all four charts at once

## 📈 Key Insights

- Male customers show a higher average income than female customers across both buyers and non-buyers
- Middle-aged customers (31–54) represent the largest share of both buyers and non-buyers, making them the core customer segment
- Purchase behavior varies notably by region, with North America showing the highest customer volume
- Single customers show a slightly higher bike purchase rate compared to married customers

## ✅ Skills Demonstrated

- Data cleaning and preprocessing in Excel
- Conditional logic with nested IF formulas
- PivotTable and PivotChart construction
- Dashboard design and layout for stakeholder-facing reporting
- Interactive filtering using Slicers and Report Connections
- Data storytelling through appropriate chart type selection

## 📌 How to Use

1. Open the Excel file
2. Navigate to the **Dashboard** sheet
3. Use the slicers on the left/right panels to filter by Purchased Bike, Marital Status, Region, or Education
4. All four charts update simultaneously to reflect the selected filter(s)

## 🧠 What I Learned / Conclusion

This project gave me hands-on, practical experience with the full analytics workflow — from messy raw data to a finished, decision-ready dashboard — rather than just learning Excel features in isolation.

**Data cleaning is the real foundation.** Before any chart or pivot table means anything, the underlying data has to be trustworthy. Working through duplicate removal, standardizing inconsistent category labels, and engineering a new Age Bracket column using nested IF logic taught me how much upfront effort goes into making data "analysis-ready" — and how a single unclean field (like inconsistent gender codes) can silently distort every downstream chart.

**PivotTables are more powerful than they first appear.** Rather than writing manual formulas to calculate averages or counts per category, I learned to let PivotTables handle aggregation dynamically — switching between Sum and Count, filtering with the Values Field Settings, and understanding how Rows, Columns, and Values interact to reshape the same dataset into different views instantly.

**Chart type choice affects how insights are perceived.** I initially used clustered column charts for everything, but learned that line charts communicate trends across ordered categories (like age brackets) more clearly, while column charts are better for direct category-to-category comparison. Mixing chart types deliberately — rather than defaulting to one style — made the dashboard easier to read and more visually engaging.

**Slicers and Report Connections are what make a dashboard "interactive" rather than just a collection of static charts.** Understanding that a single slicer can control multiple PivotTables simultaneously — as long as they share the same source data and are explicitly connected — was the key technical concept that turned four separate charts into one cohesive, filterable dashboard.

**Dashboard layout and design matter as much as the data itself.** Small details — a title banner, consistent chart sizing, axis labels, data labels, and slicer placement — significantly changed how "professional" the end result looked. I learned that a dashboard isn't just about correct numbers; it's about presenting those numbers in a way that's immediately scannable for a non-technical viewer.

Overall, this project strengthened my confidence in using Excel not just as a spreadsheet tool, but as a lightweight BI (Business Intelligence) platform — skills that translate directly to tools like Power BI, where the same core concepts (data modeling, aggregation, filtering, and visualization) apply at a larger scale.
```

Want me to also save this as an actual `.md` file you can directly upload to your GitHub repo?
