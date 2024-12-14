# Airline_data-_ingestion_ETL
The Airline Data Ingestion ETL Pipeline project is designed to streamline and automate the process of extracting, transforming, and loading (ETL) large volumes of airline data into an analytics-ready data warehouse. Leveraging a serverless architecture on AWS, the pipeline integrates several AWS services, including AWS Glue, Amazon Redshift, AWS Step Functions, Amazon EventBridge, and Amazon S3. This solution aims to optimize data flow, improve data accessibility, and support advanced analytics for airline operations, customer insights, and performance tracking. 

# Project archetecture 
![Untitled design](https://github.com/user-attachments/assets/6281addb-4b9f-4c33-91d9-2efca2ff8592)

# Working of project
Data Extraction: Collect raw data from multiple sources, such as CSV, JSON, or log files, that represent various airline operational datasets (e.g., flight schedules, ticket sales, customer feedback, and operational logs).

Data Transformation: Process and clean raw data using AWS Glue, converting it into a consistent format suitable for analytics, such as structured relational tables.

Data Loading: Store the transformed data into Amazon Redshift, enabling fast querying and analysis for business intelligence and reporting.
Automation & Orchestration: Automate the entire ETL workflow using AWS Step Functions to manage the flow of data through the pipeline and trigger necessary transformations and loads based on events.

Event-Driven Architecture: Use Amazon EventBridge to capture and respond to events in real-time, ensuring that data updates and transformations are handled as soon as new data is available.

Data Storage & Access: Utilize Amazon S3 as a scalable and cost-efficient storage solution for raw, intermediate, and final datasets, ensuring the availability and durability of data throughout the process.

# Flow
![Airport-Execution-Flow](https://github.com/user-attachments/assets/1f0e06ea-f305-47ca-8c1b-2358a1ffc5a0)
