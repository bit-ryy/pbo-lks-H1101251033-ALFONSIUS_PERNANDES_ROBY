# PBO LKS - Portofolio Praktikum

## Identitas
- Nama: Alfonsius Pernandes Roby
- NIM:** H1101251033
- Kelas: A

## Daftar Fitur yang Dibuat
- Pembuatan struktur database dan tabel Buku & Kategori.
- Implementasi REST API menggunakan PHP 8 dengan PSR-4, OOP, MVC, dan pola SOLID (Repository Pattern & Dependency Injection).
- Pengelolaan environment variables (`.env`) dan koneksi PDO MySQL.
- Error handling & validasi API.
- Skrip pengujian otomatis menggunakan cURL dan Bash.
- Aplikasi Frontend SPA terpisah menggunakan Vanilla JavaScript, Tailwind CSS, dan Fetch API.
- Fitur CORS di backend untuk integrasi lintas origin (Port 8003 ke Port 3008).

## Cara Menjalankan Proyek
1. Setup Database:
- Import file `rest-api-perpustakaan/database/schema.sql` ke MySQL kamu.
- Sesuaikan username dan password database di file `rest-api-perpustakaan/.env`.

2. Menjalankan Backend:
Buka terminal, masuk ke folder backend, dan jalankan server PHP:
```bash
cd rest-api-perpustakaan
php -S localhost:8003 -t public