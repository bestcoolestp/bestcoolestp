# 🚀 Production Systems Engineering Portfolio

**Target Role:** Production Systems Engineer / DevOps Engineer / Site Reliability Engineer  
**Location:** Seoul, South Korea (Open to Remote / Relocation)

I am a **Production Systems Engineer** with a software engineering background, experienced in operating production platforms, investigating real-world incidents, and improving system reliability through automation and cloud-native engineering
My primary interests are **production reliability, infrastructure automation, Kubernetes operations, CI/CD, observability, cloud infrastructure, data integrity, and incident response**.

---

## 🏆 Key Credentials & Technical Highlights

- **Certifications**
  - ✅ **AWS Certified Solutions Architect – Associate (SAA)** — Jun 2026
  - ✅ **CKA – Certified Kubernetes Administrator** — Nov 2025

- **Production Engineering Experience**
  - Investigated and remediated production synchronization failures involving external APIs, legacy business workflows, and database consistency.
  - Operated and maintained university SaaS platforms built with ASP.NET MVC, Java, Spring, MySQL, IIS, and Apache Tomcat.
  - Used historical database backups, structured logs, SQL validation, and source-code tracing to reproduce production defects.

- **Core Toolchain**
  - Kubernetes • Docker • AWS • Terraform • Helm • Jenkins • Linux • GitHub Actions • Prometheus • Grafana

- **Core Engineering Areas**
  - Infrastructure as Code
  - Kubernetes Operations
  - Production Incident Response
  - Observability
  - CI/CD Automation
  - Linux Administration
  - Cloud Infrastructure
  - Data Integrity Investigation
  - Legacy System Modernization

---

## 🆕 Kubernetes Troubleshooting Playbook

📂 `k8s-troubleshooting`

### What this shows

- Systematic troubleshooting of realistic Kubernetes incidents.
- Root cause analysis using `kubectl describe`, Events, container logs, metrics, and resource inspection.
- Step-by-step investigation workflows rather than command memorization.
- Emphasis on failure isolation, evidence collection, and operational recovery.

### Key skills demonstrated

- Kubernetes Troubleshooting
- Root Cause Analysis
- Incident Response
- Production Debugging
- Cluster Operations
- Reliability Engineering

### Current Scenarios

- ✅ ImagePullBackOff
- ✅ Pending Pod — Insufficient CPU
- ✅ Pending Pod — Untolerated Taint
- ✅ CrashLoopBackOff — Nginx Permission Denied
- ✅ ContainerCreating — hostPath Not a Directory
- ✅ Pod Creation — ResourceQuota Exceeded
- ✅ PodInitializing — Init Container Command Not Found
- ✅ Deployment Creation — Selector/Label Mismatch
- ✅ HPA — Metrics Server Unavailable
- ✅ DaemonSet - Control Plane Taint
- ✅ Service Connectivity
- ✅ pending-pod-cordoned-node
- ✅ node-diskpressure-pod-eviction
- ✅ kubeconfig-wrong-api-server
- ✅ pod-priority-preemption
- 🚧 Ingress
- 🚧 NetworkPolicy
- 🚧 PVC Issues

