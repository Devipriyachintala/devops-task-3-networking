# DevOps Internship – Task 3  
## Networking Basics for DevOps (AWS EC2)

This repository contains the implementation of basic networking diagnostics performed on an **AWS EC2 Ubuntu 22.04 LTS instance** using the Linux Command Line Interface. The objective of this task is to understand how systems communicate over a network and how to troubleshoot common connectivity, DNS, and service-related issues in a cloud environment.

---

## 🔧 Tools Used
- AWS EC2 (Ubuntu 22.04 LTS)
- Linux CLI (EC2 Instance Connect – Browser Terminal)
- GitHub

---

## 🧪 Task Description
The following networking concepts were practiced and verified:
- IP address identification
- Internet connectivity testing
- Open ports and services inspection
- DNS resolution
- Network path tracing
- Network failure simulation and recovery

---

## 🧾 Commands Overview
| Command | Description |
|---------|-------------|
| `ip a` | Displays network interfaces and assigned IP address |
| `ping 8.8.8.8` | Tests internet connectivity and latency |
| `ss -tuln` | Lists open TCP/UDP ports and services |
| `nslookup google.com` | Resolves domain name to IP address |
| `dig google.com` | Shows detailed DNS records |
| `traceroute google.com` | Traces network path to destination |

---

## ⚠️ Network Failure Simulation
Disabling the primary network interface results in loss of internet connectivity and SSH access to the EC2 instance.  
Connectivity was restored by stopping and restarting the instance from the AWS console, which reinitialized the network interface.

---

## 🎯 Final Outcome
This task helped build practical knowledge of:
- Cloud-based IP addressing
- Network connectivity testing
- DNS troubleshooting
- Port and service monitoring
- Real-world cloud network recovery

---

## 👤 Author
DevOps Intern – Task 3 Submission

