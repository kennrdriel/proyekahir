<div align="center">
  <img src="https://raw.githubusercontent.com/AdrielClimateBot/assets/main/hero.png" alt="ClimateBot Banner" width="100%"/>

  <h1>🌍 ClimateBot</h1>
  <h3>Bot Discord Interaktif & Edukatif untuk Perubahan Iklim</h3>

  <p>
    <img src="https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python">
    <img src="https://img.shields.io/badge/discord.py-2.3.2-purple?style=for-the-badge&logo=discord">
    <img src="https://img.shields.io/badge/Open%20Source-Yes-brightgreen?style=for-the-badge&logo=github">
    <img src="https://img.shields.io/badge/Made%20with-❤️%20by%20Adriel-ff69b4?style=for-the-badge">
  </p>

  <p><i>"Karena bumi cuma satu. Dan sekarang dia lagi butuh bantuan kita."</i></p>
</div>

---

## 🧩 Apa Itu ClimateBot?

**ClimateBot** adalah bot Discord yang dibangun untuk menyebarkan kesadaran dan edukasi tentang **perubahan iklim** dengan cara yang:

- 💬 interaktif  
- 📊 informatif  
- 🎮 menyenangkan  
- 🌱 mengajak aksi nyata

Bot ini bukan cuma bot. Dia partner belajar, alarm hati nurani, dan sahabat yang peduli sama planet kita.

---

## 🧠 Fitur Unggulan

<div align="center">

| 🎮 Perintah        | 🔍 Penjelasan                                                                 |
|--------------------|--------------------------------------------------------------------------------|
| `!penjelasan`      | Menjelaskan apa itu perubahan iklim dengan bahasa santai dan ilmiah.          |
| `!dampak`          | Menunjukkan dampak perubahan iklim dari berbagai belahan dunia.               |
| `!solusi`          | Daftar solusi nyata yang bisa kamu mulai dari rumah sendiri.                  |
| `!quiz`            | Tantangan kuis acak seputar perubahan iklim. Skor-mu tercatat!                |
| `!tips`            | Tips hidup hijau yang bisa langsung kamu praktekkan.                          |
| `!fakta`           | Fakta mengejutkan dan update terbaru soal kondisi bumi.                       |
| `!tanya`           | Bertanya apapun ke bot tentang iklim—dibantu AI.                             |
| `!simulasi`        | Simulasi interaktif efek suhu naik 1–5°C. Ngeri, tapi nyata.                  |
| `!tantangan`       | Weekly eco-challenge: tantangan hijau yang bisa kamu bagikan ke server.       |
| `!event`           | Kalender event lingkungan dari seluruh dunia.                                |
| `!adriel`          | Info tentang developer bot: siapa gue, kenapa bikin ini.                      |

</div>

---

## 🔥 Cuplikan Bot Beraksi

> Tambahkan screenshot GIF/PNG untuk bikin pembaca klik bintang langsung 🌟

| 📸 `!quiz` | 📸 `!simulasi` | 📸 `!penjelasan` |
|-----------|----------------|------------------|
| ![quiz](https://raw.githubusercontent.com/AdrielClimateBot/assets/main/quiz.gif) | ![simulasi](https://raw.githubusercontent.com/AdrielClimateBot/assets/main/simulasi.gif) | ![penjelasan](https://raw.githubusercontent.com/AdrielClimateBot/assets/main/penjelasan.png) |

---

## 🛠️ Teknologi di Balik Layar

| Teknologi     | Keterangan                                                                 |
|---------------|-----------------------------------------------------------------------------|
| 🐍 Python     | Bahasa utama untuk logic bot & integrasi                                     |
| 💬 discord.py | Framework komunikasi antar bot & Discord                                     |
| 🌍 aiohttp    | Fetch berita & data real-time dari API publik                                |
| 🧠 OpenAI     | Untuk jawaban cerdas di `!tanya` (opsional, bisa toggle via env)             |
| 🗂️ Modular    | Command handler yang bisa dikembangkan dengan mudah                         |

---

## 📦 Instalasi & Setup

```bash
# 1. Clone repo ini
git clone https://github.com/AdrielClimateBot/climatebot.git
cd climatebot

# 2. Install dependency
pip install -r requirements.txt

# 3. Siapkan token bot di file .env
DISCORD_TOKEN=your_discord_token_here

# 4. Jalankan bot
python bot.py
