# 👋 Hello, I'm ShaoG-R

这里汇集了我最近维护和开发的开源项目，主要专注于 **Rust 高性能基础设施**、**Cloudflare Serverless 应用** 以及 **NixOS 自动化运维**。

## 🚀 核心项目概览 | Featured Projects

### 🦀 Rust 高性能组件与库 (High Performance Rust)

| 项目 | 简介 | 核心特性 |
|------|------|----------|
| **[SMR-Swap](https://github.com/ShaoG-R/smr-swap)** | **高性能单写多读交换容器**<br>专为读多写少场景设计的高性能并发原语。 | • Wait-Free 读取<br>• 基于版本的内存回收 (Safe Reclamation)<br>• 性能优于 `RwLock` / `ArcSwap` |
| **[LfrLock](https://github.com/ShaoG-R/lfrlock)** | **无锁读取锁 (Lock-Free Read Lock)**<br>高性能无锁读取、串行写入并发原语。 | • Wait-Free 读取<br>• 类似 Mutex 的易用 API (`write()` Guard)<br>• 读密集场景性能极佳 |
| **[Kestrel Timer](https://github.com/ShaoG-R/kestrel-timer)** | **分层时间轮异步定时器**<br>基于 Hierarchical Timing Wheels 算法的高效定时器库。 | • O(1) 时间复杂度<br>• 双层时间轮 (L0/L1) 自动分层<br>• 支持 10,000+ 高并发任务 |
| **[Hydra-DL](https://github.com/ShaoG-R/hydra-dl)** | **多线程极速下载器**<br>功能强大的现代化下载工具与 Rust 库。 | • 动态智能分块 (Dynamic Chunking)<br>• 渐进式 Worker 启动<br>• 支持 CLI 与 Library 双模式 |

### ☁️ Serverless 与 Web 应用 (Cloud & Web)

| 项目 | 简介 | 技术栈 |
|------|------|--------|
| **[VerWatch](https://github.com/ShaoG-R/verwatch)** | **Serverless GitHub 版本看门狗**<br>运行在 Cloudflare 边缘的 Release 监控服务，支持自动触发 Actions。 | • **Backend**: Rust + Cloudflare Workers (Durable Objects)<br>• **Frontend**: Leptos Dashboard (Rust + Wasm)<br>• 强一致性与高可用设计 |

### 🛠️ 运维与基础设施 (Infrastructure / DevOps)

| 项目 | 简介 | 亮点 |
|------|------|------|
| **[NixOS Config](https://github.com/ShaoG-R/nixos-config)** | **模块化 NixOS 服务器配置**<br>机制与策略分离的现代化服务器配置库。 | • **内核调优**: CachyOS Kernel + BBRv3<br>• **网络优化**: SmartDNS 并行查询<br>• **一键部署**: 支持 一键 DD 与 nixos-anywhere |

> Note: 这些项目均在活跃维护中，欢迎提交 Issue 或 PR。

---

### 🛠️ 技术栈

- **主力语言**:
  ![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)
- **掌握的语言与技术**:
  ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
  ![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
  ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
  ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
  ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
  ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

---

### 📊 GitHub 统计

<p align="center">
  <a href="https://github.com/ShaoG-R/github-readme-stats">
    <img align="center" src="https://github-readme-stats-zeta-lovat-89.vercel.app/api?username=ShaoG-R&show_icons=true&theme=radical" />
  </a>
  <a href="https://github.com/ShaoG-R/github-readme-stats">
    <img align="center" src="https://github-readme-stats-zeta-lovat-89.vercel.app/api/top-langs/?username=ShaoG-R&layout=compact&theme=radical" />
  </a>
  <br>
  <img align="center" src="./github-metrics.svg" alt="Metrics" />
</p>

---

### 📫 如何联系我

- 📧 **邮箱**: [shaog.rs@gmail.com](mailto:shaog.rs@gmail.com)