# My Prompts Repository

A curated library of specialized AI system prompts for enterprise systems engineering, observability, security, and personal productivity.

---

## Quick Start

1. Browse the categorized directories below to find the prompt you need.
2. Open the prompt file and copy the full system prompt.
3. Paste into your AI assistant's system instructions, Custom GPT, or agent framework.
4. Provide your scenario, requirements, or question to execute.

> [!TIP]
> **Combine prompts for maximum impact.** See the [Recommended Prompt Combinations](#recommended-prompt-combinations) table at the bottom for multi-prompt strategies.

---

## 🏗️ Infrastructure & Platform Engineering

Core datacenter, virtualization, compute, networking, and operating system prompts.

| Prompt | Persona | Key Focus Areas |
| :--- | :--- | :--- |
| **[VMware Virtualization Expert](vmware_virtualization_expert_prompt.md)** | Senior Principal Virtualization Architect | ESXi/vCenter/VCSA, HA/DRS/FT, vMotion, vSAN, Distributed Switches, NSX, Aria Operations, HCX, PowerCLI |
| **[Windows Server Expert](windows_server_expert_prompt.md)** | Senior Principal Windows Platform Architect | AD DS/FSMO, GPO (LSDOU), DNS/DHCP, Failover Clustering, Hyper-V, IIS, Storage Spaces Direct, PKI, LAPS |
| **[Linux Systems Administration Expert](linux_systems_administration_prompt.md)** | Senior Principal Linux Systems Architect | systemd, dnf/apt, LVM, SELinux/AppArmor, SSH hardening, Bash scripting, performance tuning, Podman/Docker |
| **[Enterprise Networking Infrastructure Expert](networking_infrastructure_expert_prompt.md)** | Senior Principal Network Architect | VLANs/STP/LACP, OSPF/BGP routing, Palo Alto/Fortinet firewalls, IPSec/SSL VPN, F5, SD-WAN, 802.1X NAC |
| **[Enterprise Data Center Hardware Expert](datacenter_hardware_expert_prompt.md)** | Distinguished 30+ Year Hardware Architect | Lenovo/HPE/Dell/Cisco server portfolios, storage arrays, CPU/RAM/NIC selection matrices, workload blueprints |
| **[Kubernetes & Container Platform Engineer](kubernetes_container_platform_prompt.md)** | Senior Principal Kubernetes Architect (CKA/CKS) | Control plane HA, etcd, Cilium/Calico CNI, vSphere CSI, MetalLB, ArgoCD/Flux GitOps, Helm 3, Kyverno |

---

## ☁️ Cloud, IaC & Automation

Azure cloud services, infrastructure as code, configuration management, and scripting.

| Prompt | Persona | Key Focus Areas |
| :--- | :--- | :--- |
| **[Azure Cloud Solutions Architect](azure_cloud_solutions_architect_prompt.md)** | Senior Principal Azure Architect | Full Azure service catalog, Zero-Trust, Well-Architected Framework (WAF), Landing Zones (CAF), Bicep/Terraform |
| **[Terraform Infrastructure Expert](terraform_infrastructure_expert_prompt.md)** | Senior Principal IaC Architect | HCL, multi-provider (Azure/AWS/VMware), state management, modules, Terragrunt, Policy-as-Code (Sentinel/OPA) |
| **[Ansible Automation Expert](ansible_automation_expert_prompt.md)** | Senior Principal Automation Architect | Playbooks, Roles/Collections, AWX/AAP, Jinja2, variable precedence, Vault, Windows/Linux modules, Molecule |
| **[PowerShell Expert](powershell_expert_prompt.md)** | 20+ Year PowerShell Principal Engineer | Enterprise scripting, PSScriptAnalyzer, pipeline architecture, PSGallery module integration |
| **[CI/CD & GitOps Infrastructure Pipeline Engineer](cicd_gitops_infrastructure_prompt.md)** | Senior Principal DevSecOps Architect | Azure DevOps YAML, GitHub Actions OIDC, quality gates (tflint/checkov/Pester), Atlantis GitOps, drift detection |
| **[Cloud FinOps & Cost Optimization Architect](cloud_finops_cost_optimization_prompt.md)** | Principal Cloud FinOps Architect | Reservations vs. Savings Plans, Azure Hybrid Benefit, storage tiering math, waste hunting scripts, tagging |
| **[Microsoft Enterprise AI Architect & Mentor](microsoft_ai_architect_mentor_prompt.md)** | Enterprise AI Architect | M365 Copilot, Copilot Studio, Azure AI Foundry, Semantic Kernel, Azure AI Search RAG, Purview governance |

---

## 🔐 Security, Compliance & Cryptography

Security hardening, regulatory compliance, PKI, and certificate lifecycle management.

| Prompt | Persona | Key Focus Areas |
| :--- | :--- | :--- |
| **[Security & Compliance Hardening Expert](security_compliance_hardening_prompt.md)** | Senior Principal Security Architect | CIS/NIST/STIG/ISO 27001/SOC 2, Zero-Trust, IAM/PAM/PIM, vulnerability/patch management, hardening checklists |
| **[PKI, TLS/SSL & Certificate Lifecycle Architect](pki_certificate_lifecycle_prompt.md)** | Senior Principal PKI Architect | AD CS hierarchy, Certificate Templates, GPO Auto-Enrollment, ACME/SCEP, Key Vault, OpenSSL CLI, TLS hardening |

---

## 📊 Observability, SIEM & Log Engineering

Log pipelines, SIEM platforms, and observability architecture.

| Prompt | Persona | Key Focus Areas |
| :--- | :--- | :--- |
| **[Microsoft Sentinel Architect & SecOps Expert](azure_sentinel_expert_prompt.md)** | Senior Principal Microsoft Sentinel Architect | Workspace design, DCR/DCE, AMA, CCF, Logs Ingestion API, cost optimization (Analytics/Basic/Auxiliary/Archive), Commitment Tiers, ASIM, SOAR Logic Apps |
| **[Cribl Cloud & Stream Expert](cribl_cloud_expert_prompt.md)** | Senior Observability Pipeline Architect | All pipeline functions, Source/Destination catalog, C.* expressions, volume reduction, Pack-first design, Lake & Search |
| **[Cribl Pipeline Architect (Elastic & Sentinel)](cribl_elastic_sentinel_pipeline_prompt.md)** | Dual-SIEM Pipeline Specialist | Pack-first design, ECS compliance, Sentinel DCR/DCE & ASIM mapping, Clone/Output Router, SIEM cost reduction |
| **[Elastic Serverless Cloud & Stack Expert](elastic_serverless_cloud_prompt.md)** | Senior Security Analytics Architect | Elasticsearch, KQL/ES\|QL/EQL, ingest pipelines, Elastic Agent/Fleet, SIEM detection rules, MITRE ATT&CK, APM |

---

## 🛡️ Backup, Disaster Recovery & Business Continuity

Enterprise data protection, replication, cyber recovery, and DR orchestration.

| Prompt | Persona | Key Focus Areas |
| :--- | :--- | :--- |
| **[Enterprise BCDR & Multi-Platform Recovery Architect](bcdr_disaster_recovery_expert_prompt.md)** | Distinguished BCDR Architect | Rubrik (Atlas/Radar/Sonar), Zerto CDP journaling, Veeam v12+ (HLR/SOBR/CDP), Cohesity FortKnox, NetApp MetroCluster, Pure ActiveCluster, ASR, 3-2-1-1-0, Clean Room |

---

## 📋 Operations, Project Management & Documentation

Incident management, project delivery, procedure documentation, and knowledge transfer.

| Prompt | Persona | Key Focus Areas |
| :--- | :--- | :--- |
| **[Incident Response & Troubleshooting Expert](incident_response_troubleshooting_prompt.md)** | Senior Principal SRE & Incident Commander | P1-P4 severity, 5 Whys/Ishikawa RCA, runbook templates, blameless post-mortems, SLI/SLO/SLA, diagnostics |
| **[IT Project Management Expert](project_management_expert_prompt.md)** | Senior IT Project Management Architect | Agile/Scrum/Kanban, ITIL 4, Change/Incident/Problem management, RACI, risk registers, EVM, Azure DevOps Boards |
| **[Systems & Procedure Documentation Architect](systems_procedure_documentation_expert_prompt.md)** | Principal Documentation Architect | Zero-Excuse SOPs, tacit knowledge extraction (shorthand expansion, interview, legacy refactor), runbooks, SAD, tribal gotchas, escalation gates |

---

## 🏠 Personal & Lifestyle

Non-technical prompts for personal productivity, finance, and daily life.

| Prompt | Persona | Key Focus Areas |
| :--- | :--- | :--- |
| **[Adult ADHD Executive Function Coach](adhd_executive_function_coach_prompt.md)** | Board-Certified ADHD Life Strategist & CBT Coach | 7 executive functions, task initiation, time blindness, working memory, RSD/emotional regulation, hyperfocus management, sleep/circadian, exercise/dopamine, nutrition, workplace strategies for IT pros, parenting, relationships, habit formation |
| **[Culinary Logistics & Meal Planner](culinary_logistics_meal_planner_prompt.md)** | Meal Planning Agent | 7-day budget meal planning, grocery categorization, teen calorie/protein scaling, single-question interview |
| **[Personal Finance Management](personal_finance_management_prompt.md)** | Personal Finance Agent | Budget planning, expense tracking, debt payoff strategies, savings optimization, financial goal setting |
| **[Formal Logic Engine & Analytical Reasoner](formal_logic_engine_prompt.md)** | Analytical Philosophy Evaluator | Syllogistic mapping, enthymeme extraction, fallacy & bias matrix, countermodels, epistemic crux analysis |

---

## Recommended Prompt Combinations

For maximum effectiveness, combine related prompts based on your current task:

| Task | Primary Prompt | Supporting Prompt(s) |
| :--- | :--- | :--- |
| Cloud infrastructure deployment | Azure Cloud Solutions Architect | Terraform Expert, Security & Compliance |
| On-prem VM environment management | VMware Virtualization Expert | Windows Server Expert, PowerShell Expert |
| Log pipeline engineering | Cribl Cloud & Stream Expert | Elastic Serverless Cloud Expert |
| Dual-SIEM log routing & optimization | Cribl Pipeline Architect (Elastic & Sentinel) | Elastic Serverless Cloud, Azure Solutions Architect |
| Infrastructure automation | Ansible Automation Expert | Linux Admin, Windows Server, Terraform |
| Security audit & compliance hardening | Security & Compliance Hardening | Windows Server, Linux Admin, Networking |
| Enterprise PKI & certificate management | PKI, TLS/SSL & Certificate Lifecycle | Windows Server Expert, Linux Admin, Enterprise Networking |
| Production incident response | Incident Response & Troubleshooting | (any technology-specific prompt) |
| Infrastructure project planning | IT Project Management Expert | (any technology-specific prompt) |
| Hardware procurement & DC design | Data Center Hardware Expert | VMware Expert, Windows Server Expert, Networking Expert |
| Disaster recovery & backup architecture | Enterprise BCDR Architect | VMware Expert, Windows Server Expert, Azure Solutions Architect |
| Container platform & Kubernetes ops | Kubernetes & Container Platform Engineer | Linux Admin, Ansible Expert, Enterprise Networking |
| Cloud cost reduction & FinOps governance | Cloud FinOps & Cost Optimization | Azure Solutions Architect, Terraform Expert |
| Infrastructure CI/CD & GitOps delivery | CI/CD & GitOps Pipeline Engineer | Terraform Expert, Ansible Expert, PowerShell Expert |
| Cloud SIEM, detection & SecOps engineering | Microsoft Sentinel Architect | Azure Cloud Solutions Architect, Cribl Expert, Security & Compliance |
| Operational delegation & SOP generation | Systems & Procedure Documentation | (any technology-specific prompt for context) |