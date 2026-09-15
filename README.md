# 🐧 Red Hat System Administration II (RH134) - Comprehensive Mastery Guide

Welcome to the **Red Hat System Administration II (RH134)** repository! This repository serves as an advanced, hands-on reference for Enterprise Linux Administration, covering the complete curriculum of the second part of the Red Hat Certified System Administrator (RHCSA) track.

---

## 📌 Course Description

Red Hat System Administration II (RH134) is designed for IT professionals who have completed Red Hat System Administration I (RH124). This course goes deeper into core Linux system administration skills, including storage configuration and management, scalable installation and deployment of Red Hat Enterprise Linux (RHEL), management of security features such as SELinux and firewalls, control of recurring system tasks, management of the boot process and emergency troubleshooting, system tuning, command-line automation, and container administration.

---

## 📌 Repository Overview

This repo is designed to bridge theoretical concepts with real-world enterprise implementation:
* **Original Guide (`Linux_Administrator2_Original_Guide.pdf`):** Complete core curriculum slides and official materials.
* **Enhanced Mastery Guide (`/Linux-Admin-Enhanced-Mastery-Guide`):** A custom, highly detailed 6-part module series expanded with step-by-step CLI commands, practical notes, troubleshooting workflows, and real-world system admin insights.

---

## 🎯 Key Learning Outcomes

Upon completing this course material, you will be able to:
* Install Red Hat Enterprise Linux using scalable methods (Kickstart).
* Access and secure files, file systems, and network resources.
* Execute shell scripting and CLI automation techniques.
* Manage storage devices, logical volumes, swap space, and advanced file systems.
* Control security policies, SELinux contexts, and system access.
* Control the boot process, systemd targets, and core system services.
* Run, inspect, and manage rootless containers using Podman.

---

## 🛠️ Comprehensive Technical Topics & Applied Skills

### 📜 1. Shell Scripting & Command-Line Automation
* Writing automated Bash scripts using `for` loops, `while` loops, and `test` constructs.
* Automating network management and diagnostic scripts (e.g., `ifconfig` parsing and automated connectivity checks).

### ⏰ 2. Task Scheduling & Automation
* Scheduling non-recurring future tasks using `at`.
* Configuring recurring system and user cron jobs via `crontab`.

### ⚡ 3. System Performance Tuning & Cockpit Management
* System performance analysis and profile optimization using `tuned`.
* Managing, creating, and applying custom tuning profiles.
* Web-based server monitoring and administration using **Red Hat Cockpit**.

### 🔐 4. Advanced Access Control (ACLs)
* Fine-grained permission management using Access Control Lists (ACLs).
* Viewing, modifying, and troubleshooting file permissions with `getfacl` and `setfacl`.
* Managing effective rights using ACL masks.

### 🛡️ 5. SELinux Security & Management
* Core SELinux architecture: Enforcing, Permissive, and Disabled modes.
* Managing SELinux labels, file contexts, and Booleans.
* Adding, modifying, and restoring default contexts (`semanage fcontext`, `restorecon`).
* Advanced SELinux troubleshooting and log analysis (`audit.log`, `sealert`).

### 💾 6. Basic Storage & Disk Partitioning
* Partitioning storage devices using MBR and GPT partition schemes (`fdisk`, `gdisk`, `parted`).
* Creating, activating, and managing Swap space.

### 🗄️ 7. Logical Volume Management (LVM)
* Physical Volumes (PV), Volume Groups (VG), and Logical Volumes (LV) creation.
* Dynamic volume expansion, filesystem resizing, and storage allocation.

### 🚀 8. Advanced Storage Solutions & NFS
* **Stratis Storage:** Hybrid storage management, pool creation, and snapshot management.
* **Network File System (NFS):** Setting up NFS servers, exporting shares, mounting NFS shares, and persistence configuration.

### 🧱 9. Boot Process Control & Firewall Security
* Controlling the GRUB2 boot process, target isolation (`systemd`), and emergency mode recovery.
* Enterprise network security management using `firewalld`, managing active zones, ports, services, and rich rules.

### 💿 10. Automated RHEL Installation
* Unattended and scalable Red Hat Enterprise Linux installation using **Kickstart** configuration files.

### 🐳 11. Container Management & Deployment
* Running, managing, and inspecting rootless containers using Podman.
* Container image handling, registry interaction, and storage mounting.

---

## 🤝 Connect & Inquiries

Maintained by **Mahmoud Elhalawany** (IT & Computer Networks Engineer - Delta Technological University).

* 💼 **LinkedIn:** [Mahmoud Elhalawany Profile](www.linkedin.com/in/mahmoud-walid-elhalawany)
* 📞 **Phone:** 01026146606
* 📧 **Open for Internship / Trainee opportunities in Systems Administration & DevOps.**
