# Poor5G - WiFi Attack Tool v2.5
# Developed by Kevin & Khemra

# This document now contains the raw README content without 'echo' commands, in English.

👻 Poor5G - WiFi Attack Tool v2.5

**Developed by Kevin & Khemra**

Poor5G is a powerful and stylish terminal-based tool for WiFi network testing and deauthentication attacks.

---

## 🔥 Features

* **WiFi Scanning**: Scans 2.4GHz and 5GHz WiFi networks, as well as all available bands.
* **Deauth Attack**: Performs deauthentication attacks on routers (AP) or selected clients.
* **Channel Control**: Allows setting the WiFi channel as needed.
* **Sniff Deauth Packets**: Captures deauthentication packets (requires tshark).
* **Action Logging**: Automatically logs all actions.
* **User Interface**: Features an attractive hacker-style animated UI.

---

## 🖥️ Requirements

* **Operating System**: Kali Linux or any Debian-based distro.
* **Permissions**: Root access.
* **Tools**: `aircrack-ng`, `tshark` (must be installed).
* **WiFi Adapter**: Must support monitor mode.

**How to Install Tools**

```bash
sudo apt update
sudo apt install aircrack-ng tshark -y
```

---

## 📦 Files

* `Poor5G.bin` → Compiled and encrypted binary.
* ✅ **No Source Code Exposed**: A protected version.

---

## ⚙️ How to Run

```bash
git clone [https://github.com/KevinnRaa/Poor5G.git](https://github.com/KevinnRaa/Poor5G.git)
cd Poor5G
chmod +x Poor5G.bin
sudo ./Poor5G.bin
```

> ⚠️ Always use with `sudo` to enable monitor mode and packet injection.

---

## 🧭 Menu Overview

```
1. 🟣 Start Monitor Mode (wlan0 → wlan0mon)
2. 📶 Scan WiFi 5GHz
3. 📶 Scan WiFi 2.4GHz
4. 🌐 Scan All Bands
5. 📡 Set WiFi Channel
6. 💣 Deauth Router
7. 🎯 Deauth Client
7. 👀 Sniff Deauth Packets
0. ❌ Exit
```

---

## ⚠️ Disclaimer

> 📛 This tool is strictly for educational, testing, and red team simulation purposes only.
> ❌ Do NOT use this tool on any network without **explicit permission**.
> 📚 The developer(s) are not responsible for any misuse.

---

## 📡 Follow Us

* **GitHub**: [KevinRaa](https://github.com/KevinRaa)
* **TikTok**: @RaaTechOfficial

---
