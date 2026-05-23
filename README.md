# homelab
Self-hosted homelab running on Linux Mint. Documents setup, configuration, and documentation for all services.

## Hardware

- **CPU:** Intel i7-9700K
- **GPU:** Nvidia RTX 3060 12GB
- **RAM:** 32GB DDR4
- **Boot Drive:** 500GB NVMe SSD
- **Storage:** 2TB Consumer HDD (dedicated to camera footage)
- **OS:** Linux Mint (headless, accessed via SSH)
- **Doorbell Camera:** Reolink Video Doorbell WiFi (2K, wired power, WiFi connected)
- **Network:** TP-Link Deco XE75 Pro (2-node mesh, wired backhaul) — Homelab connected via Ethernet

## Prerequisites

All services run in Docker containers All services run in Docker containers. Install Docker Engine before deploying any services:

- [Docker Engine Install Guide](https://docs.docker.com/engine/install/ubuntu/)
- [Docker Post-Install Steps](https://docs.docker.com/engine/install/linux-postinstall/)

## Services 

| Service | Description |
|--------|-------------|
| Portainer | Docker container management UI |
| Frigate | Local AI security camera system |
| Ollama | Local LLM runtime |
| Open WebUI | Web interface for Ollama |
| Home Assistant | Home automation platform |
