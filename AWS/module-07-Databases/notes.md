# Module 7: Databases 🗄️☁️

---

## 📌 What are Databases in Cloud?

Databases in cloud are managed services used to store, organize, and retrieve structured or unstructured data without maintaining physical database servers.  

They help applications handle data efficiently while improving scalability, availability, and security.

AWS provides different database services based on application needs.

---

## 🧾 Types of Databases

### Relational Databases

Relational databases store data in tables with rows and columns and use SQL for querying.  

They are best suited for applications that require structured data and strong consistency.

📌 Example: Banking systems, ERP applications

---

### Non-Relational Databases (NoSQL)

Non-relational databases store data in flexible formats such as key-value, document, or graph models.  

They are useful for applications requiring high speed, scalability, and unstructured data handling.

📌 Example: Social media apps, real-time applications

---

## 🏢 Amazon RDS (Relational Database Service)

Amazon RDS is a managed service for relational databases that simplifies setup, operation, and scaling.  

It supports databases like MySQL, PostgreSQL, Oracle, SQL Server, and MariaDB.

AWS handles backups, patching, and maintenance automatically.

---

## ⚡ Amazon DynamoDB

Amazon DynamoDB is a fully managed NoSQL database service designed for high performance and low latency.  

It automatically scales and is ideal for applications requiring fast and predictable performance.

📌 Example: Gaming apps, IoT applications

---

## 🧠 Amazon Redshift

Amazon Redshift is a data warehouse service used for large-scale data analysis and business intelligence.  

It helps organizations analyze huge amounts of data quickly using SQL-based tools.

📌 Example: Sales reporting and analytics dashboards

---

## 🔁 Database Backups and Replication

AWS provides automatic backup and replication features to protect data and improve availability.  

Replication creates copies of data across multiple locations to reduce downtime during failures.

This ensures better reliability and disaster recovery.

---

## 📈 High Availability with Multi-AZ

Multi-AZ deployment in Amazon RDS creates a standby copy of the database in another Availability Zone.  

If the primary database fails, AWS automatically switches to the standby database to minimize downtime.

---

## 🔒 Database Security

AWS provides database security through encryption, access control, and network isolation.  

IAM roles, security groups, and encryption help protect sensitive business data.

---

## 🧠 Key Takeaways

Cloud databases remove the need to manage physical database servers.  

Amazon RDS is used for relational databases, while DynamoDB is used for NoSQL workloads.  

Redshift is mainly used for analytics and data warehousing.  

Backup, replication, and Multi-AZ improve database reliability and availability.

---

## 🎯 Interview Questions

### Q1. What is Amazon RDS?  
Amazon RDS is a managed relational database service that automates setup, backup, patching, and scaling.

---

### Q2. What is the difference between RDS and DynamoDB?  
RDS is used for relational databases with structured data, while DynamoDB is used for NoSQL workloads requiring high speed and flexible data models.

---

### Q3. What is Amazon Redshift?  
Amazon Redshift is a cloud data warehouse service used for large-scale analytics and reporting.

---

### Q4. What is Multi-AZ in RDS?  
Multi-AZ creates a standby database in another Availability Zone to improve availability and reduce downtime during failures.

---

### Q5. When should you use DynamoDB?  
DynamoDB should be used for applications requiring low latency, high scalability, and flexible NoSQL data storage.
