# Big Data Processing with Apache Hadoop and Apache Spark

This repository contains notes and summaries of what I learned about big data processing with **Apache Hadoop** and **Apache Spark**. The information is based on a [Coursera Course](https://www.coursera.org/learn/introduction-to-big-data-with-spark-hadoop). Below is a summary of each module covered in the course.

## Course Modules

### Module 1: Introduction to Big Data
- **How Personal Assistants Use Big Data:** Tools like Siri, Alexa, and Google Now use Big Data and the Internet of Things (IoT) to gather information and respond to questions.
- **Big Data Analytics:** Big Data Analytics helps businesses get useful insights from data collected by IoT devices.
- **Parallel Processing:** Big Data requires parallel processing because it’s too large to fit on a single computer. 
- **“Embarrassingly Parallel” Calculations:** These are calculations that can be easily split up and run independently, so if one part fails, it doesn’t affect the others.
- **Open-Source Tools:** Free and open-source tools like Hadoop, Apache Hive, and Apache Spark are essential to Big Data.
- **Big Data Tool Categories:** The Big Data tool ecosystem includes:
  - Data technologies
  - Analytics and visualization tools
  - Business intelligence tools
  - Cloud providers
  - NoSQL databases
  - Programming tools

### Module 2: Introduction to the Hadoop Ecosystem
- **Hadoop Framework:** Hadoop is an open-source framework for processing Big Data, especially helpful for handling large amounts of data with low-cost solutions. 
- **MapReduce:** A computing framework within Hadoop that handles data in parallel and uses two main functions: "map" to sort data and "reduce" to summarize it.
- **Stages of the Hadoop Ecosystem:** Hadoop works in four stages:
  1. Ingest (bringing data in)
  2. Store (saving data)
  3. Process and Analyze (working with the data)
  4. Access (retrieving data)
- **HDFS Benefits:** The Hadoop Distributed File System (HDFS) is cost-effective, scalable, and stores data across multiple computers with backup copies (“write once, read many”).
- **Hive:** A tool within Hadoop for reading, writing, and managing large datasets, often used for analyzing static data.
- **HBase:** A NoSQL database that runs on HDFS, HBase is highly scalable and lets users make changes to data easily. It’s great for handling real-time data.
