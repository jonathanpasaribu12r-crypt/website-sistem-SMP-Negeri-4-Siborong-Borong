# Website Sistem Informasi SMP Negeri 4 Siborong-Borong

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)

Website resmi dan sistem informasi akademik untuk **SMP Negeri 4 Siborong-Borong**. Proyek ini dirancang dengan tampilan responsif menggunakan **Bootstrap** untuk memudahkan siswa, guru, orang tua, dan masyarakat dalam mengakses profil sekolah, berita terbaru, hingga informasi Penerimaan Peserta Didik Baru (PPDB).

## Fitur Utama

* **Profil & Informasi Sekolah:** Halaman profil sekolah, struktur organisasi, dan tata tertib siswa.
* **Informasi PPDB & Zonasi:** Panduan lengkap pendaftaran siswa baru serta informasi pembagian wilayah zonasi.
* **Portal Berita & Pengumuman:** Menampilkan daftar berita kegiatan sekolah dan halaman detail berita secara dinamis.
* **Direktori Guru:** Informasi daftar tenaga pendidik di SMP Negeri 4 Siborong-Borong.
* **Panel Administrator:** Halaman khusus admin untuk mengelola konten berita, data guru, dan informasi sekolah.
* **Formulir Kontak:** Fitur pengiriman pesan langsung yang terintegrasi dengan PHPMailer.

## Teknologi yang Digunakan

* **Frontend:** HTML5, CSS3, JavaScript, **Bootstrap**
* **Backend:** PHP Native
* **Database:** MySQL
* **Library & Plugin:** FontAwesome, GLightbox, Swiper, PHPMailer

## Cara Menjalankan di Komputer Lokal

1. **Unduh atau Clone Repository:**
   ```bash
   git clone [https://github.com/jonathanpasaribu12r-crypt/website-sistem-SMP-Negeri-4-Siborong-Borong.git](https://github.com/jonathanpasaribu12r-crypt/website-sistem-SMP-Negeri-4-Siborong-Borong.git)
   ```
2. **Pindahkan ke Folder Server Lokal:**
   Letakkan folder proyek ke dalam direktori `htdocs` (jika menggunakan XAMPP) atau `www` (jika menggunakan Laragon).
3. **Import Database:**
   * Buka `http://localhost/phpmyadmin` di browser.
   * Buat database baru (misalnya: `db_admin`).
   * Import file **`db_admin.sql`** yang ada di dalam folder proyek ke database tersebut.
4. **Konfigurasi Koneksi Database:**
   Buka file **`db_config.php`** dan sesuaikan nama database, username, serta password dengan pengaturan server lokalmu.
5. **Jalankan Website:**
   Buka browser dan akses `http://localhost/website-sistem-SMP-Negeri-4-Siborong-Borong`.