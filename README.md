# OrangeFox Recovery for Samsung Galaxy A6+ (a6plus)

## 📱 Information
- **Device:** Samsung Galaxy A6+  
- **Model(s):** SM-A605F / SM-A605FN / SM-A605G / SM-A605GN (others may work)  
- **Codename:** `a6plus`  
- **Recovery:** OrangeFox Recovery (Unofficial Port)  
- **Based on:** TWRP  
- **Build status:** Unofficial / Port  
- **Developer:** Mr.Nick

---

## 📥 How to Install

### ⚠️ Prerequisites
- Unlocked bootloader (this will void warranty and trip Knox)
- A Windows PC with **Samsung USB drivers** and **Odin** installed
- A working USB cable (preferably original)
- The provided **OrangeFox recovery `.tar` file** (or `.img` if you already have a custom recovery)

> 🔔 **Important:** After flashing with Odin, you **must** reboot directly into recovery. Otherwise, the stock ROM will overwrite OrangeFox with the stock recovery.

---

### Method 1: Flash with Odin (recommended for first-time installation)

1. Download the OrangeFox `.tar` file onto your PC.
2. Power off your phone completely.
3. Boot into **Download Mode**:  
   Press and hold **Volume Up + Volume Down**, then connect the phone to your PC with the USB cable.  
   Release the buttons when the warning screen appears, then press **Volume Up** to continue.
4. Launch **Odin** on your PC. Make sure your phone is recognised (a blue or yellow COM port should appear).
5. Click the **AP** button and select the OrangeFox `.tar` file.
6. In the **Options** tab, **untick “Auto Reboot”**.
7. Click **Start**. Wait for the process to finish and show **PASS!**.
8. Disconnect the USB cable.
9. Forcefully reboot straight into recovery:  
   Press and hold **Volume Up + Power** until the phone restarts and you see the OrangeFox logo.
10. Release the buttons – you are now in OrangeFox Recovery.

---

### Method 2: Flash from an existing custom recovery (e.g. TWRP)

1. Copy the OrangeFox `.img` file to your phone’s internal storage or SD card.
2. Boot into your current custom recovery.
3. Tap **Install** → **Install Image**.
4. Navigate to and select the `OrangeFox-*.img` file.
5. Choose **Recovery** as the target partition and swipe to flash.
6. Go back to the home screen and select **Reboot** → **Recovery**.

---

## ✨ Features
- Modern **Material Design 2** interface
- Built-in **password/PIN protection** for recovery
- Full support for **Treble and non-Treble ROMs**
- Complete **backup/restore** (System, Data, Boot, Vendor, EFS, Modem…)
- Advanced **File Manager** and **Terminal**
- Flashlight, screen timeout, brightness control and other handy utilities
- **Magisk** and other flashable zips support (up-to-date)
- **OTG** and external SD card support
- OTA-style incremental updates (where applicable)
- Ability to flash `.img` files directly to various partitions
- More OrangeFox exclusive tweaks (check the settings!)

---

## 🐞 Bugs / Known Issues
**No bugs have been identified so far!** 🎉  
But if you find any, please **you tell me** – I’d really appreciate your report.  
📧 Click here to send an email: [mohammad..nikparvarian@gmail.com](mailto:mohammad..nikparvarian@gmail.com)

I will update this section as soon as any issue is confirmed.

---

## 🛡️ Anti‑Copyright / Disclaimer

> **This project is strictly non‑commercial.**  
> Selling, monetising, or using this recovery in any paid service is **forbidden**.

- Do **not** steal, re‑upload, or mirror this work without **explicit permission** and proper credits.
- If you use my port as a base for your own project, **ask first** and clearly mention the original source.
- “OrangeFox” and its logo are the property of the **OrangeFox Recovery Project**. This is an unofficial port.
- I am **not responsible** for bricked devices, lost data, thermonuclear war, or anything else that happens after you flash this recovery. You do it at your own risk.

---

**Enjoy OrangeFox on your A6+!**  
If you appreciate the work, a simple “thank you” or a credit is always welcome 😊
