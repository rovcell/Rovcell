# ROVCELL SMARTPHONE - PWA PACKAGE FOR PWABuilder.com

File-file ini sudah disiapkan agar 100% siap di-upload atau di-host untuk diproses di **pwabuilder.com**:

## Cara Upload & Generate APK di PWABuilder:
1. **Upload / Deploy Website**: 
   - Anda perlu meng-host file-file ini secara online (misalnya menggunakan Netlify, GitHub Pages, Vercel, atau Firebase Hosting).
   - *Catatan Netlify*: Cukup drag and drop folder atau zip ini ke Netlify (atau gunakan Netlify CLI/Git). Pastikan URL publiknya bisa diakses (contoh: `https://rovcell.netlify.app`).
2. **Buka PWABuilder**:
   - Kunjungi [pwabuilder.com](https://www.pwabuilder.com/).
   - Masukkan URL website Anda (misalnya `https://rovcell.netlify.app`).
   - Klik **Start**.
3. **Analisis PWA**:
   - PWABuilder akan memeriksa Manifest dan Service Worker Anda (Manifest, Service Worker, Icons sudah lengkap di paket ini!).
   - Klik **Generate** pada bagian **Android** (atau platform lain yang diinginkan).
4. **Build APK**:
   - Sesuaikan package name (misal: `com.rovcell.smartphone`), App Name, dan upload logo ikon jika diminta.
   - Klik **Generate** / **Download** untuk mengunduh file APK siap install di Android.

## File yang Tersedia dalam Paket Ini:
- `index.html` (Aplikasi utama Rovcell Service & Admin Dashboard)
- `manifest.json` (Konfigurasi PWA Web Manifest)
- `sw.js` (Service Worker untuk dukungan offline & caching)
- `icon-192.png` & `icon-512.png` (Ikon aplikasi PWA)
- `Qris Rovcell.PNG` (QRIS pembayaran)
