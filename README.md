# PowerBI-Data
# Roderick Fulton’s Data Engineering Portfolio

Welcome! I’m Roderick Fulton, an experienced Data Engineer specializing in end-to-end pipeline development, data modeling, and cloud-scale analytics. This repository showcases three complete Power BI template projects along with their Functional & Technical Requirement Documents, demonstrating my ability to design robust data architectures, build reliable ETL/ELT processes, and deliver high-performance dashboards that scale across enterprise environments. These examples reflect the kinds of data engineering challenges I solve daily.

---

## Table of Contents

1. [Why I’m a Strong Data Engineering Candidate](#why-i’m-a-strong-data-engineering-candidate)  
2. [Project Highlights](#project-highlights)  
   - [Financial Reports](#financial-reports)  
   - [PM Total Project Report](#pm-total-project-report)  
   - [MSP Portfolio Production Report](#msp-portfolio-production-report)  
3. [Technical Summary](#technical-summary)  
4. [Repository Structure](#repository-structure)  
5. [How to Explore](#how-to-explore)  
6. [Key Tools & Technologies](#key-tools--technologies)  
7. [Next Steps for Interviewers](#next-steps-for-interviewers)  
8. [Contact](#contact)  

---

## Why I’m a Strong Data Engineering Candidate

- **End-to-End ETL/ELT Expertise**  
  Designed and orchestrated data pipelines using Power Query and Azure Data Factory to ingest hundreds of millions of rows, ensuring data accuracy, lineage, and auditability.
- **Cloud Data Platform Proficiency**  
  Built and managed Snowflake and SQL Data Warehouse environments, optimizing storage, clustering, and compute for sub-second query performance at scale.
- **Data Modeling & Schema Design**  
  Applied star and snowflake schemas in Azure Synapse Analytics and Databricks to support both dimensional reporting and ad-hoc analytics.
- **Performance & Cost Optimization**  
  Implemented partitioning, incremental loads, and aggregated tables. Tuned queries and DAX measures, reducing refresh times by 70% and cutting compute costs by 40%.
- **CI/CD & Version Control**  
  Automated deployment pipelines using Azure DevOps and GitHub Actions, enforcing code reviews, unit tests, and documentation to guarantee production-ready deliverables.
- **Collaboration & Stakeholder Engagement**  
  Partnered closely with finance, PMO, and IT teams to gather requirements, define SLAs, and iterate rapidly based on feedback—delivering business value on day one.

---

## Project Highlights

### Financial Reports

- **Data Architecture**  
  - Source systems: On-prem SQL Server → Azure Data Factory → Azure Data Lake Storage  
  - Semantic layer: Power BI dataset published to Power BI Service
- **ETL Processes**  
  - Parameterized Power Query functions for multi-environment deployments  
  - Incremental load pattern with watermark tables  
- **Key Deliverables**  
  - Functional & Technical Requirements Document  
  - Reusable Power Query M scripts  
  - Scheduled daily refresh via Enterprise Gateway  
- **Impact**  
  - Reduced manual variance reporting by 90%  
  - Delivered real-time budget vs. actual insights to 50+ users  

📄 [Requirements Document](docs/Financial_Reports_Functional_Technical_Requirements.docx)  
📂 [Template (.pbit)](templates/Financial_Reports.pbit)  

---

### PM Total Project Report

- **Data Pipeline**  
  - Dataflow in Power BI for ingesting Azure DevOps and Jira REST APIs  
  - Azure Functions for API pagination and caching  
  - Data landing in Snowflake tables via Azure Databricks notebooks
- **Modeling & Metrics**  
  - Star schema with fact tables for Planned vs. Actual task data  
  - DAX measures for Schedule Variance, Cost Variance, Resource Utilization
- **Automation & Monitoring**  
  - CI pipeline: GitHub Actions triggers deployment to Power BI Service  
  - Alerting: Azure Monitor tracks pipeline failures and emails PMO  
- **Outcome**  
  - Real-time portfolio status for 100+ projects  
  - Automated weekly executive summaries

📄 [Requirements Document](docs/PM_TOTAL_PROJECT_REPORT_Functional_Technical_Requirements.docx)  
📂 [Template (.pbit)](templates/PM_TOTAL_PROJECT_REPORT.pbit)  

---

### MSP Portfolio Production Report

- **Unified Data Layer**  
  - Combined data from multiple ERP systems into a single Snowflake schema  
  - Applied RLS (Row-Level Security) based on Active Directory groups
- **Sophisticated KPIs**  
  - Custom “Portfolio Health Score” computed in SQL stored procedures  
  - Streamlined risk data ingestion via scheduled Azure Data Factory pipelines  
- **Scalability & Governance**  
  - Data cataloged in Azure Purview for lineage and compliance  
  - Usage metrics tracked to optimize compute and storage
- **Business Value**  
  - Provided 24/7 access to portfolio health metrics  
  - Empowered program managers to drill down and resolve bottlenecks proactively

📄 [Requirements Document](docs/MSP_Portfolio_Prod_Functional_Technical_Requirements.docx)  
📂 [Template (.pbit)](templates/MSP_Portfolio_Prod.pbit)  

---

## Technical Summary

| Area                     | Technologies & Tools                                 |
|--------------------------|------------------------------------------------------|
| **Ingestion & Integration**  | Azure Data Factory, Azure Functions, REST APIs       |
| **Data Storage**            | Azure Data Lake Storage, Snowflake, Azure Synapse   |
| **Transformation**          | Power Query (M), Databricks (PySpark), Stored Procs |
| **Modeling**                | Star Schema, DAX measures, SSDT Tabular Models     |
| **Orchestration & CI/CD**   | Azure DevOps, GitHub Actions                       |
| **Visualization & Reporting** | Power BI Desktop & Service                        |
| **Governance & Monitoring**  | Azure Purview, Azure Monitor                       |

---

## Repository Structure


