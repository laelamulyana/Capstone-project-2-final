# Unilever Distribution App

Aplikasi manajemen distribusi produk FMCG (Fast-Moving Consumer Goods) sederhana berbasis Python, dibuat sebagai capstone project. Aplikasi ini mensimulasikan sistem CRUD produk, transaksi penjualan ke outlet, riwayat transaksi, dan laporan analisis penjualan.

## 📋 Fitur

1. **Lihat Semua Data Produk** — menampilkan daftar produk beserta stok dan harga
2. **Tambah Data Produk Baru** — menambahkan produk baru dengan validasi duplikat
3. **Update Data Produk** — mengubah ukuran, stok, atau harga produk
4. **Hapus Data Produk** — menghapus produk dari katalog
5. **Input Penjualan ke Outlet** — mencatat transaksi penjualan dan mengurangi stok otomatis
6. **Lihat Riwayat Penjualan** — mencari riwayat transaksi berdasarkan kode transaksi
7. **Laporan Penjualan** — menampilkan ringkasan total pendapatan, produk terlaris, dan wilayah dengan penjualan tertinggi

## 🛠️ Teknologi

- Python 3 (tanpa library eksternal — pure Python)

## 🚀 Cara Menjalankan

1. Pastikan Python 3 sudah terinstall di komputer kamu
2. Masuk ke folder project dan jalankan:   4. Ikuti instruksi menu yang muncul di terminal

## 📊 Struktur Data

**Produk:**
```python
[nama, ukuran, kategori, stok, harga]
```

**Riwayat Penjualan:**
```python
[kode_transaksi, outlet, wilayah, nama_produk, ukuran, qty, subtotal]
```

## 👤 Penulis

Laela Mulyana

## 📝 Catatan

Project ini dibuat untuk keperluan belajar dan latihan pengembangan aplikasi CRUD sederhana menggunakan Python.
             
