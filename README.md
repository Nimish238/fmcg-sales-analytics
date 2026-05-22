# Cloud-Based FMCG Analytics Pipeline

## Project Overview

This project demonstrates an end-to-end cloud analytics and business intelligence pipeline built using AWS services, Python ETL automation, and Power BI.

The pipeline automates the process of uploading FMCG sales data to Amazon S3, performs schema discovery using AWS Glue, enables serverless SQL querying through Amazon Athena, and visualizes business insights using Power BI dashboards.

The project focuses on analyzing:
- Sales performance
- Profitability trends
- Regional analysis
- Product performance
- Marketing effectiveness
- Customer insights

# Technologies Used

| Technology | Purpose |
|---|---|
| Python | ETL automation |
| boto3 | AWS SDK for Python |
| AWS S3 | Cloud storage |
| AWS Glue | Metadata management |
| AWS Athena | SQL analytics engine |
| Power BI | Interactive dashboards |
| ODBC Driver | Athena-Power BI connectivity |


# Project Workflow

1. Raw FMCG CSV dataset uploaded using Python ETL script
2. Data stored in Amazon S3 bucket
3. AWS Glue crawler detects schema automatically
4. Glue Data Catalog stores metadata
5. Amazon Athena queries S3 data using SQL
6. Power BI connects to Athena using ODBC driver
7. Interactive dashboards generated for analytics


**Architecture:-**

<img width="672" height="341" alt="image" src="https://github.com/user-attachments/assets/12ece803-fd69-4daa-b8f2-3f4b85ad2682" />


**S3 bucket:-**

<img width="1548" height="556" alt="image" src="https://github.com/user-attachments/assets/c730122e-ed25-43ba-a82a-e59f496fb6ee" />


**Glue crawler:-**

<img width="1554" height="386" alt="image" src="https://github.com/user-attachments/assets/da8190eb-dec2-41bd-a8e8-c5e6fa530da0" />




**PowerBI dashboard:-**
<img width="1111" height="634" alt="image" src="https://github.com/user-attachments/assets/95087379-e617-410e-bdeb-308f66d0eade" />

<img width="1106" height="630" alt="image" src="https://github.com/user-attachments/assets/fc928d5d-3cbc-4130-b8f1-8ba1c9fe2d6e" />

