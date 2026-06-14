# 🚀 DevOps / Site Reliability Engineering Portfolio

**Target Role:** DevOps Engineer / Site Reliability Engineer (SRE)  
**Location:** Seoul, South Korea (Open to Remote / Relocation)

I am a **Software Engineer transitioning into DevOps/SRE**, combining a solid foundation in backend development with hands-on experience in designing, automating, and operating **highly available, production-grade systems** across cloud infrastructure, CI/CD pipelines, and Kubernetes platforms.

My engineering philosophy centers on **infrastructure reliability, reproducible automation, and metrics-driven troubleshooting**, rather than isolated, tool-only demonstrations. Driven by a "Life-long Learner" mindset, I actively bridge the gap between application logic and robust system architecture.

---

## 🏆 Key Credentials & Technical Highlights

* **Certifications:**
  * ✅ **AWS Certified Solutions Architect – Associate (SAA)** (Earned: Jun 2026)
  * ✅ **CKA – Certified Kubernetes Administrator** (Earned: Nov 2025)
* **Core Track Record:** Successfully managed **1,000% traffic spikes** for production-level administrative platforms, maintaining **99.9% availability** and reducing server resource consumption by **80%** through proactive performance tuning.
* **Core Toolchain:** Kubernetes • Docker • AWS • Terraform • Ansible • Jenkins • Linux • GitHub Actions
* **SRE Expertise:** Infrastructure as Code (IaC), Observability (Prometheus, Grafana, Datadog), CI/CD Automation, Cluster Micro-segmentation, and Network Optimization.

---

## ⭐ Featured DevOps / SRE Case Studies

These case studies reflect **how real-world cloud-native systems are systematically built, delivered, and operated**:
**Cloud Infrastructure (IaC) → Automated Delivery (CI/CD) → Platform Orchestration (K8s) → Full-Stack Observability**.

---

### 1️⃣ Cloud Infrastructure Case Study — Terraform + Ansible (AWS)

📂 `infra-as-code/aws-terraform-ansible-ec2`

**What this shows**
- End-to-end Infrastructure-as-Code (IaC) workflow on AWS guided by the **AWS Well-Architected Framework**.
- Clean separation of concerns: **Terraform** for mutable cloud resource orchestration and **Ansible** for post-provisioning configuration management.
- Secure infrastructure design utilizing restricted SSH key handling and strict Security Group IP constraints.

**Key skills demonstrated**
- **AWS Networking & Security:** Designing secure VPC topologies, multi-AZ subnets, routing tables, and security groups.
- **Stateful IaC Management:** Managing infrastructure state, provider configurations, and declarative modules via Terraform.
- **Configuration Management:** Writing reproducible Ansible playbooks over secure SSH channels to deploy containerized workloads.
- **Infrastructure Hygiene:** Enforcing full lifecycle discipline (Create ➔ Configure ➔ Validate ➔ Cost-aware Teardown).

