# Module 9: Security 🔒☁️

---

## 📌 What is Security in Cloud?

Security in cloud means protecting data, applications, and cloud resources from unauthorized access, threats, and failures.  

AWS provides built-in security services and follows strong security practices to help users keep their systems safe.

Security is a shared responsibility between AWS and the customer.

---

## 🤝 Shared Responsibility Model

The Shared Responsibility Model defines which security tasks are handled by AWS and which are handled by the customer.  

AWS is responsible for the security **of** the cloud, while customers are responsible for security **in** the cloud.

### AWS Responsibilities

- Physical security of data centers  
- Hardware and infrastructure maintenance  
- Networking and virtualization security

### Customer Responsibilities

- Managing user access  
- Protecting application data  
- Configuring security settings properly

---

## 👤 AWS IAM (Identity and Access Management)

AWS IAM is a service used to securely control access to AWS resources.  

It allows you to create users, groups, roles, and permissions for secure resource management.

IAM follows the principle of least privilege, meaning users should only get the permissions they need.

---

## 🔑 Multi-Factor Authentication (MFA)

MFA adds an extra layer of security by requiring more than just a password to access an account.  

It usually includes a second verification method such as a mobile code or authentication app.

This helps prevent unauthorized access even if the password is compromised.

---

## 🔐 Encryption

Encryption protects data by converting it into an unreadable format that can only be accessed using the correct key.  

AWS supports encryption for data both at rest and in transit.

This helps protect sensitive customer and business information.

---

## 🛡️ AWS Shield

AWS Shield is a managed service that protects applications from Distributed Denial of Service (DDoS) attacks.  

It helps maintain application availability during malicious traffic attacks.

---

## 📜 AWS WAF (Web Application Firewall)

AWS WAF protects web applications by filtering and monitoring HTTP and HTTPS requests.  

It helps block harmful traffic such as SQL injection and cross-site scripting attacks.

---

## 📊 AWS CloudTrail

AWS CloudTrail records account activity and API usage across AWS services.  

It helps in auditing, monitoring, and troubleshooting security events.

📌 Example: Tracking who deleted a resource and when

---

## 🔍 AWS Inspector

AWS Inspector is a security assessment service that helps identify vulnerabilities and security risks in applications.  

It improves security by checking for weaknesses and compliance issues.

---

## 🧠 Key Takeaways

Cloud security is a shared responsibility between AWS and the customer.  

IAM controls access to resources, while MFA improves login security.  

Encryption protects sensitive data, and services like Shield and WAF defend against attacks.  

CloudTrail helps track and audit user activity for better security management.

---

## 🎯 Interview Questions

### Q1. What is the Shared Responsibility Model?  
It is a security model where AWS manages the security of the cloud, and customers manage security in the cloud.

---

### Q2. What is IAM in AWS?  
IAM is a service used to manage users, roles, permissions, and secure access to AWS resources.

---

### Q3. Why is MFA important?  
MFA adds an extra layer of security by requiring a second verification step beyond the password.

---

### Q4. What is the difference between AWS Shield and AWS WAF?  
AWS Shield protects against DDoS attacks, while AWS WAF protects web applications from application-level threats like SQL injection.

---

### Q5. What is AWS CloudTrail?  
CloudTrail is a service that records account activity and API usage for auditing and security monitoring.
