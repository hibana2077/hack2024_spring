---
marp: true
theme: gaia
class: invert
---

<!-- _backgroundImage: url('https://marp.app/assets/hero-background.jpg')-->
<!-- _class: lead -->

# Greenbone X 滲透測試平台

---

# 簡介

- 課程目標
    - Docker 的基本操作
    - Greenbone 的基本操作
    - 滲透測試的基本操作

---

# Docker 介紹與安裝

Docker 是一個開源的容器化平台，它允許開發者將應用程式及其依賴項打包到一個容器中。這個容器可以在任何支持Docker的系統上運行，確保了應用程式在不同環境間的一致性和可移植性。這對於開發、測試和生產環境的一致性提供了極大的便利。

---

## Docker 架構

![w:900](./basic_taxonomy.png)

---

## Docker Overview

![w:900](./docker_overview.png)

---

## Docker 安裝

- Windows
    - [Docker Desktop](https://www.docker.com/products/docker-desktop)

- Mac
    - [Docker Desktop](https://www.docker.com/products/docker-desktop)

- Linux
    - ```bash
      sudo apt-get update
      curl -sSL https://get.docker.com | sh
      ```

---

# Greenbone 介紹與安裝

Greenbone Security Manager (GSM) 是一款強大的漏洞管理解決方案，用於識別、管理和減輕網絡安全風險。它是基於開源漏洞管理工具OpenVAS的商業版本，提供全面的漏洞掃描、網絡監測以及報告功能。

![](./greenbone.png)

---

#### 為什麼使用Greenbone?
- **全面的安全評估**：提供廣泛的漏洞掃描覆蓋，從網絡服務到應用程序層面的弱點。
- **持續監控**：能夠持續監控網絡狀態，即時發現新的或已知的漏洞。
- **易於管理的報告功能**：生成詳細的安全報告，幫助分析風險並規劃糾正措施。

---

## Greenbone 安裝

```bash
git clone https://github.com/hibana2077/hack2024_spring.git
cd hack2024_spring
cd greenbone
```

Windows

```bash
docker-compose up -d
```

Linux

```bash
sudo docker-compose up -d
```

## Greenbone 登入

- 網址：[http://localhost:9392](https://localhost:9392)