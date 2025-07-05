# ChangeDataCapture-CDC
## Change Data Capture (CDC) Tutorial: How to Stream PostgreSQL Changes to a Kafka Cluster in Real Time with Debezium

Nowadays, most applications use Change Data Capture (CDC). Whether you're tracking user activity, syncing microservices, or updating data warehouses, CDC is a key enabler for modern data architectures. You can stream real-time data changes from your database to Kafka topics for more processing with CDC. 
I will guide you through the process of setting up Change Data Capture (CDC) with Kafka, Debezium, and Postgres on Azure Cloud. You'll learn how to capture and stream database changes to Kafka topics, monitor them via Debezium UI and Kafka UI, and verify everything with a hands-on example database. 
I will start the Debezium services, run a PostgreSQL database server with a simple example database, and use Debezium to monitor and capture the database for changes. At the same time, we will monitor the processes via Kafka UI and Debezium UI. By the end of this guide, you'll have a fully functional CDC pipeline running on Azure, ideal for real-time analytics, event-driven architectures, or syncing distributed systems.
We'll learn how to create a CDC Pipeline step by step, and most importantly, we'll put theory into practice through hands-on examples that you can apply in your own environment.

## 📗 Medium Articles Link:
- [📝Change Data Capture (CDC) Tutorial: How to Stream PostgreSQL Changes to a Kafka Cluster in Real Time with Debezium]()


## Topics we will cover:
1. Introduction
1.1. What is Change Data Capture (CDC)?
1.2. Apache Kafka
1.3. Kafka Connect
1.6. Kafka UI
1.5. Debezium
1.6. Debezium UI
1.7. PostgreSQL
2. Setting up the CDC environment (CDC Pipeline)
3. Creating the CDC connector
4. Verify Connection and Functionality
5. Monitoring the Changes in PostgreSQL with CDC as a "Kafka Consumer Message"
6. Using Kafka UI
7. Using Debezium UI
8. Clean Up
9. Conclusion
10. Next post: "Change Data Capture (CDC) from Azure Database for PostgreSQL Flexible Server Using Apache Kafka Cluster and Debezium for Java App"
11. References

## 📗 Note: If you want to get more information and hands-on training for Kafka and Message Queues, you can read my Medium articles below. 
- [📝 Message Queue (MQ) Systems-1: Amazon SQS (Simple Queue Service)](https://cmakkaya.medium.com/message-queue-mq-systems-1-amazon-sqs-simple-queue-service-42fb5962cf3d)
- [📝 Message Queue(MQ) Systems-2: Installing and Using Apache Kafka as an Event Streaming Platform](https://cmakkaya.medium.com/message-queue-mq-systems-2-installing-and-using-apache-kafka-as-an-event-streaming-platform-fad3e99ded85)




