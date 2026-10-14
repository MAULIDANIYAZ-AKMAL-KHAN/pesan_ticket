# 🎟️ Sistem Pemesanan Tiket Event Online

Aplikasi web berbasis **Laravel** untuk pemesanan tiket konser musik, festival seni, dan seminar. Aplikasi ini memfasilitasi pengguna untuk memesan tiket secara daring serta menyediakan panel admin untuk manajemen data event dan monitoring pesanan.

---

## 🚀 Fitur Utama

### 👤 Halaman Pengunjung / Customer
* **Katalog Tiket:** Menampilkan daftar tiket event lengkap dengan foto banner, harga tiket, dan deskripsi.
* **Filter Kategori:** Memfilter event berdasarkan kategori (*Musik*, *Festival*, dan *Seminar*).
* **Form Pemesanan & Checkout:** Form ringkas untuk memasukkan identitas pemesan (nama & email) serta jumlah tiket yang dipesan.
* **Kalkulasi Otomatis:** Perhitungan subtotal dan total biaya pesanan secara otomatis.

### 🛡️ Dashboard Admin
* **Autentikasi & Keamanan:** Fitur login akun pengelola berbasis Laravel Breeze.
* **Master Data Event (CRUD):** 
  * Tambah event baru dengan unggah banner (mendukung JPEG, PNG, dan WebP).
  * Edit informasi tiket, harga, kategori, dan deskripsi.
  * Hapus event beserta file gambar dari *storage*.
* **Manajemen Pesanan Masuk:**
  * Memantau detail pembeli, rincian item tiket, dan total pembayaran.
  * Pembaruan status pesanan (*Pending*, *Confirmed / Selesai*, *Cancelled*).

---

## 🛠️ Teknologi yang Digunakan

* **Backend:** PHP 8.x, Laravel Framework
* **Frontend:** Blade Templating, Tailwind CSS, Vite
* **Database:** MySQL
* **Autentikasi:** Laravel Breeze

---

## ⚙️ Panduan Instalasi Lokal

Ikuti langkah-langkah berikut untuk menjalankan project ini di komputer lokal:

### 1. Clone Repository
```bash
git clone [https://github.com/Ilham6648/Pesan_ticket.git](https://github.com/Ilham6648/Pesan_ticket.git)
cd Pesan_ticket