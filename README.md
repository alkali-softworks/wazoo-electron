# <img src="public/icon.png" width="48" align="center" /> Wazoo (Deprecated)

> [!WARNING]
> ## ⚠️ DEPRECATION NOTICE
>
> **This repository (`wazoo-electron`) is deprecated and is no longer maintained.**
>
> It has been completely superseded by the native Rust rewrite:
> ### 👉 **[Wazoo (Rust) — github.com/alkali-softworks/wazoo](https://github.com/alkali-softworks/wazoo)**
>
> ### Why switch to Wazoo (Rust)?
> - **Native Media Engine:** Built on libmpv and WGPU, eliminating Electron/Chromium overhead and high RAM usage.
> - **Zero Transcoding:** Plays all formats natively (H.265/HEVC, AV1, VP9, ProRes, 10-bit MKVs, etc.) with no background FFmpeg transcoding needed.
> - **High Performance:** Instant boot times, low CPU usage, and silky-smooth non-stop ambient playback.

---

**Wazoo** was originally developed as an Electron-based ambient media engine designed for those who want to experience their local video collection without the burden of choice. Built as a "moving mood-board" for artists, designers, and curators, Wazoo provides a non-stop feed of visuals that flows continuously based on your library and optional search queries.

Forget the play button. Just open Wazoo and let your media collection become the atmosphere.

---

## 📦 Downloads & Releases

For the latest desktop releases (Windows, macOS, and Linux), please download the native Rust version from:

* 🚀 **[Wazoo (Rust) Latest Releases](https://github.com/alkali-softworks/wazoo/releases)**

---

## 🧠 The Philosophy: "Zero-Choice Viewing"

Wazoo was born from a simple problem: **digital fatigue.** We spend more time scrolling through thumbnails than actually watching our media. 

Wazoo flips the script. Instead of making you "pick," it creates a **continuous, non-stop feed** based on your entire collection or a specific theme. It's designed to be:
*   **A Moving Mood-Board:** Perfect for artists needing background inspiration.
*   **An Ambient Engine:** For those who want visuals running in the corner of their vision.
*   **Effortless Discovery:** Rediscover forgotten gems in your library without ever having to click "Open File."

---

## ✨ Features (Historical Electron Version)

### 🖼️ Ambient Orchestration
Run multiple videos simultaneously in **Grid**, **Row**, or **Column** layouts. Handles layouts dynamically in the background of your workspace.

### 🌊 The Infinity Stream
Experience your local library as a living river of content. The **Scroll Mode** provides a vertical feed that plays videos at random indices while scrolling at a constant rate with smooth audio cross-fading.

### ⚡ H.265 (HEVC) Transcoding
Built-in FFmpeg-powered transcoding engine that converts H.265 content for playback in the Electron environment *(note: the new Rust version plays H.265 natively without transcoding)*.

### 🔍 Smart Library Management
* **Instant Search:** Find any video in your collection in milliseconds.
* **Media Scanning:** Automatically indexes your folders into a local SQLite database.
* **Persistent State:** Remembers where you left off, including your last search and window layout.

### 🌍 Global by Design
Localization support for **16+ languages**:
*   **RTL Ready:** Support for Arabic and Hebrew with automatic layout mirroring.
*   **Multi-Lingual:** Support for English, Spanish, French, German, Japanese, Chinese, Hindi, Russian & more.
*   **Alt-Drag Navigation:** Quickly move the window anywhere on your screen with a simple Alt+Drag.

---

## 🚀 Archival Development Setup

*(Note: For current development, please contribute to [wazoo (Rust)](https://github.com/alkali-softworks/wazoo).)*

### Prerequisites
* [Node.js](https://nodejs.org/) (v20 or higher recommended)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/alkali-softworks/wazoo-electron.git
   cd wazoo-electron
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the development environment:
   ```bash
   npm run dev
   ```
4. Build / Package locally:
   ```bash
   npm run package
   ```

---

## 📄 License

This project is licensed under the MIT License - Do whatever you want with it (but give credit where credit is due).

---

<p align="center">Made with ❤️ by <a href="https://alkalisoftworks.com/">Alkali Softworks</a></p>
