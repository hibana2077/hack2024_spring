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