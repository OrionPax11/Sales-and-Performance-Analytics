# Power BI Corporate Reporting System

## Description
A comprehensive, interactive corporate reporting system developed during a 60-day data analytics internship project. This project transforms raw transaction data into a multi-page functional dashboard, focusing on robust data modeling, complex DAX calculations, and actionable business intelligence visualizations.

## Key Features
*   **Data Modeling & ETL:** Connected multiple data sources using a star schema. Performed data cleaning and transformation using Jupyter Notebooks and Power BI to resolve mismatched keys and handle blank data points.
*   **Advanced Navigation:** Implemented contextual drill-through pathways for deeper data exploration (e.g., right-click navigation), alongside global reset buttons utilizing bookmarks and the selection pane.
*   **Row-Level Security (RLS):** Configured role-based security filters within the data model to ensure users only access data relevant to their authorized regions.
*   **Business Performance Visuals:** Utilized combo charts for target-vs-actual tracking, deep-dive matrices for quarterly breakdowns, and gauge visuals for goal achievement monitoring.
*   **Mobile Optimized:** Designed an interactive mobile view to provide on-the-go access to key metrics.

## Dashboard Overview
The reporting system is structured across three primary views:

1.  **Executive Summary:** A high-level corporate snapshot displaying essential health metrics (total revenue, profit margins, orders) segmented by major regions and product categories for rapid executive evaluation.
2.  **Sales Analysis:** A detailed time-based performance view tracking monthly revenue trends and distribution channels, complemented by a top-10 product leaderboard and a quarterly performance matrix.
3.  **Performance Tracker:** Focused on target accountability, this page compares actual revenue directly against sales goals using gauge and combo charts, supported by salesperson leaderboard tracking and role-based security.

## Repository Structure
*   `data/`: Contains the raw and processed datasets used for the project.
*   `notebooks/`: Jupyter Notebooks used for initial data exploration, cleaning, and the ETL process.
*   `power bi/`: Contains the core `.pbix` (Power BI Desktop) file encompassing the data model, DAX measures, and report layouts.
*   `reports/`: Exported reports, final dashboard screenshots, and related documentation.

## Technology Stack
*   **Business Intelligence:** Power BI (Data Modeling, DAX, RLS, Bookmarks)
*   **Data Processing:** Python, Jupyter Notebooks

## Key Learnings
This project provided hands-on experience in tackling complex backend data schema challenges, systematically resolving database errors, and writing advanced DAX logic. It reinforced the importance of building a solid technical foundation in data analytics and treating data visualization as an exercise in logical problem-solving rather than just creating appealing charts.
