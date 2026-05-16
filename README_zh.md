<p align="right">
  <b>中文</b> | <a href="README.md">English</a>
</p>

<p align="center">
  <img src="appicon.png" alt="TrackLogic" width="120">
</p>

<p align="center">
  <strong>驾驶 &middot; 分析 &middot; 提升 &middot; 重复</strong>
</p>

<p align="center">
  <a href="#快速开始">下载使用</a> &middot;
  <a href="#功能">功能</a> &middot;
  <a href="#-赞助">☕ 请我喝杯咖啡</a>
</p>

---

## 简介

TrackLogic 是一款免费的 iRacing 第三方遥测插件，通过 iRacing 官方共享数据接口读取实时遥测数据，提供五大实时叠加面板，帮助你在比赛中做出更好的决策，赛后进行数据驱动的复盘。

## 功能

### 实时面板（Overlay）

| 面板 | 说明 |
|------|------|
| **实时排行榜** | 排名、圈速、GAP/INT/DELTA、iRating 变化估算。支持按组别分组与视口智能裁剪。 |
| **赛道动态地图** | 俯瞰视角呈现全部车辆实时位置，按组别着色、前三名高亮标记，进站与拖车状态即时可见。 |
| **踏板与方向盘** | 油门、刹车、离合开度实时可视化，挡位与方向盘转角同步呈现，ABS 激活状态即时提醒。 |
| **盲区监测** | 基于 iRacing 侧向信号实时追踪左右盲区内车辆，可视化并排距离与位置。 |
| **智能驾驶提醒** | 内置刹车点提醒与换挡提示，基于遥测数据实时驱动，音量可调。 |

### 智能分析引擎

内置算法引擎自动解析轨迹与操作时序，生成直观总结，瞬间定位制动迟疑与走线偏差。无需读懂图表，也能看透数据。

## 快速开始

1. 下载 [TrackLogic.exe](TrackLogic.exe)
2. 启动 iRacing 并进入任意赛道
3. 双击运行 `TrackLogic.exe`
4. 首次使用将引导完成 iRacing OAuth 授权
5. 按 `F8` 循环切换面板模式：预览 → 编辑 → 游戏 → 隐藏

## 系统要求

- **操作系统**：Windows 10 / 11（64 位）
- **模拟器**：iRacing（已安装并运行）
- **网络**：首次使用需联网完成 iRacing OAuth 绑定

## 技术说明

- 通过 iRacing 官方共享内存接口（`CreateFileMapping`）**只读**获取数据
- **不修改、不注入、不干预** iRacing 进程或任何游戏文件
- 所有数据仅用于本地显示与分析


## ☕ 赞助

如果 TrackLogic 帮到了你，请我喝杯咖啡吧！

<p align="center">
  <img src="https://img.shields.io/badge/微信-WeChat-07C160?style=for-the-badge&logo=wechat&logoColor=white" alt="微信">
  &nbsp;
  <img src="https://img.shields.io/badge/支付宝-Alipay-1677FF?style=for-the-badge&logo=alipay&logoColor=white" alt="支付宝">
</p>

<p align="center">
  <sub>扫码赞助</sub>
</p>


## 免责声明

本软件仅供 iRacing 玩家的数据复盘与技术分享使用。使用本软件产生的任何比赛影响，开发者不承担任何责任。

---

<p align="center">
  <sub>&copy; 2026 ApexRacing</sub>
</p>
