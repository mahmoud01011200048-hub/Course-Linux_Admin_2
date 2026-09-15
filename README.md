# 🐧 Red Hat System Administration II (RH134) - Comprehensive Mastery Guide

Welcome to the **Red Hat System Administration II (RH134)** repository! This repository serves as an advanced, hands-on reference for Enterprise Linux Administration, covering the second half of the Red Hat Certified System Administrator (RHCSA) track.

---

## 📌 Repository Overview

This repo is designed to bridge theoretical concepts with real-world enterprise implementation:
* **Original Guide (`Linux_Administrator2_Original_Guide.pdf`):** Complete core curriculum slides and official materials.
* **Enhanced Mastery Guide (`/Linux-Admin-Enhanced-Mastery-Guide`):** A custom, highly detailed 6-part module series expanded with step-by-step CLI commands, practical notes, troubleshooting workflows, and real-world system admin insights.

---

## 🛠️ Key Topics & Skills Covered

### 💾 1. Storage Configuration & Management
* Partitioning storage devices using `fdisk`, `gdisk`, and `parted`.
* Logical Volume Manager (LVM) creation, resizing, and volume group management.
* Advanced file systems, swap space configuration, and storage troubleshooting.

### 🛡️ 2. Security & System Access
* **SELinux:** Managing modes, booleans, file contexts, and troubleshooting policy violations.
* **Firewall Management:** Configuring `firewalld`, ports, rich rules, and service zones.
* User security, PAM, and SSH key-based access control.

### 🚀 3. Boot Process, Services & System Tuning
* Controlling the GRUB2 boot process, targets, and emergency repair modes.
* Systemd service unit management, system target isolation, and socket activation.
* Basic system performance tuning and process prioritization (`nice` / `renice`).

### ⚡ 4. Command-Line Automation & Scripting
* Shell scripting techniques for automated system task execution.
* Scheduling recurring system tasks using `cron` and `at`.

### 🐳 5. Container Administration
* Running, managing, and inspecting rootless containers using Podman.
* Managing container images, registries, and persistent storage integration.

---

## 📂 Repository Structure

```text
.
├── Linux_Administrator2_Original_Guide.pdf    # Full original course material
├── Linux-Admin-Enhanced-Mastery-Guide/         # 6-Part expanded module notes & labs
│   ├── Part_01_Storage_and_LVM.pdf
│   ├── Part_02_SELinux_and_Security.pdf
│   ├── Part_03_Boot_Process_and_Troubleshooting.pdf
│   ├── Part_04_Automation_and_Scripting.pdf
│   ├── Part_05_Container_Management.pdf
│   └── Part_06_System_Tuning.pdf
└── README.md                                  # Documentation
