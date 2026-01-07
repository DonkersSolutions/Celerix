# 🚀 Donkers Dev Toolbox

**A lightweight, local-first developer productivity suite.**

![Release Version](https://img.shields.io/github/v/release/DonkersSolutions/DevToolbox?label=Pre-Alpha&color=orange)
![License](https://img.shields.io/badge/license-Custom-blue)
![Platform Support](https://img.shields.io/badge/platform-macOS%20|%20Windows%20|%20Linux-lightgrey)

---

### ⚠️ **PRE-ALPHA & SOURCE STATUS**
* **Usage:** This is a **Public Pre-Alpha**. It is free to use but provided "as-is" under a Fair Use license.
* **Source Code:** The repository is currently **Private** while we stabilize the core architecture. We intend to transition to a fully **Open Source** model once the application reaches a stable 1.0 release.
* **Use at your own risk:** Expect bugs, breaking changes, and frequent updates.

---

## 🛡️ Installation & Security Notes

As this project is in a **Pre-Alpha** stage, the binaries are not yet digitally signed or notarized. Your operating system will likely flag the application as a security risk. This is expected behavior for unsigned software.

### 🍎 For macOS Users
If macOS claims the app is **"Damaged"** or should be moved to the Trash, it is simply because the app is unsigned. To bypass this:

1. Drag the application into your **Applications** folder.
2. Open your **Terminal** and run:
   ```shell
   sudo xattr -rd com.apple.quarantine /Applications/Donkers\ Dev\ Toolbox.app
   ```

### 🪟 For Windows Users
Windows **SmartScreen** will likely prevent the installer from starting with a blue banner stating "Windows protected your PC." This is standard for apps that are not yet digitally signed.

1. Click the **"More info"** link (this is the small underlined text directly under the main warning message).
2. A new button labeled **"Run anyway"** will appear at the bottom of the window.
3. Click **Run anyway** to start the installation.

### 🐧 For Linux Users
To install the `.deb` package and ensure all dependencies are correctly handled, use the terminal:
```shell
sudo apt install ./donkers-toolbox_0.1.4_amd64.deb
``` 

---

## 🛠 What is it?
**Donkers Dev Toolbox** is a high-performance "Swiss Army Knife" for your daily development workflow, built with **Tauri 2.0** and **Rust**.

### Core Philosophy
* **Local-First:** Your data stays on your machine. Import/Export functionality works directly with your local file system.
* **No Bloat:** A native desktop experience that stays out of your way (~35MB RAM usage).
* **Privacy:** No tracking, no cloud-syncing, no accounts required.

---

## ✨ Current Features

### 🐙 Git GUI (Experimental)
A visual interface for your local repositories.
* **Prerequisite:** You must have **Git** installed on your system, and SSH setup, the app can help you with that step (See GitGUI → Settings)
* **Status:** Supports basic git operations branches/commits/pull/push/fetch/tags/stashes.

### ⚙️ Developer Utilities
* **UUID Generator:** Fast, offline ID generation.
* **BASE64 Encode/Decode:** Clean up messy data locally.
* **JWT Decoder:** Decode JWT tokens for quick inspection.
* **Data Portability:** Full support for importing/exporting your settings and data to local files.

---

## 🗺 Roadmap
- [ ] **Phase 1 (Current):** Stabilize cross-platform builds and core utilities.
- [ ] **Phase 2:** Expand the toolset (Base64, Regex Tester, JWT Decoder).
- [ ] **Phase 3 (Stability):** Bug fixing and UI polish.
- [ ] **Phase 4 (Launch):** **Open Source Release** and migration to public code repository.

---

## ⬇️ Installation
Visit the **[Releases](https://github.com/DonkersSolutions/DevToolbox/releases)** page for the latest installers:
* **macOS:** Apple Silicon & Intel versions.
* **Windows:** x64 & ARM64 versions.
* **Linux:** `.deb` package for Debian/Ubuntu.

---

## 📜 License
This software is currently provided as **Freeware**. See the [LICENSE](./LICENSE) file for the full terms of the Pre-Alpha period.

*Copyright © 2026 Donkers IT*