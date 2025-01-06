# Catalog Sepatu App

Aplikasi Katalog Sepatu adalah aplikasi yang dirancang untuk mengelola data sepatu, mulai dari menampilkan daftar sepatu hingga menambahkan sepatu baru melalui form input. Aplikasi ini memanfaatkan API untuk melakukan komunikasi dengan server.

## Fitur Utama

1. Menampilkan Daftar Sepatu
   - Mengambil dan menampilkan semua data sepatu dari server.
   - Data sepatu ditampilkan dalam bentuk katalog dengan informasi lengkap seperti brand, nama, kategori, harga, diskon, warna, dan    gambar.

2. Form Input Sepatu
   - Form untuk menambahkan sepatu baru ke dalam katalog.
   - Form ini menerima data seperti brand, nama sepatu, kategori, harga, diskon, warna, dan gambar sepatu.

3. Pengelolaan Data
   - Data sepatu dikelola dalam bentuk model (KatalogSepatuModel) yang memudahkan pengolahan data.
   - Konversi data dari dan ke format JSON dilakukan melalui metode fromJson dan toJson.

4. Upload Gambar
   - Aplikasi mendukung unggahan file gambar sepatu melalui form input.
   - Gambar dikirim sebagai file multipart menggunakan dio.