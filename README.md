# 🚗 Car Inventory & Rental Management System

Sistem manajemen inventori dan penyewaan mobil berbasis web yang dibangun menggunakan framework **Laravel**. Proyek ini dirancang untuk mendigitalisasi pengelolaan aset kendaraan, memantau status ketersediaan secara real-time, dan mencatat transaksi penyewaan dengan efisien.

## 🌟 Fitur Utama
- **Dashboard Overview:** Ringkasan jumlah total kendaraan, kendaraan yang tersedia, dan transaksi aktif.
- **Inventory Management (CRUD):** Pengelolaan data mobil lengkap (Merk, Model, Plat Nomor, Tahun, dan Harga Sewa).
- **Status Tracking:** Pembaruan status kendaraan otomatis (Available, Rented, Maintenance).
- **Customer Management:** Pendataan pelanggan yang menyewa kendaraan.
- **Rental Transactions:** Sistem pencatatan sewa yang terintegrasi antara data pelanggan dan mobil.
- **Database Migrations & Seeders:** Memudahkan setup basis data dan pengisian data dummy untuk keperluan testing.

## 🛠️ Tech Stack
- **Framework:** [Laravel 10+](https://laravel.com/)
- **Language:** PHP >= 8.1
- **Database:** MySQL
- **Frontend:** Blade Templating, Bootstrap 5
- **Tooling:** Composer, NPM

## 📐 Arsitektur Database
Proyek ini menggunakan hubungan antar tabel (Relational Database) untuk menjaga integritas data:
- **Tabel `cars`**: Menyimpan detail aset kendaraan.
- **Tabel `customers`**: Menyimpan identitas penyewa.
- **Tabel `rentals`**: Menghubungkan data mobil dan pelanggan untuk pencatatan transaksi.



## 🚀 Panduan Instalasi

Ikuti langkah-langkah berikut untuk menjalankan proyek ini di lingkungan lokal Anda:

1. **Clone Repositori:**
   ```bash
   git clone [https://github.com/ferandlim00/INVENTORI-MOBIL.git](https://github.com/ferandlim00/INVENTORI-MOBIL.git)
   cd INVENTORI-MOBIL
