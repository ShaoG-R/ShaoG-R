# 👋 Hello, I'm ShaoG-R

这里汇集了我最近维护和开发的开源项目，主要专注于 **Rust 高性能基础设施**、**Cloudflare Serverless 应用** 以及 **NixOS 自动化运维**。

## 🚀 核心项目概览 | Featured Projects

### 🦀 Rust 高性能组件与库 (High Performance Rust)

| 项目 | 简介 | 核心特性 |
|------|------|----------|
| **[SMR-Swap](./smr-swap/README_CN.md)** | **高性能单写多读交换容器**<br>专为读多写少场景设计的高性能并发原语。 | • Wait-Free 读取<br>• 基于版本的内存回收 (Safe Reclamation)<br>• 性能优于 `RwLock` / `ArcSwap` |
| **[Kestrel Timer](./kestrel-timer/README_CN.md)** | **分层时间轮异步定时器**<br>基于 Hierarchical Timing Wheels 算法的高效定时器库。 | • O(1) 时间复杂度<br>• 双层时间轮 (L0/L1) 自动分层<br>• 支持 10,000+ 高并发任务 |
| **[Hydra-DL](./hydra-dl/README.md)** | **多线程极速下载器**<br>功能强大的现代化下载工具与 Rust 库。 | • 动态智能分块 (Dynamic Chunking)<br>• 渐进式 Worker 启动<br>• 支持 CLI 与 Library 双模式 |

### ☁️ Serverless 与 Web 应用 (Cloud & Web)

| 项目 | 简介 | 技术栈 |
|------|------|--------|
| **[VerWatch](./verwatch/backend/README.md)** | **Serverless GitHub 版本看门狗**<br>运行在 Cloudflare 边缘的 Release 监控服务，支持自动触发 Actions。 | • **Backend**: Rust + Cloudflare Workers (Durable Objects)<br>• **Frontend**: [Leptos Dashboard](./verwatch/frontend/README.md) (Rust + Wasm)<br>• 强一致性与高可用设计 |

### 🛠️ 运维与基础设施 (Infrastructure / DevOps)

| 项目 | 简介 | 亮点 |
|------|------|------|
| **[NixOS Config](./nixos-config/README.md)** | **模块化 NixOS 服务器配置**<br>机制与策略分离的现代化服务器配置库。 | • **内核调优**: CachyOS Kernel + BBRv3<br>• **网络优化**: SmartDNS 并行查询<br>• **一键部署**: 支持 [一键 DD](./nixos-config/docs/install.md) 与 nixos-anywhere |

---

## 📚 项目导航

- **SMR-Swap**: [中文文档](./smr-swap/README_CN.md) | [English](./smr-swap/README.md)
- **Kestrel Timer**: [中文文档](./kestrel-timer/README_CN.md)
- **Hydra-DL**: [文档](./hydra-dl/README.md)
- **VerWatch**: [后端文档](./verwatch/backend/README.md) | [前端文档](./verwatch/frontend/README.md)
- **NixOS Config**: [首页](./nixos-config/README.md) | [安装指南](./nixos-config/docs/install.md)

> Note: 这些项目均在活跃维护中，欢迎提交 Issue 或 PR。
