# Module 6: Storage 📦☁️

---

## 📌 What is Storage in Cloud?

Storage in cloud refers to saving data on cloud infrastructure instead of physical devices like hard drives or local servers.  

It allows users to store, access, manage, and protect data from anywhere using the internet.

Cloud storage provides high durability, scalability, and security for both small and large applications.

---

## 🪣 Amazon S3 (Simple Storage Service)

Amazon S3 is an object storage service used to store and retrieve any amount of data from anywhere.  

It is designed for high durability, availability, and scalability.

S3 stores data as objects inside containers called buckets.

📌 Example: Storing images, videos, backups, and application files.

---

## 🧱 Amazon EBS (Elastic Block Store)

Amazon EBS provides block-level storage that is attached to EC2 instances.  

It is mainly used for applications that require frequent updates, such as databases and operating systems.

EBS works like a hard disk attached to a virtual machine.

---

## 📁 Amazon EFS (Elastic File System)

Amazon EFS provides scalable file storage for use with multiple EC2 instances at the same time.  

It is useful when applications need shared access to the same files.

It automatically grows and shrinks as files are added or removed.

---

## 🗄️ Storage Types in AWS

### Object Storage

Object storage is used to store files as objects with metadata and unique identifiers.  

Amazon S3 is the main example of object storage.

---

### Block Storage

Block storage divides data into blocks and is commonly used for operating systems and databases.  

Amazon EBS is the main example of block storage.

---

### File Storage

File storage organizes data using folders and files, similar to traditional file systems.  

Amazon EFS is the main example of file storage.

---

## 🔁 S3 Storage Classes

Amazon S3 offers different storage classes based on access frequency and cost.

### Common Storage Classes:

- S3 Standard → Frequently accessed data  
- S3 Standard-IA → Infrequently accessed data  
- S3 Glacier → Long-term archival storage  
- S3 Intelligent-Tiering → Automatically moves data based on usage

This helps optimize storage cost.

---

## 🔒 Data Backup and Recovery

AWS provides backup solutions to protect important data from accidental deletion or failures.  

Backup and recovery help ensure business continuity and reduce data loss risks.

S3 versioning and backup services are commonly used for this purpose.

---

## 🧠 Key Takeaways

Cloud storage helps store and manage data securely without physical infrastructure.  

Amazon S3 is used for object storage, EBS for block storage, and EFS for shared file storage.  

Choosing the correct storage type depends on the application requirements.  

Storage classes help reduce cost by matching storage to usage patterns.

---

## 🎯 Interview Questions

### Q1. What is Amazon S3?  
Amazon S3 is an object storage service used to store and retrieve any amount of data with high durability and scalability.

---

### Q2. What is the difference between S3 and EBS?  
S3 is object storage used for files and backups, while EBS is block storage attached to EC2 instances for operating systems and databases.

---

### Q3. What is Amazon EFS?  
Amazon EFS is a scalable file storage service that allows multiple EC2 instances to access the same files.

---

### Q4. What are S3 storage classes?  
S3 storage classes are different storage options based on access frequency and cost, such as Standard, Glacier, and Intelligent-Tiering.

---

### Q5. When should you use EBS instead of S3?  
EBS should be used when an application needs block storage with frequent read/write operations, such as databases or system disks.
