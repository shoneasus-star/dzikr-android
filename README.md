# Dzikr Android

Repositori khusus untuk membangun aplikasi Dzikr menjadi APK Android melalui GitHub Actions.

## Cara memasukkan proyek
Unggah arsip `dzikr-play-project.zip` ke halaman utama repositori (Add file → Upload files), lalu commit ke branch `main`.

Workflow akan mengekstrak folder `dzikr-play/`, memasang dependensi Capacitor, lalu membangun APK debug.

Hasil APK tersedia di tab **Actions** pada artifact bernama `dzikr-debug-apk`.
