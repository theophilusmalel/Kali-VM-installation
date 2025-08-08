---
layout: single
title: "Lab - Deploy a Pre-Built Kali Linux Virtual Machine (VM)"
author: "Your Name"
toc: true
toc_label: "Contents"
toc_sticky: true
---

Welcome to the **Kali Linux VM Deployment Lab** guide.  
This lab shows how to deploy a **pre-built customized Kali Linux Virtual Machine (VM)** on **Windows** using **Oracle VirtualBox**, and then explore basic Linux commands.

---

## 🎯 Objectives
In this lab, you will complete the following:
1. Deploy a customized Kali Linux VM on AMD or Intel chip-based computers.
2. Explore Linux commands, root privileges, and keyboard shortcuts.

---

## 🖥 Environment
- **Host OS:** Windows 10/11 (64-bit)
- **Virtualization Software:** Oracle VirtualBox
- **VM OS:** Kali Linux (Pre-built OVA from NetAcad)
- **Minimum Requirements:**
  - 4 GB RAM (8 GB recommended)
  - 50 GB free disk space
  - Internet access

---

## 🚀 Deployment Steps

### Part 1: Install VirtualBox
1. Go to [VirtualBox.org](https://www.virtualbox.org/).
2. Download the Windows installer.
3. Install using default options.

---

### Part 2: Download the Pre-Built Kali OVA
1. Log in to the [NetAcad Resource Hub](https://www.netacad.com/).
2. Download the **Kali.ova** file.
3. Save it in a known location.

---

### Part 3: Import Kali OVA into VirtualBox
1. Open VirtualBox.
2. Go to **File → Import Appliance**.
3. Select `Kali.ova`.
4. Adjust RAM if needed.
5. Click **Finish**.
6. Start the VM.

---

## 🐧 Exploring Linux

### Root Privileges
- `su` – switch to root user.
- `sudo` – run commands with admin privileges.

Example:
```bash
sudo visudo
