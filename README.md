## 🚀 DevOps End-to-End Project
This is a full-fledged DevOps project that sets up and executes a CI/CD pipeline for deploying a containerized application to a Kubernetes cluster with code quality, security scanning, and monitoring. The entire project is structured across various phases to simulate a real-world corporate DevOps setup.

## 🧭 Architecture Overview

The architecture represents a complete automated CI/CD pipeline:

Code is pushed to GitHub

Jenkins pulls code and runs build/test with Maven

Code is scanned using SonarQube and Trivy

Artifacts are pushed to Nexus

Docker images are built, scanned, and deployed to Kubernetes

Notifications are sent and monitoring is performed using Prometheus and Grafana

Jira is used for task management


![image](https://github.com/user-attachments/assets/16b440fc-256d-45d0-b2dc-50a0b244a5da)


## 🧩 Phases of a Corporate DevOps Pipeline
The project is divided into multiple structured phases that mirror corporate workflows:

Infrastructure Setup – Creating a Kubernetes cluster and supporting VMs

Security Hardening – Scanning Kubernetes and container images

DevOps Toolchain Setup – Jenkins, SonarQube, Nexus, Trivy

CI/CD Pipeline – Automating the process from code push to deployment

Monitoring & Alerts – Using Prometheus, Grafana, Email notifications

Documentation & Tracking – Using Jira and GitHub


