# 💻 ThinkBook 14 IIL – OpenCore EFI

OpenCore EFI files for **Lenovo ThinkBook 14 IIL**, built to run **Tahoe 26.3** 🍎

This repository focuses on achieving a stable and usable macOS experience on this specific laptop model. No unnecessary stuff — just what’s needed.

<img width="1920" height="1080" alt="Ventura2" src="https://raw.githubusercontent.com/ThinkDifferentInc/ThinkBook-14IIL/refs/heads/main/tahoe.png" />

## Download EFI:
* macOS Sequoia: https://drive.google.com/drive/folders/1VMz4Yaxe3_fghepef3be9NsOCd2qku6s?usp=sharing
* macOS Ventura: https://drive.google.com/drive/folders/1WuMxAMflbLl8MsAcO1EEp1bnmMXVatbr?usp=sharing
* macOS Tahoe (buggy): In repo downloads.

---

## 🚀 Supported macOS Versions

- **macOS Monterey → macOS Tahoe** *(depending on which version you choose)*

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
| **HDMI**             | ✅ Partially yes, with an adapter. |
| **Audio**            | ✅ Yes, but check MyKextInstaller
| **Touchpad**         | ❌ No, help appreciated.   |


---

> [!NOTE]
> You will need to edit the Info.plist file inside the itlwm.kext file to gain internet access. The file in question is in itlwm.kext/Contents. Change the YOURPASSWORDHERE and YOURWIFINAMEHERE accordingly.
> Or you can use the Itlwmjector.py Wi-Fi injector to edit the kext for you on ThinkDifferentInc/Itlwmjector. (Works on Windows, Linux)

> [!TIP]
> If you want a working HDMI connection, you will have to buy a USB3.0 to HDMI adapter with macOS support.


---

## 🛠️ Bootloader used

* **OpenCore**

---

## 👥 Credits

* **@devbyreqqel** (Initial plan, Sequoia development, Tahoe development)
* **@prodbyeternal** (Ventura development, Contributor)

---
> [!CAUTION]
> This EFI is made for **this exact hardware configuration**.<br>
> If your ThinkBook differs, you’ll need to adjust the config accordingly.<br>
> You are downloading a **_PRE-MADE EFI_**. 99% of Hackintosh communities won't help with pre-made EFI's. You are on your own.<br>
> Also, Ice Lake CPU's suck, never doing Ice Lakes again.<br>
> Tahoe sucks, its very very buggy...
