# Enterprise Network & Infrastructure Monitoring with Uptime Kuma

Tools for monitoring a Home LAB Server (Self-hosted) built on Proxmox VE using Docker. This system provides real-time visibility into the server's online/offline status as well as network health and performance.

## 🛠 Tech Stack
- **Platform:** Proxmox VE (LXC Container)
- **OS:** Ubuntu Server
- **Orchestration:** Docker Compose
- **Monitoring:** Uptime Kuma
- **Analytics:** Speedtest Tracker
- **Connectivity:** Cloudflare Tunnel 
- **Notifications:** Telegram Bot API

## Main Feature
- **Real-time Monitoring:** Monitor network device connections (Mikrotik/Switch) via ICMP.
- **Service Alerts:** Instant notification to Telegram if the network or connection is down.
- **Secure Remote Access:** Accessed through the Cloudflare subdomain without port forwarding.

  Example: https://monitor.profileaby.me/status/networklabs

##  Screenshots
![Dashboard Monitoring](./screenshots/dashboard_main.png)
![Status Page](./screenshots/status_page.png)

## ⚙ Installation Method
1. Clone this repository.
2. Run `docker-compose up -d`.
3. Access the dashboard on port 3001 (Uptime Kuma)

