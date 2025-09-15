# Spring Boot Microservices — Production-Ready DevOps Project

A full-stack **Spring Boot microservices** project with **end-to-end DevOps implementation**, containerized with **Docker**, orchestrated on **Kubernetes (EKS)**, and automated using **CI/CD pipelines (GitHub Actions/Jenkins)**. Includes **AWS infrastructure as code (Terraform)**, **observability (Grafana, Prometheus, Loki)**, and production-ready deployment practices.

---

## 🚀 Project Overview

This project demonstrates a **real-world microservices architecture** with multiple services communicating via **Kafka and RabbitMQ**. It showcases best practices for:

- **Microservices development:** Spring Boot, JPA, PostgreSQL, MongoDB
- **API gateways & service discovery:** Spring Cloud Gateway, Eureka
- **Security:** Keycloak for authentication & authorization
- **Observability:** Logging (Loki), metrics (Prometheus), tracing (Zipkin)
- **Containerization & orchestration:** Docker, Docker Compose, Kubernetes
- **Infrastructure automation:** Terraform (VPC, EKS, RDS, S3, IAM)
- **CI/CD pipelines:** Build, test, and deploy microservices automatically

---

## 🛠️ Tech Stack

- **Backend / Microservices:** Spring Boot, Java, JPA, PostgreSQL, MongoDB, Kafka, RabbitMQ
- **Security:** Keycloak, Spring Security
- **Containerization:** Docker, Docker Compose
- **Orchestration:** Kubernetes, Helm
- **CI/CD:** GitHub Actions / Jenkins
- **Monitoring / Observability:** Grafana, Prometheus, Loki, Zipkin
- **Cloud / Infrastructure:** AWS, Terraform

---

## 📂 Repository Structure

springboot-microservices-devops/
├── microservices/ # All Spring Boot services
├── docker/ # Dockerfiles & Docker Compose configurations
├── k8s/ # Kubernetes manifests & Helm charts
├── terraform/ # AWS infrastructure as code (IaC)
├── cicd/ # CI/CD pipeline configurations (GitHub Actions/Jenkins)
├── monitoring/ # Grafana, Prometheus, Loki configurations
├── scripts/ # Helper scripts for deployment & teardown
└── README.md # Project documentation



---

## ⚡ Key Features

- Production-ready **multi-service architecture**
- **Full CI/CD automation** for build, test, and deployment
- AWS EKS cluster with **scalable, resilient microservices**
- Observability stack for **logs, metrics, and distributed tracing**
- **Secrets management** using AWS Secrets Manager
- Modular, maintainable, and fully **cloud-native**

---

## 📌 Usage

### 1. Clone the repository
```bash
git clone git@github-devops:devops0425/ecom-microservices.git
cd ecom-microservices
```

### 2. Run Docker Compose locally
```dockerfile
docker-compose up -d
```

### 3. Deploy to Kubernetes using Helm
```bash
helm install <release-name> ./k8s/helm
```

### 4. Provision AWS infrastructure using Terraform
```bash
cd terraform
terraform init
terraform apply
```

### 5. CI/CD Pipelines
```text
Automatically build, test, and deploy microservices using GitHub Actions or Jenkins pipelines.
```

### 🔑 Contributing / Notes

- This project is primarily for learning and demonstrating DevOps + microservices practices.

- Contributions to enhance automation, observability, or architecture are welcome.
### 📄 License

- This repository is open for personal use and learning purposes. Please contact the owner for commercial usage.

## 📌 Contact / Support

- Maintainer: DevOps Team

- Email: devopsapps.info@gmail.com

- GitHub: https://github.com/devops0425

