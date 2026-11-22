# kali-linux-setup
Week 1 Cybersecurity Internship - Kali Linux Installation and Setup
# 🔐 Kali Linux Lab Setup

### CYBERSECURITY INTERNSHIP · WEEK 01

Building my cybersecurity foundation, one lab at a time.

A documented setup of my Kali Linux virtual machine using VMware Workstation Pro on Windows.

---

## 📌 Table of Contents

- [🎯 Project Overview](#-project-overview)
- [🛠️ Lab Environment](#-lab-environment)
- [⚙️ Network Configuration](#️-network-configuration)
- [🚀 Setup Process](#-setup-process)
- [🌐 Internet Connectivity Test](#-internet-connectivity-test)
- [📸 Screenshots](#-screenshots)
- [✅ Week 1 Checklist](#-week-1-checklist)
- [📚 Key Learnings](#-key-learnings)
- [👩‍💻 Author](#-author)

---

## 🎯 Project Overview

The objective of this task was to set up and run a functional Kali Linux virtual machine as the foundation for hands-on cybersecurity learning.

I downloaded and set up Kali Linux using VMware Workstation Pro and verified that the virtual machine boots successfully and has internet connectivity.

### Objectives

- Set up Kali Linux in a virtualized environment.
- Explore the Kali Linux desktop and terminal.
- Verify system information and configuration.
- Check the assigned IP address and network configuration.
- Test internet connectivity from inside Kali Linux.
- Document the setup with screenshots.

---

## 🛠️ Lab Environment

| Component | Configuration |
|---|---|
| Name | [Your Name] |
| Program | Cybersecurity Internship |
| Task | Week 1 — Kali Linux Lab Setup |
| Host Operating System | Windows |
| Virtualization Software | VMware Workstation Pro |
| Guest Operating System | Kali Linux |
| Installation Method | [Prebuilt VMware image / ISO installation] |
| Desktop Environment | [Your desktop environment] |
| Network Adapter Mode | [NAT / Bridged] |
| Kali Linux IPv4 Address | [Your actual IP address] |
| Internet Connectivity | [Working / Not working] |

> Note: The IP address assigned to the virtual machine may change depending on the network and DHCP configuration.

---

## ⚙️ Network Configuration

The Kali Linux virtual machine uses a network adapter configured through VMware Workstation Pro.

The network adapter allows the virtual machine to communicate with other devices and access the internet, depending on its configuration.

### Configuration Details

| Setting | Value |
|---|---|
| Network Adapter | [NAT / Bridged] |
| IPv4 Address | [Your actual IPv4 address] |
| Connectivity | [Verified / Not verified] |

### Check the IP Address

Open the Kali Linux terminal and execute:

```bash
ip addr
```

Locate the active network interface and check its IPv4 address.

To inspect the routing configuration, use:

```bash
ip route
```

---

## 🚀 Setup Process

### Step 1 — Download Kali Linux

Downloaded Kali Linux from the official Kali Linux website.

Official download page: https://www.kali.org/get-kali/

### Step 2 — Set Up Kali Linux

Prepared the Kali Linux virtual machine for use with VMware Workstation Pro.

### Step 3 — Open VMware Workstation Pro

Opened VMware Workstation Pro and selected the Kali Linux virtual machine.

### Step 4 — Boot Kali Linux

Started the virtual machine and confirmed that Kali Linux booted successfully into the desktop environment.

### Step 5 — Explore the Linux Environment

Opened the Kali Linux terminal and executed basic Linux commands to inspect the system.

### Step 6 — Verify Network Connectivity

Checked the assigned IP address and tested connectivity using the `ping` command.

---

## 🌐 Internet Connectivity Test

To verify connectivity from Kali Linux, open the terminal and run:

```bash
ping -c 4 google.com
```

This sends four ICMP echo requests to Google's domain.

### Expected Result

Successful connectivity typically produces replies similar to:

```text
64 bytes from ...: icmp_seq=1 ttl=... time=... ms
64 bytes from ...: icmp_seq=2 ttl=... time=... ms
64 bytes from ...: icmp_seq=3 ttl=... time=... ms
64 bytes from ...: icmp_seq=4 ttl=... time=... ms
```

The exact response times and TTL values may vary.

**Interpretation:** Successful replies indicate that the virtual machine can reach the destination and resolve its domain name.

---

## 📸 Screenshots

Screenshots documenting the actual setup should be added to the repository's `screenshots/` folder.

| Screenshot | Description |
|---|---|
| `01-kali-desktop.png` | Kali Linux running in VMware Workstation Pro |
| `02-username.png` | Terminal showing the current username |
| `03-os-version.png` | Operating system information |
| `04-kernel-version.png` | Linux kernel version |
| `05-disk-space.png` | Disk space information |
| `06-memory.png` | Memory usage |
| `07-ip-address.png` | Terminal output showing the assigned IPv4 address |
| `08-network-interfaces.png` | Network interface information |
| `09-internet-connectivity.png` | Terminal output from the connectivity test |
| `10-dns-resolution.png` | DNS resolution verification |

### 🖼️ Lab Preview

**Kali Linux Desktop**

![Kali Linux Desktop](screenshots/01-kali-desktop.png)

**Network Configuration**

![Network Configuration](screenshots/07-ip-address.png)

**IP Address Verification**

![IP Address Verification](screenshots/07-ip-address.png)

**Internet Connectivity**

![Internet Connectivity](screenshots/09-internet-connectivity.png)

> Important: These image paths will display correctly only after you upload the corresponding screenshots to the `screenshots/` folder.

---

## ✅ Week 1 Checklist

- [x] Downloaded Kali Linux.
- [x] Set up the Kali Linux virtual machine.
- [x] Opened the virtual machine in VMware Workstation Pro.
- [x] Booted Kali Linux successfully.
- [x] Accessed the Kali Linux desktop environment.
- [x] Explored the Linux terminal.
- [x] Checked operating system information.
- [x] Verified kernel version and architecture.
- [x] Checked disk space and memory.
- [x] Verified the assigned IP address.
- [x] Checked network interfaces and routing configuration.
- [x] Tested internet connectivity.
- [x] Documented the lab setup for the internship.

---

## 📚 Key Learnings

Through this setup, I gained practical familiarity with:

- **Virtualization:** Running a Linux operating system inside a virtual machine.
- **Kali Linux:** Accessing and exploring a Linux environment for cybersecurity learning.
- **Linux Commands:** Using basic terminal commands to inspect the operating system.
- **Network Adapters:** Understanding virtual machine network configuration.
- **IP Addressing:** Identifying the virtual machine's assigned IPv4 address.
- **Network Diagnostics:** Using `ip addr`, `ip route`, and `ping` to inspect connectivity.
- **Technical Documentation:** Recording the lab configuration and verification process in GitHub.

---

## 👩‍💻 Author

Sufiyan Pathan

Cybersecurity Intern

Week 1 — Kali Linux Lab Setup

---

🔐 Learn · Practice · Document · Improve

Building a strong foundation in cybersecurity.
