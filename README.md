## 🌟 Somnia Bot - Faucet & Swap Automator 🚀
Otomatisasi faucet dan swap token di Somnia Testnet!

Bot berbasis Node.js ini mengklaim token dari faucet dan melakukan swap otomatis untuk dompet Anda.

## 🎉 Fitur Utama
• 🚰 Faucet Otomatis: Klaim token testnet secara otomatis.

• 🔁 Swap Otomatis: Swap token PING ↔ PONG dengan mudah.

• 🌐 Dukungan Proxy: Gunakan proxy untuk privasi (opsional).

• 📊 Progress & Tabel: Pantau proses dengan progress bar dan tabel hasil.

• 🕘 Jadwal Otomatis: Bot berjalan terus hingga eksekusi berikutnya (default: 9 pagi WIB).

## 🛠️ Instalasi
1. Prasyarat:
Pastikan Node.js dan npm sudah terinstal (versi LTS direkomendasikan).
2. Instal Dependensi:
Jalankan perintah berikut untuk menginstal semua dependensi yang diperlukan:

```bash
npm install colors axios https-proxy-agent ethers cli-progress cli-table3 gradient-string
```

3. Siapkan File Konfigurasi:
`data.txt`: Isi dengan format `address|privateKey` per baris. Contoh:

```text
0x1234...abcd|0x5678...efgh
```

`proxy.txt` (opsional): Isi dengan format `http://ip:port` per baris. Contoh:

```text
http://192.168.1.1:8080
```

## ▶️ Cara Menjalankan
Jalankan bot dengan perintah:

```bash
node bot.js
```

## 📘 Catatan Penting
Pastikan koneksi internet stabil.
Jika proxy gagal atau `proxy.txt` kosong, bot akan pakai IP lokal.
Eksekusi otomatis terjadwal (default: 9 pagi WIB).


## 📜 Lisensi  

Script ini didistribusikan untuk keperluan pembelajaran dan pengujian. Penggunaan di luar tanggung jawab pengembang.  

Untuk update terbaru, bergabunglah di grup **Telegram**: [Klik di sini](https://t.me/sentineldiscus).


---

## 💡 Disclaimer
Penggunaan bot ini sepenuhnya tanggung jawab pengguna. Kami tidak bertanggung jawab atas penyalahgunaan skrip ini.
