# Module 3: Exploring Compute Services ⚙️☁️

---

## 📌 What are Compute Services?

Compute services provide the processing power required to run applications in the cloud.  
They allow developers to choose how much control they want over infrastructure and how much they want AWS to manage.

---

## 🖥️ Amazon EC2 (Elastic Compute Cloud)

Amazon EC2 provides virtual servers in the cloud, allowing users to run applications with full control over the operating system and configurations.  

It is best suited for applications where customization, flexibility, and long-running processes are required.

📌 Example: Hosting a backend server or a full web application.

---

## 📈 Amazon EC2 Auto Scaling

Auto Scaling automatically increases or decreases the number of EC2 instances based on application demand.  

This ensures that the application can handle traffic spikes while also reducing costs during low usage periods.

---

## ⚖️ Elastic Load Balancing (ELB)

Elastic Load Balancing distributes incoming traffic across multiple EC2 instances to ensure no single server is overloaded.  

This improves application availability, fault tolerance, and overall performance.

---

## ⚡ AWS Lambda (Serverless Computing)

AWS Lambda allows developers to run code without provisioning or managing servers.  

It automatically scales based on incoming requests and charges only for the execution time used.

📌 Example: Running backend logic when a file is uploaded or an API is triggered.

---

## 📦 Amazon ECS (Elastic Container Service)

Amazon ECS is a managed service that allows you to run and manage containerized applications using Docker.  

It simplifies container deployment without requiring deep knowledge of orchestration tools.

---

## ☸️ Amazon EKS (Elastic Kubernetes Service)

Amazon EKS is a managed Kubernetes service that allows you to run containerized applications using Kubernetes.  

It is suitable for complex, large-scale applications that require advanced container orchestration.

---

## 🚀 AWS Fargate

AWS Fargate is a serverless compute engine for containers that removes the need to manage underlying servers.  

It works with ECS and EKS and allows developers to focus only on running containers.

---

## 🧠 How to Choose the Right Service

- EC2 is used when full control over the environment is required.  
- Lambda is used when you want to run code without managing servers.  
- ECS is used for simple container management.  
- EKS is used for advanced Kubernetes-based applications.  
- Fargate is used when you want serverless container execution.

---

## 🧠 Key Takeaways

- AWS provides multiple compute services based on different levels of control and abstraction.  
- Serverless and containers reduce operational complexity for developers.  
- Auto Scaling and Load Balancing help maintain high availability and performance.  
- Choosing the right compute service depends on the application requirements.

---

## 🎯 Interview Questions

### Q1. What are AWS compute services?
AWS compute services are services that provide processing power to run applications, such as EC2, Lambda, ECS, EKS, and Fargate.

---

### Q2. When should you use AWS Lambda?
AWS Lambda should be used when you want to run event-driven code without managing servers and prefer automatic scaling.

---

### Q3. What is the difference between ECS and EKS?
ECS is an AWS-native container service that is simpler to use, while EKS is based on Kubernetes and provides more flexibility and control.

---

### Q4. What is AWS Fargate?
AWS Fargate is a serverless compute engine for containers that removes the need to manage servers.

---

### Q5. How do you choose between EC2 and Lambda?
EC2 is used for long-running applications requiring full control, while Lambda is used for short, event-driven tasks with no server management.

---
