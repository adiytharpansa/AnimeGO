<div align="center">

# Kumo

**Aplikasi Android untuk nonton anime subtitle Indonesia.**

[![Release](https://img.shields.io/github/v/release/adiytharpansa/AnimeGO?color=orange&label=Release&style=for-the-badge)](https://github.com/adiytharpansa/AnimeGO/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Android-brightgreen?style=for-the-badge)](https://developer.android.com)

</div>

---

## Unduh APK

[**Download Kumo (kumo.apk)**](https://github.com/adiytharpansa/AnimeGO/releases/latest/download/kumo.apk)

Cara install: unduh `kumo.apk`, buka berkasnya, lalu izinkan "install dari sumber tidak dikenal" bila diminta. Syarat: Android 8.0 (API 26) atau lebih baru.

## Fitur

| Fitur | Keterangan |
|---|---|
| **Katalog anime asli** | Data langsung dari AniList (poster, rating, sinopsis, trailer). |
| **7 server putar** | Videasy, VidLux, VidFast, VidFlix, ScreenScape, VidRock, 111Movies — Server 1 terbuka otomatis, ganti server kapan saja. |
| **Panel magnet Torrentio** | Sumber magnet (NyaaSi dll, urut seed terbanyak) untuk putar gratis lewat Stremio. |
| **Tampilan gaya AniBay** | Tema gelap pekat + aksen oranye, hero Spotlight, Rankings Top 10. |
| **Fullscreen otomatis** | Video diputar landscape layar penuh seperti pemutar video biasa. |
| **Daftarku & riwayat** | Simpan anime, lanjutkan menonton, tersimpan di perangkat. |

## Build

APK dibangun otomatis oleh GitHub Actions setiap ada push ke `main`
(workflow **Build APK Kumo**): Gradle 8.12 + JDK 17 menjalankan
`gradle assembleRelease`, hasilnya diunggah sebagai artifact **kumo-apk**
dan diterbitkan ke Release **v1.0.0** sebagai `kumo.apk`.

Aplikasi ini adalah pembungkus WebView native (Kotlin, tanpa dependensi
tambahan) untuk Kumo 2.0 di `app/src/main/assets/www/index.html`.

---

<div align="center">

Kumo — dibuat oleh Adiyth

</div>
