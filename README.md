FY21 Overall Performance Summary Dashboard: Excel to Power BI Migration

## Project Overview

This project involved the successful migration and automation of the **FY21 Overall Performance Summary** report—originally a manual, monthly report produced using **Excel Pivot Tables**—to a dynamic, scalable dashboard in **Microsoft Power BI Desktop**.

The goal was to replicate the exact "look and feel" and analytical structure of the original report, while leveraging Power BI's advanced capabilities for automated data refresh, greater interactivity, and enhanced performance, especially for the full dataset.

## Key Project Goals 

The client decision to automate this report in Power BI was driven by the need to:

1.  **Direct Replication:** Produce a dashboard in Power BI whose visuals, layout, and metrics are as close as possible to the original Excel report.
2.  **Automation & Efficiency:** Automate the monthly report generation process, replacing the manual pivot table creation with a scheduled data refresh in Power BI.
3.  **Data Scalability:** Utilize Power BI to handle the full IT company dataset provided in the worksheet, ensuring performance remains fast even as data grows.
4.  **Interactive Analysis:** Transform the static Excel summary into a dynamic tool allowing users to segment and filter the data easily.

---

## Dashboard Features & Replicated Visuals

The Power BI dashboard faithfully replicates four key analytical sections from the Excel summary:

### 1. FY21 Revenue vs Target Graph
* **Visual Type:** A dual-axis or combination chart showing monthly **Revenue** alongside **Target** for comparison.
* **Metrics:** Revenue broken down by different fee types (Registration Fee, Future Ops, Partner Fee, etc.).

### 2. Revenue Performance Graph MoM (Month-over-Month)
* **Visual Type:** A detailed matrix/table showcasing actual performance metrics against the monthly Target.
* **Key Calculations (DAX):** Requires precise calculation of **Total Revenue**, **Target**, and **% Vs Target** with color-coded conditional formatting for quick assessment of performance (Green for target hit, Red for miss).

### 3. Segment Summary
* **Visual Type:** Tables providing a breakdown of performance metrics.
* **Focus Areas:** Total Revenue, Target, and % Vs Target segmented by **Segment** (e.g., Primary PS, Public Sector, Corporate).

### 4. Product Category Summary
* **Visual Type:** Tables providing a breakdown of performance metrics.
* **Focus Areas:** Total Revenue, Target, and % Vs Target segmented by **Product Category** (e.g., Online Products, Services, Support).

### Additional Analysis
* **Revenue vs Marketing Spend Relationship:** Replication of the scatter plot visual to analyze the correlation between revenue and marketing spend.
* **Slicer Functionality:** Inclusion of slicers for key dimensions like **Segment**, **Product Category**, and **Additional Slicers** (Industry, Partner Name, Account Name) for dynamic filtering.

## Tech Stack

| Component | Tool / Language | Purpose |
| :--- | :--- | :--- |
| **Source Report** | Microsoft Excel (using Pivot Tables) | Baseline for the dashboard design, metrics, and conditional formatting rules. |
| **Data Visualization** | Microsoft Power BI Desktop | Dashboard creation, report design, and interactivity implementation. |
| **Data Preparation** | Power Query (M Language) | Data ingestion, cleaning, transformation, and connecting to the full dataset. |
| **Calculations & Logic** | DAX (Data Analysis Expressions) | Implementing all required custom measures, month-over-month comparisons, and conditional formatting logic to exactly match the Excel outputs. |
