---
title: "Uni Project: Big Data Transaction Default Detection"
date: 2025-04-25
categories:
  - data
tags:
  - uni project
  - big data
  - kafka
  - spark
  - streaming
  - python
excerpt: "Simulated a bank's real-time transaction monitoring system using Apache Kafka and Spark Streaming for default detection in a distributed environment."
author_profile: true
---

As part of a university big data processing course, this project simulates a bank’s infrastructure for detecting default transactions in real-time.

### ⚙️ Project Components:
- **Kafka Producer**: Simulates real-time transactions
- **Spark Streaming**: Ingests and processes data for rule-based default detection
- **Kafka Consumer**: Logs transactions flagged as default

### 💻 Tech Stack:
- Apache Kafka, Apache Spark (PySpark)
- Python, Jupyter Notebooks

### 📦 Pipeline Flow:
1. Run the producer to send transactions to a Kafka topic
2. Spark Streaming filters transactions
3. Consumer logs suspicious/default cases

📌 Make sure Kafka and Zookeeper are running locally, and update topic names if needed.

🔗 [View on GitHub](https://github.com/xc017/big_data_banking)
