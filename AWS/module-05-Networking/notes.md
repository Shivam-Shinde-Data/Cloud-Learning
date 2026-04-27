# Module 5: Networking 🌐☁️

---

## 📌 What is Networking in Cloud?

Networking in cloud refers to how cloud resources communicate with each other and with the internet.  

It enables secure and controlled connectivity between applications, users, and services.

---

## 🌐 Amazon VPC (Virtual Private Cloud)

Amazon VPC is a logically isolated network within AWS where you can launch and manage your resources.  

It allows you to define your own IP address range, create subnets, and configure routing.

---

## 🏢 Subnets

Subnets are subdivisions of a VPC that allow you to organize and manage resources more effectively.  

They help control access and improve security within the network.

### Types of Subnets:

- Public Subnet → Resources can access the internet  
- Private Subnet → Resources are not directly accessible from the internet  

---

## 🌍 Internet Gateway

An Internet Gateway is a component that allows communication between a VPC and the internet.  

It enables resources in a public subnet to send and receive traffic from the internet.

---

## 🔒 NAT Gateway

A NAT Gateway allows resources in a private subnet to access the internet without exposing them to incoming internet traffic.  

It provides secure outbound internet connectivity.

---

## 📡 Route Tables

Route tables contain rules that determine how network traffic is directed within a VPC.  

They control where traffic goes, such as to the internet gateway or other resources.

---

## 🔐 Security Groups

Security groups act as virtual firewalls that control inbound and outbound traffic for instances.  

They allow only specified traffic and automatically block everything else.

---

## 🛡️ Network ACLs (Access Control Lists)

Network ACLs provide an additional layer of security at the subnet level.  

They control traffic entering and leaving the subnet using rules.

---

## 🌍 DNS and Amazon Route 53

Amazon Route 53 is a Domain Name System (DNS) service that translates domain names into IP addresses.  

It helps route user requests to the correct resources.

📌 Example: Converting a website name into its server IP address.

---

## 🧠 Key Takeaways

Networking in cloud enables communication between resources and users securely.  

Amazon VPC allows you to create an isolated network environment.  

Security groups and network ACLs help control and protect network traffic.  

Services like Route 53 ensure users can access applications using domain names.

---

## 🎯 Interview Questions

### Q1. What is a VPC?  
A VPC is a logically isolated network in AWS where you can launch and manage cloud resources.

---

### Q2. What is the difference between public and private subnet?  
A public subnet allows internet access, while a private subnet restricts direct internet access.

---

### Q3. What is a NAT Gateway?  
A NAT Gateway allows private resources to access the internet securely without being exposed to incoming traffic.

---

### Q4. What is a security group?  
A security group is a virtual firewall that controls traffic at the instance level.

---

### Q5. What is Route 53?  
Route 53 is a DNS service that routes user requests to the correct cloud resources.

---
