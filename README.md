# azure-synapse-fraud-analytics
Fraud detection and risk scoring using Azure Synapse Analytics and Apache

This project demonstrates how to build a complete fraud analytics pipeline using Azure Synapse Analytics:

- Ingest transaction data into ADLS Gen2
- Use Spark notebooks to process, clean, and enrich data
- Create and query managed Spark tables
- Build analytics dashboards in Synapse Studio or Power BI
- Automate using Synapse Pipelines with email alerts

## Technologies Used
- Azure Synapse Analytics
- Apache Spark
- ADLS Gen2
- Power BI
- Azure Monitor

## How to Run
1. Upload dataset to ADLS container `users/raw/transactions/`
2. Open Synapse Studio, run `ProcessTransactions` and `Deeper_Analytics`
3. Visualize outputs via Synapse Studio SQL scripts or notebooks
4. Optionally connect Power BI using Synapse SQL Pool
