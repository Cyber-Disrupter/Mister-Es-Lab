# 🖥️ Hardware Lab: Master Control Station

## 🛠️ Core System Specifications
* **CPU:** AMD FX-6300 (6 Cores) - Optimized for multitasking and VM environments.
* **GPU:** NVIDIA GeForce GTX 750 Ti - Configured with proprietary drivers for dual-monitor stability.
* **OS:** Ubuntu 24.04 (XFCE Desktop Environment) - Lightweight, high-performance IT workstation.
* **Memory Management:** Configured for real-time monitoring of power and thermals.

## 📊 Visual Infrastructure
* **Monitor 1 (Main):** HP w2007 (1680x1050) - Horizontal workspace.
* **Monitor 2 (Vertical):** 768x1280 - Dedicated terminal and log monitoring.
* **Optimization:** NVIDIA 'Force Full Composition Pipeline' enabled to resolve screen tearing across mismatched resolutions.

## 🌐 Network Topology (The "Dad-Link")
* **Tunneling:** P2P WireGuard Mesh VPN via Tailscale.
* **Remote Node:** Legacy 32-bit (i686) Debian 12 (Bookworm) laptop.
* **Security:** SSH Key-based authentication with customized shell aliasing for rapid deployment.
