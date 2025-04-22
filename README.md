# OPS205-LAMP-WordPress-Deployment
Configured a secure LAMP stack and deployed WordPress on a CLI-based Ubuntu server, using nftables for firewall protection. Completed as part of OPS205 at Seneca Polytechnic.

# LAMP Stack and WordPress Deployment – OPS205 Assignment 2

**Course:** OPS205 – Open Source Operating Systems  
**Date:** November 2023  
**Institution:** Seneca Polytechnic

---

## 🧠 Overview
This project involved deploying a full LAMP stack (Linux, Apache, MariaDB, PHP) on a fresh Ubuntu VM, then using it to host a WordPress blog. The setup was manually configured for security, optimized to run in command-line interface (CLI) mode, and hardened using `nftables` firewall rules.

---

## 🛠️ Tasks Performed
- Created a new Ubuntu virtual machine (full GUI install converted to CLI mode)
- Configured a static IP using Netplan
- Set up hostname resolution using the `/etc/hosts` file
- Installed and configured the following:
  - **Apache2** – Web server
  - **PHP & php-mysql** – Server-side scripting and DB integration
  - **MariaDB** – MySQL-compatible database backend
  - **WordPress** – CMS for blog creation
- Created and secured a dedicated WordPress database and user
- Configured Apache virtual hosting for WordPress at `/blog`

---

## 🔐 Firewall & System Security
- Installed and enabled **nftables** as the primary firewall
- Disabled UFW to avoid service conflicts
- Configured firewall rules to:
  - Allow HTTP (port 80) and SSH (port 22)
  - Permit DNS and APT traffic
  - Drop all other incoming traffic by default

---

## 📝 WordPress Blog Posts (Created via Web UI)
1. **Tech Stack Explained**
   - Breakdown of Apache, PHP, MariaDB, and WordPress roles
   - Installation challenges and how they were resolved
2. **Exam Readiness Reflection**
   - Self-assessment of strengths, concerns, and questions for review

---

## 🧠 Skills Demonstrated
- Full-stack web environment deployment
- Ubuntu system configuration via CLI
- Apache virtual host management
- MySQL database setup for CMS
- Secure firewall setup using `nftables`
- Web-based content management with WordPress

---

## 📂 Notes
Screenshots were not retained for this project. However, all deployment steps, configurations, and validations (including the instructor's check script `marka2.bash`) were successfully completed during the lab period.

---

## ✅ Project Status
- ✔️ WordPress blog deployed and accessible
- ✔️ LAMP stack operational with custom DB
- ✔️ Firewall hardened and configured properly

