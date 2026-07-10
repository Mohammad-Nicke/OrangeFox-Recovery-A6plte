# 🦊 OrangeFox Recovery for Samsung Galaxy A6+ (a6plus)

## 📱 Information

|---------------|---------------------------------------------------------------|
| **Device**    | Samsung Galaxy A6+                                            |
| **Models**    | SM-A605F / SM-A605FN / SM-A605G / SM-A605GN (others may work) |
| **Codename**  | `a6plus`                                                      |
| **Recovery**  | OrangeFox Recovery (Unofficial Port)                          |
| **Based on**  | TWRP                                                          |
| **Status**    | Unofficial / Port                                             |
| **Developer** | Mr.Nick                                                       |

---

> ⚠️ **IMPORTANT**  
> If you cannot flash the **Disable_Dm-Verity_ForceEncrypt** file directly in OrangeFox, **first install TWRP recovery**, then flash your `Disable_Dm-Verity_ForceEncrypt` zip from TWRP.  
> After that, install OrangeFox using the method described below.  
> **The order of flashing is critical!**

---

## 📥 Installation

### 🔧 Prerequisites
- Unlocked bootloader (this will void warranty and trip Knox)
- A custom recovery already installed (for the ZIP method)  
- The OrangeFox **`.zip`** file (any build)

> 💡 **For first-time installation** you may also use the **Build #1 Odin `.tar`** – see the note at the bottom of this section.

---

### 📂 Recommended Method: Flash via Custom Recovery (ZIP)

1. Copy the OrangeFox `.zip` file to your phone’s internal storage or SD card.
2. Boot into your current custom recovery (e.g., TWRP).
3. Tap **Install**.
4. Navigate to the `OrangeFox-*.zip` file and select it.
5. Swipe to confirm the flash.
6. Once the installation finishes, return to the home screen.
7. Go to **Reboot → Recovery** to restart into OrangeFox.
8. (Optional) You can delete the `.zip` file after the first successful boot.

> 🔁 **If you are upgrading from an older OrangeFox build**, simply flash the newer ZIP in the same way.  
> Your backups and settings will be preserved.

---

### 📦 Additional Note: Odin Flash (Build #1 only)

> ℹ️ **Odin flashing is available only in Build #1.**  
> Newer builds can **only** be installed via the custom recovery method above.

If you prefer to start with Odin (for example, if you have no custom recovery yet), you can use the special Build #1 `.tar` file:  
[**Download Odin flashable Build #1**](https://github.com/Mohammad-Nicke/OrangeFox-Recovery-A6plte/releases/download/R11.0-B1/OrangeFox-R11.0-install_with_Odin.tar)

> ⚠️ **IMPORTANT:** After flashing Build #1 with Odin, **it is strongly recommended to immediately update to the latest build** using the ZIP method (flash the newest `.zip` file from within OrangeFox itself). This ensures you have all the latest fixes and improvements.

---

## ✨ Features

- Modern **Material Design 2** interface
- Password / PIN protection for the recovery itself
- Full support for **Treble** and **non‑Treble** ROMs
- Complete **backup & restore** (System, Data, Boot, Vendor, EFS, Modem, etc.)
- Advanced **File Manager** and **Terminal**
- Up‑to‑date **Magisk** and flashable ZIP support
- **OTG** and external SD card support
- OTA‑style incremental updates (where applicable)
- Direct flashing of `.img` files to various partitions
- **Full English language support** – recovery UI in English
- **Ported recovery merged with TWRP 3.3.1 kernel** – best compatibility for the A6+
- Many more OrangeFox‑exclusive tweaks (explore the settings!)

### 🔄 Backup Migration (Build #2+)
When you update from Build #1 to Build #2 or later, your existing backups are **automatically moved** from the `/TWRP` folder to the `/Fox` folder.  
This way you can still restore all your previous backups directly through OrangeFox without any manual copying.

### 🌐 Supported Languages
The recovery interface is fully translated into the following languages (switchable in settings):

- Čeština (Czech)
- Deutsch (German)
- Ελληνικά (Greek)
- English
- Español (Spanish)
- فارسی (Persian)
- Français (French)
- Magyar (Hungarian)
- Bahasa Indonesia (Indonesian)
- Italiano (Italian)
- Nederlands (Dutch)
- Polski (Polish)
- Português (Portuguese)
- Română (Romanian)
- Русский (Russian)
- Slovenčina (Slovak)
- Slovenščina (Slovenian)
- Svenska (Swedish)
- Türkçe (Turkish)
- Українська (Ukrainian)
- Tiếng Việt (Vietnamese)
- 简体中文 (Chinese Simplified)
- 繁體中文 (Chinese Traditional)

---

## 🐞 Bugs / Known Issues

**No bugs have been identified so far!** 🎉  
If you encounter something, please **let me know** – your report is highly appreciated.  
📧 [mohammad..nikparvarian@gmail.com](mailto:mohammad..nikparvarian@gmail.com)  

I’ll update this section as soon as any issue is confirmed.

---

## 🛡️ Anti‑Copyright / Disclaimer

> **This project is strictly non‑commercial.**  
> Selling, monetising, or using this recovery in any paid service is **forbidden**.

- Do **not** steal, re‑upload, or mirror this work without **explicit permission** and proper credits.
- If you use this port as a base for your own project, **ask first** and clearly mention the original source.
- “OrangeFox” and its logo are the property of the **OrangeFox Recovery Project**. This is an unofficial port.
- I am **not responsible** for bricked devices, lost data, thermonuclear war, or anything else that happens after you flash this recovery. Everything you do is at your own risk.

---

## 🙏 Acknowledgments & Contact

A huge thanks to everyone who helped with testing and bug fixing during the development of this port.

If you run into any problems, need help, or just have a question, feel free to reach out:

- 📱 **Telegram:** [@Mohammad_nicke](https://t.me/Mohammad_nicke)  
- 📧 **Email:** [mohammad.nikparvarian@gmail.com](mailto:mohammad.nikparvarian@gmail.com)
