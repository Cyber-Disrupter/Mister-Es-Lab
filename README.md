# 🛡️ Cybersecurity & IT Support Learning Lab
**[Google IT Support & Google Cybersecurity Professional Certified]**

Welcome to my documentation repository. This space serves as a live application of the concepts covered in my professional certifications. I use this lab to practice **Network Security**, **System Optimization**, and **Legacy Hardware Support** in a multi-node Linux environment.

---

## 🖥️ Lab Infrastructure: "Master Control"
I have configured a custom **XFCE "Hacker Dashboard"** on **Ubuntu 24.04** to monitor system vitals and security tools in real-time.

* **Workstation Hardware:** AMD FX-6300 (6-Core) | NVIDIA GeForce GTX 750 Ti.
* **Display Configuration:** Dual-monitor setup (1680x1050 horizontal and 768x1280 vertical) optimized for log analysis and terminal multitasking.
* **Remote Connectivity:** Secured P2P Mesh VPN via **Tailscale (WireGuard)** connecting to a remote legacy node.

---

## 🔍 Security Research & Toolset (Learning Journey)
My current focus is on understanding the practical implementation of security tools within a home lab setting:

* **Wireshark:** Capturing and analyzing traffic on the `tailscale0` interface to study encrypted packet headers and network protocols.
* **Burp Suite:** Exploring the fundamentals of web application security and HTTP/S interception.
* **Bash Automation:** Developed custom scripts for **XFCE Genmon** and **Netsweep** to automate asset discovery and hardware health monitoring.
* **Legacy Support:** Successfully deployed and secured a **Debian 12 "Bookworm" (32-bit)** remote node for technical support simulations.

---

## 🛠️ Documented Troubleshooting Cases
* **Display Mapping:** Resolved screen tearing on legacy NVIDIA hardware using `ForceFullCompositionPipeline`.
* **Environment Recovery:** Restored XFCE panel configurations and UI elements following proprietary driver migrations.
* **Permission Management:** Navigated Linux access controls to manage system-level services like Tailscale via the terminal
