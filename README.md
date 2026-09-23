<div align="center">

# 🔐 Cybersecurity Lab Environment Setup

**Building an isolated virtual lab for penetration testing and ethical hacking practice**
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ver-Virtualbox%20v7.2-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Kali%20Linux-v2026.2-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Linux-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Network-10.0.0.0%2F24-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-C00000?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Virtualization-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Kali%20Linux-404040?style=flat-square&labelColor=C00000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/NetworkWalks-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Waqas%20Karim%20CCIE-C00000?style=flat-square" />
</p>

---

I managed to set up my first Cybersecurity lab setup and it was successful.

# 🛡️ Virtual Cybersecurity Lab Environment

## 📌 Project Overview

This project documents the creation of a virtual cybersecurity laboratory using
VirtualBox and Kali Linux.

The laboratory provides a controlled environment for learning and practicing
cybersecurity concepts, network administration, reconnaissance, security
assessment, and other authorized security-testing techniques.

The virtual environment uses an isolated NAT Network, allowing virtual machines
to communicate within a controlled network while maintaining connectivity
through the configured virtual network.

---

## 🎯 Project Objectives

The main goals of this laboratory setup are to:

- Install and configure Oracle VirtualBox.
- Set up Kali Linux as a virtual machine.
- Create a dedicated NAT Network for the laboratory.
- Configure Kali Linux network connectivity.
- Assign and verify the required IP configuration.
- Test communication between the virtual machine and the network gateway.
- Verify external connectivity and DNS resolution.
- Create a VM snapshot for easy recovery.
- Document the configuration and troubleshooting process.
- Establish a foundation for future cybersecurity laboratory exercises.

---

## 🔐 Laboratory Environment

The laboratory consists of a virtualized network designed specifically for
cybersecurity learning and authorized testing.

### Main Components

| Component | Configuration |
|-----------|---------------|
| Hypervisor | Oracle VirtualBox |
| Operating System | Kali Linux |
| Network Type | NAT Network |
| Network Address | `10.0.0.0/24` |
| Gateway | `10.0.0.1` |
| DNS Server | `8.8.8.8` |
| Network Interface | `eth0` |

> **Note:** Network addresses and interface names may differ depending on the
> VirtualBox and Kali Linux configuration.

---

## 💡 Key Takeaways

Working on this project helped me understand how to build and prepare an isolated virtual environment for cybersecurity training and practical exercises.

Some of the main concepts I gained knowledge of include:

### 1. NAT and NAT Network

I learned that VirtualBox provides different networking modes for virtual machines, including standard NAT and NAT Network.

A NAT Network makes it possible for several virtual machines to operate on the same private virtual network. The machines can communicate with each other while still being able to access external networks through network address translation.

This type of setup is useful when creating a controlled environment for cybersecurity labs involving multiple virtual machines.

### 2. Virtual Machine Networking

I learned how VirtualBox network adapters are used to connect virtual machines to different network environments.

The network mode selected for a virtual machine affects how that machine communicates with other virtual machines, the host computer, and external networks.

Understanding these settings is important when preparing an isolated cybersecurity testing environment.

### 3. Static IP Configuration

I gained practical experience configuring IPv4 network settings in Kali Linux.

This included working with:

- IP addresses
- Subnet masks
- Default gateways
- DNS servers

I also learned how to verify that the network configuration is working correctly after applying the settings.

### 4. Virtual Machine Snapshots

I learned the importance of creating a snapshot of a virtual machine before carrying out experimental or potentially disruptive cybersecurity activities.

A snapshot provides a restore point that can be used to return the virtual machine to a previous working state if something goes wrong.

This is particularly useful when experimenting with different configurations and cybersecurity tools.

### 5. Project Documentation

Another important lesson was the value of documenting the work carried out during a technical project.

Recording commands, configurations, screenshots, errors, troubleshooting steps, and solutions makes the project easier to understand, reproduce, and review.

Good documentation is an important part of maintaining a professional cybersecurity project.

---

## 🔐 Security and Ethical Use

This laboratory environment was created for educational and cybersecurity training purposes.

All testing and experimentation should be performed only on systems and networks where permission has been granted.

The virtual environment provides a controlled space for learning networking, system configuration, cybersecurity tools, and penetration-testing concepts without intentionally affecting unauthorized systems.

---

## 🔗 Tools and Resources

The following resources were useful during the setup and configuration of the laboratory:

- **7-Zip:** https://7-zip.org/download.html
- **VirtualBox:** https://virtualbox.org/wiki/Downloads
- **Kali Linux:** https://kali.org/get-kali

These resources provide the software and documentation required for setting up the virtual cybersecurity environment.

---

## 👤 Author

**Tiffany Lucia**

Cybersecurity Learner / Student

GitHub: []

LinkedIn: []

---

## 📌 Project Information

**Program:** Cybersecurity Training

**Week:** 01

**Project:** Virtual Cybersecurity Laboratory Setup

**Environment:** VirtualBox + Kali Linux

**Network Type:** NAT Network

**Network Range:** `10.0.0.0/24`

**Repository:** GitHub

---

## 📝 Final Note

This project provided practical experience with virtual machines, network configuration, Kali Linux, and documentation. It also established a controlled environment that can be used for future cybersecurity exercises and additional laboratory activities.
---

