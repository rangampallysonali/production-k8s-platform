# Production Kubernetes Platform on AWS EKS

## Overview
This project builds a production-style Kubernetes platform on AWS EKS using Terraform, ArgoCD, Helm, Prometheus, Grafana, and Trivy.

The platform deploys Gitea, a self-hosted Git service, as a real-world internal developer tool.

## Architecture
Terraform provisions AWS infrastructure and EKS.
ArgoCD deploys applications using GitOps.
Helm charts manage Kubernetes applications.
Prometheus and Grafana provide monitoring.
Trivy scans infrastructure code for security issues.

## Tools Used
- AWS EKS
- Terraform
- Kubernetes
- Helm
- ArgoCD
- Prometheus
- Grafana
- GitHub Actions
- Trivy

## Features
- Infrastructure as Code with Terraform
- Managed Kubernetes cluster on AWS EKS
- GitOps deployment using ArgoCD
- Real-world application deployment using Helm
- Monitoring stack using Prometheus and Grafana
- CI checks for Terraform validation
- Security scanning using Trivy
- LoadBalancer services for external access

