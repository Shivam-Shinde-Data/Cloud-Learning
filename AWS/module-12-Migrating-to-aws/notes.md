# Module 12: Migrating to the AWS Cloud 🚀☁️

---

## 📌 What is Cloud Migration?

Cloud migration is the process of moving applications, data, databases, and other business workloads from on-premises infrastructure to the cloud.  

It helps organizations improve scalability, reduce costs, increase flexibility, and modernize their IT systems.

Migration can also happen from one cloud provider to another.

---

## 🎯 Why Migrate to AWS?

Organizations migrate to AWS to reduce infrastructure costs and avoid managing physical hardware.  

AWS provides better scalability, security, reliability, and global access for modern applications.

It also supports faster innovation by providing managed services and automation tools.

---

## 🔁 The 6 Rs of Cloud Migration

AWS commonly uses the “6 Rs” strategy for migration planning.

### 1. Rehosting

Rehosting means moving applications to the cloud without major changes.  

It is often called “lift and shift.”

📌 Example: Moving a virtual machine from on-premises to EC2

---

### 2. Replatforming

Replatforming means making small optimizations during migration without changing the core architecture.  

It improves performance while keeping migration simple.

📌 Example: Moving a database to Amazon RDS

---

### 3. Repurchasing

Repurchasing means replacing the current application with a cloud-based SaaS solution.  

📌 Example: Replacing a local CRM system with Salesforce

---

### 4. Refactoring / Re-architecting

Refactoring means redesigning the application to fully use cloud-native features.  

It provides the highest long-term benefits but requires more effort.

📌 Example: Converting a monolithic app into microservices

---

### 5. Retiring

Retiring means removing applications that are no longer needed.  

This helps reduce unnecessary cost and complexity.

---

### 6. Retaining

Retaining means keeping some applications on-premises due to compliance, latency, or business requirements.  

Not every workload needs to move immediately.

---

## 🛠️ AWS Migration Services

AWS provides services to simplify cloud migration.

### AWS Migration Hub

AWS Migration Hub helps track and manage migration progress across multiple AWS and partner tools.

---

### AWS Application Migration Service (MGN)

This service helps move physical, virtual, and cloud servers to AWS with minimal downtime.

---

### AWS Database Migration Service (DMS)

AWS DMS helps migrate databases to AWS securely with minimal downtime.  

It supports both homogeneous and heterogeneous database migrations.

📌 Example: Moving MySQL to Amazon RDS PostgreSQL

---

### AWS Snow Family

AWS Snow Family devices are used to transfer large amounts of data physically when internet transfer is too slow.  

📌 Example: Migrating petabytes of data from a data center

---

## 📋 Migration Planning

Successful migration requires proper planning, including:

- Understanding current workloads  
- Choosing the right migration strategy  
- Estimating costs and risks  
- Testing performance after migration  
- Ensuring security and compliance  

This reduces migration failures and business disruption.

---

## 🧠 Key Takeaways

Cloud migration helps organizations modernize applications and reduce infrastructure costs.  

The 6 Rs strategy helps choose the right migration approach for each workload.  

AWS provides services like DMS, Migration Hub, and Snow Family to simplify migration.  

Not all workloads should be migrated in the same way.

---

## 🎯 Interview Questions

### Q1. What is cloud migration?  
Cloud migration is the process of moving applications, data, and workloads from on-premises systems to the cloud.

---

### Q2. What is Rehosting in cloud migration?  
Rehosting means moving applications to the cloud without major changes and is also called lift and shift.

---

### Q3. What is AWS DMS?  
AWS Database Migration Service helps migrate databases to AWS securely with minimal downtime.

---

### Q4. When should AWS Snow Family be used?  
AWS Snow Family should be used when transferring very large amounts of data and internet transfer is too slow.

---

### Q5. What is the difference between Rehosting and Refactoring?  
Rehosting moves applications with minimal changes, while Refactoring redesigns applications to fully use cloud-native features.
