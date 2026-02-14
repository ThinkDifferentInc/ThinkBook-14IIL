# 💻 ThinkBook 14 IIL – OpenCore EFI

OpenCore EFI files for **Lenovo ThinkBook 14 IIL**, built to run **macOS Sequoia (15)** 🍎

This repository focuses on achieving a stable and usable macOS experience on this specific laptop model. No unnecessary stuff — just what’s needed.

<img width="1920" height="1080" alt="Ventura2" src="https://raw.githubusercontent.com/ThinkDifferentInc/ThinkBook-14IIL/refs/heads/main/Sequoia.png" />

## Download EFI:
* macOS Sequoia: https://drive.google.com/drive/folders/1VMz4Yaxe3_fghepef3be9NsOCd2qku6s?usp=sharing
* macOS Ventura: https://drive.google.com/drive/folders/1WuMxAMflbLl8MsAcO1EEp1bnmMXVatbr?usp=sharing

---

## 🚀 Supported macOS Version

* **macOS Sequoia**
* *Supports from macOS Monterey up to.....*

---

## 🧩 Hardware Specifications

| Component | Details                        |
| --------- | ------------------------------ |
| **CPU**   | Intel Core i5-1035G1 @ 1.0 GHz |
| **GPU**   | Intel Iris Graphics            |
| **RAM**   | 8 GB DDR4                      |

---

## ✅ What’s working?

| Feature              | Status |
| -------------------- | ------ |
| **Wi‑Fi**            | ✅ Yes  |
| **Bluetooth**        | ✅ Yes  |
| **GPU Acceleration** | ✅ Yes  |
| **Keyboard**         | ✅ Yes  |
| **USB**              | ✅ Yes  |
| **Battery Status**   | ✅ Yes  |
| **HDMI**             | ❌ No, won't be supported. |
| **Touchpad**         | ❌ No, please help   |


---

> [!NOTE]
> You will need to edit the Info.plist file inside the itlwm.kext file to gain internet access. The file in question is in itlwm.kext/Contents. Change the YOURPASSWORDHERE and YOURWIFINAMEHERE accordingly.
> Or you can use the included itlwmPass.py Wi-Fi injector to edit the kext for you. (Works on Windows, Linux)

> [!NOTE]
> If you want a HDMI connection, you will have to buy a USB3.0 to HDMI adapter with macOS Driver support.


---

## 🛠️ Bootloader used

* **OpenCore**

---

## 👥 Credits

* **@devbyreqqel**
* **@prodbyeternal**

---
> [!WARNING]
> This EFI is made for **this exact hardware configuration**.
> If your ThinkBook differs, you’ll need to adjust the config accordingly.
> Also, Ice Lake CPU's suck, never doing Ice Lakes again.
