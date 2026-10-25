<div align="center">

# Rahul Singh
### **Senior Cloud & DevSecOps Architect**
*Designing resilient, secure, and cost-optimized cloud platforms at enterprise scale.*

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&pause=1000&color=38BDF8&center=true&vCenter=true&random=false&width=650&lines=Azure+%26+AWS+Cloud+Architect+(5%2B+Years);Enterprise+Zero-Trust+DevSecOps;100%2B+Workloads+Migrated+to+Cloud;Modular+IaC+%7C+Terraform+Landing+Zones;FinOps+Strategist+%7C+28%25%2B+Cost+Optimization)](https://git.io/typing-svg)

<p align="center">
  <a href="#-about-me">About Me</a> •
  <a href="#-core-competencies">Competencies</a> •
  <a href="#-enterprise-architectures">Architectures</a> •
  <a href="#-devsecops-delivery-pipeline">DevSecOps Pipeline</a> •
  <a href="#-tech-stack">Tech Stack</a> •
  <a href="#-github-stats">Stats</a> •
  <a href="#-contact">Contact</a>
</p>

[![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)](https://azure.microsoft.com/)
[![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-web-services&logoColor=white)](https://aws.amazon.com/)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)](https://kubernetes.io/)
[![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)](https://terraform.io/)
[![DevSecOps](https://img.shields.io/badge/DevSecOps-Shift--Left-00C7B7?style=flat-square&logo=shield&logoColor=white)](#-devsecops-delivery-pipeline)
[![FinOps](https://img.shields.io/badge/FinOps-Cloud_Economics-10B981?style=flat-square&logo=google-cloud&logoColor=white)](#-enterprise-architectures)

---

</div>

## 👨‍💻 About Me

Senior Cloud & DevSecOps Architect with **5+ years of enterprise experience** architecting high-availability infrastructure, automated security guardrails, and mission-critical cloud solutions across **Microsoft Azure** and **AWS**.

Specialized in orchestrating end-to-end cloud adoption—from foundational **Cloud Adoption Framework (CAF)** Landing Zones to zero-downtime workload migrations, automated compliance pipelines, and strategic **FinOps** governance.

```yaml
profile:
  name: "Rahul Singh"
  role: "Senior Cloud & DevSecOps Architect"
  experience: "5+ Years"
  focus_areas:
    - "Enterprise Landing Zones (CAF & Well-Architected)"
    - "Shift-Left Security & Policy-as-Code"
    - "Multi-Cloud Infrastructure as Code (Terraform / Terragrunt)"
    - "Zero-Trust Networking & Micro-segmentation"
    - "FinOps & Cloud Economics"
  impact_highlights:
    workloads_migrated: "100+ Enterprise Applications"
    availability_sla: "99.99% Production Uptime"
    cloud_cost_reduction: "28%+ via FinOps Automation"
    security_standard: "CIS Benchmark & Zero-Trust Architecture"
```

---

## 🎯 Core Competencies

<table width="100%">
<tr>
<td width="50%" valign="top">

### ☁️ Cloud Architecture & Landing Zones
* **Enterprise Landing Zones:** Architected scalable Azure CAF & AWS multi-account governance models with strict subscription boundaries (`Platform`, `Corp`, `Online`, `Sandbox`).
* **Hub-and-Spoke Networking:** Centralized traffic inspection via Azure Firewall / NVAs, forced tunneling with UDRs, and 100% Private Endpoints for PaaS.
* **High Availability & Disaster Recovery:** Multi-region active-active architectures, Zone-Redundant Storage (ZRS/GRS), and aggressive RTO (< 1 hr) / RPO (< 15 min).

</td>
<td width="50%" valign="top">

### 🛡️ DevSecOps & Zero-Trust Governance
* **Shift-Left Security:** Integrated GitLeaks, Checkov, Trivy, and SonarQube directly into CI/CD pipelines to catch vulnerabilities pre-merge.
* **Identity & Access Management:** Entra ID Privileged Identity Management (PIM) with Just-In-Time (JIT) access, strict RBAC, and Managed Identities.
* **Policy-as-Code:** Enforced organizational compliance through Azure Policy and Open Policy Agent (OPA) with automated remediation.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚙️ Infrastructure as Code & Automation
* **Modular Terraform:** Author of enterprise-grade, reusable IaC modules with strict semantic versioning and automated documentation.
* **Drift Management:** Automated nightly CI pipelines running `terraform plan -detailed-exitcode` to catch and alert on out-of-band portal drift.
* **Configuration Management:** Automated VM baseline provisioning and hardening using Ansible and Cloud-Init.

</td>
<td width="50%" valign="top">

### 💰 FinOps & Cloud Economics
* **Waste Eradication:** Automated discovery and purge of unattached disks, idle public IPs, obsolete snapshots, and orphaned resources.
* **Commitment Planning:** Structural evaluation of 1-Year / 3-Year Reserved Instances (RI) and Savings Plans against steady-state baseline.
* **Telemetry Optimization:** Configured Azure Monitor Data Collection Rules (DCR) to filter noisy diagnostic logs, slashing ingestion costs.

</td>
</tr>
</table>

---

## 🏗️ DevSecOps Delivery Pipeline

An automated shift-left pipeline where every pull request is validated for syntax, security, cost impact, and compliance before touching cloud state:

```
  [ Feature Branch ]
          │
          ▼
  [ Automated Linting & Unit Tests ] ─── (tflint / terraform fmt / yamllint)
          │
          ▼
  [ Secret & Credential Scanning ] ─── (GitLeaks / TruffleHog)
          │
          ▼
  [ IaC Security & SAST Gates ] ────── (Checkov / Trivy / tfsec)
          │
          ▼
  [ FinOps Cost Estimation ] ───────── (Infracost PR Comment & Thresholds)
          │
          ▼
  [ Peer Approval & Policy Gate ] ──── (2+ Senior Approvals / CODEOWNERS)
          │
          ▼
  [ Terraform Plan & Blob Lease Lock ]
          │
          ▼
  [ Automated Deployment & Runtime Telemetry ]
          │
          ▼
  [ Scheduled Nightly Drift Detection CI ]
```

---

## 🏛️ Enterprise Architectures & Real-World Impact

<details>
<summary><b>Case Study 1: Zero-Downtime Migration of 100+ Enterprise Workloads</b> (Click to expand)</summary>
<br/>

* **Challenge:** Migrating 100+ multi-tier legacy workloads across Dev, UAT, and Production from an on-premises datacenter to Azure without business disruption.
* **Approach:**
  1. **Discovery & Assessment:** Ran Azure Migrate and automated dependency mapping to establish resource sizing and determine 7 R's strategy.
  2. **Foundation Readiness:** Provisioned Azure CAF Landing Zones with ExpressRoute connectivity, hub-spoke routing, and CIS compliance baselines.
  3. **Cutover Orchestration:** Staged data replication, executed low-TTL DNS failover during maintenance windows, and ran automated smoke testing suites.
  4. **Hypercare:** Maintained 24x7 War Room telemetry for 3 weeks post-cutover with zero critical escalations.
* **Result:** 100% on-time migration with zero data loss and an immediate 28% reduction in monthly infrastructure overhead.

</details>

<details>
<summary><b>Case Study 2: Enterprise Hub-and-Spoke Network with Zero-Trust Isolation</b> (Click to expand)</summary>
<br/>

* **Architecture Pattern:** Centralized Hub VNet connected to On-Prem via ExpressRoute and S2S VPN failover.
* **Traffic Inspection:** All spoke-to-spoke and egress internet traffic routed through Azure Firewall Premium via `0.0.0.0/0` User Defined Routes (UDRs) with TLS inspection.
* **Data Security:** All PaaS components (Azure Key Vault, Storage Accounts, SQL Databases) provisioned without public IPs, accessible solely through Azure Private Endpoints and Private DNS Zones.
* **Result:** Achieved 100% network micro-segmentation and satisfied rigorous financial-grade audit requirements.

</details>

<details>
<summary><b>Case Study 3: Enterprise FinOps Framework & Automated Cost Control</b> (Click to expand)</summary>
<br/>

* **Automated Cleanup:** Deployed scheduled serverless functions to identify and eliminate orphaned managed disks and unassociated PIPs.
* **Environment Scheduling:** Automated start/stop for non-production environments during non-business hours, saving ~65% on non-prod compute.
* **Log Ingestion Tuning:** Restructured Log Analytics workspaces and implemented Data Collection Rules (DCR), curbing non-essential log ingestion by 40%.
* **Result:** Sustained 28%+ recurring annual cloud spend savings while improving resource visibility across engineering squads.

</details>

---

## 🛠️ Tech Stack & Tooling

<div align="center">

| Domain | Technologies |
| :--- | :--- |
| **Cloud Platforms** | `Azure` `AWS` `Hybrid Cloud` |
| **Infrastructure as Code** | `Terraform` `Terragrunt` `Azure Bicep` `ARM Templates` `Ansible` |
| **Containers & Orchestration**| `Kubernetes (AKS / EKS)` `Docker` `Helm` `ArgoCD` |
| **DevSecOps & Security** | `Checkov` `Trivy` `GitLeaks` `tfsec` `SonarQube` `HashiCorp Vault` `Entra ID PIM` |
| **CI / CD Automation** | `Azure DevOps Pipelines` `GitHub Actions` `GitLab CI` `Jenkins` |
| **Observability & Monitoring**| `Azure Monitor` `Log Analytics` `Prometheus` `Grafana` `Infracost` |
| **Scripting & Automation** | `Bash` `PowerShell` `Python` `YAML / JSON` |

</div>

<br/>

<div align="center">

<!-- Badges Grid -->
![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-web-services&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/-Azure_DevOps-0078D7?style=flat-square&logo=azure-devops&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/-PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=rahulent&show_icons=true&theme=github_dark&hide_border=true&title_color=38bdf8&icon_color=38bdf8&text_color=94a3b8&bg_color=0d1117" alt="Rahul's GitHub Stats" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rahulent&layout=compact&theme=github_dark&hide_border=true&title_color=38bdf8&text_color=94a3b8&bg_color=0d1117" alt="Top Languages" height="165" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=rahulent&theme=github_dark&hide_border=true&stroke=38bdf8&ring=38bdf8&fire=38bdf8&background=0d1117" alt="GitHub Streak" />

</div>

---

## 📫 Contact & Connect

Interested in discussing enterprise cloud architecture, DevSecOps transformations, or large-scale migrations? Let's connect.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rahulent)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rahulent)
[![Email](https://img.shields.io/badge/Email-Get_in_Touch-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rahulsingh.clouddevops@gmail.com)

</div>

<br/>

<div align="center">
<sub>Designed with high engineering standards for <b>Rahul Singh</b> • Senior Cloud & DevSecOps Architect</sub>
</div>
