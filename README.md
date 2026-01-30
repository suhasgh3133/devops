# DevOps Interview Preparation – Complete Topic-wise Roadmap

This document contains a **comprehensive, topic-wise list of DevOps interview questions and learning areas**, covering Linux, Networking, Programming, CI/CD, Containers, Kubernetes, Cloud, Security, and more.

---

## 1. Linux Fundamentals

### Basics
- History of Operating Systems
- What is Linux Standard Base (LSB)?
- Popular Linux Distributions
- Linux boot process (Power ON → Login Prompt)

### Filesystem & Permissions
- What is an inode?
- Linux file types
- Hard links vs Symbolic links
- What happens when a hard link is removed?
- What is sticky bit?
- What happens if you delete the root user?
- What is `chroot`?
- What is the `/proc` filesystem?

### Memory & Processes
- Memory types in Linux
- What is virtual memory?
- What is swap space?
- What is a zombie process?
- What is OOM and OOM Killer? How does it work?
- What is kernel panic?

### Process & System Monitoring
- Linux process monitor (`top`) – explain all fields
- What is load average?
- What are cgroups?

### Commands & Scenarios
- What is `nohup` used for?
- Restore a deleted bash script that is still running
- Imagine you ran `chmod -x /bin/chmod` – how do you fix it?

### Storage
- What is RAID?

---

## 2. Networking & Security

### Networking Basics
- What is NAT?
- What is VLAN?
- What is ARP?
- TCP/IP layers
- Compare OSI vs TCP/IP model
- TCP 3-way handshake

### DNS & Connectivity
- What is DNS?
- DNS records: SOA, PTR, A, MX, CNAME
- How to check routing table in Linux?
- Server1 can’t reach Server2 – possible reasons
- How to check all open ports on a server?

### Remote Access
- What is SSH and how does it work?

---

## 3. Programming & Scripting

### Bash Scripting
- How to check if the last command was successful?
- What is a function? How to write one?
- Loops in Bash
- Compare two strings in Bash
- Print all array elements with indexes
- Print numbers 1 to 10 using a loop
- How to debug a shell script?

### Python
- Python for sysadmins
- How to compile a Python application?
- What is PEP 8 and why is it important?

---

## 4. Databases

- What is SQL?
- SQL vs NoSQL
- Tables and fields
- What is an index?
- What is a primary key?
- What is database replication?
- What is DynamoDB?

---

## 5. Version Control (GIT)

### Basics
- What is Git?
- Benefits of Git

### Commands & Concepts
- `git pull` vs `git fetch`
- `git reset` vs `git revert`
- What is `git rebase`?
- How to reset the last commit?

### Workflows
- Dev / Test / Production workflow using Git
- Git branching strategies (GitFlow, trunk-based)
- Monorepo vs Polyrepo
- Code review best practices

---

## 6. DevOps Fundamentals

### Configuration Management
- Ansible tutorials
- Salt tutorials
- Puppet tutorials

### CI/CD
- What is Continuous Integration?
- What is Continuous Delivery?
- What is Continuous Deployment?
- Benefits of CI/CD
- Describe a simple CI/CD pipeline
- Deployment strategies
- Jenkins tutorials
- Kubernetes-native CI/CD

---

## 7. Containerization & Orchestration

### Containers & Docker
- What is a container?
- Containers vs Virtual Machines
- What is Docker?
- Docker architecture
- Docker image vs container
- Dockerfile & best practices
- Docker Compose
- Multi-stage builds
- RUN vs CMD vs ENTRYPOINT
- ADD vs COPY
- Docker registry
- Docker volumes
- Docker namespaces
- History of containers (chroot, LXC)

### Kubernetes Basics
- What is Kubernetes?
- Why container orchestration?
- Kubernetes architecture (Control Plane & Workers)
- Pods, Deployments, Services, Ingress
- Namespaces
- ConfigMaps & Secrets
- StatefulSets & use cases
- DaemonSets
- Persistent Volumes & Storage Classes
- Helm

