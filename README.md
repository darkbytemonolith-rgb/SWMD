# 🚀 SWMD - Steam Workshop Manager & Downloader
### **Version 1.2.0 "Vibrant Update"**

SWMD (Steam Workshop Management & Download) is a high-performance, professional-grade automation tool designed for power users who need to manage large mod libraries and collections with ease. Built on .NET 8 with a premium WPF interface, it combines raw SteamCMD power with modern UI aesthetics.

---

## ✨ Key Features

- **⚡ Multi-Threaded Downloads:** Concurrent mod downloads with configurable thread counts to maximize your bandwidth.
- **🔄 Smart IP Rotation:** Built-in proxy manager with a real-time health monitor and automatic IP switching to bypass Steam rate limits.
- **🎨 Premium Visual Experience:**
  - Dynamic **Color-Shifting Progress Bar** (Red → Yellow → Green).
  - High-fidelity thumbnail previews for both Mods and Collections.
  - Sleek Dark Mode with blurred glass effects.
- **📂 Collection Management:** Fully automated detection and recursive downloading of large workshop collections.
- **🛡️ Self-Healing Environment:** Portable design that automatically downloads and sets up SteamCMD upon first launch.
- **🔍 Intelligent Version Tracking:** Atomic metadata tracking ensures you only download what's updated.

---

## 📸 Preview

![Dashboard Preview](https://ibb.co/r22dR40t)
*Modern Dashboard with Real-Time Proxy Monitoring and News Strip*

---

## 🛠️ Installation & Usage

### Option 1: Single-File Executable (Recommended)
1. Download the latest `SWMD_SingleFile.exe` from the [Releases](https://github.com/darkbytemonolith-rgb/SWMD/releases) page.
2. Drop the EXE into any folder.
3. Run and let SWMD handle the initial SteamCMD setup automatically.

### Option 2: Portable Folder
1. Download the ZIP release.
2. Extract all files (EXE and supporting DLLs) into a folder.
3. Launch `SWMD.exe`.

---

## ⚙️ Technical Specifications

- **Framework:** .NET 8.0 (Windows Desktop)
- **Engine:** SteamCMD (Automated Integration)
- **UI Architecture:** WPF (XAML) with Async/Await pattern
- **Concurrency:** Semaphore-based thread locking for safe file operations
- **Network:** ProxyScrape API integration for reliable IP rotation

---

## 📜 Version History

### v1.2.0 (Current)
- Implemented **Vibrant Progress Bar** with smooth RGB interpolation.
- Added **Collection Preview** support in the main library.
- Optimized **Proxy Rotation** engine with 5-second health cycles.
- Fixed thread-safety race conditions in progress reporting.

### v1.1.0
- Added Multi-threading support.
- Implemented automatic SteamCMD downloader.

---

## 🤝 Contributing
Feel free to fork this project at [darkbytemonolith-rgb/SWMD](https://github.com/darkbytemonolith-rgb/SWMD). For major changes, please open an issue first to discuss what you would like to change.

## ⚖️ License
[MIT](https://choosealicense.com/licenses/mit/)

---
*Developed with ❤️ by Dark_Byte*