🔗 **View Project:** [infra-as-code/aws-terraform-ansible-ec2](https://github.com/bestcoolestp/DevOps-Portfolio/tree/main/infra-as-code/aws-terraform-ansible-ec2)

---

### 2️⃣ CI/CD Case Study — Jenkins ➔ Kubernetes (kind)

📂 `ci-cd/jenkins-kind-cicd`

**What this shows**
- A robust, containerized continuous integration and delivery pipeline using Jenkins.
- Automated Docker image orchestration, secure registry delivery, and automated rollouts to a local Kubernetes environment.
- Defensive deployment practices, including automated port-forward smoke testing and declarative health verifications.

**Key skills demonstrated**
- **Pipeline Architecture:** Designing multi-stage declarative Jenkins pipelines with strict error handling and cleanup stages.
- **Containerized Build Environments:** Operating Jenkins within distributed container ecosystems to ensure build isolation.
- **Real-World Troubleshooting:** Debugging complex TLS handshakes, `kubeconfig` multi-context routing, and local network endpoint exposures.

🔗 **View Project:** [ci-cd/jenkins-kind-cicd](https://github.com/bestcoolestp/DevOps-Portfolio/tree/main/ci-cd/jenkins-kind-cicd)

---

### 3️⃣ Kubernetes Reliability Case Study — Application Scaling & Self-Healing

📂 `k8s-projects/sample-app-deploy`

**What this shows**
- Native workload design and deployment strategies on Kubernetes to guarantee service continuity.
- High-availability configurations using ReplicaSets, proper network abstraction with Services, and environment isolation via Namespaces.
- Runbook-style documentation designed for standard on-call engineering execution.

**Key skills demonstrated**
- **Workload Engineering:** Authoring deterministic, declarative YAML manifests for multi-replica microservices.
- **Service Networking:** Mapping internal cluster communications and external load balancing policies.
- **Resilience Validation:** Verifying horizontal pod auto-scaling and proving the cluster’s native self-healing capabilities during node pressure simulations.

🔗 **View Project:** [k8s-projects/sample-app-deploy](https://github.com/bestcoolestp/DevOps-Portfolio/tree/main/k8s-projects/sample-app-deploy)

---

### 4️⃣ Observability Case Study — Prometheus + Grafana (kube-prometheus-stack)

📂 `observability`

**What this shows**
- Deep production visibility and telemetry instrumentation for a cloud-native Node.js service.
- Dynamic metric collection architecture using Kubernetes-native operators (`ServiceMonitor`).
- Production-oriented Grafana dashboard implementation reflecting industry-standard SLI/SLO metrics (Latency, Traffic, Errors, Saturation).
- **Live Failure Drill:** Executing intentional chaos injections (pod failures) to visually audit cluster self-healing and alerting mechanics in real time.

**Key skills demonstrated**
- **Metrics Instrumentation:** Exposing custom application runtime telemetry using `prom-client` histograms.
- **Cloud-Native Scraping:** Operating Helm-managed `kube-prometheus-stack` and configuring dynamic target discovery.
- **Observability Engineering:** Correlating infrastructure resource consumption metrics with application-level latency anomalies.

🔗 **View Project:** [observability](https://github.com/bestcoolestp/DevOps-Portfolio/tree/main/observability)

---

## 📈 Architectural Research & Deep-Dives

I treat DevOps/SRE as a discipline of structural engineering and continuous system-level optimization. I maintain structured engineering logs to evaluate cloud-native patterns and architectural trade-offs.

* **AWS Cloud Architecture Deep-Dives:** [View AWS Engineering Logs](https://github.com/bestcoolestp/DevOps-Portfolio/tree/main/learning-logs/aws-saa)  
  *Focus: Deep dive into highly available multi-region topologies, IAM least-privilege policies, secure VPC peering, and CloudFront/Route 53 global latency acceleration.*

---

## 📂 Full DevOps / SRE Portfolio Repository

For the complete and comprehensive set of configurations, infrastructure templates, and automated pipelines, please explore the primary repository root:

🔗 **Explore Main Codebase:** [DevOps-Portfolio](https://github.com/bestcoolestp/DevOps-Portfolio)

---

## 📚 Previous Software Engineering Experience (Archive)

Prior to dedicating my focus to DevOps/SRE, I spent 2+ years working as a Professional Software Engineer, building high-concurrency systems and optimizng application codebases. This application-level depth gives me a distinct advantage in tracing production bugs back to the source code.

📂 **Archived Development Repositories:** [Full-Stack & Software Projects](https://github.com/bestcoolestp?tab=repositories)

*(Tech Stack Utilized: C# .NET, ASP.NET MVC, LINQ, Entity Framework, Java, Spring, MySQL, IIS, Apache Tomcat, JavaScript, jQuery, Python, etc.)*

---

## 🔗 Connect with me

- **LinkedIn:** [linkedin.com/in/sang-bong-lee-devops/](https://www.linkedin.com/in/sang-bong-lee-devops/)
- **GitHub:** [github.com/bestcoolestp](https://github.com/bestcoolestp)
- **Email:** bestcoolest@gmail.com