### Kubernetes Advanced
- Resource limits & requests
- Kubernetes networking model
- Init containers
- Probes (liveness, readiness, startup)
- kubelet
- kubectl
- CNI
- Headless services
- CPU & memory units in Pod specs
- Deploying stateful applications
- Deployment strategies (blue-green, canary, rolling)
- etcd & etcd backup
- Custom Resource Definitions (CRDs)
- NodePort vs ClusterIP

---

## 8. Monitoring, Logging & SRE

- What is observability?
- Prometheus
- Prometheus architecture
- Grafana
- ELK Stack
- Distributed tracing (Jaeger, Zipkin)
- Log aggregation vs streaming
- SLI, SLO, SLA
- What is APM?

---

## 9. GitOps

- What is GitOps?
- GitOps tools (ArgoCD, Flux)

---

## 10. Security & Compliance (DevSecOps)

- What is DevSecOps?
- Container security scanning (Trivy, Clair, Aqua)
- SAST vs DAST
- Secret management (Vault, AWS Secrets Manager)
- Kubernetes RBAC
- Admission Controllers
- Network Policies
- Pod Security Policies / Pod Security Standards

---

## 11. Service Mesh

- What is a service mesh?
- Istio overview
- Linkerd overview

---

## 12. Chaos Engineering

- What is Chaos Engineering?
- Tools: Chaos Monkey, Gremlin, Litmus

---

## 13. Infrastructure as Code (IaC)

### Terraform
- Terraform tutorials
- Terraform interview questions
- Terraform modules
- `.terraform` directory
- `terraform init`
- Terraform backends & recommended backends
- Terraform lock file

### CloudFormation
- AWS CloudFormation basics

---

## 14. Cloud Computing Fundamentals

- What is cloud computing?
- IaaS, PaaS, SaaS
- Private, public, hybrid cloud
- Multi-cloud
- Cloud services
- Serverless computing
- Cloud-native
- Elasticity
- Availability zones
- Regions

---

## 15. AWS (Amazon Web Services)

- EC2
- S3
- VPC
- Lambda
- RDS
- ECS & EKS
- CloudFormation
- IAM
- CloudWatch
- Route53
- ELB
- Auto Scaling
- CloudFront
- SNS & SQS
- KMS
- Secrets Manager
- DynamoDB
- ElastiCache
- Step Functions
- AWS Organizations

---

## 16. Azure (Microsoft Azure)

- Virtual Machines
- App Service
- Blob Storage
- Azure Functions
- AKS
- ARM
- Azure Active Directory
- Azure DevOps
- Azure Monitor
- Azure SQL Database
- Cosmos DB
- Key Vault
- Azure Load Balancer
- Azure CDN

---

## 17. GCP (Google Cloud Platform)

- Compute Engine
- Cloud Storage
- Cloud Functions
- GKE
- Cloud Run
- BigQuery
- Cloud SQL
- Cloud Spanner
- Firestore
- Pub/Sub
- Cloud IAM
- Cloud Monitoring
- Load Balancing
- Cloud CDN
- VPC
- Cloud Build
- Anthos

---

## 18. Other Cloud & Platforms

- DigitalOcean
- OpenStack tutorials

---

## 19. Books & Learning Resources

- Brendan Gregg – Systems Performance Blog  
  http://www.brendangregg.com/blog/index.html
- Systems Performance Book – Brendan Gregg  
  http://www.brendangregg.com/sysperfbook.html
- The Phoenix Project
- Google SRE Books
- Linux System Administration Handbook – Evi Nemeth
- The DevOps Handbook
- Continuous Delivery – Jez Humble

---

## ✅ How to Use This README

- Treat each section as a **checkpoint**
- Add notes/examples under each topic
- Convert this into a **GitHub DevOps learning repo**
- Ideal for **₹15–30 LPA DevOps / SRE roles**

---
