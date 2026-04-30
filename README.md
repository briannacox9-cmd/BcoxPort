🧑‍💻 Brianna Cox — DevOps / Platform Engineering Portfolio

🚀 Observability • Automation • AI Microservices • Platform Reliability

🔷 Overview

This repository showcases a hands-on platform engineering portfolio focused on:

📊 Observability (Prometheus, Grafana, Alertmanager)
⚙️ Automation (Ansible, Bash, CI/CD concepts)
🤖 AI-integrated microservices (FastAPI + OpenAI)
🔐 Linux hardening & security practices
🧪 Real-world troubleshooting in virtualized environments

This portfolio is designed to reflect production-style engineering, not just tutorials.

🏗️ Architecture
                ┌─────────────────────┐
                │   API Requests      │
                └────────┬────────────┘
                         ↓
                ┌─────────────────────┐
                │  FastAPI Service    │
                └────────┬────────────┘
                         ↓
         ┌─────────────────────────────────┐
         │ AI Logic (OpenAI / Fallback)    │
         └────────┬────────────────────────┘
                  ↓
        ┌───────────────────────┐
        │ Logging + Metrics     │
        └────────┬──────────────┘
                 ↓
     ┌─────────────────────────────┐
     │ Prometheus → Grafana        │
     └────────┬────────────────────┘
              ↓
     ┌─────────────────────────────┐
     │ Alertmanager (Notifications)│
     └─────────────────────────────┘
📊 Project 1: Observability Stack
🔹 Stack
Prometheus
Node Exporter
Grafana
Alertmanager
Linux (CentOS / RHEL)
🔹 Features
System metrics collection (CPU, memory, disk, network)
Custom Grafana dashboards
Alerting rules for system thresholds
Service-level troubleshooting (systemd, ports, configs)
🔹 Real Issues Solved
Prometheus config failure (static_configs duplication)
Grafana service access (port/firewall issues)
YAML parsing + service restart failures
🔹 Key Takeaway

Built a full monitoring pipeline that reduces MTTR through visibility and alerting.

🤖 Project 2: AI Sponsorship SaaS
🔹 Stack
FastAPI
Uvicorn
OpenAI API (feature flag controlled)
Python (async)
REST API (Swagger UI)
🔹 Endpoint Example
POST /sponsorships/draft
🔹 Sample Response
{
  "fit_score": 87,
  "brand_alignment_summary": "...",
  "audience_insight": "...",
  "campaign_idea": "...",
  "risks": "...",
  "recommended_next_step": "..."
}
🔹 Features
AI + fallback logic (USE_AI=true/false)
Structured output for business use
Async-ready design (future queue integration)
Clean API interface with docs
🔹 Key Takeaway

Designed a scalable AI-ready service with production-minded architecture.

🔐 Project 3: Linux Hardening & Security
🔹 Focus Areas
SSH hardening (key-based auth, no root login)
FirewallD configuration
SELinux policy awareness
Log rotation + backups
🔹 Key Takeaway

Applied secure-by-default practices aligned with enterprise compliance (STIG mindset).

⚙️ Project 4: Automation & DevOps
🔹 Tools
Ansible
Bash
Jenkins (conceptual / pipeline workflows)
🔹 Work
Automated infrastructure tasks
Created reusable scripts
Reduced manual intervention
🔹 Key Takeaway

Improved consistency and reliability through automation.

🧪 Lab Environment
Layer	Setup
Host	Windows 11
Linux	WSL2 (Ubuntu)
VM	VirtualBox (CentOS 9)
Enterprise	VMware vSphere (experience)# BcoxPort
Portfolio Sample
