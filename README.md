<h1 align="center">
  🌐 Dockerized Network Monitoring Dashboard
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana">
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white" alt="Prometheus">
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey?style=for-the-badge" alt="Platform">
</p>

<p align="center">
  <strong>A fully automated, production-ready network and system monitoring solution.</strong><br>
  <i>Developed by <b>Shenol Perera</b></i>
</p>

<hr>

## 📖 Table of Contents
- [🌟 Overview](#-overview)
- [✨ Features](#-features)
- [🚀 Quick Start (A to Z)](#-quick-start-a-to-z)
- [📊 Using the Dashboard](#-using-the-dashboard)
- [🛑 Managing Services](#-managing-services)
- [📁 Project Structure](#-project-structure)

---

## 🌟 Overview
This project provides a **"one-click"** monitoring stack that tracks your hardware and network metrics in real-time. It uses **Node Exporter** to collect system metrics, **Prometheus** to store them, and **Grafana** to visualize them on a beautiful, auto-configured dashboard.

> **Note:** Zero manual configuration is required! Thanks to Grafana Provisioning, the dashboard and data sources load automatically on startup.

---

## ✨ Features
* 📦 **One-Click Deployment:** Spin everything up with a single `docker compose` command.
* ⚙️ **Automated Provisioning:** Dashboards and data sources are pre-linked.
* 📈 **Live Metrics Tracking:**
  * Network Traffic (Rx/Tx, Bandwidth, Packets)
  * CPU Usage, Load Averages & Temperatures
  * RAM & Swap Consumption
  * Disk Space & I/O usage
* 🎨 **Custom Branding:** Includes a personalized layout.
* 🐳 **100% Containerized:** Clean, isolated, and easy to remove.

---

## 🚀 Quick Start (A to Z)

### Prerequisites
1. **[Docker Desktop](https://www.docker.com/products/docker-desktop/)**: Ensure Docker is installed and the engine is running (look for the green whale icon).
2. **Git** *(Optional)*: For cloning the repository.

### Step 1: Get the Project
Clone this repository to your machine, or download and extract the ZIP file.
```bash
git clone <YOUR-GITHUB-REPO-LINK>
cd <YOUR-REPO-FOLDER-NAME>
