<div align="center">

  <h1>DevSecOps CI/CD Pipeline for Cloud-Native Application</h1>

  <p>
    End-to-end DevOps implementation using AWS, Docker, Jenkins, SonarQube, Trivy, Prometheus, Grafana, Kubernetes, and ArgoCD.
  </p>
</div>

---

# Project Overview

This repository demonstrates how a DevOps Engineer can build, secure, deploy, monitor, and scale a production-grade frontend application using modern DevOps tools and cloud practices.

The goal is not only to run the application, but to automate the complete software delivery lifecycle.

---

# Tech Stack

| Category | Tools |
|--------|------|
| Cloud | AWS EC2 |
| CI/CD | Jenkins |
| Containers | Docker |
| Code Quality | SonarQube |
| Security Scanning | Trivy, OWASP Dependency Check |
| Monitoring | Prometheus, Grafana |
| Orchestration | Kubernetes |
| GitOps | ArgoCD |
| Source Control | GitHub |

---

# Responsibilities as DevOps Engineer

- Provision cloud infrastructure
- Containerize application
- Build CI/CD pipelines
- Implement DevSecOps scanning
- Automate deployments
- Configure observability stack
- Manage Kubernetes workloads
- Enable GitOps delivery
- Optimize uptime, security, and scalability

---

# Architecture Workflow

```text
Developer Push Code → GitHub → Jenkins Pipeline →
Code Scan → Dependency Scan → Docker Build →
Push to Registry → Deploy →
Prometheus Monitoring → Grafana Dashboard →
Kubernetes Scaling → ArgoCD GitOps
