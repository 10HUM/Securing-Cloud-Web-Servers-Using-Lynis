# Cloud Security, System Hardening & Cloud Migration Project

## 📋 Project Overview
This project simulates a real-world scenario as a **Junior DevOps Engineer** tasked with evaluating, securing, and scaling a client's web-server infrastructure. The client currently relies on a localized web-server setup facing severe scalability bottlenecks, security vulnerabilities, and disaster recovery risks. 

This repository documents the end-to-end process of auditing system security, applying industrial hardening standards (CIS Benchmarks), and designing a robust, scalable cloud solution with a comprehensive disaster recovery plan.

---

## 🛠️ Tools & Technologies
- **Containerization & OS:** Docker (`nwendlo1/c1w2m6`), Ubuntu 22.04
- **Security Auditing:** Lynis
- **Compliance & Hardening Standards:** CIS Benchmark for Ubuntu 22.04, CIS Benchmark for Apache Web Server
- **Documentation:** Structured Cloud Security Implementation Report

---

## 📌 Project Tasks & Implementation Steps

### **Task 1: Understand Customer Challenges & Requirements**
* Identified core client pain points: scalability limitations, security risks, and compliance gaps.
* Correlated business challenges with real-world infrastructure vulnerabilities.
* Executed automated security auditing via **Lynis** within an isolated Docker container to establish a baseline security posture.

### **Task 2: Evaluate Cloud Service Models**
* Compared **IaaS (Infrastructure as a Service)**, **PaaS (Platform as a Service)**, and **SaaS (Software as a Service)** models.
* Determined the optimal model alignment based on the client's control requirements, maintenance capacity, and scalability goals.

### **Task 3: Explore Deployment Options**
* Analyzed the pros and cons of **Public**, **Private**, and **Hybrid** cloud environments.
* Formulated a strategy matching the client's data sensitivity and workload fluctuations.

### **Task 4: Develop a Cloud Solution Recommendation**
* Demonstrated how local web-server system hardening (remediating Lynis warnings using CIS Benchmarks) directly mitigates attack surfaces.
* Translated local hardening findings into production-ready cloud architectural recommendations.

### **Task 5: Disaster Recovery Planning**
* Designed a comprehensive disaster recovery (DR) strategy covering system backup procedures, data redundancy, and high-availability (HA) mechanisms in the cloud.

### **Task 6: Overall Reflection**
* Evaluated the synergy between proactive system hardening and scalable cloud design principles.

---

## 🚀 Getting Started & Local Lab Reproduction

To spin up the assessment environment and run the Lynis security audit locally:

1. **Pull and run the Docker assessment container:**
   ```bash
   docker run -it nwendlo1/c1w2m6 /bin/bash
