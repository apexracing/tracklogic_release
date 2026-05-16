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
  <table>
    <tr>
      <td align="center"><img src="wechat-qr.png" alt="WeChat" width="160"><br><sub>WeChat</sub></td>
      <td align="center"><img src="alipay-qr.png" alt="Alipay" width="160"><br><sub>Alipay</sub></td>
    </tr>
  </table>
</p>

Also available on [Buy Me a Coffee](https://buymeacoffee.com/apexracing) and [爱发电](https://afdian.com/a/apexracing).


## Disclaimer

This software is provided for iRacing players' data review and knowledge sharing only. The developer assumes no liability for any race outcome resulting from its use.

---

<p align="center">
  <sub>&copy; 2026 ApexRacing</sub>
</p>
