# Jawaban Tes Debugging SIMRS Mini

Nama: Koandres
Tanggal: 04 November 2026 

Salin blok di bawah untuk setiap bug yang Anda temukan.

## Bug 1

- Gejala: Tidak bisa koneksi database
- Lokasi (file:baris): config/database.php:51
- Penyebab: port tidak sesuai dengan mesin lokal
- Perbaikan: penyesuaian port menjadi 3307

## Bug 2

- Gejala: Jumlah pasien perempuan tidak tampil
- Lokasi (file:baris): controllers/DashboardControllers.php:17
- Penyebab: filter jenis kelamin salah
- Perbaikan: mengubah filter dari Perempuan menjadi P
