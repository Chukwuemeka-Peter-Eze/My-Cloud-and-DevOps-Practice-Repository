# My-Cloud-and-DevOps-Practice-Repository

My Cloud and DevOps Practice Repository showcases hands-on labs, scripts, and projects across Linux, Python, AWS, Terraform, Docker, Kubernetes, CI/CD, Monitoring, and Security. It serves as a structured space to document learning, apply concepts, and build strong, industry-ready Cloud and DevOps skills.

**Purpose**: Learn → Practice → Document → Share → Master

## Repository Structure / How to use this repo
  * Each `day-XX-topic-name/` folder contains:
      * `notes.md` → concise learnings, commands, explanations.
      * practice artifacts → scripts, configs, Dockerfiles, manifests, Terraform, workflow examples.
      * optional `examples/` subfolder for runnable demos.

* **Active CI/CD workflows** live in `.github/workflows/` at the repository root.
* **Polished projects** will be hosted in separate repositories.

## My Cloud and DevOps Tech Stack

**Operating Systems and Shell**
* Linux (Ubuntu, Debian, CentOS/RHEL basics)
* Bash shell scripting, basic Python for automation

**Version Control**
* Git (branching, rebasing, pull requests) and GitHub (profiles, releases)

**Containers and Orchestration**
* Docker (images, Dockerfile best practices, Compose)
* Kubernetes (pods, deployments, services, ingress, volumes)
* Helm, kustomize, eksctl/minikube

**Cloud (Primary: AWS)**
* Core services: EC2, S3, VPC, IAM, RDS, ELB/ALB, Route 53
* Serverless: Lambda, API Gateway
* Managed K8s: EKS (concepts)
* Cloud CLI: AWS CLI, with exposure to Azure/GCP CLI

**Infrastructure as Code / Provisioning**
* Terraform (state, modules, providers)
* Ansible (configuration management and provisioning)
* CloudFormation (overview)

**CI/CD and Automation**
* GitHub Actions (workflows, triggers, secrets), Jenkins basics
* Pipeline strategies (blue-green, canary), artifact registries (ECR, Docker Hub)

**Monitoring, Logging and Observability**
* Prometheus, Grafana, Alertmanager
* ELK stack or OpenSearch for logging
* Distributed tracing / OpenTelemetry

**Security and DevSecOps**
* IAM best practices, least privilege patterns
* Secrets management: HashiCorp Vault, AWS Secrets Manager
* Scanning: Trivy, Snyk, static analysis tools, container scanning

**Networking and Infrastructure**
* TCP/IP basics, subnetting, routing, NAT, firewall rules
* Load balancers, DNS, CDN basics

**Databases and Queues**
* Relational: MySQL/Postgres (RDS)
* NoSQL: DynamoDB/Cassandra basics
* Message queues: RabbitMQ, Kafka basics

**Other essential tools**
* kubectl, helm, terraform, docker, docker-compose, awscli
* Monitoring tooling: node-exporter, kube-state-metrics
* CI helpers: make, shell scripts, docker buildx

**Soft skills / Practices**
* Infrastructure testing (unit and integration), GitOps practices, documentation, writing clear READMEs and `notes.md` files

**Highlighted Mini-Projects**
* Terraform AWS VPC Setup
* Dockerized Python App with CI/CD
* Kubernetes Deployment with Ingress
* GitHub Actions CI/CD Pipeline
* Prometheus + Grafana Monitoring Lab

**Future Plans**
* Add Jenkins pipelines for CI/CD.
* Expand Kubernetes with Helm and kustomize projects.
* Implement advanced monitoring with OpenTelemetry.
* Explore multi-cloud deployments (Azure & GCP).

**Final Note**
This repository is more than just practice, it represents my journey from beginner to Cloud and DevOps Engineer. Every folder, script, and project here is a step toward mastering the principles of automation, scalability, and reliability that power modern infrastructure.

If you’re a learner, feel free to fork and practice along.
If you’re a recruiter or hiring manager, this repo reflects my commitment, consistency, and ability to apply concepts in real-world scenarios.

Learning never stops, and this repository is living proof.
