# HRG Data Engineer Test Assignment

## Overview
This repository contains the **Data Vault 2.0 model** for handling event-driven gaming data. The model is designed for **scalability, auditability, and flexibility** while ensuring historical integrity.

## Technologies Used
- **Storage**: BigQuery
- **Event Ingestion**: Kafka
- **ETL Processing**: dbt
- **Orchestration**: Apache Airflow/dbt Scheduler
- **Monitoring**: Grafana

## Data Vault 2.0 Model
The data model follows **Data Vault 2.0 methodology**, consisting of:
- **Hubs**: Representing core business entities (Users, Applications)
- **Links**: Capturing relationships between hubs (Purchases, Spins, Auth Events, Sessions)
- **Satellites**: Storing descriptive attributes and historical changes

## Key Features
- **Supports event-based modeling** for real-time analytics
- **Ensures referential integrity** with foreign key constraints
- **Captures event metadata** for deeper insights
- **Optimized for BigQuery performance**

For a detailed schema and queries, refer to the [document.pdf](DataVault_Design/[Vardhan%20Seepala]%20HRG%20Data%20Engineer%20Design.pdf) in this repository.