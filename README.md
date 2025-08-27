# IPL-Data-Analysis-ETL
## End to End ETL Pipeline Project using PySpark and Databricks

##  Project Overview

This project demonstrates a complete **ETL (Extract-Transform-Load)** pipeline using **Amazon S3**, **Databricks (Community Edition)**, and **PySpark**. The final insights are exported and visualized using **PowerPoint**, making this a full-stack data engineering and visualization workflow for Big Data.

---

##  Objective

To build a scalable ETL pipeline that:
- Extracts raw cricket match data from an **Amazon S3 bucket**
- Transforms it using **PySpark** (e.g., calculating high-impact events)
- Loads and exports the processed data for local use
- Visualizes final insights in **tableau**

---

##  Technologies Used

| Component | Tool/Technology |
|----------|----------------|
| Storage  | Amazon S3 (public bucket) |
| Compute  | Databricks Community Edition |
| Language | PySpark (Python + Apache Spark) |
| Visualization |tableau |

---

##  Project Architecture

```plaintext
             +------------+
             |  Amazon S3 |
             +------------+
                   |
                   ▼
          +------------------+
          |  Databricks (CE) |
          |   - PySpark      |
          |   - Notebooks    |
          +------------------+
                   |
                   ▼
        +-----------------------+
        |  Transformed Dataset  |
        +-----------------------+
                   |
                   ▼
         +--------------------+
         |   tableau Charts   |
         +--------------------+
