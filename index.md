# Dave's Engineering Portfolio

Welcome — this repository is an index of my hands-on lab work in Linux systems administration, infrastructure automation, data engineering, and full-stack development. I'm a self-taught infrastructure/data engineer with 17+ years of experience (ETL pipelines, SQL development, Python automation, Salesforce integrations, cloud platforms), currently transitioning toward Linux/DevOps, Platform Engineering, SRE, and Data Engineering roles. Based in Washington, DC. Open to DC-area and remote positions.

Every project here was built to solve a real problem or close a real skills gap — not to check a box. Most were built alongside my preparation for the **Linux Foundation Certified System Administrator (LFCS)** exam, so a lot of the infrastructure work reflects that curriculum: LVM, systemd, networking, firewalls, storage, and automation at the command line.

## How this repo is organized

Each linked project has its own README with setup instructions, design notes, and — where relevant — the specific concepts it was built to demonstrate.

### Linux / Systems / DevOps
- **Home Lab** — A three-VM KVM/Vagrant topology (`lb01`/`app01`/`db01`) running Ubuntu Server 24.04, simulating a small company's infrastructure: SSH hardening, UFW firewall rules, user/role management, and a Python ETL pipeline into PostgreSQL, all scripted in shell with study annotations.
- **LFCS Study Environment** — A dedicated two-VM Vagrant practice-exam environment plus a 40+ task multi-day simulation lab covering Docker, NFS, LVM, iptables, and systemd against a realistic scenario.
- **Bash Logging Toolkit** — Shell scripting utilities for system logging and automation.
- **Firefox Backup Tool** — A Python backup script driven by systemd user timers, built after a real power-loss data corruption incident.

### Data Engineering
- **Salesforce → Snowflake Sync Pipeline** — A production-quality sync pipeline (Jupyter notebook) using Bulk API 2.0, incremental watermarks, and Snowflake `MERGE`, with schema drift handling and ODS enrichment columns.
- **ETL Pipeline** — General-purpose Python ETL work.
- **Weather Dashboard** — An Open-Meteo-driven notebook and Streamlit app with SQLite caching, live data pulls, and matplotlib visualizations.

### Full-Stack / Application Development
- **Django CRM** — Contact/Transaction/Event models, a custom CSV management command, and a Chart.js dashboard.
- **Django Homepage Lab** — A Docker + Nginx + gunicorn setup for prototyping and A/B-testing multiple homepage design variants with live-reload bind mounts.
- **Qt6/C++ Notes App** — A desktop notes application with a SQLite backend, demonstrating named connections, foreign key enforcement, parameterized queries, and a signal-mediator design pattern.

## Core skills demonstrated

`Linux Administration` `Bash` `Python` `SQL` `Docker` `Systemd` `Networking & Firewalls (iptables/UFW)` `LVM & Storage` `PostgreSQL` `SQLite` `Snowflake` `Salesforce Integration` `Django` `Git`

## About the LFCS focus

Several of these repos double as my study environment for the LFCS exam. I've deliberately built and rebuilt infrastructure by hand — provisioning VMs, hardening SSH, managing storage with LVM, writing systemd units, configuring NFS shares, and scripting firewall rules — rather than relying on managed tooling, so the labs reflect real command-line fluency rather than just conceptual familiarity.

## Contact

Feel free to reach out via GitHub or [LinkedIn](https://www.linkedin.com/in/david-adam-aparicio) if you'd like to talk about any of these projects or potential opportunities.
