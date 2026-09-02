# Real-Time DevOps Project

## Project Overview

End-to-end DevOps project implementing CI/CD, containerization,
Kubernetes, AWS infrastructure, security scanning, monitoring,
and GitOps.

## Tools & Technologies

- Git
- GitHub
- Jenkins
- Maven
- Docker
- Kubernetes
- AWS
- Terraform
- Trivy
- Prometheus
- Grafana
- Argo CD

## Project Architecture

Developer
    |
    v
GitHub
    |
    v
Jenkins
    |
    +---- Maven Build
    |
    +---- Unit Tests
    |
    +---- Trivy Security Scan
    |
    +---- Docker Build
    |
    v
Container Registry
    |
    v
Kubernetes / AWS EKS
    |
    +---- Deployment
    +---- Service
    +---- Ingress
    +---- HPA
    |
    v
Prometheus
    |
    v
Grafana
