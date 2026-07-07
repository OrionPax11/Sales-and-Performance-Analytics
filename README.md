# Power BI Corporate Reporting System
## Description
A comprehensive, interactive corporate reporting system designed to transform raw transaction data into a multi-page, functional business intelligence dashboard. This project focuses on robust data modeling, complex DAX calculations, and actionable visualizations to provide deep insights into corporate health, sales trends, and performance metrics.
## Key Features
*   **Data Modeling & ETL:** Utilizes a star schema architecture to connect multiple data sources. The Extract, Transform, and Load (ETL) process involves rigorous data cleaning to resolve mismatched keys and eliminate blank data points, ensuring a highly accurate backend model.
*   **Advanced Navigation:** Features contextual drill-through pathways for intuitive data exploration (e.g., right-click navigation between pages), supported by global reset buttons built using bookmarks and the selection pane.
*   **Row-Level Security (RLS):** Implements role-based security filters within the data model, restricting information access by region to ensure enterprise-level data governance.
*   **Business Performance Visuals:** Employs advanced tracking tools including combo charts for target-versus-actual comparisons, deep-dive matrices for quarterly performance breakdowns, and gauge visuals for monitoring goal achievements.
*   **Mobile Optimized:** Includes a dedicated, interactive mobile layout for seamless on-the-go dashboard access.
## Dashboards' Overview
The reporting system is structured across three primary views/pages:
1.  **Executive Summary:** Provides a high-level corporate snapshot of essential health metrics like total revenue, profit margins, and orders, broken down by main regions and product categories for quick executive evaluation.
2.  **Sales Analysis:** Offers a deep-dive look at time-based performance, tracking monthly revenue trends and distribution channels alongside a top-10 product leaderboard and a detailed quarterly matrix.
3.  **Performance Tracker:** Focuses on target accountability by using gauge and combo charts to compare actual revenue directly against sales goals, supported by role-based security filters and salesperson leaderboard tracking.
## Repository Structure
*   `data/`: Contains the raw and processed datasets used to power the dashboard.
*   `notebooks/`: Jupyter Notebooks documenting the initial data exploration, cleaning, and ETL processes.
*   `power bi/`: Contains the core `.pbix` (Power BI Desktop) file encompassing the full data model, DAX measures, and interactive report layouts.
*   `reports/`: Exported reports, final dashboard screenshots, and related documentation.
## Technology Stack
*   **Business Intelligence & Visualization:** Power BI (Data Modeling, DAX, RLS, Bookmarks)
*   **Data Processing:** Python, Jupyter Notebooks
## For Aspiring Data Analysts
This repository serves as a practical reference for building an end-to-end corporate reporting solution. By exploring the provided `.pbix` file and datasets, you can see exactly how raw transactional data is transformed into a functional star schema, and how complex DAX formulas are written to solve real business logic. 
If you are looking to build your skills, I highly encourage you to download the raw files from the `data/` folder and attempt to build your own version of this dashboard from scratch. Tackling the data modeling and DAX challenges yourself is an incredible way to practice real-world problem-solving!