🔗 **View Project:** [k8s-troubleshooting](https://github.com/bestcoolestp/DevOps-Portfolio/tree/main/k8s-troubleshooting)

---

## ⭐ Featured DevOps / SRE Case Studies

These case studies show how I approach production systems across the full engineering lifecycle:

**Infrastructure → Delivery → Runtime Operations → Observability → Incident Response → Reliability Improvement**

---

## 1️⃣ Production Incident Case Study — HTTP 500 Member Synchronization

📂 `production-incidents/http500-member-sync`

### What this shows

- Investigation and resolution of a production member synchronization failure caused by intermittent HTTP 500 responses from an external Student Information API.
- Root cause analysis using structured logging, SQL validation, API response inspection, and historical execution records.
- Defensive JSON validation and resilient synchronization logic to prevent malformed responses from terminating the entire synchronization process.

### Key skills demonstrated

- Production Incident Response
- Root Cause Analysis
- Reliability Engineering
- REST API Troubleshooting
- Defensive Programming
- Structured Logging
- ASP.NET MVC
- C#
- MySQL

### Highlights

- Identified malformed API responses such as `status=500` and empty `data` payloads as the true source of synchronization failures.
- Added validation, retry handling, and graceful failure behavior.
- Prevented malformed pages from terminating the entire synchronization process.
- Successfully synchronized 34,000+ member records after remediation.

🔗 **View Case Study:** [production-incidents/http500-member-sync](https://github.com/bestcoolestp/DevOps-Portfolio/tree/main/production-incidents/http500-member-sync)

---

## 2️⃣ Production Incident Case Study — Oracle-to-API Data Integrity Regression

📂 `production-incidents/api-sync-data-integrity`

### What this shows

- Investigation of a production data integrity regression introduced during migration from direct Oracle synchronization to REST API-based member synchronization.
- Historical database comparison, SQL validation, legacy workflow tracing, and application-level root cause analysis.
- Identification of a missing downstream business rule that left inactive members assigned to active safety education schedules.
- Permanent remediation with active-schedule cleanup logic and business-result logging.

### Key skills demonstrated

- Production Incident Response
- Root Cause Analysis
- Data Integrity Investigation
- REST API Migration
- Legacy System Analysis
- Functional Parity Validation
- SQL Troubleshooting
- Historical Database Comparison
- Operational Logging
- ASP.NET MVC
- C#
- MySQL

### Highlights

- Identified a functional parity gap between legacy Oracle and REST API synchronization workflows.
- Confirmed inconsistent states between current member status and education-target status.
- Reproduced the issue using historical production database backups.
- Distinguished a query-level workaround from the actual data-integrity defect.
- Restored the missing active-schedule cleanup workflow.
- Preserved completed education history and avoided modifying completed schedules.
- Added synchronization result logging for future operational verification.

🔗 **View Case Study:** [production-incidents/api-sync-data-integrity](https://github.com/bestcoolestp/DevOps-Portfolio/tree/main/production-incidents/api-sync-data-integrity)

---

## 3️⃣ Cloud Infrastructure Case Study — Terraform + Ansible on AWS

📂 `infra-as-code/aws-terraform-ansible-ec2`

### What this shows

- End-to-end Infrastructure-as-Code workflow on AWS.
- Clear separation of responsibilities between Terraform and Ansible.
- Secure infrastructure design using restricted SSH access and tightly scoped Security Group rules.
- Full infrastructure lifecycle from provisioning to validation and cost-aware teardown.

### Key skills demonstrated

- **AWS Networking & Security**
  - VPC design
  - Multi-AZ subnets
  - Routing tables
  - Internet gateway configuration
  - Security Groups

- **Infrastructure as Code**
  - Terraform providers
  - State management
  - Declarative resource creation
  - Reusable infrastructure configuration

- **Configuration Management**
  - Ansible playbooks
  - Secure SSH execution
  - Application deployment
  - Reproducible server configuration

- **Infrastructure Hygiene**
  - Create
  - Configure
  - Validate
  - Document
  - Tear down

🔗 **View Project:** [infra-as-code/aws-terraform-ansible-ec2](https://github.com/bestcoolestp/DevOps-Portfolio/tree/main/infra-as-code/aws-terraform-ansible-ec2)

---

## 4️⃣ CI/CD Case Study — Jenkins ➔ Kubernetes with kind

📂 `ci-cd/jenkins-kind-cicd`

### What this shows

- Containerized CI/CD workflow using Jenkins.
- Automated Docker image build and registry delivery.
- Automated application deployment to a local Kubernetes cluster.
- Defensive deployment practices with smoke testing and health verification.

### Key skills demonstrated

- **Pipeline Architecture**
  - Multi-stage Jenkins pipelines
  - Failure handling
  - Cleanup stages
  - Reproducible delivery steps

- **Containerized Build Environments**
  - Jenkins in Docker
  - Isolated build execution
  - Docker image lifecycle management

- **Kubernetes Delivery**
  - Declarative manifests
  - Rollout verification
  - Port-forward smoke tests
  - Health validation

- **Troubleshooting**
  - TLS handshake issues
  - Registry authentication
  - `kubeconfig` context routing
  - Local network endpoint exposure

🔗 **View Project:** [ci-cd/jenkins-kind-cicd](https://github.com/bestcoolestp/DevOps-Portfolio/tree/main/ci-cd/jenkins-kind-cicd)

---

## 5️⃣ Kubernetes Reliability Case Study — Application Scaling & Self-Healing

📂 `k8s-projects/sample-app-deploy`

### What this shows

- Native Kubernetes workload design for availability and continuity.
- Multi-replica application deployment.
- Service-based network abstraction.
- Namespace-based environment isolation.
- Runbook-style documentation for operational execution.

### Key skills demonstrated

- **Workload Engineering**
  - Deployments
  - ReplicaSets
  - Declarative YAML
  - Multi-replica services

- **Service Networking**
  - ClusterIP
  - Port mapping
  - Internal service discovery
  - External access patterns

- **Reliability Validation**
  - Pod self-healing
  - Replica recovery
  - Scaling verification
  - Failure simulation

🔗 **View Project:** [k8s-projects/sample-app-deploy](https://github.com/bestcoolestp/DevOps-Portfolio/tree/main/k8s-projects/sample-app-deploy)

---

## 6️⃣ Observability Case Study — Prometheus + Grafana

📂 `observability`

### What this shows

- Production-style monitoring for a cloud-native Node.js service.
- Kubernetes-native metrics discovery through `ServiceMonitor`.
- Helm-managed `kube-prometheus-stack`.
- Grafana dashboards based on core SRE signals.
- Failure drills to validate alerting and self-healing behavior.

### Key skills demonstrated

- **Metrics Instrumentation**
  - Application-level metrics
  - Runtime telemetry
  - Histograms
  - Custom metrics with `prom-client`

- **Cloud-Native Monitoring**
  - Prometheus Operator
  - `ServiceMonitor`
  - Helm
  - Kubernetes target discovery

- **Observability Engineering**
  - Latency
  - Traffic
  - Errors
  - Saturation
  - Resource correlation

- **Failure Validation**
  - Intentional pod failure
  - Recovery observation
  - Dashboard verification
  - Alert behavior review

🔗 **View Project:** [observability](https://github.com/bestcoolestp/DevOps-Portfolio/tree/main/observability)

---

## 📈 Architectural Research & Engineering Deep-Dives

I treat DevOps and SRE as disciplines of systems thinking, operational evidence, and continuous reliability improvement.

I maintain structured engineering logs to document architectural trade-offs, service behavior, failure modes, and cloud design decisions.

### AWS Cloud Architecture Deep-Dives

📂 `learning-logs/aws-saa`

Focus areas include:

- Highly available architectures
- Multi-AZ and multi-region design
- IAM least privilege
- Secure VPC networking
- Route 53 routing strategies
- CloudFront distribution patterns
- Disaster recovery
- Cost-aware architecture
- AWS Well-Architected principles

🔗 **View AWS Engineering Logs:** [learning-logs/aws-saa](https://github.com/bestcoolestp/DevOps-Portfolio/tree/main/learning-logs/aws-saa)

---

## 📂 Full DevOps / SRE Portfolio Repository

This repository contains:

- Infrastructure templates
- Kubernetes manifests
- CI/CD pipelines
- Monitoring configurations
- Troubleshooting playbooks
- Production incident reports
- Architecture notes
- Learning logs
- Operational runbooks

🔗 **Explore Main Codebase:** [DevOps-Portfolio](https://github.com/bestcoolestp/DevOps-Portfolio)

---

## 📚 Previous Software Engineering Experience

Before focusing on DevOps, SRE, and Production Systems Engineering, I worked on production web applications built with C#, ASP.NET MVC, Java, Spring, MySQL, IIS, and Apache Tomcat.

This software engineering background helps me trace infrastructure and operational failures across multiple layers:

```text
User Interface
      ↓
Application Logic
      ↓
API Integration
      ↓
Database
      ↓
Operating System
      ↓
Infrastructure
```

### Application and Platform Technologies

- C# / .NET
- ASP.NET MVC
- LINQ
- Entity Framework
- Java
- Spring MVC
- MyBatis
- MySQL
- IIS
- Apache Tomcat
- JavaScript
- jQuery
- Python

📂 **Archived Development Repositories:** [Full-Stack & Software Projects](https://github.com/bestcoolestp?tab=repositories)

---

## 🔗 Connect With Me

- **LinkedIn:** [linkedin.com/in/sang-bong-lee-devops](https://www.linkedin.com/in/sang-bong-lee-devops/)
- **GitHub:** [github.com/bestcoolestp](https://github.com/bestcoolestp)
- **Email:** bestcoolest@gmail.com
