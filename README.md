# 🚀 DevOps Upskilling Roadmap – 6 Months

A structured 6-month plan to master DevOps skills from the ground up.  
This repo is my personal learning tracker – I’ll check off each milestone as I complete it ✅.

---

## 📅 Month 1 – Core Fundamentals
**Goal:** Build a strong foundation in Linux, scripting, Git, and troubleshooting.

### 📌 Topics
- Linux Essentials: navigation, permissions (`chmod`, `chown`), processes (`ps`, `top`, `kill`)
- Networking commands: `ping`, `netstat`, `curl`, `ss`
- Bash scripting: variables, loops, conditionals
- Git & GitHub: commits, branches, merges, pull requests

### 🛠 Practice Tasks
- [ ] Write a Bash script to back up `/var/log` daily
- [ ] Create 3+ automation scripts
- [ ] Create a GitHub repo for scripts & practice branching/merging

### ✅ Milestones
- [ ] Linux basics mastered  
- [ ] Bash scripting projects committed  
- [ ] Git workflow practiced  

---

## 📅 Month 2 – Cloud & Networking
**Goal:** Learn cloud basics (AWS) and networking concepts.

### 📌 Topics
- AWS: EC2, S3, IAM, VPC basics
- Networking: IP, DNS, HTTP/HTTPS, firewalls
- AWS Security Groups & NACLs

### 🛠 Practice Tasks
- [ ] Create IAM user with least-privilege policy
- [ ] Launch EC2 instance and install Apache/Nginx
- [ ] Host a static website on S3

### ✅ Milestones
- [ ] EC2, S3, IAM basic setup done  
- [ ] Static website live on AWS S3  
- [ ] Networking basics documented in repo  

---

## 📅 Month 3 – CI/CD + Docker
**Goal:** Automate builds and deployments.

### 📌 Topics
- Jenkins: installation, pipelines (Freestyle & Declarative)
- GitHub Actions: workflow YAML, triggers
- Docker: images, containers, Dockerfile, volumes, networks

### 🛠 Practice Tasks
- [ ] Dockerize a Node.js or Python app
- [ ] Create Jenkins pipeline to build & run Docker image
- [ ] Create GitHub Actions workflow for automated builds

### ✅ Milestones
- [ ] Dockerized app committed  
- [ ] Jenkins pipeline configured  
- [ ] GitHub Actions workflow working  

---

## 📅 Month 4 – Kubernetes + IaC
**Goal:** Deploy applications at scale with Kubernetes & Terraform.

### 📌 Topics
- Kubernetes: pods, deployments, services, ingress, ConfigMaps, secrets
- Helm: chart basics
- Terraform: providers, resources, variables

### 🛠 Practice Tasks
- [ ] Deploy app to Kubernetes (Minikube/k3s)
- [ ] Use Helm chart for deployment
- [ ] Create Terraform script to deploy EC2 & S3

### ✅ Milestones
- [ ] Kubernetes deployment working  
- [ ] Helm chart committed  
- [ ] Terraform AWS infra created  

---

## 📅 Month 5 – Monitoring + Security
**Goal:** Add observability and security scanning.

### 📌 Topics
- Monitoring: Prometheus & Grafana
- Logging: ELK stack or Loki
- Security: Trivy image scanning, SonarQube code analysis

### 🛠 Practice Tasks
- [ ] Install Prometheus + Grafana for Kubernetes
- [ ] Create dashboard to monitor CPU/memory
- [ ] Integrate Trivy in CI/CD pipeline

### ✅ Milestones
- [ ] Grafana dashboard live  
- [ ] Image scans in CI/CD logs  
- [ ] Logging configured  

---

## 📅 Month 6 – End-to-End Project
**Goal:** Combine all skills into one portfolio project.

### 📌 Project
**Deploy a Full-Stack Application on AWS with:**
- GitHub Actions/Jenkins CI/CD
- Docker & Kubernetes
- Terraform provisioning
- Helm deployment
- Prometheus/Grafana monitoring
- Trivy security scans

### 🛠 Steps
1. Store code in GitHub
2. Build Docker image via CI/CD
3. Provision AWS EKS via Terraform
4. Deploy app via Helm
5. Monitor with Prometheus & Grafana
6. Scan images with Trivy

### ✅ Milestones
- [ ] Full project deployed on AWS  
- [ ] Architecture diagram added to repo  
- [ ] All configs/scripts committed  

---

## 📂 Suggested Repo Structure

