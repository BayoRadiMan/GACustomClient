# 🚀 GACustom Client

A lightweight, dedicated workspace browser wrapper built for performance, privacy, and profile isolation.

GACustom Client is a portable Windows application designed to provide a clean, isolated environment for your web workflows. Unlike standard browsers, it keeps your data contained within its own folder, making it perfect for portable use or managing specific workspace sessions.

---

## ✨ Key Features

* **🗄️ Profile Isolation:** All cookies, history, and session data are stored locally in the `UserData` folder.
* **📦 Zero Installation:** A single standalone `.exe` file. No installers, no registry clutter.
* **🛡️ Integrated Crash Logger:** Automatically captures technical details during unexpected errors or crashes to help with troubleshooting.
* **🔄 Smart Auto-Update:** Built-in version checking that automatically backs up your old version before upgrading.
* **🚀 Performance Focused:** Powered by the Microsoft WebView2 (Chromium) engine for modern web compatibility and speed.

---

## 📥 Getting Started

### Installation
1.  Go to the [**Latest Release**](https://github.com/BayoRadiMan/GACustomClient/releases/latest).
2.  Download `GACustomClient.exe`.
3.  **Important:** Place the `.exe` in its own dedicated folder (e.g., `C:\Apps\GACustom\`).
4.  Launch the application.

### 🛡️ Security & Trust
Because this is an independent, unsigned C# application:
* **Windows SmartScreen:** You may see a "Windows protected your PC" popup. Click **More Info** -> **Run Anyway**.
* **Antivirus:** Some AI-based scanners may flag the file as "Suspicious" due to the embedded dependencies. These are false positives. Please refer to the scan notes in the Release description for more details.

---

## 📂 File Structure
Upon first launch, the client will create the following in its directory:
* `UserData/`: Your isolated browser profile (Keep this private!).
* `Backups/`: Previous versions of the client saved during auto-updates.
* `CrashLogs/`: Diagnostic files created automatically if the application encounters an error.

---

## 🛠 Requirements
* **OS:** Windows 10 or 11 (64-bit).
* **Engine:** [Microsoft WebView2 Runtime](https://developer.microsoft.com/en-us/microsoft-edge/webview2/) (Included in most modern Windows updates).

---

## 📄 License
This project is proprietary software.
* **BayoRadiMan** © 2026. All rights reserved.
* Reverse engineering, unauthorized redistribution, and commercial resale are strictly prohibited.
