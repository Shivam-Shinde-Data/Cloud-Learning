# Module 2: Compute in the Cloud 💻☁️

---

## 📌 What is Compute in Cloud?

Compute refers to the processing power required to run applications.

In cloud computing, you don’t need physical servers. Instead, you use virtual machines and managed services provided by cloud platforms.

---

## ⚙️ Types of Compute Services

### 1. Virtual Machines (VMs)
- Virtual version of a physical computer
- Run applications, OS, and software

📌 Example:
- AWS EC2
- Azure Virtual Machines
- GCP Compute Engine

---

### 2. Containers
- Lightweight environment to run applications
- Faster and more efficient than VMs

📌 Example:
- Docker
- Kubernetes

---

### 3. Serverless Computing
- No need to manage servers
- Code runs only when triggered

📌 Example:
- AWS Lambda
- Azure Functions
- Google Cloud Functions

---

## 🖥️ Amazon EC2 (Elastic Compute Cloud)

EC2 is a core AWS service that provides resizable virtual servers in the cloud.

### Key Features:
- Launch virtual servers (instances)
- Choose OS (Linux/Windows)
- Full control over configuration
- Scalable (increase/decrease instances anytime)

---

## 🔧 EC2 Instance Types

Different instance types are designed for different workloads:

- General Purpose → Balanced (web apps)
- Compute Optimized → High CPU (data processing)
- Memory Optimized → Large RAM (databases)
- Storage Optimized → High disk usage

---

## 📦 EC2 Pricing Options

### 1. On-Demand
- Pay per use
- No long-term commitment

### 2. Reserved Instances
- Lower cost with long-term commitment

### 3. Spot Instances
- Cheapest option
- Can be interrupted anytime

---

## 📈 Scaling in Cloud

### What is Scaling?
Adjusting resources based on demand.

### Types:
- Vertical Scaling → Increase power of one server
- Horizontal Scaling → Add more servers

📌 Cloud mainly uses **horizontal scaling**

---

## 🔁 Auto Scaling

Automatically adjusts number of instances based on demand.

### Benefits:
- Handles traffic spikes
- Reduces cost
- Improves performance

---

## ⚖️ Load Balancing

Distributes incoming traffic across multiple servers.

### Benefits:
- Prevents overload
- Improves availability
- Ensures reliability

📌 Example:
- AWS Elastic Load Balancer (ELB)

---

## 🧠 Key Takeaways

- Compute = processing power for applications
- EC2 is the main compute service in AWS
- Multiple pricing models available
- Auto Scaling + Load Balancer = high availability system
- Serverless removes server management completely

---

## 🎯 Interview Questions

### Q1. What is EC2?
EC2 is a service that provides virtual servers in the cloud.

---

### Q2. Difference between VM and Containers?

- VM → Full OS, heavier
- Container → Lightweight, faster

---

### Q3. What is serverless computing?
A model where you run code without managing servers.

---

### Q4. What is Auto Scaling?
Automatically increases/decreases resources based on demand.

---

### Q5. What is Load Balancing?
Distributing traffic across multiple servers to improve performance.

---
