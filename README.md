# CardioTracker 21K — PWA

Versi PWA dari CardioTracker 21K.

## Struktur
- `index.html` — aplikasi utama
- `manifest.json` — konfigurasi installable PWA
- `sw.js` — service worker/cache
- `icon-192.png` dan `icon-512.png` — icon aplikasi

## Cara menjalankan
PWA membutuhkan HTTPS atau localhost. Jangan hanya membuka `index.html` dengan `file://`.

Pilihan paling mudah:
1. Upload folder ini ke GitHub Pages, Netlify, Vercel, atau hosting HTTPS lain.
2. Buka URL dari Chrome Android.
3. Pilih **Install app** / **Add to Home screen**.
4. Setelah terpasang, CardioTracker akan muncul seperti aplikasi.

## Catatan
Data sesi tetap menggunakan `localStorage`, seperti skrip asli. Jadi data tersimpan di browser/perangkat tempat aplikasi digunakan.
