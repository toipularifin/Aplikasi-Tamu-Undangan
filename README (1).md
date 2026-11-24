# Buku Tamu Digital & Dokumentasi Hajatan

Aplikasi web pencatatan buku tamu hajatan berbasis QR Code, pencatatan sumbangan (uang & beras), serta portal download foto dokumentasi bagi tamu undangan.

## Fitur Utama
1. **Meja Penerima Tamu (Scan QR)**: Memindai QR Code pada undangan fisik tamu untuk memunculkan nama & alamat secara otomatis, lalu mencatat nominal uang (Rp) dan beras (Kg).
2. **Generator Kartu QR Undangan**: Membuat QR Code unik untuk setiap tamu undangan yang dapat diunduh atau langsung dicetak.
3. **Upload & Portal Download Foto**: Panitia mengunggah foto dokumentasi acara, dan tamu dapat memindai QR undangannya untuk langsung mengunduh foto dokumentasi ke HP.
4. **Export Laporan Excel (CSV)**: Mengunduh rekap seluruh tamu hadir beserta total sumbangan uang dan beras.

## Cara Hosting di GitHub Pages
1. Buat repository baru di GitHub (atur visibilitas menjadi **Public**).
2. Upload file `index.html`, `README.md`, dan `.nojekyll` ke dalam repository tersebut.
3. Masuk ke menu **Settings > Pages**.
4. Pada bagian **Build and deployment > Branch**, pilih `main` dan folder `/ (root)`, lalu klik **Save**.
5. Tunggu beberapa saat hingga alamat website GitHub Pages Anda aktif.
