# 🎓 Project Ujian Sekolah

[![Laravel Version](https://img.shields.io/badge/Laravel-v12.x-red)](https://laravel.com)
[![PHP Version](https://img.shields.io/badge/PHP-8.2%2B-blue)](https://php.net)

Sebuah platform manajemen ujian berbasis web yang dirancang untuk memudahkan proses administrasi, pelaksanaan, hingga penilaian ujian di lingkungan sekolah secara digital dan efisien.

---

## 📝 Latar Belakang

Transisi dari ujian berbasis kertas ke digital seringkali menghadapi kendala dalam hal kompleksitas manajemen data dan keamanan hasil. **Project Ujian Sekolah** ini dikembangkan untuk memberikan solusi yang:
* **Efisien:** Mengurangi penggunaan kertas (paperless) dan mempercepat distribusi soal.
* **Akurat:** Meminimalisir kesalahan manusia dalam koreksi jawaban.
* **Terpusat:** Memudahkan pihak sekolah dalam memantau perkembangan nilai siswa secara real-time.

---

## ✨ Fitur Utama

Aplikasi ini mencakup berbagai modul penting, antara lain:

* **Manajemen User:** Multi-role untuk Admin, Guru, dan Siswa.
* **Bank Soal:** Pengelolaan soal pilihan ganda maupun esai dengan dukungan upload gambar.
* **Ujian Real-time:** Pelaksanaan ujian dengan batasan waktu yang ketat.
* **Penilaian Otomatis:** Hasil ujian pilihan ganda langsung terakumulasi setelah ujian selesai.
* **Laporan Hasil:** Rekapitulasi nilai siswa dalam format yang mudah dipahami atau diekspor.
* **Dashboard Statistik:** Visualisasi data jumlah siswa, kelas, dan rata-rata nilai.

---

## 🚀 Instalasi 

Ikuti langkah-langkah di bawah ini untuk menjalankan proyek ini di lingkungan lokal kamu.

### 1. Clone Repositori
```bash
git clone https://github.com/Sayntao/project_ujian_sekolah.git
cd project_ujian_sekolah
```
### 2. Instalasi Dependency
```bash
composer install
```
### 3. Konfigurasi Environment
Salin file `.env.example` menjadi `.env` dan sesuaikan pengaturan database Anda
```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=project_ujian_sekolah
DB_USERNAME=root
DB_PASSWORD=
```
Pastikan bagian `DB_DATABASE`, `DB_USERNAME`, dan `DB_PASSWORD` sudah sesuai.
### 4. Generate App Key
```bash
php artisan key:generate
```
### 5. Migrasi Database & Seeding
```bash
php artisan migrate --seed
```
### 6. Jalankan Server
```bash
php artisan serve
```
Aplikasi sekarang dapat diakses melalui browser di: `http://127.0.0.1:8000`

---

## 🛠️ Teknologi yang Digunakan
* **Framework: Laravel 12**
* **Database: MySQL**
* **Frontend: Tailwind CSS**

---

## 📞 Kontak
Jika ada pertanyaan lebih lanjut mengenai proyek ini, silakan hubungi team development
