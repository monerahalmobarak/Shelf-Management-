# Shelf Management System

## Overview
The Shelf Management System is a solution designed to automate and streamline inventory management in retail stores, particularly in the fast-paced fashion industry. By leveraging technologies such as IoT sensors, barcode scanning, and machine learning, the system provides real-time insights into stock levels, product placement, and alerts for low inventory or misplaced items.

---

## System Architecture

1. **Data Collection**:
   - Collects key-value pairs such as (product ID, product_quantity_from_iot) and (product ID, product_location_from_iot).

2. **Data Ingestion**:
   - Processes incoming data using Apache Spark.

3. **Data Storage**:
   - Stores structured data in Apache Hive and unstructured data in Apache HBase.

4. **Real-time Streaming**:
   - Utilizes Apache Kafka for streaming and Apache Spark Streaming for real-time processing.

5. **Data Analysis**:
   - Leverages Spark MLlib for statistical analysis and machine learning.

6. **Alerts**:
   - Generates real-time notifications based on processed data.

7. **Monitoring**:
   - Uses Apache Ambari for system monitoring and maintenance.

---

## Dataset
- Simulated using the Python Faker library.
- Includes:
  - 5000 rows of product data.
  - 2000 rows of alert notification data.
- Provides realistic scenarios for testing the system’s efficiency in managing inventory.
