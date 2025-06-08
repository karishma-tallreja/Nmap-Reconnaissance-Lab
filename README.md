# 🔐 Nmap Reconnaissance & Network Scanning Lab

## 📘 Objective
- Perform network reconnaissance using **Nmap** in a secure host-only virtual network.
- Identify systems and enumerate services running on three isolated **DSL servers**.
- Learn how attackers gather intelligence during the reconnaissance phase.

---

## 🛠️ Tools & Environment
- **VMware Workstation** – to set up isolated virtual machines  
- **Damn Small Linux (DSL)** – lightweight Linux distro used as scanning targets  
- **Zenmap (GUI for Nmap)** – for network scanning and analysis  
- **Command Prompt & ifconfig** – to identify local and VM IP addresses  
- **VMnet1 (Host-Only Network)** – to isolate the test lab from public networks  

---

## 📚 Skills Learned
- Network scanning and subnet targeting using Nmap
- Detecting open ports and identifying services (FTP, SSH, HTTP)
- Understanding network topology using scan visualization
- Setting up secure, isolated test environments
- Basics of reconnaissance and enumeration in ethical hacking

---

## 🧪 Scan Methods Used
- 🔍 Intense Scan  
- 🔎 Intense Scan (All TCP Ports)  
- 🚀 Quick Traceroute  
- 🐢 Slow Comprehensive Scan  

---

## 🖼️ Screenshots

### 1️⃣ Nmap Output Tab – DSL Server Selected  
Displays output for DSL server `192.168.217.129`, showing open ports like FTP and SSH.

> ![Nmap Output Tab - DSL1](https://i.imgur.com/i1lDsoa.png)

---

### 2️⃣ Topology Tab – Network Map  
Visual network layout detected by Nmap. Includes the Windows host and three DSL VMs, all with clearly visible IPs.

> ![Topology Tab - All Hosts](https://i.imgur.com/5Dl8aeC.png)

---

### 3️⃣ Ports/Hosts Tab – DSL Server A  
- Target: `192.168.217.129`  
- Services Detected:  
  - FTP (vsftpd)  
  - SSH (OpenSSH)

> ![Ports Tab - FTP & SSH](https://i.imgur.com/7ldmuLP.png)

---

### 4️⃣ Ports/Hosts Tab – DSL Server B  
- Target: `192.168.217.130`  
- Services Detected:  
  - SSH (OpenSSH)  
  - HTTP (Monkey Web Server)

> ![Ports Tab - SSH & HTTP](https://i.imgur.com/VAcfFwd.png)

---

## 📝 Summary
This lab focused on simulating an attacker’s reconnaissance efforts using **Nmap** in a private virtual environment. By configuring three **DSL servers** with distinct service sets (FTP, SSH, HTTP), I scanned and analyzed the network to extract system and service-level data. The exercise enhanced my understanding of how vulnerabilities are discovered during the early stages of an attack and reinforced the importance of minimizing exposed services on production systems.

---


