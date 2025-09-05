# E-commerce Analytics Dashboard

This project presents an **E-commerce Analytics Dashboard** designed to provide actionable insights into declining customer engagement and conversion rates by leveraging multi-source marketing and customer data.

## Project Overview

The dashboard integrates data from various sources, performs advanced data cleaning and transformation, applies sentiment analysis, and delivers interactive visualizations for data-driven decision making. It enables stakeholders to correlate customer ratings, reviews, and engagement metrics effectively.

Key objectives include:

- Understanding trends in customer engagement and conversion.
- Identifying sentiment patterns in customer feedback.
- Supporting strategic marketing and product decisions.

## Features

- **Multi-source Data Integration:** Aggregates marketing and customer data from SQL databases for comprehensive analysis.  
- **ETL Workflow:** Engineered a T-SQL ETL pipeline for data cleansing, bucketing, deduplication, and missing value imputation using **CTEs** and **Window functions**.  
- **Python Pipeline:** Implemented a multi-stage Python pipeline using **PyODBC** for SQL data ingestion and **NLTK VADER** for hybrid sentiment classification.  
- **Power BI Star Schema:** Built a star schema model in Power BI using **Power Query ETL** for optimized query performance, including query folding.  
- **Advanced DAX Measures:** Authored complex, context-aware DAX measures to enable dynamic insights.  
- **Interactive Dashboard:** Designed reports with slicers, drill-downs, funnel charts, and scatter plots to explore relationships between ratings and sentiment data.

## Technologies Used

- **Database & ETL:** SQL Server, T-SQL, CTEs, Window Functions  
- **Python & Data Processing:** Python 3.x, PyODBC, NLTK VADER  
- **Data Visualization:** Power BI (Power Query, DAX, star schema modeling)  

## Getting Started

### Prerequisites

- Python 3.x installed
- SQL Server access with necessary database credentials
- Power BI Desktop

### Setup Instructions

1. **Clone the repository:**
    ```bash
    git clone https://github.com/DivyanshKgpian/E-commerce Analytics Dashboard.git
    ```
2. **Install Python dependencies:**
    ```bash
    pip install pyodbc nltk pandas
    ```
3. **Connect to SQL Database:** Update the connection string in the Python scripts with your SQL Server credentials.  
4. **Run the Python pipeline:** This will ingest, clean, and analyze the data.  
5. **Open Power BI Dashboard:** Load the processed dataset into Power BI and explore the interactive reports.

## Dashboard Insights

The dashboard allows you to:

- Monitor customer engagement trends over time.
- Correlate customer ratings with sentiment from reviews.
- Identify areas of declining conversion and take targeted actions.
- Drill down into specific product categories, regions, or customer segments.



