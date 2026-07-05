# Free Serial Checker

A lightweight C++ utility designed to instantly retrieve, verify, and track your computer's unique hardware serial numbers. This tool is ideal for verifying that hardware identifiers change successfully after a system modification or spoofing process.

## ⚠️ Important Requirement
* **Run as Administrator:** This application requires administrative privileges to safely query low-level hardware structures (such as disk and motherboard serials).

## 🛠️ Features
* **MAC Address:** Extracts active network interface identifiers.
* **Motherboard Serial:** Fetches native motherboard system information.
* **Disk Serial:** Queries physical drive serial numbers.

## 💻 Available Commands
Type these commands directly into the application console:
* `scan` — Pulls and displays your current hardware serials.
* `clear` — Resets the session screen so you can cleanly scan again (ideal for checking before/after spoofing).
* `help` — Displays the built-in command menu.

## 🚀 Getting Started

### Execution
1. Right-click `Serial Checker.exe`.
2. Select **Run as administrator**.

## 🔒 Privacy & Safety
This utility operates **100% locally and offline**. Your hardware identifiers are processed strictly within your console window and are never transmitted over the internet.
