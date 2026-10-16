# My Prompts Repository

A curated library of **47** specialized AI system prompts for enterprise systems engineering, identity, observability, security, communication, and personal productivity.

---

## Quick Start

1. Browse the categorized tables below to find the prompt you need.
2. Open the prompt file and copy the full system prompt.
3. Paste it into your AI assistant's system instructions (Claude Project, Custom GPT, Claude Code skill, or agent framework).
4. Provide your scenario, requirements, or question.

> [!TIP]
> **Combine prompts for maximum impact.** See the [Recommended Prompt Combinations](#recommended-prompt-combinations) table at the bottom for multi-prompt strategies.

---

## 🏗️ Infrastructure & Platform Engineering

Core datacenter, virtualization, compute, networking, and operating system prompts.

| Prompt | Persona | Key Focus Areas |
| :--- | :--- | :--- |
| **[VMware Virtualization Expert](vmware_virtualization_expert_prompt.md)** | Senior Principal Virtualization Architect | ESXi/vCenter/VCSA, HA/DRS/FT, vMotion, vSAN, Distributed Switches, NSX, VCF Operations (Aria), HCX, PowerCLI |
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
| **[Microsoft Enterprise AI Architect & Mentor](microsoft_ai_architect_mentor_prompt.md)** | Enterprise AI Architect | M365 Copilot, Copilot Studio, Microsoft Foundry, Semantic Kernel, Azure AI Search RAG, Purview governance |

---

## 🔐 Identity, Security, Compliance & Cryptography

Identity and endpoint management, security hardening, regulatory compliance, PKI, and certificate lifecycle management.

| Prompt | Persona | Key Focus Areas |
| :--- | :--- | :--- |
| **[Entra ID, Intune & Modern Workplace Identity Architect](entra_id_intune_identity_prompt.md)** | Senior Principal Identity & Endpoint Architect | Hybrid identity (Cloud Sync/Connect, PHS), Conditional Access baselines, passkeys/phishing-resistant MFA, PIM, Intune/Autopilot, Windows LAPS, Graph PowerShell, Microsoft365DSC |
| **[Security & Compliance Hardening Expert](security_compliance_hardening_prompt.md)** | Senior Principal Security Architect | CIS/NIST/STIG/ISO 27001/SOC 2, Zero-Trust, IAM/PAM/PIM, vulnerability/patch management, hardening checklists |
| **[PKI, TLS/SSL & Certificate Lifecycle Architect](pki_certificate_lifecycle_prompt.md)** | Senior Principal PKI Architect | AD CS hierarchy, Certificate Templates, GPO Auto-Enrollment, ACME/SCEP, Key Vault, OpenSSL CLI, TLS hardening |

---

## 📊 Observability, Monitoring, SIEM & Log Engineering

Metrics and alerting, log pipelines, SIEM platforms, and observability architecture.

| Prompt | Persona | Key Focus Areas |
| :--- | :--- | :--- |
| **[Infrastructure Monitoring, Metrics & Alerting Architect](infrastructure_monitoring_alerting_prompt.md)** | Senior Principal Monitoring Architect | USE/RED/Golden Signals, symptom-based alerting, SLO burn-rate alerts, Azure Monitor/AMBA, Prometheus/Grafana/Alertmanager, Zabbix, SCOM, alert-noise reduction |
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

## 📋 Operations, Communication & Documentation

Incident management, project delivery, stakeholder communication, procedure documentation, and knowledge transfer.

| Prompt | Persona | Key Focus Areas |
| :--- | :--- | :--- |
| **[Incident Response & Troubleshooting Expert](incident_response_troubleshooting_prompt.md)** | Senior Principal SRE & Incident Commander | P1-P4 severity, 5 Whys/Ishikawa RCA, runbook templates, blameless post-mortems, SLI/SLO/SLA, diagnostics |
| **[IT Project Management Expert](project_management_expert_prompt.md)** | Senior IT Project Management Architect | Agile/Scrum/Kanban, ITIL 4, Change/Incident/Problem management, RACI, risk registers, EVM, Azure DevOps Boards |
| **[Systems & Procedure Documentation Architect](systems_procedure_documentation_expert_prompt.md)** | Principal Documentation Architect | Zero-Excuse SOPs, tacit knowledge extraction (shorthand expansion, interview, legacy refactor), runbooks, SAD, tribal gotchas, escalation gates |
| **[Technical Communication & Executive Translator](technical_communication_executive_translator_prompt.md)** | Principal Technical Communications Strategist | BLUF writing, audience translation matrix, exec status updates, outage notifications, CAB summaries, business cases, vendor escalations |

---

## ⚡ Daily Productivity & Workflow

Short, repeatable prompts built to be used every day: start/end the day, clear the inbox, process meetings, make decisions, and digest reading.

| Prompt | Persona | Key Focus Areas |
| :--- | :--- | :--- |
| **[Daily Kickoff & Shutdown Ritual Coach](daily_kickoff_shutdown_ritual_prompt.md)** | Daily Operations Coach (ADHD-aware) | 5-min morning kickoff (one win, real focus time, < 2-min first step), midday re-anchor, end-of-day shutdown, work log & brag capture, standup generation, Floor Day mode |
| **[Inbox & Message Triage Assistant](inbox_message_triage_reply_prompt.md)** | Executive Assistant & Comms Triage Specialist | 6-bucket triage, consequence ranking, hidden-ask & deadline detection, phishing red flags, BLUF reply drafts, "no" templates |
| **[Meeting Notes, Decisions & Action Item Extractor](meeting_notes_action_extractor_prompt.md)** | Program Coordinator & Meeting Scribe | Decision vs. discussion separation, owner/due-date enforcement, "your actions" list, CAB/incident/design/vendor/1:1 add-ons, follow-up email draft |
| **[Everyday Decision Coach & Decision-Fatigue Breaker](everyday_decision_coach_prompt.md)** | Decision Strategist (ADHD-aware) | Two-way vs. one-way door sizing, default rules, satisficing, weighted matrix, pre-mortem, research-loop breaker, always-recommend output |
| **[Rapid Research & Briefing Analyst](rapid_research_briefing_analyst_prompt.md)** | Senior Research Analyst | 2-minute layered briefings, "does this affect me?" impact checks, source credibility ladder, fact/claim/inference labeling, compare & explain modes |

---

## 🏠 Personal, Career & Lifestyle

Non-technical prompts for personal productivity, career growth, finance, and daily life.

| Prompt | Persona | Key Focus Areas |
| :--- | :--- | :--- |
| **[Adult ADHD Executive Function Coach & Behavioral Analyst](adhd_executive_function_coach_prompt.md)** | ADHD Life Strategist & Executive Function Coach (not a clinician) | Behavioral decoding (ABC model), 10 ADHD behavioral archetypes (Waiting Mode, Restraint Collapse, Urgency Addiction), 7 executive functions, task initiation, time blindness, working memory, RSD, workplace strategies for IT pros, parenting, habit formation |
| **[Weekly Reset & Life Operating System Coach](weekly_reset_life_planning_prompt.md)** | Personal Operations Coach (GTD + ADHD scaffolding) | 20–30 min weekly reset, brain dump → sort buckets, Big 3 priorities, time-blindness padding, daily/monthly check-ins |
| **[Health, Fitness & Sustainable Habit Coach](health_fitness_habit_coach_prompt.md)** | Personal Trainer & Habit Coach (non-medical) | Minimum-effective-dose strength plans, "Floor" plans for bad weeks, sleep & energy, desk-worker correctives, habit stacking |
| **[Home Maintenance & Household Operations Manager](home_maintenance_household_ops_prompt.md)** | Household Ops Manager ("Home as Infrastructure") | Home asset inventory, seasonal PM schedules, DIY vs. pro decisions, contractor vetting, chore matrix, capital replacement forecast |
| **[Everyday Computer Help Desk Technician](everyday_computer_help_desk_prompt.md)** | Patient Help Desk Technician for non-technical users | One-action-per-step fix guides, plain-language clarifying questions, "what you should see" checks, OS identification, Wi-Fi/printer/email/password/slow PC fixes, scam pop-up safety, when to call a pro |
| **[Family Travel & Trip Logistics Planner](family_travel_trip_planner_prompt.md)** | Travel Logistics Planner | Day trips to week-long vacations, pacing rules, teen buy-in, booking priority, weather backups, packing & prep timelines, Game Day mode |
| **[Genealogy & Local History Research Assistant](genealogy_local_history_research_prompt.md)** | Professional Genealogist & Local Historian | Genealogical Proof Standard, PA/Mid-Atlantic record map, PA German church records, brick-wall strategies, archive naming & metadata |
| **[Learning Strategist & Skill Acquisition Coach](learning_skill_acquisition_coach_prompt.md)** | Learning Scientist & Skill Coach | Project-first learning plans, retrieval & spaced repetition, Anki flashcards, teach & quiz modes, ADHD-friendly 20–30 min sessions |
| **[Career Interest Discovery & Occupational Fit Assessment](career_interest_discovery_assessment_prompt.md)** | Career Assessment Specialist & Vocational Counselor | Step-by-step RIASEC (Holland Code) interest inventory, O\*NET work values, strengths & peak experiences, work style, constraints, ranked occupation matches, 30-day exploration plan; works for teens through career changers |
| **[Senior Infrastructure Career Strategist & Interview Coach](career_growth_interview_coach_prompt.md)** | Career Strategist & Former Infrastructure Hiring Manager | Brag document/XYZ bullets, resume & LinkedIn tailoring, STAR-L story bank, mock interviews, cert roadmap, negotiation scripts, ADHD-aware job search |
| **[Culinary Logistics & Meal Planner](culinary_logistics_meal_planner_prompt.md)** | Meal Planning Agent | 7-day budget meal planning, grocery categorization, teen calorie/protein scaling, single-question interview |
| **[Personal Finance Management](personal_finance_management_prompt.md)** | Personal Finance Agent | Budget planning, expense tracking, debt payoff strategies, savings optimization, financial goal setting |
| **[Investing Mentor & Market Strategist for Beginners](investing_mentor_beginner_prompt.md)** | Veteran Investing Mentor & Educator (not a licensed adviser) | One-question-at-a-time beginner intake, investing order of operations, index funds & allocation templates, stock deep-dive method, high-risk & scam warnings, fiduciary referrals |
| **[End-of-Life Planning & Legacy Organizer](end_of_life_planning_legacy_organizer_prompt.md)** | Compassionate Planning Guide (estate paralegal + hospice social worker + organizer; not an attorney) | Gentle module-by-module interview, will/trust/POA/advance directive, beneficiary checks, asset & digital-life inventory (no secrets in chat), final wishes, prioritized to-do plan, Letter of Instruction |
| **[Formal Logic Engine & Analytical Reasoner](formal_logic_engine_prompt.md)** | Analytical Philosophy Evaluator | Syllogistic mapping, enthymeme extraction, fallacy & bias matrix, countermodels, epistemic crux analysis |

---

## 🧰 Meta & Prompt Engineering

Prompts for building and maintaining this library.

| Prompt | Persona | Key Focus Areas |
| :--- | :--- | :--- |
| **[Prompt Engineering Architect & System Prompt Builder](prompt_engineering_architect_prompt.md)** | Principal Prompt Engineer | Build/audit/refactor/combine prompts, `my_prompts` house-style blueprint, audit rubric, Claude skill/Project/Custom GPT packaging, test inputs |

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
| Entra ID / Conditional Access / Intune rollout | Entra ID, Intune & Identity Architect | Security & Compliance, PowerShell Expert, Windows Server Expert |
| Monitoring & alert-noise cleanup | Infrastructure Monitoring & Alerting | Incident Response, VMware Expert, Azure Solutions Architect |
| Outage comms, CAB submissions & exec updates | Technical Communication & Executive Translator | Incident Response, IT Project Management |
| Figuring out what career fits (teen or adult) | Career Interest Discovery Assessment | Learning Strategist & Skill Coach, Career Strategist & Interview Coach |
| Promotion, resume & interview prep | Career Strategist & Interview Coach | Technical Communication, ADHD Executive Function Coach |
| Weekly planning that actually sticks | Weekly Reset & Life Operating System | ADHD Executive Function Coach |
| Healthy routines for the whole family | Health, Fitness & Habit Coach | Culinary Logistics & Meal Planner, Weekly Reset |
| Home repairs, projects & big-expense planning | Home Maintenance & Household Ops | Personal Finance Management |
| Family vacations & day trips | Family Travel & Trip Planner | Personal Finance Management |
| Family tree & local history archive | Genealogy & Local History Research | Systems & Procedure Documentation (archive SOPs) |
| Learning a new technology or hobby | Learning Strategist & Skill Coach | (the matching technical prompt, e.g., Kubernetes, Terraform) |
| Starting and ending the workday | Daily Kickoff & Shutdown Ritual | Weekly Reset, ADHD Executive Function Coach |
| Clearing a backed-up inbox or Teams | Inbox & Message Triage | Technical Communication & Executive Translator |
| Turning meetings into tracked work | Meeting Notes & Action Item Extractor | IT Project Management, Daily Kickoff & Shutdown |
| Stuck on a choice (work or home) | Everyday Decision Coach | Personal Finance, Home Maintenance, Formal Logic Engine |
| Release notes, advisories & long docs | Rapid Research & Briefing Analyst | (the matching technical prompt), Security & Compliance |
| Starting to invest (complete beginner) | Investing Mentor & Market Strategist | Personal Finance Management, Everyday Decision Coach |
| Getting affairs in order for loved ones | End-of-Life Planning & Legacy Organizer | Personal Finance Management, Investing Mentor, Systems & Procedure Documentation |
| Adding or improving a prompt in this repo | Prompt Engineering Architect | (the prompt being created or audited) |

---

## Using These Prompts with Claude

| Platform | How |
| :--- | :--- |
| **Claude Projects** | Paste the prompt into *Project instructions*; upload large reference docs as project knowledge. |
| **Claude Code (skill)** | Create `~/.claude/skills/<name>/SKILL.md` with `name` and `description` frontmatter, then paste the prompt body. Use the Prompt Engineering Architect (Mode E) to convert. |
| **API / agents** | Use the file contents as the `system` prompt; pass your scenario as the user message. |

---

## Prompt Anatomy (House Style)

Every prompt follows the same skeleton so they are predictable and combinable:

1. **Persona**: seniority, domain, signature outcome
2. **Role & Primary Objective**: what it produces and which modern standards it enforces
3. **Clarification Protocol**: only the questions that change the answer
4. **Core Knowledge Domains**: decision matrices, standards tables, deprecations
5. **Structured Response Protocol**: `<verification>` self-check, then delivery format
6. **Ground Rules**: one-line *Never/Always* guardrails

New prompts: use the [Prompt Engineering Architect](prompt_engineering_architect_prompt.md) in **Build** mode, name the file `snake_case_name_prompt.md`, and add a row to the matching table above.
