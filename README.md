<!-- Animated Header -->
<p align="center">
  <a href="#">
    <img src="https://readme-typing-svg.herokuapp.com?size=28&color=00AEEF&center=true&vCenter=true&width=700&lines=Franklin+%7C+DevOps+%26+SRE+Engineer;AWS+%7C+CI%2FCD+%7C+Automation+%7C+Observability;Building+Reliable+Scalable+Systems" />
  </a>
</p>

# 👋 Hi, I'm Franklin  
**DevOps & Site Reliability Engineer | AWS | CI/CD | Automation | Observability**

I design **reliable, scalable, and fully automated systems** using AWS, Docker, GitHub Actions, Linux, and modern SRE tooling.  
My work focuses on **clean infrastructure, reproducible workflows, and real-world DevOps engineering**.

---

## 👀 Visitor Counter
<img src="https://komarev.com/ghpvc/?username=Franklindot04&color=blue" />

---

## 🚀 Core Expertise
- **Cloud Infrastructure:** AWS (EC2, Lambda, API Gateway, DynamoDB, S3, IAM, VPC)  
- **CI/CD Pipelines:** GitHub Actions, Jenkins  
- **Containers & Orchestration:** Docker, Kubernetes  
- **Automation:** Bash, Python, Ansible  
- **Observability:** Prometheus, Grafana, Alertmanager  
- **Serverless Architectures**  
- **Monitoring, Logging & SRE Practices**

---

## 🧰 Tech Stack & Tools
<p align="left">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/IAM-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/VPC-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white" />
  <img src="https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white" />

  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" />

  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
</p>

---

# 📌 Featured Projects

---

## **DevOps & SRE Engineering**

<details>
<summary><strong>🚀 DevOps Deployment Automation (Slack‑Driven CI/CD + Rollback)</strong></summary>

