# X-ADB Manager 📱

A professional, lightweight Bash tool for Android developers and enthusiasts. Effortlessly manage your devices via ADB over Wi-Fi and mirror your screen using Scrcpy with auto-IP detection.

> **Developed by CwC (Cwc84)** 🚀

---

## ✨ Features
- **Auto-IP Detection**: No more searching for IP addresses in settings. Fetch it instantly via USB.
- **Persistent Database**: Save your devices with custom aliases (e.g., `WorkPhone`, `Pixel6`).
- **One-Click Connectivity**: Connect and start `scrcpy` mirroring in one command.
- **Smart ADB Management**: Easily switch to TCP/IP mode and reset the ADB server when needed.
- **Safe & Fast**: Uses timeout-guarded connection attempts to prevent hanging.

---

## 🛠 Prerequisites
Make sure you have the following installed on your Linux system:
- `adb` (Android Debug Bridge)
- `scrcpy` (Screen Mirroring)
- `awk` (Standard on most distros)

---

## 📦 Installation

To use **Xadb** from anywhere in your terminal, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Cwc84/xadb.git](https://github.com/Cwc84/xadb.git)
   cd xadb

  **Install to system**
-sudo cp xadb /usr/local/bin/Xadb
-sudo chmod +x /usr/local/bin/Xadb

 **Run The Tool**
 
-Xadb


**🚀 Usage**

1: Connect your Android device via USB.

2: Select "Enable Wireless Mode" to open port 5555.

3: Select "Add/Update Device" -> "Automatic Detection" to save your device.

4: Unplug the USB and select "Connect & Mirror Screen" to go wireless!




----------------------------------------------------------------Made with ❤️ by CwC (Cwc84)------------------------------------------------------------------
