# 🏗️ End-to-End Azure Data Engineering Pipeline

This is full-stack data engineering project built on Microsoft Azure. It demonstrates ingestion, transformation, storage, and visualization of real-world API data using production-ready patterns.

## 🚀 Project Highlights

### Tech Stack
- **Azure Data Factory**: orchestrates pipelines and schedules API ingestion.
- **Azure Data Lake Storage Gen2**: stores raw, silver, and gold data layers.
- **Azure Databricks + PySpark**: transforms raw data into cleaned, structured formats.
- **Delta Lake**: manages data versioning, schema enforcement, and time travel.
- **MongoDB**: optional NoSQL sink for lookup or serving use cases.
- **Power BI**: dashboards for data visualization and insights.

### Architecture
1. **Bronze Layer** – Staging raw API data with logs and schema drift checks.  
2. **Silver Layer** – Cleaned and curated datasets optimized for query.  
3. **Gold Layer** – Aggregated data ready for analytics and reporting.

### Security & Governance
- Azure Key Vault integration for secret management.
- Managed identities and Unity Catalog for access control.

### Performance Optimization
- Incremental ingestion pipelines.
- Partitioning, vacuuming, and Delta Lake optimization for faster queries.

## 📁 Repository Structure

<img width="3437" height="1842" alt="image" src="https://github.com/user-attachments/assets/c921b9b6-53db-481b-96a5-001a28aec032" />