**Repo:**  
• [DevOps Deployment Automation](https://github.com/Franklindot04/devops-deployment-automation)

**Badges:**  
![Deploy Staging](https://github.com/Franklindot04/devops-deployment-automation/actions/workflows/deploy_staging.yml/badge.svg)
![Deploy Production](https://github.com/Franklindot04/devops-deployment-automation/actions/workflows/deploy_production.yml/badge.svg)
![Promote to Production](https://github.com/Franklindot04/devops-deployment-automation/actions/workflows/promote_to_production.yml/badge.svg)
![Rollback Production](https://github.com/Franklindot04/devops-deployment-automation/actions/workflows/rollback_production.yml/badge.svg)

**Description:**  
Slack‑driven deployment automation with GitHub Actions, AWS Lambda, API Gateway, version tracking, and stateless rollback.

</details>

---

<details>
<summary><strong>📊 Prometheus + Grafana SRE Observability Platform</strong></summary>

**Repo:**  
• [Prometheus + Grafana SRE Platform](https://github.com/Franklindot04/prometheus-grafana-sre-project-Franklin)

**Shields:**  
<img src="https://img.shields.io/badge/FastAPI-App-green?style=flat-square" />
<img src="https://img.shields.io/badge/Prometheus-Metrics-orange?style=flat-square" />
<img src="https://img.shields.io/badge/Grafana-Dashboards-yellow?style=flat-square" />
<img src="https://img.shields.io/badge/Alertmanager-Alerts-red?style=flat-square" />
<img src="https://img.shields.io/badge/Blackbox-Exporter-lightgrey?style=flat-square" />

**Description:**  
A full production‑grade observability and alerting platform built around a FastAPI application instrumented with Prometheus metrics, visualized through Grafana dashboards, monitored externally via Blackbox Exporter, and equipped with a complete alerting pipeline using Prometheus alert rules + Alertmanager + Grafana‑managed alerts.

**Key Capabilities:**  
- Custom FastAPI metrics (request count, latency histograms, Python internals)  
- Blackbox Exporter for external uptime monitoring  
- Auto‑provisioned Grafana dashboards (FastAPI, Blackbox, Prometheus internals)  
- Full alerting pipeline (Prometheus → Alertmanager → Slack)  
- Grafana‑managed alert rules for external probe failures  
- Environment‑aware configuration (macOS vs Linux exporters)  
- Secure secret management using `.env` + Alertmanager variable injection  
- Modular, production‑ready Docker Compose architecture  

**Alerting Features:**  
- Critical & warning alerts (latency, traffic spikes, target down, app down)  
- Blackbox probe alerts for external endpoint failures  
- Slack notifications with runbook links, severity labels & metadata  
- Automatic alert resolution when services recover  

**Architecture Overview:**  
FastAPI → Prometheus → Grafana → Alertmanager → Slack  
Blackbox Exporter → Prometheus → Grafana → Alerts  

**What This Demonstrates:**  
Real SRE practices: instrumentation, exporters, alerting, dashboards, runbooks, secret management, and operational readiness.

</details>


---

<details>
<summary><strong>🛠 Ansible Automation Suite — 15+ Production‑Style Playbooks</strong></summary>

**Repo:**  
• [Ansible Work 1](https://github.com/Franklindot04/ansible-work-1)

**Shields:**  
<img src="https://img.shields.io/badge/Ansible-Automation-red?style=flat-square" />
<img src="https://img.shields.io/badge/Linux-Servers-grey?style=flat-square" />
<img src="https://img.shields.io/badge/Playbooks-15%2B-blue?style=flat-square" />

**Description:**  
A comprehensive collection of 15+ Ansible playbooks designed to automate real‑world Linux server operations, application deployments, configuration management, and environment provisioning.  
This suite demonstrates production‑style automation patterns including multi‑play orchestration, templating, handlers, dynamic variables, and reusable role‑based structures.

**Key Capabilities:**  
- Server provisioning & configuration (users, packages, services)  
- Web application deployments (HTML, PHP, Angular)  
- Apache/HTTPD setup & environment configuration  
- Maintenance mode workflows (blue/green‑style switch)  
- Dynamic Jinja2 templating & variable injection  
- Logical conditions, handlers & multi‑play orchestration  
- Role‑ready structure for scalable automation  

**Included Playbooks:**  
- Server setup & package installation  
- Apache/HTTPD provisioning  
- E‑commerce & food‑delivery sample deployments  
- HTML, PHP & Angular app deployments  
- Maintenance mode automation  
- Static & dynamic variable examples  
- Ubuntu server configuration  
- Multi‑package & logical condition automation  

**What This Demonstrates:**  
- Infrastructure automation fundamentals  
- Idempotent configuration management  
- Reusable automation patterns  
- Real DevOps workflows using Ansible at scale  

</details>

---

## **Backend & Microservices**

<details>
<summary><strong>🧠 Face Recognition Platform (Private Repo)</strong></summary>

**Description:**  
InsightFace + FastAPI + Docker + AWS.  
Embedding generation, vector search, user enrollment, secure APIs.

</details>

---

<details>
<summary><strong>⚙ Python Background Job Microservice</strong></summary>

**Repo:**  
• [Python Background Job Microservice](https://github.com/Franklindot04/python-background-job-microservice)

**Shields:**  
<img src="https://img.shields.io/badge/Python-Microservice-blue?style=flat-square" />

**Description:**  
Modular background job runner with Docker and clean architecture.

</details>

---

<details>
<summary><strong>💰 Finance Tracker API — FastAPI • Docker • Terraform • AWS ECS Fargate</strong></summary>

**Repo:**  
• [Finance Tracker API](https://github.com/Franklindot04/finance-tracker-api)

**Shields:**  
<img src="https://img.shields.io/badge/FastAPI-Backend-009688?style=flat-square" />
<img src="https://img.shields.io/badge/Terraform-IaC-844FBA?style=flat-square" />
<img src="https://img.shields.io/badge/AWS-ECS%20Fargate-orange?style=flat-square" />
<img src="https://img.shields.io/badge/AWS-RDS-blue?style=flat-square" />
<img src="https://img.shields.io/badge/Docker-Containerized-2496ED?style=flat-square" />
<img src="https://img.shields.io/badge/CloudWatch-Logs-yellow?style=flat-square" />

**Description:**  
A production‑ready FastAPI backend for tracking personal expenses — fully containerized with Docker and deployed to AWS ECS Fargate using Terraform.  
This project demonstrates real‑world DevOps engineering: Infrastructure as Code, secure VPC networking, load‑balanced container workloads, RDS PostgreSQL, and cloud‑native observability.

**Key Capabilities:**  
- JWT‑based authentication (register/login)  
- CRUD operations for expenses  
- SQLite locally, PostgreSQL (RDS) in production  
- Modular FastAPI architecture (routers, models, schemas, core)  
- Dockerfile + docker‑compose for local development  
- Swagger UI at `/docs`  
- CI/CD‑ready structure for GitHub Actions → ECS  

**Cloud Infrastructure (Terraform):**  
- VPC with public + private subnets  
- Application Load Balancer (public)  
- ECS Fargate service (private subnets)  
- RDS PostgreSQL (private subnets)  
- Security groups with least‑privilege access  
- IAM roles for ECS task execution & logging  
- CloudWatch log groups for observability  
- ECR repository for container images  

**High‑Level Architecture:**  
ALB → ECS Fargate Task → RDS PostgreSQL  
VPC with NAT Gateway, route tables, and VPC endpoints for ECR/S3.

**Authentication Flow:**  
- Register → Login → Receive JWT → Use token in Authorization header  
- Fully stateless, token‑based authentication  

**What This Demonstrates:**  
- Cloud‑native application deployment  
- Infrastructure as Code with Terraform  
- Secure networking and IAM design  
- Container orchestration with ECS Fargate  
- Production‑grade backend engineering  

</details>

---

<details>
<summary><strong>🎮 Number Guess Game — Full CI/CD Pipeline (Jenkins • Maven • SonarQube • Nexus • Tomcat)</strong></summary>

**Repo:**  
• [Number Guess Game](https://github.com/Franklindot04/number_guess_game/tree/master)

**Shields:**  
<img src="https://img.shields.io/badge/Jenkins-Pipeline-blue?style=flat-square" />
<img src="https://img.shields.io/badge/Java-8%2F17%2F21-orange?style=flat-square" />
<img src="https://img.shields.io/badge/Maven-Build-red?style=flat-square" />
<img src="https://img.shields.io/badge/SonarQube-Quality-brightgreen?style=flat-square" />
<img src="https://img.shields.io/badge/Nexus-Artifacts-yellow?style=flat-square" />
<img src="https://img.shields.io/badge/Tomcat-Deployment-lightgrey?style=flat-square" />
<img src="https://img.shields.io/badge/AWS-EC2-ff9900?style=flat-square" />

**Description:**  
A fully automated CI/CD pipeline for a Java Servlet web application deployed on AWS EC2.  
This project demonstrates a complete DevOps workflow: build, test, quality gate checks, artifact versioning, and automated deployment to Tomcat — all orchestrated through Jenkins Pipeline‑as‑Code.

**Key Capabilities:**  
- Maven build + unit tests on every commit  
- SonarQube Quality Gates for static analysis  
- Versioned `.war` artifacts stored in Nexus  
- Automated deployment to Apache Tomcat  
- Zero manual steps — fully automated CI/CD  
- Clean, production‑style multi‑server architecture on AWS  

**Infrastructure:**  
- Jenkins (CI engine)  
- SonarQube (code quality)  
- Nexus Repository Manager (artifact storage)  
- Apache Tomcat (deployment target)  
- AWS EC2 instances (isolated services, no config drift)  

**Versioning & Rollback:**  
- Every build stored in Nexus with unique version  
- Any version can be redeployed via Jenkins  
- Safe, controlled rollback workflow  

**UI Enhancements:**  
- Centered layout  
- Modern block‑style container  
- Mossy‑hollow color theme  
- Improved user feedback  

**Tech Stack:**  
Java Servlets + JSP • Maven • Jenkins Pipeline • SonarQube • Nexus • Tomcat • AWS EC2

</details>


---

## 🧩 Currently Working On
- Expanding my **DevOps automation portfolio**  
- Building a **full SRE observability platform**  
- Improving my **Go programming skills**  
- Designing a **Personal Finance Tracker API**

---

## 📊 GitHub Stats & Activity
<p align="center">
  <img height="170" src="https://streak-stats.demolab.com/?user=Franklindot04&theme=tokyonight" />
  <img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Franklindot04&theme=tokyonight" />
</p>

<p align="center">
  <img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Franklindot04&theme=tokyonight" />
  <img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Franklindot04&theme=tokyonight" />
</p>

<p align="center">
  <img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Franklindot04&theme=tokyonight" />
</p>

---

## 👨‍💻 About Me
I'm Franklin — a DevOps & SRE engineer passionate about automation, cloud infrastructure, observability, and building production-ready systems.  
I enjoy documenting my work, mentoring others, and creating real-world engineering projects.

---

## ⭐ Support
If you find my work useful, consider giving a ⭐ — it helps others discover it.
