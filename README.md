# 👋 Hey, I'm Paulo Janoti

I'm a **Linux Systems Engineer** passionate about building and automating infrastructure at scale — from bare-metal to cloud, from Proxmox clusters to ML pipelines.

With **years of hands-on experience in infrastructure and DevOps**, I design, deploy, and maintain production environments spanning **SDN controllers, ZFS storage, container orchestration, and monitoring at scale** — while currently expanding into **Machine Learning Engineering** through a postgraduate program at FIAP (PosTech).

My day-to-day involves turning complex infrastructure problems into automated, observable, self-healing systems.

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat&logo=proxmox&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![ZFS](https://img.shields.io/badge/ZFS-2A667F?style=flat)
![Zabbix](https://img.shields.io/badge/Zabbix-D40000?style=flat&logo=zabbix&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-102230?style=flat)
![MLOps](https://img.shields.io/badge/MLOps-0A66C2?style=flat)

Core interests:

- Infrastructure as Code & GitOps
- Observability & Predictive Monitoring
- ML Engineering applied to Operations (AIOps)
- Network Automation & SDN

&nbsp;

## 🚀 Repositories worth checking out

### 🧠 [ML Engineering — FIAP PosTech Tech Challenge](https://github.com/Janoti/mlet-grupo4-tech-challenge)

Group project from the **FIAP PosTech ML Engineering** postgraduate program. Applied Machine Learning to real-world problems as part of the Tech Challenge curriculum — covering the full lifecycle from data exploration to model deployment.

---

### ⚙️ [SRE/DevOps Challenge](https://github.com/Janoti/desafio-sre-devops)

Infrastructure and DevOps challenge project showcasing skills in CI/CD, containerization, and cloud-native deployments.

&nbsp;

## 🃏 Side Project — VaultSpell

> *The all-in-one Magic: The Gathering companion app — built by a player, for players.*

🔗 **[vaultspell.com](https://vaultspell.com)**

- **Problem:** MTG players juggle 3–5 different tools just to manage their collection, build decks, track prices, and find local events.
- **Solution:** VaultSpell brings everything into one place — collection manager, AI-powered deck analysis, real-time price tracking (USD & BRL), wishlist, trade/sell marketplace, and a local events & stores directory.
- **Stack:** `React` · `Node.js` · `Scryfall API` · `AI/LLM` · `PostgreSQL`
- **Status:** Beta — actively developed, new features shipped weekly.
- Available in 🇧🇷 Portuguese · 🇺🇸 English · 🇪🇸 Spanish

![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

&nbsp;

## 🧪 Professional Experience & Private Projects

Projects built in production environments with proprietary code — happy to discuss the approaches and architectures behind them.

---

### 📊 ZFS Capacity Prediction (ML + n8n + Zabbix)

- **Problem:** Reactive storage management — teams only noticed ZFS pool exhaustion when alerts fired at critical thresholds.
- **Solution:** End-to-end ML pipeline that pulls historical Zabbix telemetry, runs linear regression (30/14/7-day windows with R² validation), and predicts days-until-full. Integrated with n8n for automated reporting.
- **Stack:** `Python`, `Zabbix API`, `n8n`, `Linear Regression`, `Parquet`, `Ollama/LLaMA`.

### 🌐 SDN Monitoring & Alerting Automation

- **Problem:** No centralized visibility into circuit distribution across SDN gateways; overloaded gateways went undetected.
- **Solution:** Automated workflow polling the WNC SDN controller API, tracking per-gateway circuit counts with stateful thresholds, and alerting via Rocket.Chat when gateways exceed capacity.
- **Stack:** `n8n`, `REST API`, `Rocket.Chat`, `JavaScript`.

### 🏗️ Proxmox/Ceph Cluster Automation

- **Problem:** Manual node provisioning with inconsistent configurations across sites (network bonds, Corosync, LDAP, ZFS pools).
- **Solution:** Ansible-driven automation for full node lifecycle — from network interface configuration (LACP bonds, VLAN-aware bridges, Corosync links) to FreeIPA/LDAP integration and ZFS pool creation. Idempotent playbooks covering 10+ sites.
- **Stack:** `Ansible`, `Proxmox API`, `Bash`, `FreeIPA`, `ZFS`.

### 🔍 ZFS Health Monitoring (Six-Axis Severity Model)

- **Problem:** Basic ZFS monitoring only caught failures after the fact; no early warning for degradation patterns.
- **Solution:** Extended telemetry wrapper scripts feeding a six-axis severity model (capacity, pool integrity, fragmentation, scrub health, snapshot health, ARC performance) into Zabbix, with LLM-generated analysis summaries.
- **Stack:** `Bash`, `Zabbix`, `Ollama/LLaMA`, `n8n`.

### 🎫 Jira Stale Ticket Detection & Notification

- **Problem:** Open tickets aging silently in the backlog with no visibility for the team.
- **Solution:** Automated weekly JQL queries detecting tickets open >7 days, with formatted card-style notifications pushed to Rocket.Chat including direct links and metadata.
- **Stack:** `n8n`, `Jira API`, `Rocket.Chat Webhooks`.

&nbsp;

## 📬 Contact

💼 **LinkedIn:** [linkedin.com/in/janotijr](https://linkedin.com/in/janotijr/)  
🐙 **GitHub:** [github.com/Janoti](https://github.com/Janoti)  
🃏 **VaultSpell:** [vaultspell.com](https://vaultspell.com)
