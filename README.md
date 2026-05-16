<p align="right">
  <a href="README_zh.md">中文</a> | <b>English</b>
</p>

<p align="center">
  <img src="appicon.png" alt="TrackLogic" width="120">
</p>

<p align="center">
  <strong>Drive &middot; Analyze &middot; Improve &middot; Repeat</strong>
</p>

<p align="center">
  <a href="#quick-start">Quick Start</a> &middot;
  <a href="#features">Features</a> &middot;
  <a href="#-sponsor">☕ Sponsor</a>
</p>

---

## Overview

TrackLogic is a free third-party telemetry plugin for iRacing. It reads real-time telemetry via iRacing's official shared memory interface and provides five real-time overlay panels to help you make better decisions during races and conduct data-driven post-race analysis.

## Features

### Overlays

| Panel | Description |
|-------|-------------|
| **Standings** | Position, lap times, GAP/INT/DELTA, iRating estimates. Grouped by class with smart viewport clipping. |
| **Track Map** | Top-down real-time positions of all cars, colored by class, top 3 highlighted. Pit & tow status visible. |
| **Input Telemetry** | Throttle, brake, clutch inputs visualized. Gear, steering angle, and ABS activation in real time. |
| **Blind Spot** | Tracks cars in left/right blind spots via iRacing lateral signals. Visualizes side-by-side distance. |
| **Smart Spotter** | Built-in braking point & shift prompts driven by live telemetry, with adjustable volume. |

### Smart Analysis

The built-in analysis engine automatically parses racing lines and input timing, generating clear summaries that instantly flag braking hesitation and line deviations. No need to read complex charts.

## Quick Start

1. Download [TrackLogic.exe](TrackLogic.exe)
2. Launch iRacing and enter any session
3. Double-click `TrackLogic.exe`
4. On first run, follow the iRacing OAuth login flow
5. Press `F8` to cycle overlay modes: Preview → Edit → Game → Hide

## System Requirements

- **OS**: Windows 10 / 11 (64-bit)
- **Sim**: iRacing (installed and running)
- **Network**: Internet required for initial iRacing OAuth authentication

## Technical Notes

- Reads data via iRacing's official shared memory interface (`CreateFileMapping`) — read-only
- Does **not** modify, inject, or interfere with any iRacing process or game file
- All data is processed locally for display and analysis only


## ☕ Sponsor

If TrackLogic helps you on track, buy me a coffee!

<p align="center">
  <img src="https://img.shields.io/badge/WeChat-07C160?style=for-the-badge&logo=wechat&logoColor=white" alt="WeChat">
  &nbsp;
  <img src="https://img.shields.io/badge/Alipay-1677FF?style=for-the-badge&logo=alipay&logoColor=white" alt="Alipay">
</p>

<p align="center">
  <sub>Scan to sponsor</sub>
</p>


## Disclaimer

This software is provided for iRacing players' data review and knowledge sharing only. The developer assumes no liability for any race outcome resulting from its use.

---

<p align="center">
  <sub>&copy; 2026 ApexRacing</sub>
</p>
