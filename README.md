# ⚡ ClatScope-Mini

> **"Mata-mata digitalmu dalam genggaman. Ringan, cepat, dan tanpa jejak."**

ClatScope-Mini adalah alat OSINT (Open Source Intelligence) ringan namun ampuh, dirancang untuk pengintaian digital seperti IP lookup, pencarian username, dan pelacakan nomor HP. Cukup dijalankan di Termux, WSL, atau Linux. Tanpa API Key. Tanpa ribet.

---

## 🧙‍♂️ Fitur Dewa

- 🌍 **IP Lookup** – Cari lokasi, ISP, dan negara dari IP target.
- 🕵️‍♀️ **Username Lookup** – Lacak username di ratusan platform.
- 📱 **Phone Number Lookup** – Cek operator & lokasi nomor HP.
- 📂 **Auto Log** – Simpan semua hasil secara otomatis.
- 📲 **Telegram Notify (Opsional)** – Kirim hasil ke Telegram Bot.
- 🧪 **Tanpa API Key** – Serius, ini tool OSINT paling simpel sejagad.

---

## ⚙️ Instalasi Kilat

### Termux / WSL / Linux:
```bash
# Clone project
git clone https://github.com/kongali1720/ClatScope-Mini.git
cd ClatScope-Mini

# Install dependencies
pip install -r requirements.txt

# Jalankan tool
python3 clatscope_mini.py
```

---

## 🔎 Contoh Penggunaan

```bash
python3 clatscope_mini.py
```

Kemudian pilih salah satu:
```
[1] IP Lookup
[2] Username Lookup
[3] Phone Number Lookup
```
Masukkan data ➜ BOOM! Info keluar dan tersimpan di folder `logs/`

---

## 🧠 Struktur Repositori

| File/Folder           | Fungsi                             |
|-----------------------|------------------------------------|
| `clatscope_mini.py`   | File utama untuk menjalankan tool |
| `requirements.txt`    | Dependensi Python                 |
| `README.md`           | Dokumentasi ini                   |
| `logs/`               | Folder hasil log scan             |

---

## 🛡️ Telegram Notify (Opsional Tapi Keren)

1. Buat bot via [@BotFather](https://t.me/BotFather)
2. Catat `BOT_TOKEN`
3. Chat bot kamu dan dapatkan `CHAT_ID`
4. Buat file `.env`:
```env
TELEGRAM_BOT_TOKEN=isi_token_anda
TELEGRAM_CHAT_ID=isi_chat_id_anda
```
5. Jalankan tool ➜ Hasil scan langsung mendarat di Telegram!

---

## 🧩 Rencana Fitur Lanjutan

- [x] Logging otomatis
- [x] Telegram notification
- [ ] DNS & WHOIS scanner
- [ ] Reverse IP Lookup
- [ ] Export hasil ke PDF / CSV
- [ ] CLI interface modern dengan Rich

---

## 🔓 Lisensi

MIT License — Bebas digunakan, dimodifikasi, dan disebarkan selama mencantumkan atribusi.

---

## 👨‍💻 Kontribusi?

Silakan fork, modifikasi, dan kirim pull request. Tool ini open untuk siapa saja yang mau bantu push OSINT lokal ke level global!

---

# ☕ Dukung aku agar tetap waras menulis script tengah malam...

👉 [Buy Me a Coffee via PayPal](https://www.paypal.com/paypalme/bungtempong99) 👈  
Support with 💸 so I can buy ☕ and keep being 🔥!

---

## 📫 Let’s Connect Like Hackers

- 🧙 GitHub: [kongali1720](https://github.com/kongali1720)
- 💌 Email: [kongali1720@gmail.com](mailto:kongali1720@gmail.com)
- 🕵️‍♂️ Site: Coming soon — stay curious...

---

💻 INITIATING HUMANITY MODE...

🎯 Target Locked: Anak-anak Pejuang Down Syndrome  
🩺 Status: Butuh Dukungan  
❤️ Response: Buka Hati + Klik Link = Satu Senyum Baru

🧬 Mereka bukan berbeda — mereka dilahirkan untuk mengajarkan dunia tentang cinta yang murni dan kesabaran yang luar biasa.

👣 Setiap langkah kecil mereka = Keajaiban besar.

⚡ Bantu mereka melangkah lebih jauh, dengan caramu sendiri.

<p align="center">
  <a href="https://mydonation4ds.github.io/" target="_blank">
    <img src="https://img.shields.io/badge/SUPPORT--NOW-%F0%9F%A7%A1-orange?style=for-the-badge&logo=heart" />
  </a>
</p>

"Karena jadi hacker hati bukan cuma soal kode... tapi juga soal peduli." 🖤

"Ngoding boleh sambil senyum, asal jangan inject SQL sambil ngambek!" 😜

---
