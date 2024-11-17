# Stock Market Real-Time Data Pipeline with Kafka and AWS 

Project Overview:
The aim of this project was to design and implement a real-time data pipeline that mimics a producer-consumer relationship using Apache Kafka. The pipeline processes stock market data, stores it on AWS S3, and extracts valuable insights using AWS Glue and Amazon Athena.

Here’s how the pipeline works:

Stock Dataset (Kaggle): A stock market dataset was used as the base input.
Real-Time Data Simulation: Python scripts mimic real-time data producers using the Kafka library, generating stock data streams.
Apache Kafka: Serves as the backbone for handling and streaming the data. Kafka producers push the data to topics, and consumers retrieve the data for further processing.
AWS S3: Consumers write the processed data to S3 buckets.
AWS Glue: Crawlers organize and catalog the data stored in S3.
Amazon Athena: SQL queries were written to analyze data, including calculating daily stock returns.
This project highlights my understanding of distributed systems, data streaming, cloud computing, and SQL-based analytics.

Key Features:
Real-Time Simulation: Used Python and Kafka to simulate a real-time producer-consumer workflow.
Cloud Storage: Integrated with AWS S3 for scalable data storage.
Data Organization: Deployed AWS Glue crawlers to structure and catalog the data.
Querying Insights: Created SQL queries in Athena to calculate daily stock returns, gaining insights into stock performance trends.


Tools & Technologies 🛠️
Programming:
Python: Developed scripts to simulate stock data and manage Kafka producer-consumer flow.
Data Streaming:
Apache Kafka: Managed the real-time streaming of stock market data.
Cloud Services:
AWS EC2: Hosted the Kafka ecosystem.
AWS S3: Stored the streaming data in a secure and scalable manner.
AWS Glue: Automated data crawling and cataloging.



