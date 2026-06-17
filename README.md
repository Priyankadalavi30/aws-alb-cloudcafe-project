# ☕ Cloud Café - AWS ALB Project

## 📌 Project Overview
This project demonstrates a simple highly available web application using AWS services. Two EC2 instances are placed behind an Application Load Balancer (ALB) to distribute traffic evenly.

---

## ☁️ Architecture Diagram

- Users access application via ALB
- ALB distributes traffic across multiple EC2 instances
- Each EC2 runs Nginx web server
- Ensures high availability and fault tolerance

---

## ☁️ AWS Services Used
- Amazon EC2
- Application Load Balancer (ALB)
- Target Groups
- Security Groups

---

## ⚙️ Setup Summary
- Launched 2 EC2 instances (t2.micro)
- Installed and configured Nginx web server
- Created Target Group and registered instances
- Created Application Load Balancer
- Configured listener on port 80

---

## 🔄 Load Balancing Working
- ALB distributes incoming traffic between both EC2 instances
- If one server fails, traffic is routed to the healthy instance
- Ensures high availability and fault tolerance

---

## 🌐 Result
Accessing the ALB DNS shows response from:
- Server 1 OR
- Server 2 (based on load balancing)

---

## 🎯 Key Learning
- How ALB works in AWS
- Target Group and Health Checks
- High Availability concept
- Basic AWS architecture design