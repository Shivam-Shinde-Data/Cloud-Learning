# Module 4: Going Global 🌍☁️

---

## 📌 What is AWS Global Infrastructure?

AWS Global Infrastructure is a network of data centers distributed across different geographical locations worldwide.  

It allows applications to run closer to users, improving performance and reducing latency.

---

## 🌎 Regions

A Region is a physical location in the world where AWS groups multiple data centers.  

Each region is isolated from others, which helps in achieving better fault tolerance and reliability.

📌 Example: Mumbai Region (ap-south-1)

---

## 🏢 Availability Zones (AZs)

Availability Zones are multiple isolated data centers within a single region.  

They are connected with high-speed networks but are designed to operate independently to avoid single points of failure.

---

## 🌐 Edge Locations

Edge locations are data centers located closer to end users and are used to deliver content with low latency.  

They help improve the speed of applications by serving data from nearby locations.

---

## ⚡ Amazon CloudFront

Amazon CloudFront is a content delivery network (CDN) that delivers content to users with low latency by caching it at edge locations.  

It improves performance by serving content from the nearest location instead of the origin server.

---

## 🔁 High Availability

High availability refers to designing systems in a way that they remain operational even if some components fail.  

This is achieved by deploying applications across multiple Availability Zones.

---

## 📉 Fault Tolerance

Fault tolerance is the ability of a system to continue functioning even when there is a failure in one or more components.  

It ensures minimal downtime and uninterrupted service.

---

## 🧭 Choosing a Region

When selecting a region, important factors include latency, cost, compliance requirements, and service availability.  

Choosing the right region ensures better performance and adherence to business requirements.

---

## 🧠 Key Takeaways

AWS uses regions, availability zones, and edge locations to build a global infrastructure.  

Deploying applications across multiple Availability Zones improves availability and reliability.  

Services like CloudFront help reduce latency by delivering content closer to users.

---

## 🎯 Interview Questions

### Q1. What is an AWS Region?  
An AWS Region is a geographical area where AWS has multiple data centers to host cloud resources.

---

### Q2. What is an Availability Zone?  
An Availability Zone is an isolated data center within a region designed to improve availability and fault tolerance.

---

### Q3. What is the difference between Region and Availability Zone?  
A region is a geographical area, while an Availability Zone is a data center within that region.

---

### Q4. What is CloudFront?  
CloudFront is a content delivery network that delivers content with low latency using edge locations.

---

### Q5. How do you achieve high availability in AWS?  
High availability is achieved by deploying applications across multiple Availability Zones and distributing traffic effectively.

---
