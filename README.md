# dp-700-lab-03

🎯 Objective
This lab focuses on working with Delta Tables in Microsoft Fabric Lakehouse. You’ll learn how to ingest data, create managed and external Delta tables, perform SQL operations, manage table versioning, and use Delta tables for streaming data.

🧪 Key Steps Performed
Workspace & Lakehouse Setup:

Created a Fabric-enabled workspace.

Created a lakehouse and uploaded products.csv to a new folder.

DataFrame & Delta Table Creation:

Loaded CSV into a Spark DataFrame using a defined schema.

Created both managed and external Delta tables using saveAsTable.

SQL Queries & Table Versioning:

Queried tables with %%sql.

Updated data (price reduction) and explored version history using DESCRIBE HISTORY.

Accessed data from version 0 for comparison.

Data Aggregation with Views:

Created a temporary SQL view to analyze product categories.

Displayed results using both SQL and PySpark.

Streaming Data with Delta Sink:

Simulated IoT device data using structured streaming.

Wrote streaming data into a Delta table and queried it dynamically.

Demonstrated stream append and stop operations.

🧠 What I Learned
How to manage relational data in a Delta Lake format.

Differences between managed vs external Delta tables.

How to perform versioned queries on Delta tables.

Using Structured Streaming with Delta as a sink.

Combining SQL and PySpark in a seamless workflow within Fabric notebooks.

🔍 Real-World Use Cases
Managing data lakehouses with transactional consistency.

Creating audit trails with versioned tables.

Supporting real-time analytics using streaming ingestion.

Building scalable ETL pipelines in data engineering workloads.

📌 Technologies Used
Microsoft Fabric Lakehouse

Apache Spark (PySpark, SQL)

Delta Lake

Structured Streaming

✅ Status
Lab completed successfully.
All tasks tested, validated, and results visualized.
![Screenshot 2025-04-29 at 16 52 09](https://github.com/user-attachments/assets/790cf4b1-c8cd-4a12-9159-fee19076a541)
![Screenshot 2025-04-29 at 16 12 15](https://github.com/user-attachments/assets/716517a0-53db-4a6d-af06-0ffcdd1853cd)
![Screenshot 2025-04-29 at 16 57 13](https://github.com/user-attachments/assets/30a81b5f-5416-4a78-a858-3dfe7c9d281e)
![Screenshot 2025-04-29 at 16 51 19](https://github.com/user-attachments/assets/9aba04e3-2fa1-4012-b162-8b56381bcdc7)
![Screenshot 2025-04-29 at 16 11 45](https://github.com/user-attachments/assets/0e04c446-4df3-4e32-a44a-3f410edab454)
![Screenshot 2025-04-29 at 16 11 23](https://github.com/user-attachments/assets/c98b126f-8bc1-4230-a5fa-aa4b8e054a23)
![Screenshot 2025-04-29 at 16 56 28](https://github.com/user-attachments/assets/d9fe0bc0-90ca-4f86-82dd-e0c1752f696b)
![Screenshot 2025-04-29 at 16 15 13](https://github.com/user-attachments/assets/107a7610-d6d7-4082-865e-95c27efe1b3e)
![Screenshot 2025-04-29 at 16 03 17](https://github.com/user-attachments/assets/0de0f12e-7096-4044-8c9e-25da63b0d8ff)
![Screenshot 2025-04-29 at 16 01 46](https://github.com/user-attachments/assets/2db215d7-47ff-4f26-8baa-60342f6f347e)
![Screenshot 2025-04-29 at 16 01 40](https://github.com/user-attachments/assets/821d5474-ddb7-42f1-8941-0b27b6e0c82a)
![Screenshot 2025-04-29 at 16 01 34](https://github.com/user-attachments/assets/27db5f10-9259-45b8-b636-280815c4b069)
![Screenshot 2025-04-29 at 16 55 41](https://github.com/user-attachments/assets/40d72ddc-219a-4c87-947d-98344ba40808)
![Screenshot 2025-04-29 at 16 14 56](https://github.com/user-attachments/assets/c131d984-0c44-4e42-a7db-8622a62ab72d)
![Screenshot 2025-04-29 at 16 14 34](https://github.com/user-attachments/assets/ef059a08-ddc1-4a1d-b99d-d46113e4c647)
![Screenshot 2025-04-29 at 16 14 12](https://github.com/user-attachments/assets/1271d1f7-2c3c-471e-9367-9f70066ef2b1)
![Screenshot 2025-04-29 at 16 13 14](https://github.com/user-attachments/assets/6be18981-671e-4d6c-b52d-e6a44eaa7def)
![Screenshot 2025-04-29 at 16 55 01](https://github.com/user-attachments/assets/dad4516a-3c08-45d5-806e-fd6f41f717ba)
![Screenshot 2025-04-29 at 16 54 48](https://github.com/user-attachments/assets/2d5ec116-0e9b-4d31-90dc-8dc06d05e5aa)
![Screenshot 2025-04-29 at 16 53 51](https://github.com/user-attachments/assets/217d8ea2-98f1-4030-bf47-2bbd9c908de8)

