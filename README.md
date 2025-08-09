# 🚀 FastBot v2 — Termux Spam Simulation Tool

![FastBot Logo](https://img.shields.io/badge/FastBot-v1-blue?style=for-the-badge&logo=linux)
![Platform](https://img.shields.io/badge/Platform-Termux-green?style=for-the-badge&logo=android)
![License](https://img.shields.io/badge/License-MIT-orange?style=for-the-badge)

FastBot v1 adalah **alat simulasi spam WhatsApp** yang berjalan di Termux.  
⚠️ **Catatan**: Ini hanyalah simulasi, tidak mengirim pesan sungguhan.  
Didesain untuk **pembelajaran & hiburan**, bukan untuk penyalahgunaan.

---

## ✨ Fitur
- Tampilan tema **FastBot** yang unik.
- Intro otomatis yang mengarahkan ke:
  - YouTube: [ImFastro](https://www.youtube.com/ImFastro)
  - GitHub: [ImFastro](https://github.com/ImFastro)
- Efek suara **ketikan hacker palsu**.
- Log hasil simulasi ke file `sent.log`.

---

## 📥 Instalasi
Jalankan perintah ini di Termux:

```bash
pkg update -y && pkg install git -y
git clone https://github.com/ImFastro/FastBot.git
cd FastBot-v1
chmod +x install_fastbot.sh
./install_fastbot.sh
