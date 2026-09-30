<p align="center">
  <img src="icon.png" alt="Pengaturan Router" width="140">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-4.2%2B%20sampai%2014-green" alt="Android">
  <img src="https://img.shields.io/badge/Platform-Universal-orange" alt="Platform">
  <img src="https://img.shields.io/badge/License-Bebas%20digunakan-lightgrey" alt="License">
</p>

# Pengaturan Router

Aplikasi Android pintar yang otomatis mendeteksi WiFi yang sedang terhubung, lalu membuka halaman admin router langsung di dalam aplikasi - tanpa perlu mengingat IP router atau berpindah ke browser.

## Daftar Isi

- [Fitur](#fitur)
- [Cara Pakai](#cara-pakai)
- [Kompatibilitas](#kompatibilitas)
- [Izin yang Dibutuhkan](#izin-yang-dibutuhkan)
- [FAQ](#faq)
- [Download](#download)

## Fitur

- **Pintar & otomatis** - mendeteksi IP router dari WiFi yang sedang terhubung, tanpa perlu setup manual.
- **Buka di dalam aplikasi** - halaman admin router tampil di dalam aplikasi (WebView), bukan di browser.
- **Universal** - mendukung semua merek router: ZTE, TP-Link, Huawei, Xiaomi, Indihome, Biznet, MyRepublic, First Media, dan lainnya.
- **Mode HP / PC** - tombol untuk ganti tampilan antara mode mobile dan mode desktop (tampilan seperti di komputer, semua menu terlihat lengkap).
- **Offline support** - tetap bisa membuka admin router walau WiFi tidak ada koneksi internet.
- **Multi-metode deteksi** - coba gateway dari Android, IP umum, dan scan jaringan otomatis.
- **Auto-fit** - tampilan desktop otomatis menyesuaikan ukuran layar HP, bisa pinch zoom pakai 2 jari.

## Cara Pakai

1. Install APK dari halaman [Releases](https://github.com/ainnefasarome/pengaturan-router/releases).
2. Pastikan HP terhubung ke WiFi.
3. Klik ikon Pengaturan Router.
4. Aplikasi otomatis membuka halaman admin router.
5. Login ke router seperti biasa.
6. Klik tombol **PC** di kanan atas untuk beralih ke tampilan desktop (semua menu terlihat lengkap).
7. Klik tombol **HP** untuk kembali ke tampilan mobile.

## Kompatibilitas

| Item | Keterangan |
|------|------------|
| Minimum Android | 4.2 (Jelly Bean, API 17) |
| Target Android | 14 (API 34) |
| Arsitektur | Universal (semua) |

**Mendukung otomatis sebagian besar router:**
ZTE, TP-Link, Huawei, Xiaomi, Tenda, Indihome, Biznet, MyRepublic, First Media, dan lainnya.

## Izin yang Dibutuhkan

Aplikasi ini membutuhkan beberapa izin standar Android:

- **INTERNET** - untuk membuka halaman admin router.
- **ACCESS_NETWORK_STATE** - untuk cek status koneksi.
- **ACCESS_WIFI_STATE** - untuk baca info WiFi yang sedang terhubung (IP gateway).
- **ACCESS_FINE_LOCATION / COARSE_LOCATION** - dibutuhkan Android untuk mengakses info WiFi di beberapa versi.
- **NEARBY_WIFI_DEVICES** - dibutuhkan Android 13+ untuk akses info WiFi.

## FAQ

**Apakah aplikasi ini butuh root?**
Tidak. Berjalan sepenuhnya tanpa root.

**Apakah bisa dipakai untuk semua router?**
Ya, aplikasi ini mendukung semua merek router karena mendeteksi IP gateway secara otomatis dari WiFi yang terhubung.

**Kenapa butuh izin lokasi?**
Android mewajibkan izin lokasi untuk aplikasi yang mengakses info WiFi. Ini aturan dari Android, bukan dari aplikasi ini.

**Apakah bisa dipakai offline?**
Bisa. Selama HP masih terhubung ke WiFi (walau tidak ada internet), aplikasi tetap bisa membuka halaman admin router.

**Kalau HP tidak konek WiFi, apa yang terjadi?**
Muncul pesan "WiFi tidak terhubung" sebentar, lalu aplikasi menutup sendiri.

## Download

Silakan kunjungi halaman [Releases](https://github.com/ainnefasarome/pengaturan-router/releases) untuk mengunduh versi terbaru.

Pastikan untuk mengunduh hanya dari halaman resmi repositori ini.
