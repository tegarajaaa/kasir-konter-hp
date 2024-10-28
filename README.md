# kasir-konter-hp
[Readme.md ](https://github.com/user-attachments/files/17545370/Readme.md)

# PROGRAM KASIR KONTER HP

# Mesin Kasir Konter HP

Proyek ini adalah aplikasi mesin kasir sederhana yang dirancang untuk konter HP. Program ini memungkinkan pengguna untuk menambahkan item yang dibeli ke dalam daftar, menghitung total biaya, dan menyelesaikan transaksi. Kode telah di-refactoring untuk membuatnya lebih modular dan mudah dipelihara.

## Fitur

- **Tambah Item**: Tambahkan produk atau layanan yang dibeli ke dalam daftar.
- **Hitung Total**: Menghitung total harga dari semua item yang ada di daftar pembelian.
- **Selesaikan Transaksi**: Menghapus daftar item setelah transaksi selesai untuk memulai transaksi baru.

## Teknologi yang Digunakan

- **Bahasa**: Java
- **Paradigma**: Pemrograman Berorientasi Objek (OOP)
- **Versi Java**: Minimum Java 8

## Struktur Proyek

MesinKasirKonterHP  Main.java # Kelas utama untuk menjalankan program MesinKasir.java # Kelas utama untuk operasi mesin kasir Item.java # Kelas untuk merepresentasikan item produk atau layanan README.md

## Compiling

Buka terminal atau Command Prompt di dalam folder proyek, lalu kompilasi semua file .java dengan perintah berikut:

javac src/*.java

## Menjalankan Program

Setelah kompilasi selesai, jalankan program menggunakan perintah:

java -cp src Main

## Menambah dan Menghitung Item

Saat program berjalan, ikuti instruksi di layar untuk menambah item ke daftar pembelian dan melihat total harga.

## Contoh Penggunaan Program
Berikut adalah contoh output dari program mesin kasir ini:

=== Mesin Kasir Konter HP ===
1. Tambah Item
2. Hitung Total
3. Selesaikan Transaksi
4. Keluar
Pilih opsi: 1
Masukkan nama item: Charger HP
Masukkan harga item: 50000

1. Tambah Item
2. Hitung Total
3. Selesaikan Transaksi
4. Keluar
Pilih opsi: 2
Total harga: 50000

## Dokumentasi Kode
Kode ini telah di-dokumentasikan menggunakan JavaDoc. Setiap kelas dan metode memiliki penjelasan singkat untuk memudahkan pemahaman. Pastikan untuk membaca file src jika ingin mengerti lebih dalam tentang logika setiap bagian program.

Pengembangan Lanjutan
Beberapa fitur tambahan yang mungkin ingin dikembangkan:

Penyimpanan Data: Menyimpan data transaksi ke dalam file untuk pencatatan dan pelacakan transaksi.
Antarmuka Grafis (GUI): Mengubah antarmuka menjadi GUI untuk mempermudah penggunaan.
Database: Mengintegrasikan sistem kasir dengan database untuk menyimpan produk dan histori transaksi.
