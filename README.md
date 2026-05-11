# Metric

Android 性能监视工具，采用 App + daemon 的运行方式。

## 简介

Metric 用于查看设备性能状态、管理悬浮窗监视器，并记录帧率相关会话数据。

## 特点

- Rust 编写 Daemon读写核心，安全高效
- 基于 SharedMemory 的数据通信，低延迟低开销

## 支持版本

- Android 12L 及以上。

## 安装

- 安装 App 后，通过 Root 或 ADB 启动  Daemon。

## 功能

- 首页仪表盘：查看内存、GPU、CPU 和进程信息。
- 监视器：负载监视器、线程监视器、迷你监视器和帧率记录器等多种监测悬浮窗，轻松掌握设备信息
- 帧率记录：详细记录应用/游戏运行信息
- 更多功能：敬请期待

## 下载

- [Releases](https://github.com/ItosEO/Metric/releases)

## 意见反馈

- [Issues](https://github.com/ItosEO/Metric/issues)

## 开发者入口

- [产品需求](docs/PRD.md)
- [技术设计](docs/TECHNICAL_DESIGN.md)
- [UI 设计](docs/UI_DESIGN.md)
