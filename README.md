**English** | [Bahasa Indonesia](README_ID.md)

# TWRP-gale-A15
> A TWRP project for redmi 13c android 15!

![Device](https://img.shields.io/badge/device-Redmi_13C-orange)
![Android](https://img.shields.io/badge/Android-15-green)
![Project](https://img.shields.io/badge/status-UNOFFICIAL-blue)

## 🕒 Status and progress 3%
**• status**

We've built the initial steps of creating a TWRP, so just wait another 2 days to start further progress😉.

**• progress**

- [ ] Recovery boots successfully
- [ ] ADB connectivity working
- [ ] Data partition mounting
- [ ] FBE decryption (Android 15)
- [ ] Backup and restore
- [ ] MTP file transfer
- [ ] Brightness control
- [ ] Vibration feedback
- [ ] Language support

## Target
- Full data decryption (FBE v2) for Android 15
- AVB 2.0 compatibility
- Touchscreen fully working
- Backup and restore functionality
- MTP support for file transfer

## 🔧 Installation
> ⚠️ **WARNING: Installation causes the smartphone bootloop, make sure you are thorough in installing Recovery or not you have to take your own risk!**

1. Download the TWRP latest release from [Releases](https://github.com/Fskris34/TWRP-gale-A15/releases)
2. Download and open the [platform tools](https://developer.android.com/tools/releases/platform-tools) on Windows
3. Boot your device into fastboot mode:
   ```bash
   adb reboot bootloader
4. After rebooting, Flash TWRP to fastboot
   ```bash
   fastboot flash recovery twrp.img
5. Then, open the recovery with the command
   ```bash
   fastboot reboot recovery
**💡NOTE: If you encounter bootloop, flash your stock recovery image back!**
## Credits
   - Based on [TeamWin Recovery Project](https://github.com/TeamWin)
   - Original source licensed under GPL v3
and Team Win LLC ©2026

    This program is just an unofficial project, all halls related to TWRP are still held by Team Win LLC, we only comply with project regulations related to the development of TWRP


