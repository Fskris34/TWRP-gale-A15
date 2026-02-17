[English](README.md) | **Bahasa Indonesia**

# TWRP-gale-A15
> Sebuah project TWRP untuk Redmi 13c android 15!

![Device](https://img.shields.io/badge/device-Redmi_13C-orange)
![Android](https://img.shields.io/badge/Android-15-green)
![Project](https://img.shields.io/badge/status-TIDAKRESMI-blue)

## 🕒 Status dan progress -%
**• status**

TWRP akan dilanjutkan ketika kami siap karena masalah selama pembuatan TWRP!

**• prepare** 

- [ ] Menyiapkan bahan-bahan
- [ ] Proses sinkronisasi TWRP
- [ ] Membuat device tree
- [ ] Menyatukan itu semua
- [ ] Proses testing
- [ ] ~~Memperbaiki kesalahan~~ (kuharap tidak☺️)
- [ ] Rilis publik

**• progress**

- [ ] Recovery boot berhasil
- [ ] ADB berhasil terkoneksi
- [ ] Data pemasangan partisi
- [ ] FBE decryption (Android 15)
- [ ] Cadangan dan memulihkan
- [ ] transfer file MTP
- [ ] kontrol kecerahan
- [ ] Umpan balik getaran
- [ ] mendukung bahasa

## Target
- Full data decryption (FBE v2) untuk Android 15
- Kompatibilitas AVB 2.0
- Layar sentuh sepenuhnya berhasil
- Fungsionalitas cadangan dan memulihkan
- MTP support untuk transfer file

## 🔧 Instalasi
> ⚠️ **PERINGATAN: Instalasi dapat menyebabkan ponsel bootloop, pastikan kamu telah teliti dalam menginstal Recovery atau tidak kamu harus menanggung resiko mu sendiri!**

1. Unduh TWRP rilisan terbaru di [Releases](https://github.com/Fskris34/TWRP-gale-A15/releases)
2. Unduh dan buka [platform tools](https://developer.android.com/tools/releases/platform-tools) di Windows
3. Boot device kamu ke mode fastboot:
   ```bash
   adb reboot bootloader
4. Setelah rebooting, Flash TWRP di fastboot
   ```bash
   fastboot flash recovery twrp.img
5. Kemudian, buka recovery menggunakan perintah
   ```bash
   fastboot reboot recovery
**💡CATATAN: Jika kamu mengalami bootloop, flash recovery stock image kamu kembali!**

## Credits
Berdasarkan [TeamWin Recovery Project](https://github.com/TeamWin)
<p align="center">
Sumber asli dilisensikan di bawah GPL v3, dan Team Win LLC, © 2026.

`This program is an unofficial initiative. All TWRP-related assets remain under the ownership of Team Win LLC. We strictly adhere to project guidelines concerning TWRP development.`
