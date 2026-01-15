# 🚀 GACustom Client

A lightweight, dedicated workspace browser wrapper built for performance, privacy, and profile isolation.

GACustom Client is a portable Windows application designed to provide a clean, isolated environment for your web workflows. Unlike standard browsers, it keeps your data contained within its own folder, making it perfect for portable use or managing specific workspace sessions.

---

## ✨ Key Features

* **🗄️ Profile Isolation:** All cookies, history, and session data are stored locally in the `UserData` folder.
* **📦 Zero Installation:** A single standalone `.exe` file. No installers, no registry clutter.
* **🛡️ Active Integrity Audit:** (New!) The client features a real-time cryptographic self-check to ensure the binary hasn't been tampered with.
* **🌐 Smart Navigation:** Intelligent URL parsing that automatically resolves domains (e.g., `google.com`) to secure HTTPS connections.
* **🚀 Performance Focused:** Powered by the Microsoft WebView2 (Chromium) engine for modern web compatibility and speed.
* **🔄 Smart Auto-Update:** Built-in version checking that automatically backs up your old version before upgrading.

---

## 📥 Getting Started

### Installation
1. Go to the [**Latest Release**](https://github.com/BayoRadiMan/GACustomClient/releases/latest).
2. Download `GACustomClient.exe`.
3. **Important:** Place the `.exe` in its own dedicated folder (e.g., `C:\Apps\GACustom\`).
4. Launch the application.

### 🛡️ Security & Trust
Starting with **v1.0.0.3 2.00A**, GACustom Client is now cryptographically signed and verified:
* **Verified Publisher:** The application is digitally signed by **BayoRadiMan**.
* **Integrity Check:** You can verify the status in the "About" menu. A **Grey/White shield** indicates a verified, secure build.
* **Antivirus:** Due to the official signature, the client now maintains a high trust score with Windows Defender and major AV providers, significantly reducing false positives.

---

## 📂 File Structure
Upon first launch, the client will create the following in its directory:
* `UserData/`: Your isolated browser profile (Keep this private!).
* `sc.txt`: Your saved shortcuts, automatically sanitized for security.
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




[README Updated 2026/01/15]
