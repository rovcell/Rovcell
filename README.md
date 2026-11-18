# ROVCELL SMARTPHONE - PWA PACKAGE FOR VERCEL & PWABuilder

Paket ini sudah dilengkapi konfigurasi khusus Vercel (`vercel.json`) dan perbaikan zona waktu lokal (WIB).

## Langkah Deploy di Vercel & PWABuilder:
1. Upload semua file di dalam paket ini ke repository GitHub Anda (atau langsung deploy ke Vercel).
2. Pastikan di Vercel **Settings > Deployment Protection**, opsi *Vercel Authentication* dimatikan untuk Production agar PWABuilder bisa memindai website Anda tanpa error *Load failed*.
3. Masukkan URL domain Vercel Anda (contoh: `https://rovcell.vercel.app`) ke [pwabuilder.com](https://www.pwabuilder.com/).
4. Unduh file `assetlinks.json` dari PWABuilder, lalu simpan di dalam folder `.well-known/assetlinks.json` pada repository Anda agar bar URL hilang saat APK dibuka.
