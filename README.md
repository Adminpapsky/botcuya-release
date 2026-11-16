<div align="center">

# 🤖 BOT-CUYA

### WhatsApp Automation • Smart Dashboard • Android APK

**Kelola aktivitas WhatsApp dengan fitur otomatisasi, kontrol praktis, dan sistem pembaruan terpusat.**

[![Android](https://img.shields.io/badge/Platform-Android-3DDC84?logo=android&logoColor=white)](https://www.android.com/)
[![WhatsApp](https://img.shields.io/badge/Integration-WhatsApp-25D366?logo=whatsapp&logoColor=white)](https://www.whatsapp.com/)
[![Release](https://img.shields.io/badge/Download-Latest%20Release-blue?logo=github)](https://github.com/Adminpapsky/botcuya-release/releases/latest)
[![Version](https://img.shields.io/badge/Version-1.2-informational)](https://github.com/Adminpapsky/botcuya-release/releases/latest)

<br>

<a href="https://github.com/Adminpapsky/botcuya-release/releases/latest">
  <img src="https://img.shields.io/badge/⬇%20UNDUH%20BOT--CUYA-APK-168B55?style=for-the-badge&logo=android&logoColor=white" alt="Unduh BOT-CUYA APK">
</a>

<br><br>

**Dibuat untuk membantu mengelola fitur WhatsApp dari satu aplikasi Android.**

</div>

---

## 📥 Unduh BOT-CUYA

Versi terbaru tersedia melalui halaman rilis resmi:

- **[⬇️ Download BOT-CUYA APK](https://github.com/Adminpapsky/botcuya-release/releases/latest/download/BOT-CUYA.apk)**
- [Lihat seluruh riwayat rilis](https://github.com/Adminpapsky/botcuya-release/releases)
- [Baca panduan dan informasi proyek](https://github.com/Adminpapsky/botcuya-app)

> **Catatan:** BOT-CUYA didistribusikan sebagai APK Android. Jika Android meminta izin memasang aplikasi dari sumber ini, pastikan file berasal dari tautan rilis resmi di repository ini sebelum melanjutkan.

## ✨ Tentang BOT-CUYA

BOT-CUYA adalah aplikasi Android yang membungkus mesin bot WhatsApp berbasis Node.js dan menyediakan dashboard untuk menghubungkan akun, mengatur fitur, menentukan tujuan pesan, serta memantau status bot.

Pengguna APK tidak perlu memasang Termux atau mengetik perintah terminal untuk penggunaan dasar. Hubungkan WhatsApp melalui aplikasi, lalu kelola pengaturan dari dashboard lokal.

## 🌟 Fitur utama

### 👁️ Otomatisasi Status WhatsApp
- **Story Watcher** — memantau status kontak dan meneruskan status baru ke chat pribadi atau tujuan yang dipilih.
- **Silent Mode** — mode pemantauan status tanpa mengirim tanda dilihat melalui fitur otomatis bot.
- **Auto Like** — menyukai status secara otomatis ketika diaktifkan dan Silent Mode dimatikan.
- **Unduh dan teruskan media status** — mendukung konten status berupa foto, video, audio, dan teks sesuai dukungan versi yang digunakan.
- **Blacklist & Whitelist** — mengatur nomor yang dikecualikan atau diprioritaskan untuk pemantauan.
- **Arsip Story** — menyimpan arsip status yang diteruskan untuk pencarian kembali.

### 🛡️ Privasi dan perlindungan pesan
- **Anti-Delete** — menyimpan cache sementara pesan masuk agar pesan yang ditarik dapat dilaporkan kembali ke tujuan yang ditentukan.
- **View Once** — fitur penanganan media sekali lihat sesuai dukungan implementasi bot.
- **Anti-Edit** — meneruskan informasi perubahan pesan jika plugin terkait tersedia dan diaktifkan.
- **Sensor Nomor** — menyamarkan nomor pada informasi status sesuai pengaturan.
- **Anti-Call** — menangani panggilan masuk sesuai konfigurasi.
- **Pemeriksa tautan** — membantu memberi peringatan terhadap tautan yang mencurigakan.

### 💬 Produktivitas chat
- **Pengingat dan pesan terjadwal** — membuat pengingat berdasarkan durasi atau jam tertentu.
- **Pesan terjadwal ke kontak** — mengirim pesan pada waktu yang ditentukan.
- **Template balasan** — menyimpan teks balasan yang sering digunakan.
- **Catatan tersimpan** — menyimpan pesan penting dan memanggilnya kembali.
- **Kata kunci dan mention** — meneruskan pesan yang sesuai aturan kata kunci atau mention.
- **Penerjemah dan transkripsi** — fitur berbantuan layanan AI, memerlukan konfigurasi API.
- **Teks menjadi voice note** — tersedia melalui layanan AI atau perangkat pendukung yang sesuai.

### 🧰 Media dan dokumen
- Membuat stiker dari media yang didukung.
- Menggabungkan gambar menjadi PDF.
- Mengambil teks artikel dari tautan.
- Mengunduh media dari tautan dengan alat pendukung.
- Mengubah voice note menjadi teks dengan layanan AI.

### 🛍️ Toko dan pencatatan
- Katalog produk, stok, pesanan, dan pencatatan transaksi.
- Alur pembayaran dan konfirmasi pesanan.
- Dukungan QRIS sesuai konfigurasi toko.
- Pengingat masa langganan.
- Pencatatan pemasukan dan pengeluaran serta laporan keuangan.

### ⚙️ Pengelolaan dan pemantauan
- Dashboard web lokal untuk melihat ringkasan dan status koneksi.
- Sakelar bot aktif/nonaktif dan kontrol sambung ulang.
- Pengaturan ON/OFF fitur dan tujuan penerusan.
- Log aktivitas untuk membantu pemeriksaan masalah.
- Pemantauan proses, peringatan kondisi tertentu, dan pemulihan proses sesuai mekanisme yang tersedia.
- Backup data terjadwal dan backup manual.
- Dukungan pengelolaan beberapa akun pada instalasi yang mendukungnya.

> **Ketersediaan fitur bergantung pada jenis instalasi.** Beberapa fungsi yang memerlukan program eksternal seperti FFmpeg, yt-dlp, espeak, Termux:API, atau konfigurasi API AI tidak tersedia di APK Android standar. Lihat bagian [Batasan APK](#-catatan-penting-dan-batasan-apk).

## 📱 Tampilan dan penggunaan

### 1. Pasang aplikasi
Unduh APK dari halaman [Latest Release](https://github.com/Adminpapsky/botcuya-release/releases/latest), lalu buka file APK untuk memasangnya.

### 2. Buka BOT-CUYA
Jalankan aplikasi dan tunggu proses persiapan pertama selesai. Berikan izin notifikasi yang diminta agar informasi status bot dapat ditampilkan.

### 3. Hubungkan WhatsApp
1. Buka tab **Ringkasan** pada dashboard.
2. Masukkan nomor WhatsApp yang ingin dihubungkan.
3. Minta kode penautan.
4. Di WhatsApp, buka **Perangkat tertaut → Tautkan perangkat → Tautkan dengan nomor telepon**.
5. Masukkan kode yang ditampilkan BOT-CUYA.

### 4. Atur fitur
Buka tab **Fitur** untuk mengaktifkan atau menonaktifkan fitur yang tersedia.

### 5. Tentukan tujuan pesan
Gunakan tab **Tujuan** untuk memilih apakah hasil fitur dikirim ke chat pribadi, nomor tertentu, atau grup yang dipilih.

### 6. Pantau bot
Gunakan tab **Ringkasan** dan **Log** untuk memeriksa koneksi serta aktivitas bot. Dashboard juga menyediakan kontrol untuk mematikan bot atau mencoba menyambungkan ulang.

## 🔄 Sistem pembaruan aplikasi

BOT-CUYA memiliki mekanisme pemeriksaan versi terpusat. Saat versi baru tersedia, aplikasi dapat menampilkan pemberitahuan pembaruan.

- Informasi versi dan catatan rilis dikelola melalui konfigurasi rilis.
- Pengguna diarahkan ke tautan APK resmi.
- Sistem mendukung kebijakan pembaruan wajib berdasarkan versi minimum.
- Pada konfigurasi rilis saat ini, masa tenggang pembaruan wajib ditetapkan **3 hari**.
- Setelah masa tenggang berakhir, versi yang sudah berada di bawah batas minimum dapat dibatasi hingga diperbarui.

**Selalu unduh pembaruan dari repository resmi BOT-CUYA Release.** Jangan memasang APK dari tautan tidak dikenal.

## 🧩 Contoh perintah bot

Untuk pengguna yang memakai fitur perintah chat, berikut beberapa contoh perintah yang tercantum dalam dokumentasi source:

| Perintah | Kegunaan |
|---|---|
| `#menu` | Menampilkan menu perintah |
| `#fitur` | Melihat daftar fitur dan status ON/OFF |
| `#on storywatcher` | Mengaktifkan Story Watcher |
| `#off storywatcher` | Menonaktifkan Story Watcher |
| `#on silent` | Mengaktifkan mode silent |
| `#on antidelete` | Mengaktifkan Anti-Delete |
| `#status` | Melihat status bot |
| `#tujuan` | Melihat pengaturan tujuan penerusan |
| `#poststory Halo semua` | Membuat status teks |
| `#ingatkan 30m Periksa pesanan` | Membuat pengingat 30 menit |
| `#backup` | Memulai backup manual |
| `#lang id` | Menggunakan bahasa Indonesia |
| `#lang en` | Menggunakan bahasa Inggris |

Daftar perintah dapat berubah mengikuti versi. Ketik `#menu` di chat bot untuk melihat menu yang tersedia pada instalasi Anda.

## ⚠️ Catatan penting dan batasan APK

- APK standar ditujukan untuk perangkat Android **64-bit (arm64)**.
- Pengguna APK tidak memerlukan Termux untuk penggunaan dasar.
- Fitur yang membutuhkan program eksternal—misalnya FFmpeg, yt-dlp, espeak, Termux:API, atau dependensi khusus lainnya—dapat tidak tersedia pada APK standar.
- Fitur AI memerlukan konfigurasi penyedia API dan dapat menimbulkan biaya sesuai kebijakan penyedia.
- Android dapat menghentikan proses latar belakang. Untuk kestabilan, izinkan notifikasi dan atur penggunaan baterai BOT-CUYA sesuai kemampuan perangkat.
- Jangan menjalankan dua instalasi bot dengan akun WhatsApp yang sama secara bersamaan karena dapat menyebabkan sesi atau balasan ganda.
- BOT-CUYA bukan aplikasi resmi WhatsApp dan tidak berafiliasi dengan WhatsApp atau Meta. Penggunaan otomasi pihak ketiga dapat memiliki risiko terhadap akun. Gunakan secara bertanggung jawab dan patuhi ketentuan layanan WhatsApp.

## 🔐 Keamanan dan privasi

- Hubungkan hanya akun WhatsApp milik Anda atau akun yang penggunaannya telah mendapat izin.
- Jangan membagikan kode penautan, token dashboard, file sesi, file konfigurasi rahasia, atau kunci backup kepada orang lain.
- Dashboard dirancang untuk diakses secara lokal dari perangkat yang menjalankan bot dan dilindungi token.
- Data sesi dan pesan merupakan data sensitif. Lindungi perangkat dan file backup Anda.
- Sebelum membagikan log atau laporan masalah, periksa terlebih dahulu apakah terdapat informasi pribadi di dalamnya.

## 🧯 Pemecahan masalah

| Masalah | Langkah awal |
|---|---|
| WhatsApp belum terhubung | Periksa nomor dan ulangi proses penautan perangkat. |
| Bot terputus | Periksa koneksi internet, lalu gunakan tombol sambung ulang. |
| Dashboard tidak terbuka | Tutup dan buka kembali aplikasi; pastikan proses bot sudah selesai dimulai. |
| Notifikasi tidak muncul | Periksa izin notifikasi dan pengaturan baterai Android. |
| Fitur tertentu tidak bekerja | Periksa apakah fitur aktif, tujuan sudah benar, dan fitur didukung oleh jenis instalasi. |
| Pembaruan tidak dapat dipasang | Unduh ulang APK dari halaman rilis resmi dan periksa kompatibilitas perangkat. |

Jika masalah berlanjut, sertakan versi aplikasi, tipe perangkat, dan langkah yang menyebabkan masalah saat menghubungi pengelola.

## 🗂️ Repository proyek

| Komponen | Tautan |
|---|---|
| Distribusi APK dan rilis | [botcuya-release](https://github.com/Adminpapsky/botcuya-release) |
| Source code dan dokumentasi teknis | [Disembunyikan](https://wa.me/628172300004 |
| Unduhan versi terbaru | [Latest Release](https://github.com/Adminpapsky/botcuya-release/releases/latest) |

## 💚 Dukungan dan kontribusi

Gunakan halaman [Issues](https://github.com/Adminpapsky/botcuya-release/issues) untuk melaporkan masalah terkait distribusi APK atau memberikan masukan.

Terima kasih telah menggunakan BOT-CUYA dan mendukung pengembangan proyek ini.

---

<div align="center">

**BOT-CUYA — Smart Tools for Your WhatsApp Workflow**

_Dibuat dan dikembangkan oleh Adminpapsky._

[⬇️ Download APK](https://github.com/Adminpapsky/botcuya-release/releases/latest) · [📦 Source Code](https://github.com/Adminpapsky/botcuya-app) · [📝 Releases](https://github.com/Adminpapsky/botcuya-release/releases)

</div>
