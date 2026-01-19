# DevOps Internship – Task 3  
## Networking Basics for DevOps (AWS EC2)

This repository demonstrates basic networking diagnostics performed on an **AWS EC2 Ubuntu 22.04 LTS instance** using the Linux Command Line Interface. The task focuses on understanding how systems communicate over networks, including IP addressing, connectivity testing, DNS resolution, open port inspection, and network path tracing.

---

## 🔧 Tools Used
- AWS EC2 (Ubuntu 22.04 LTS)
- Linux CLI (EC2 Instance Connect / Browser Terminal)
- GitHub

---

## 📁 Repository Structure
 

---

## 🧪 Task Overview
The following networking operations were performed on a cloud-based Linux server:

- IP address identification
- Internet connectivity testing
- Open port and service inspection
- DNS resolution and analysis
- Network path tracing
- Network failure simulation and recovery

---

## 🧾 Commands Used
- `ip a` — Display network interfaces and IP address
- `ping 8.8.8.8` — Test internet connectivity
- `ss -tuln` — List open ports and services
- `nslookup google.com` — Resolve domain name to IP
- `dig google.com` — View advanced DNS details
- `traceroute google.com` — Trace network path

(See `COMMANDS.md` for detailed explanations.)

---

## ⚠️ Network Failure Simulation
Disabling the primary network interface results in loss of connectivity and SSH access to the EC2 instance.  
Connectivity was restored by stopping and restarting the instance, which reinitialized the network interface.

---

## 🎯 Final Outcome
By completing this task, practical understanding was gained in:
- Cloud-based IP addressing
- Internet connectivity testing
- DNS troubleshooting
- Service port inspection
- Network path analysis
- Real-world DevOps recovery techniques

---

## 👤 Author
DevOps Intern – Task 3 Submission
