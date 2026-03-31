# ☁️ BTH Cloud Computing Portfolio

**Course:** DV1566 - Introduction to Cloud Computing  
**Institution:** Blekinge Institute of Technology (BTH)

This repository contains a collection of projects focused on cloud infrastructure, container orchestration, and automated resource management using **Amazon Web Services (AWS)** and **Docker**.

---

## 🚀 Key Projects

### 1. Adaptive Step Size Auto-Scaling Algorithm

**Objective:** Developed a scalable and cost-effective auto-scaling solution for EC2 instances.

- **Core Innovation:** Implemented a custom algorithm in **AWS Lambda** that dynamically adjusts scaling step sizes based on real-time CPU utilization metrics.
- **Monitoring:** Utilized **Amazon CloudWatch** to collect performance data and trigger scaling actions.
- **Impact:** Improved system responsiveness and accuracy compared to traditional static scaling methods, significantly minimizing resource wastage.

### 2. Infrastructure Deployment & Performance Monitoring (Lab 2)

**Objective:** Setting up and analyzing virtualized environments in AWS.

- **Networking:** Configured a secure **Virtual Private Cloud (VPC)** with custom subnets and security groups.
- **Load Testing:** Conducted performance benchmarks using **ApacheBench (ab)** to simulate concurrent user traffic.
- **Visualization:** Built CloudWatch dashboards to track `NetworkIn` and `NetworkOut` metrics for real-time traffic analysis.

### 3. Containerization & Orchestration (Lab 1)

**Objective:** Mastering application deployment using Docker.

- **Dockerization:** Scripted `Dockerfiles` using directives like `FROM`, `COPY`, and `EXPOSE` to create lightweight application images.
- **Orchestration:** Utilized **Docker Compose** to manage multi-container applications, ensuring persistent storage through volumes and automated network creation.
- **Version Control:** Managed container images through version tagging for reliable deployments.

---

## 🛠️ Technical Stack

- **Cloud Provider:** Amazon Web Services (AWS EC2, Lambda, CloudWatch, VPC, IAM)
- **DevOps Tools:** Docker, Docker Compose
- **Languages:** Python (Boto3 SDK)
- **Testing:** ApacheBench
