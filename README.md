# 🚀 Cursor Unlimited Free
### By Shivanesh

[![License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/shiva123vvv/Cursor-Unlimited-free?style=social)](https://github.com/shiva123vvv/Cursor-Unlimited-free/stargazers)

**A utility tool to reset the Cursor AI Editor trial period, allowing for continued access.**

> ⚠️ **IMPORTANT NOTICE**
> * **Windows:** Supports latest 1.0.x versions.
> * **Mac/Linux:** Supports latest 1.0.x versions.
> * **Pre-requisite:** Please check your Cursor version before using this tool.

---

## 📝 Description

This tool helps resolve common restriction messages encountered while using the free version of Cursor AI:

1.  **Trial Account Limit:** *"Too many free trial accounts used on this machine."*
2.  **API Key Limitation:** *"Composer relies on custom models that cannot be billed to an API key."*
3.  **Trial Request Limit:** *"You've reached your trial request limit."*
4.  **High Load Issues:** *"We're experiencing high demand for Claude 3.7 Sonnet."*

---

## 🛠️ General Usage Instructions

For the best results, follow this process **before** running the script:

1.  **Logout & Delete:** * Close Cursor.
    * Go to the [Cursor Website](https://cursor.sh), log in, go to **Settings** -> **General** -> **Advanced** -> **Delete Account**.
2.  **Run the Script:** Use the "One-Click Solution" commands below for your specific OS.
3.  **Register New Account:** Sign up with a new email address.
4.  **Enjoy:** Open Cursor and log in with the new account.

> **Tip:** If you still face issues, try switching your browser (e.g., from Chrome to Edge) when creating the new account or clear your browser cookies.

---

## 🚀 One-Click Solution

Run the following command in your terminal/PowerShell depending on your operating system.

### 🪟 Windows (PowerShell)

Open PowerShell as **Administrator** and run:

```powershell
irm [https://raw.githubusercontent.com/shiva123vvv/Cursor-Unlimited-free/main/scripts/run/cursor_win_id_modifier.ps1](https://raw.githubusercontent.com/shiva123vvv/Cursor-Unlimited-free/main/scripts/run/cursor_win_id_modifier.ps1) | iex

🍎 macOS
Open your Terminal and run:

Bash

curl -fsSL [https://raw.githubusercontent.com/shiva123vvv/Cursor-Unlimited-free/main/scripts/run/cursor_mac_id_modifier.sh](https://raw.githubusercontent.com/shiva123vvv/Cursor-Unlimited-free/main/scripts/run/cursor_mac_id_modifier.sh) | sudo bash
Warning for Mac Users: This script modifies your network interface MAC address to bypass hardware ID checks. It will backup your original config, but it may temporarily affect network connectivity.

🐧 Linux
Open your Terminal and run:

Bash

curl -fsSL [https://raw.githubusercontent.com/shiva123vvv/Cursor-Unlimited-free/main/scripts/run/cursor_linux_id_modifier.sh](https://raw.githubusercontent.com/shiva123vvv/Cursor-Unlimited-free/main/scripts/run/cursor_linux_id_modifier.sh) | sudo bash
🔧 Troubleshooting
For "High Load" / Claude 3.7 Issues
If you see the "High Load" message for Claude 3.7 Sonnet, Cursor is limiting free trial accounts during peak times.

Solution: Switch to Claude 3.5 Sonnet temporarily or try again during off-peak hours (typically 5-10 AM or 3-7 PM).

For Windows Execution Policy Errors
If you cannot run the script on Windows, you may need to allow script execution:

Open PowerShell as Administrator.

Run: Set-ExecutionPolicy RemoteSigned -Scope CurrentUser

Type Y and press Enter.

Manual Installation
If the one-click scripts do not work, you can manually download the scripts from the repository files and run them locally.

💻 System Support
OS,Arch,Status
Windows,"x64, x86",✅ Supported
macOS,"Intel, Apple Silicon (M1/M2/M3)",✅ Supported
Linux,"x64, ARM64",✅ Supported

Author
Shivaneshvvv
