### Laravel Sanctum REST API

Proyek ini adalah API RESTful yang dibangun dengan Laravel Sanctum untuk autentikasi dan manajemen token yang aman. API ini menyediakan endpoint untuk registrasi pengguna, login, dan pengelolaan sumber daya seperti postingan dan komentar. Laravel Sanctum menawarkan solusi sederhana dan ringan untuk autentikasi API token, yang ideal untuk aplikasi satu halaman (SPA), aplikasi mobile, dan penggunaan API dasar.

Fitur Utama:
- **Autentikasi Pengguna:** Registrasi dan login pengguna yang aman dengan autentikasi berbasis token.
- **Manajemen Token:** Mengeluarkan dan mengelola token API untuk pengguna yang terautentikasi.
- **Operasi CRUD:** Endpoint untuk membuat, membaca, memperbarui, dan menghapus sumber daya.
- **Perlindungan Middleware:** Rute dilindungi dengan middleware Sanctum, memastikan hanya pengguna yang terautentikasi yang dapat mengakses endpoint tertentu.

### Instalasi

1. Clone repositori dan navigasikan ke direktori proyek.
2. Instal dependensi dengan `composer install`.
3. Atur file `.env` Anda dan konfigurasikan database Anda.
4. Jalankan migrasi dengan `php artisan migrate`.
5. Instal Laravel Sanctum dengan `composer require laravel/sanctum`.
6. Publikasikan konfigurasi Sanctum dengan `php artisan vendor:publish --provider="Laravel\Sanctum\SanctumServiceProvider"`.
7. Jalankan server dengan `php artisan serve`.

### Tautan Terkait

- Aplikasi Flutter telah dikembangkan untuk API ini: **[Flutter Blog App](https://github.com/feisauu/flutter_blog_app)**

---

Deskripsi ini mencakup link langsung ke proyek Flutter Blog App di GitHub.
