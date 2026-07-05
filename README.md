# 📚 Sistem Informasi Perpustakaan Berbasis Laravel
## Tugas Akhir - Ujian Akhir Semester (UAS) Pemrograman Website 2

---

## 👨‍🎓 Identitas Mahasiswa

| Keterangan | Data |
|------------|------|
| **Nama** | Ahmad Sandi Maftuh |
| **NIM** | 60324010 |
| **Mata Kuliah** | Pemrograman Website 2 |
| **Kode MK** | INF2419 |
| **Kelas** | A |
| **Program Studi** | Informatika |
| **Dosen Pengampu** | Mohammad Reza Maulana, M.Kom |
| **Universitas** | UIN K.H. Abdurrahman Wahid Pekalongan |

---

## 📖 Deskripsi Proyek

Sistem Informasi Perpustakaan merupakan aplikasi berbasis web yang dibangun menggunakan framework **Laravel** dengan pola **MVC (Model-View-Controller)**. Aplikasi ini dikembangkan sebagai studi kasus berkelanjutan sepanjang perkuliahan Pemrograman Website 2, mencakup pengelolaan data buku, anggota, kategori, penerbit, hingga transaksi peminjaman dan pengembalian buku secara digital.

---

## 🎯 Tujuan Proyek

- Mempermudah pengelolaan data perpustakaan secara digital.
- Mengelola data buku, kategori, dan penerbit.
- Mengelola data anggota perpustakaan.
- Mengelola transaksi peminjaman dan pengembalian buku.
- Menyajikan dashboard statistik dan laporan secara cepat dan akurat.

---

## 🛠️ Teknologi yang Digunakan

| Kategori | Teknologi |
|---|---|
| Backend | Laravel 12, PHP 8.4 |
| Database | MySQL |
| Frontend | php, Blade, Bootstrap 5, HTML5, CSS3, JavaScript |
| Tools | Laragon, Visual Studio Code, GitHub |

---

## ✨ Fitur Sistem

### 🔐 Authentication System
- Register, Login, Logout
- Middleware protecting routes
- Password hashing (bcrypt)

### 📘 Manajemen Buku (CRUD)
- Tambah, Edit, Hapus Buku
- Pencarian & Filter Buku per Kategori

### 🏷️ Manajemen Kategori
- Tambah, Edit, Hapus Kategori

### 🏢 Manajemen Penerbit
- Tambah, Edit, Hapus Penerbit

### 👥 Manajemen Anggota (CRUD)
- Tambah, Edit, Hapus Anggota
- Date picker untuk tanggal lahir
- Validasi email & nomor telepon
- Export data ke Excel

### 🔄 Manajemen Transaksi
- Peminjaman buku (auto-generate kode transaksi, auto-hitung tanggal kembali +7 hari, update stok otomatis)
- Pengembalian buku (perhitungan denda otomatis, update stok otomatis)
- Riwayat transaksi

### 📊 Dashboard
- Statistics cards (jumlah buku, anggota, kategori, transaksi)
- Chart transaksi & kategori buku
- Data buku & anggota terpopuler

### 🔎 Global Search
- Pencarian lintas modul (buku, anggota, transaksi)

### 🧾 Laporan Transaksi
- Filter berdasarkan tanggal, status, dan anggota
- Tampilan print-friendly

---

## 💾 Database

Nama database:

---

## 📂 Struktur Folder
