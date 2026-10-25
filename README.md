<div align="center">

# ⚡ Rahul Singh | Senior DevSecOps & Cloud Architect ⚡
### *Engineering Resilient, Zero-Trust, and Autonomous Cloud Platforms Across the Universe*

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00F0FF&center=true&vCenter=true&random=false&width=680&lines=Senior+DevOps+%26+Cloud+Architect+(Azure+%2B+AWS);Zero-Trust+DevSecOps+%7C+Shift-Left+Security+Pioneer;Orchestrated+100%2B+Enterprise+Cloud+Workload+Migrations;Production-Grade+IaC%2C+Terraform+Landing+Zones+%26+FinOps;Designing+High-Availability+Ecosystems+(99.99%25+SLA))](https://git.io/typing-svg)

<br/>

[![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)](https://azure.microsoft.com/)
[![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-web-services&logoColor=white)](https://aws.amazon.com/)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)](https://kubernetes.io/)
[![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)](https://terraform.io/)
[![DevSecOps](https://img.shields.io/badge/DevSecOps-Zero--Trust-red?style=for-the-badge&logo=shield&logoColor=white)](#-multi-layered-defense-in-depth-security)
[![FinOps](https://img.shields.io/badge/FinOps-Cloud_Economy-brightgreen?style=for-the-badge&logo=google-cloud&logoColor=white)](#-finops--cloud-financial-engineering)

<br/>

[🚀 Executive Summary](#-executive-profile) •
[🏛️ Enterprise Architecture](#️-enterprise-architecture--cloud-governance) •
[🛡️ Shift-Left DevSecOps](#-end-to-end-shift-left-devsecops-pipeline) •
[📦 100+ Workload Migration](#-100-workload-enterprise-migration-blueprint) •
[🛠️ Tech Arsenal](#-technical-arsenal--toolchain) •
[📊 Telemetry](#-github-telemetry--metrics) •
[📫 Connect](#-lets-collaborate)

---

</div>

## 👨‍💻 Executive Profile

I am a **Senior DevOps & Cloud Architect** with **5+ years of hands-on production mastery** architecting, securing, and automating mission-critical infrastructure across **Microsoft Azure and Amazon Web Services (AWS)**. 

My core engineering philosophy centers on **architectural resilience, zero-trust security governance, and measurable business ROI**:
* 🏢 **100+ Enterprise Workload Migrations:** Spearheaded zero-downtime datacenter-to-cloud migrations across Dev, UAT, and Multi-Region Production tiers.
* 🛡️ **Shift-Left DevSecOps:** Embedded automated vulnerability, secret, and compliance scanning directly into CI/CD pipelines (SAST, DAST, SCA, IaC policy-as-code).
* 🌐 **Enterprise Cloud Adoption Framework (CAF):** Designed sovereign Landing Zones, Management Group hierarchies, and micro-segmented Hub-and-Spoke networks.
* 💰 **FinOps & Cost Optimization:** Slashed cloud burn rates by **28%+** through rightsizing, automated lifecycle policies, reservation planning, and log ingestion tuning.
* 🤝 **Delivery Governance & Leadership:** Spearheaded RFP/RFI techno-functional proposals, SOW execution, vendor evaluation matrixes, and mentored cross-functional engineering teams.

---

## 🏛️ The 10 Architectural Pillars of Resilient Engineering

Every architecture I engineer is mathematically audited against the 10 non-negotiable enterprise pillars:

| Pillar | Engineering Mandate & Standard |
| :--- | :--- |
| **1. Scalability** | Horizontal auto-scaling (VMSS, KEDA, HPA) tailored to traffic spikes with zero manual intervention. |
| **2. Robustness** | Self-healing architectures with automated health probes, circuit-breakers, and fallback failovers. |
| **3. Zero-Trust Security** | Least privilege access (PIM, RBAC), encrypted in-transit (mTLS 1.3) and at rest (CMK), zero public IPs. |
| **4. High Reliability** | Active-Active multi-zone availability delivering 99.99% uptime SLAs across PaaS and IaaS tiers. |
| **5. Portability** | Containerized workloads (OCI compliant) and modular, provider-agnostic Terraform/IaC modules. |
| **6. Enterprise Governance** | Azure Policy guardrails, CIS / ISO27001 compliance enforcement, and tenant-wide security baselines. |
| **7. Disaster Recovery** | Aggressive RTO (< 1 hr) and RPO (< 15 mins) with cross-region Azure Site Recovery (ASR) & GRS backups. |
| **8. FinOps Optimization** | Infracost PR checks, automated non-prod schedules, reservations, and continuous idle waste purging. |
| **9. Resilient Backup** | Immutable, air-gapped backups with multi-tier retention policies (LRS / ZRS / GRS storage redundancy). |
| **10. Deep Observability** | Centralized telemetry via Azure Monitor, Log Analytics, DCR filtering, and PagerDuty/Teams escalation. |

---

## 🌐 Enterprise Landing Zone & Governance Hierarchy

Architected following Microsoft's **Cloud Adoption Framework (CAF)** with sovereign subscription isolation and root policy enforcement:

```
                            ┌─────────────────────────────────────────┐
                            │      Microsoft Entra ID Tenant          │
                            └────────────────────┬────────────────────┘
                                                 │
                                    ┌────────────▼────────────┐
                                    │    Tenant Root Group    │
                                    └────────────┬────────────┘
                                                 │
             ┌───────────────────────────────────┼───────────────────────────────────┐
             │                                   │                                   │
┌────────────▼────────────┐         ┌────────────▼────────────┐         ┌────────────▼────────────┐
│   Platform MG           │         │  Landing Zones (Corp)   │         │  Sandbox & Decom MG     │
├─────────────────────────┤         ├─────────────────────────┤         ├─────────────────────────┤
│ • Identity (AD / DNS)   │         │ • Corp (Internal Only)  │         │ • Sandbox Subscriptions │
│ • Management (Log / Mon)│         │ • Online (DMZ / Public) │         │ • Decommissioned Sub    │
│ • Connectivity (Hub)    │         │ • Dev / UAT / Prod Subs │         │ • Policy Testing Labs   │
└─────────────────────────┘         └─────────────────────────┘         └─────────────────────────┘
```

> **Enterprise Isolation Standards:**
> * **Strict Subscription Boundaries:** Workloads separated by lifecycle (`Dev` ➔ `UAT` ➔ `Production`) to eliminate noisy neighbors and constrain blast radiuses.
> * **Management Group Policy Assignment:** Enforcing CIS Microsoft Azure Foundations Benchmark and Microsoft Cloud Security Benchmark (MCSB) with automated audit/deny triggers.
> * **Identity Governance:** 100% Group-based RBAC with Microsoft Entra ID Privileged Identity Management (PIM) for Just-In-Time (JIT) time-bound activations.

---

## 🔌 Enterprise Hub-and-Spoke Network Architecture

Zero-trust traffic routing, centralized inspection, and end-to-end private PaaS connectivity:

```
                       ┌──────────────────────────────┐
                       │   On-Premises Datacenter     │
                       └──────────────┬───────────────┘
                                      │ (ExpressRoute / S2S VPN)
                                      ▼
┌───────────────────────────────────────────────────────────────────────────────┐
│                       HUB VNet (Central Connectivity)                         │
│                                                                               │
│  ┌───────────────────────┐  ┌───────────────────────┐  ┌───────────────────┐  │
│  │ Azure Firewall Prem / │  │  GatewaySubnet        │  │  Private DNS      │  │
│  │ NVA (TLS Inspection)  │  │  (ER / VPN Gateway)   │  │  Zones Resolver   │  │
│  └───────────┬───────────┘  └───────────────────────┘  └───────────────────┘  │
└──────────────┼────────────────────────────────────────────────────────────────┘
               │ (VNet Peering + UDR 0.0.0.0/0 forced tunneling)
       ┌───────┴──────────────────────────────┐
       │                                      │
┌──────▼───────────────────────┐      ┌───────▼──────────────────────┐
│  Spoke 1: Production Workloads│      │  Spoke 2: Shared Operations  │
├──────────────────────────────┤      ├──────────────────────────────┤
│ • App & Microservices Subnets│      │ • Self-Hosted CI/CD Runners  │
│ • Database Subnets (Isolated)│      │ • Azure Bastion Host         │
│ • Private Endpoints (KeyVault│      │ • Security & Observability   │
│   Storage, Azure SQL, Redis) │      │   Scanning Gateways          │
└──────────────────────────────┘      └──────────────────────────────┘
```

* **Zero-Overlap IPAM:** Comprehensive CIDR allocation strategy preventing IP collisions with on-prem data centers.
* **Forced Egress & Ingress Inspection:** UDR routing (`0.0.0.0/0`) funneling all traffic through Azure Firewall Premium with IDPS and TLS inspection.
* **100% Private PaaS:** Zero public endpoints for Azure Key Vault, Storage Accounts, or databases via Azure Private Link & central Private DNS Zones.

---

## 🛡️ Multi-Layered Defense-in-Depth Security

Security is not an afterthought; it is woven into every structural layer:

```
                 [ Layer 1: Identity & Access ]  ── Entra ID, MFA, PIM (JIT), Managed Identities
                               │
                 [ Layer 2: Network Perimeter ]  ── Hub-Spoke, DDoS Protection, Azure Firewall, WAF
                               │
                 [ Layer 3: Network Segment ]    ── Micro-segmentation with NSGs/ASGs & UDR Routing
                               │
                 [ Layer 4: Compute & Host ]     ── Defender for Servers, CMK Disk Encryption, Patching
                               │
                 [ Layer 5: Application & IaC ]  ── GitLeaks, Checkov, Trivy, Snyk, Shift-Left SAST
                               │
                 [ Layer 6: Data & Secrets ]     ── Azure Key Vault, Envelope Encryption, Air-Gapped Backups
```

| Security Layer | Implemented Controls & Hardening |
| :--- | :--- |
| **Identity Level** | Microsoft Entra ID, Conditional Access policies, FIDO2 MFA, Just-In-Time (JIT) PIM access, Managed Identities (Zero hardcoded credentials). |
| **Perimeter & Network** | Azure DDoS Protection Standard, Web Application Firewall (WAF) v2, Azure Firewall Premium with TLS inspection and strict egress filtering. |
| **Micro-Segmentation** | Strict Network Security Groups (NSGs) and Application Security Groups (ASGs) disallowing inter-subnet lateral movement. |
| **Compute Hardening** | Microsoft Defender for Cloud Secure Score optimization, automated image baking via Packer, automated OS vulnerability patching. |
| **Data Protection** | Customer-Managed Keys (CMK) with Azure Key Vault HSM, Azure Storage blob immutability, automated TLS 1.3 enforcement. |

---

## 🚀 End-to-End Shift-Left DevSecOps Pipeline

Every infrastructure and application commit must survive an exhaustive automated quality, security, and cost gate before production deployment:

```
┌──────────────┐     ┌──────────────┐     ┌──────────────┐     ┌──────────────┐
│  Git Commit  │ ──► │ Code Linting │ ──► │ Secret Scan  │ ──► │ IaC Security │
│ & PR Created │     │ (tflint/fmt) │     │  (GitLeaks)  │     │(Checkov/Trivy│
└──────────────┘     └──────────────┘     └──────────────┘     └──────┬───────┘
                                                                      │
┌──────────────┐     ┌──────────────┐     ┌──────────────┐            │
│  Terraform   │ ◄── │ Production   │ ◄── │  FinOps Cost │ ◄──────────┘
│  Apply (Lock)│     │ Approval (2+)│     │  (Infracost) │
└──────┬───────┘     └──────────────┘     └──────────────┘
       │
       ▼
┌────────────────────────────────────────────────────────┐
│  Automated Nightly Drift Detection & Self-Healing CI   │
└────────────────────────────────────────────────────────┘
```

### 🔒 Enterprise CI/CD Governance Rules:
* **Branching Strategy:** Strict Trunk-Based Development with ephemeral feature branches (`feature/*`, `fix/*`).
* **Main Branch Lock:** Direct pushes prohibited (`No Direct Push`, `No Delete`), mandatory PRs with **minimum 2 senior approvals** and passing status checks.
* **Remote State Security:** Terraform state locked with Azure Blob Leases, fully encrypted with Customer-Managed Keys, accessed strictly via Least-Privilege OIDC Managed Identities.
* **Automated Drift Detection:** Scheduled night runs of `terraform plan -detailed-exitcode` to automatically detect and alert on unauthorized manual portal changes.

---

## 📦 100+ Workload Enterprise Migration Blueprint

A proven, systematic 5-phase framework executed across complex enterprise migrations:

```
┌─────────────────┐     ┌─────────────────┐     ┌─────────────────┐     ┌─────────────────┐     ┌─────────────────┐
│  1. Discovery   │ ──► │  2. Assessment  │ ──► │  3. Readiness   │ ──► │   4. Cutover    │ ──► │  5. Hypercare   │
├─────────────────┤     ├─────────────────┤     ├─────────────────┤     ├─────────────────┤     ├─────────────────┤
│ • Azure Migrate │     │ • TCO & ROI     │     │ • CAF Landing   │     │ • Data Sync &   │     │ • 24x7 War Room │
│ • Dependency Map│     │ • 7 R's Strategy│     │   Zone Ready    │     │   Replication   │     │ • Telemetry Mon │
│ • App Inventory │     │ • Compatibility │     │ • ExpressRoute  │     │ • DNS TTL Cut   │     │ • Perf Baseline │
└─────────────────┘     └─────────────────┘     └─────────────────┘     └─────────────────┘     └─────────────────┘
```

* **Phase 1: Discovery:** Automated dependency mapping, host discovery, and network flow analysis.
* **Phase 2: Assessment:** Workload classification (Rehost, Replatform, Refactor), business case justification, and resource rightsizing.
* **Phase 3: Readiness:** Target landing zones provisioned, network peering verified, security policies enforced.
* **Phase 4: Cutover:** Minimal downtime cutover window, active-passive database sync, DNS TTL reduction, smoke test validations.
* **Phase 5: Hypercare:** 2-4 weeks of 24x7 War Room monitoring, SLA performance verification, and operational runbook handover.

---

## 💰 FinOps & Cloud Financial Engineering

Transforming cloud operations from a cost center into an optimized, value-driven engine:

* 📉 **Eliminating Cloud Waste:** Automated cleanup scripts targeting orphaned managed disks, unassociated Public IPs, and stale snapshots.
* 📏 **Data-Driven Rightsizing:** Continuous CPU/Memory percentile rightsizing based on 30-day telemetry benchmarks.
* 💳 **Commitment Architecture:** Structured mix of 1-year / 3-year Reserved Instances (RI) and Azure Savings Plans covering steady-state baselines.
* ⏰ **Automated Power Management:** Automated Start/Stop automation for non-production environments slashing Dev/UAT run costs by ~65%.
* 📊 **Log Telemetry Tuning:** Optimization of Azure Monitor Log Analytics workspace ingestion using Data Collection Rules (DCR) to suppress noisy audit logs.

---

## 🛠️ Technical Arsenal & Toolchain

<div align="center">

| Domain | Technologies & Platforms |
| :--- | :--- |
| **Cloud Platforms** | ![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white) ![AWS](https://img.shields.io/badge/Amazon_AWS-232F3E?style=flat-square&logo=amazon-web-services&logoColor=white) ![Hybrid](https://img.shields.io/badge/Hybrid_Cloud-4A154B?style=flat-square&logo=slack&logoColor=white) |
| **Infrastructure as Code** | ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white) ![Terragrunt](https://img.shields.io/badge/Terragrunt-5C4EE5?style=flat-square&logo=terraform&logoColor=white) ![Bicep](https://img.shields.io/badge/Azure_Bicep-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) |
| **DevSecOps & Security** | ![Checkov](https://img.shields.io/badge/Checkov-1E88E5?style=flat-square&logo=bridgecrew&logoColor=white) ![Trivy](https://img.shields.io/badge/Trivy-00A4A6?style=flat-square&logo=aqua&logoColor=white) ![GitLeaks](https://img.shields.io/badge/GitLeaks-FF6B6B?style=flat-square&logo=git&logoColor=white) ![tfsec](https://img.shields.io/badge/tfsec-0A85EA?style=flat-square&logo=terraform&logoColor=white) ![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white) ![HashiCorp Vault](https://img.shields.io/badge/Vault-000000?style=flat-square&logo=vault&logoColor=white) |
| **Containers & Orchestration** | ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white) ![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white) |
| **CI / CD Pipelines** | ![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azure-devops&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) ![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white) |
| **Observability & Monitoring** | ![Azure Monitor](https://img.shields.io/badge/Azure_Monitor-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![Infracost](https://img.shields.io/badge/Infracost-00D492?style=flat-square&logo=infracost&logoColor=white) |
| **Languages & Scripting** | ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) |

</div>

---

## 🤝 Vendor Management & Delivery Governance

Senior leadership requires translating complex technical realities into business strategy and bulletproof vendor accountability:

```
┌─────────────┐     ┌─────────────┐     ┌──────────────────┐     ┌─────────────┐     ┌─────────────┐
│  RFI / RFP  │ ──► │ Technical   │ ──► │ SOW Scope &      │ ──► │ Milestone   │ ──► │ RACI Signoff│
│  Issuance   │     │ Matrix Eval │     │ Commercial Terms │     │ Sprints     │     │ & Payment   │
└─────────────┘     └─────────────┘     └──────────────────┘     └─────────────┘     └─────────────┘
```

* **SOW (Statement of Work):** Defining crystal-clear deliverables, technical boundaries, SLA definitions, and milestone sign-off criteria.
* **Technical Evaluation Matrix:** Quantifying vendor architectural fit, security posture, compliance certs, and financial projections.
* **RACI Matrix Leadership:** Establishing clear operational ownership (**R**esponsible, **A**ccountable, **C**onsulted, **I**nformed) to eradicate delivery ambiguities.
* **Knowledge Transfer & Handover:** Driving structured KT workshops, comprehensive architecture runbooks, and shadow support cycles.

---

## 📊 GitHub Telemetry & Metrics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=rahulent&show_icons=true&theme=tokyonight&hide_border=true&title_color=00F0FF&icon_color=00F0FF&text_color=9ECE6A&bg_color=0d1117" alt="Rahul's GitHub Stats" height="175" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rahulent&layout=compact&theme=tokyonight&hide_border=true&title_color=00F0FF&text_color=9ECE6A&bg_color=0d1117" alt="Top Languages" height="175" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=rahulent&theme=tokyonight&hide_border=true&stroke=00F0FF&ring=00F0FF&fire=FF6B6B" alt="GitHub Streak" />

</div>

---

## 📫 Let's Collaborate

I am always keen to discuss enterprise cloud architectures, complex zero-downtime migrations, or DevSecOps transformation initiatives.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rahulent)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rahulent)
[![Email](https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rahulsingh.clouddevops@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-DevOps_Insider-00F0FF?style=for-the-badge&logo=google-chrome&logoColor=black)](#)

</div>

---

<div align="center">

```
========================================================================================
[SYS_INIT] :: ARCHITECTURE STATUS: RESILIENT | SECURITY: ZERO-TRUST | UPTIME: 99.99%
"Security is not a gate at the end; it is the mathematical foundation of every commit."
========================================================================================
```

**Crafted with precision for Rahul Singh • Senior DevSecOps & Cloud Architect**

</div>
