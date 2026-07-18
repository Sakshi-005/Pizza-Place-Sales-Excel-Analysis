## Analysis
A comprehensive excel data modeling and interactive dashboard project analyzing restaurant operational metrics.

## The Business Problem (The "Why"?)
"The objective of this project was to analyse a year's worth of operational data for a high volume pizza restaurant.

## Project Overview
This project transforms raw, transactional restaurant data across four relational tables into a single, comprehensive data model and an interactive executive dashboard. The analysis provides actionable business insights to help the restaurant owner optimize menu engineering, kitchen staffing schedules, and inventory management.
____

## Data Architecture & Technical Skills Demonstrated
To build a scalable and professional analysis, the raw data structure was completely overhauled using advanced Excel methodologies:
*   **Relational Data Modeling:** Maintained structural integrity by flattening four distinct relational sheets (`orders`, `order_details`, `pizzas`, and `pizza_types`) into a single master analytics database using precise `XLOOKUP` and `INDEX/MATCH` logic.
*   **Operational Engineering:** Built a time-of-day operational classifier using nested `IF(AND())` and `HOUR()` formulas to automatically segment sales into specific shifts (e.g., Lunch Rush, Dinner Peak, Off-Peak).
*   **Dynamic Aggregations:** Utilized dynamic array functions—including `UNIQUE` and `COUNTA`—to bypass row-level repetition and isolate absolute unique transaction volumes.
*   **Data Presentation UI:** Designed a clean executive interface by disabling gridlines, establishing a unified corporate color palette, implementing strict typographic hierarchy, and engineering custom number formatting (`#,##0,"k"`) to maximize data readability.

*   ## Core Business Questions Solved!


### 1. High-Level Executive KPIs
*   **Total Revenue:** Generated a total of **$817k** in gross sales over the 1-year operational period.
*   **Total Transaction Volume:** Processed **21,352** unique customer orders, accounting for **49,574** individual pizzas baked.
*   **Average Order Value (AOV):** Established a baseline customer spending benchmark of **$38.30** per transaction, providing a clear target for future upselling strategies.

### 2. Operational Rushes & Staffing Efficiency
*   **The Business Question:** *When does the kitchen face the highest volume friction, and how should labor schedules adjust?*
*   **The Insight:** Analysis of sales density by hour reveals that the **Dinner Peak** accounts for the vast majority of physical product output and revenue generation. 
*   **Actionable Recommendation:** Management should strictly allocate additional kitchen labor and delivery drivers between the hours of **5:00 PM and 9:00 PM** to protect order fulfillment times, while trimming labor during off-peak morning hours.

### 3. Menu Engineering & Product Performance
*   **The Business Question:** *Which core menu items drive the restaurant's financial health, and which items underperform?*
*   **The Insight:** The revenue is heavily anchored by the **Top 5 Best-Selling Pizzas**, led dominantly by the **The Thai Chicken Pizza** and **The Barbeque Chicken Pizza**.
*   **Actionable Recommendation:** Keep the top 5 star items completely unchanged in recipe and pricing, while considering a menu reduction or marketing push for the lowest-performing varieties to reduce raw ingredient inventory waste.

### 4. Size & Category Consumer Preferences
*   **The Business Question:** *What combinations of pizza styles and sizes dominate consumer demand?*
*   **The Insight:** Using a multi-criteria breakdown matrix, data shows a major consumer preference variance. For instance, **Chicken** pizzas dramatically outperform others when ordered in a **Large** format, whereas other categories see a more uniform distribution.

---

## 🖼️ Dashboard Preview

Below is a snapshot of the final interactive executive dashboard built completely inside Microsoft Excel. It features automated summary KPI cards, dynamic matrix breakdowns, and sorted trend charts.

<img width="1892" height="907" alt="image" src="https://github.com/user-attachments/assets/40bdee63-872c-4ec4-8044-df3c50c600c6" />



