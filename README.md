# QR Code dari Excel (PWA)

Aplikasi web untuk membuat PDF A4 (10 QR code per halaman) dari kolom Status file Excel/CSV. Bisa dipasang sebagai aplikasi dan berjalan offline.

## Deploy ke GitHub Pages
1. Buat repository baru di GitHub, lalu unggah semua isi folder ini (index.html, sw.js, manifest.webmanifest, folder icons).
2. Buka Settings > Pages.
3. Di "Build and deployment", pilih Source: Deploy from a branch, branch `main`, folder `/ (root)`, lalu Save.
4. Tunggu 1-2 menit, alamatnya: https://USERNAME.github.io/NAMA-REPO/

## Catatan
- PWA hanya berfungsi lewat HTTPS (GitHub Pages sudah HTTPS) atau localhost, bukan dengan membuka file langsung.
- Setelah mengubah file, naikkan versi `CACHE` di sw.js (misal `qr-excel-v2`) agar pengguna mendapat versi terbaru.
