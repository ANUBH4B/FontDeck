<div align="center">

# FontDeck 🔤

**The Modern, Offline-First Windows Desktop Font Studio**

[![Platform: Windows](https://img.shields.io/badge/Platform-Windows%2010%2F11-0078d4?style=flat-square&logo=windows)](https://www.microsoft.com/windows)
[![Tauri 2.0](https://img.shields.io/badge/Tauri-v2.0-FFC131?style=flat-square&logo=tauri&logoColor=white)](https://v2.tauri.app/)
[![Rust](https://img.shields.io/badge/Rust-1.80+-DEA584?style=flat-square&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![Privacy: 100% Offline](https://img.shields.io/badge/Privacy-100%25%20Offline-10b981?style=flat-square&logo=shield)](https://github.com/ANUBH4B/FontDeck)
[![Downloads](https://img.shields.io/github/downloads/ANUBH4B/FontDeck/total?style=flat-square&logo=github&color=success)](https://github.com/ANUBH4B/FontDeck/releases)
[![License](https://img.shields.io/badge/License-Free%20for%20Personal%20%26%20Commercial-blue?style=flat-square)](LICENSE)

An elegant, blazing-fast desktop typography workspace built for Windows. Automatically discovers all system and user-installed fonts, monitors local project folders in real time, and renders high-fidelity typographic specimens with **zero telemetry and zero internet connection required**.

---

### 📥 Download FontDeck for Windows (x64)

[![Download .exe](https://img.shields.io/badge/Download_Setup_(.exe)-v1.0.0-0078d4?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/ANUBH4B/FontDeck/releases/latest/download/FontDeck_1.0.0_x64-setup.exe)
[![Download .msi](https://img.shields.io/badge/Download_Installer_(.msi)-v1.0.0-238636?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/ANUBH4B/FontDeck/releases/latest/download/FontDeck_1.0.0_x64_en-US.msi)

[**📦 View All Releases & Release Notes →**](https://github.com/ANUBH4B/FontDeck/releases)

</div>

---

## 🌟 Key Features

### 🔍 Instant Local Search & Smart Filtering
- **Multi-parameter Search**: Search instantly by font family name, style (`Light`, `Bold`, `Black`), weight number (`100`–`900`), or flags (`mono`, `variable`, `italic`).
- **Classification Filters**: Quick filter chips for **Sans-Serif**, **Serif**, **Monospace**, and **Variable** typefaces.
- **Sorting Options**: Sort your library alphabetically (A–Z, Z–A), by number of family styles, or by recently discovered fonts.

### 🔤 Dynamic Typography Preview Studio
- **Live Text Editing**: Type any custom sample string in the global preview bar. Every font card updates in real time using its actual native font file.
- **Pangram Presets**: Switch instantly between pre-configured specimens:
  - 🦊 Classic: *"The quick brown fox jumps over the lazy dog."*
  - 🔤 Alphabet: Uppercase & lowercase sequences.
  - 🔢 Numerals & Symbols: Complete punctuation and math characters.
  - 📰 Headline & Paragraph: Editorial display specimens.
- **Fluid Font Sizing**: Seamlessly adjust specimen size from `14px` to `96px` with continuous slider or discrete stepper controls.

### 📁 Live Watched Folders (Real-Time Sync)
- **Monitored Directories**: Add external font folders (e.g. project assets, downloads, client font packs).
- **Background File Watcher**: Powered by Rust’s native filesystem event engine. Newly added or deleted `.ttf`, `.otf`, and `.woff2` files sync automatically without restarting.
- **Persistent Cache**: Scanned folder fonts are cached locally for instant startup performance.

### 📂 Collections & Organization
- **Favorites & Custom Collections**: Bookmark your go-to fonts and organize typefaces into custom project sets.
- **Portable Backups**: Export and import your collections and preferences in JSON format for easy transfer across machines.

### 🔒 100% Offline & Private
- **Zero Telemetry**: No analytics, no phone-home tracking, no remote logging.
- **Local-Only Processing**: All registry queries, font file parsing, and rendering happen strictly on your hardware.

---

## 💻 System Requirements

| Specification | Requirement |
|---|---|
| **Operating System** | Windows 10 (Build 1809+) or Windows 11 |
| **Architecture** | 64-bit (x64) |
| **Dependencies** | Microsoft Edge WebView2 (Pre-installed on Windows 10 & 11) |
| **Network** | None required (100% offline functionality) |

---

## 🚀 Installation Guide

1. Download the latest installer:
   - **Recommended**: [**`FontDeck_1.0.0_x64-setup.exe`**](https://github.com/ANUBH4B/FontDeck/releases/latest/download/FontDeck_1.0.0_x64-setup.exe) (Easy NSIS installer)
   - **Alternative**: [**`FontDeck_1.0.0_x64_en-US.msi`**](https://github.com/ANUBH4B/FontDeck/releases/latest/download/FontDeck_1.0.0_x64_en-US.msi) (Standard Windows Installer package)
2. Run the downloaded installer on your PC.
3. Launch **FontDeck** from your Start Menu or Desktop shortcut.
4. FontDeck will immediately detect and catalogue all fonts installed on your machine.

---

## 🔄 Automatic Updates

FontDeck features built-in automated updates. Releases are cryptographically signed using cryptographic signature verification keys. When an update is available, you will be notified within the app to download and update with one click.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `/` | Jump directly to Search bar |
| `Escape` | Close active modal, drawer, or context menu |
| `Ctrl + R` | Refresh and re-scan installed fonts |
| `Ctrl + ,` | Open Settings & Preferences |
| `Arrow Keys` | Navigate through font card list |

---

## 📄 License

FontDeck is free to use for both **personal and commercial purposes**. See [LICENSE](LICENSE) for full license terms and conditions.

---

## 🤖 AI Disclosure & Transparency

This project was designed and developed with the assistance of advanced AI coding tools. All application architecture, Rust backend integrations, cryptographic signing implementations, and UI/UX designs have been carefully guided, tested, and reviewed by human developers.

---

<div align="center">
  Crafted with care for typography lovers, font collectors, and digital designers.
</div>
