# Stock Market Real-Time Data Pipeline with Kafka and AWS 

## Project Overview  

The goal of this project was to design and implement a real-time data pipeline that simulates a producer-consumer relationship using Apache Kafka. This pipeline processes stock market data, stores it in AWS S3, and extracts valuable insights using AWS Glue and Amazon Athena.  

### Pipeline Workflow  
- **Stock Dataset (Kaggle):** A stock market dataset was used as the base input.  
- **Real-Time Data Simulation:** Python scripts mimic real-time data producers using the Kafka library, generating stock data streams.  
- **Apache Kafka:** Acts as the backbone for data streaming. Kafka producers push the data to topics, and consumers retrieve the data for further processing.  
- **AWS S3:** Consumers write the processed data to S3 buckets for storage.  
- **AWS Glue:** Crawlers organize and catalogue the data stored in S3.  
- **Amazon Athena:** SQL queries analyze the data, including calculating daily stock returns.

![image](https://github.com/user-attachments/assets/fd1f046f-f335-4fe5-8e40-52235b85f6c2)

This project highlights my expertise in distributed systems, data streaming, cloud computing, and SQL-based analytics.  

---

## Key Features  

- **Real-Time Simulation:** Used Python and Kafka to simulate a real-time producer-consumer workflow.  
- **Cloud Storage:** Integrated with AWS S3 for scalable and secure data storage.  
- **Data Organization:** Deployed AWS Glue crawlers to structure and catalog data.  
- **Querying Insights:** Created SQL queries in Athena to calculate daily stock returns, providing insights into stock performance trends.  

---

## Tools & Technologies  

### Programming  
- **Python:** Developed scripts to simulate stock data and manage the Kafka producer-consumer flow.  

### Data Streaming  
- **Apache Kafka:** Managed the real-time streaming of stock market data.  

### Cloud Services  
- **AWS EC2:** Hosted the Kafka ecosystem.  
- **AWS S3:** Stored the streaming data in a secure and scalable manner.  
- **AWS Glue:** Automated data crawling and cataloging.  
- **Amazon Athena:** Queried and analyzed data using SQL.  

Query to get daily-returns:
![image](https://github.com/user-attachments/assets/a0c62eb6-45af-4eb5-8424-a35c1b0f6aa4)

![image](https://github.com/user-attachments/assets/faa50b35-371e-4d79-a371-2e94d71dbc21)




