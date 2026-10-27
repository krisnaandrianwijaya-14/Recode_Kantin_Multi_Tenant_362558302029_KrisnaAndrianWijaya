<div align="center">
  <h1>Sistem Kantin Multi-Tenant</h1>
  <p>Aplikasi berbasis web untuk mendukung pengelolaan beberapa kantin dalam satu platform secara terpusat.</p>

  <!-- Badges -->
  <img src="https://img.shields.io/badge/Laravel-13.x-FF2D20?style=for-the-badge&logo=laravel" alt="Laravel 13">
  <img src="https://img.shields.io/badge/Livewire-4.x-4E56A6?style=for-the-badge&logo=livewire" alt="Livewire 4">
  <img src="https://img.shields.io/badge/PHP-8.3+-777BB4?style=for-the-badge&logo=php" alt="PHP 8.3+">
  <img src="https://img.shields.io/badge/MariaDB-10.6+-003545?style=for-the-badge&logo=mariadb" alt="MariaDB">
  <img src="https://img.shields.io/badge/Redis-7.x-DC382D?style=for-the-badge&logo=redis" alt="Redis">

  <br>
  <br>

  <!-- Status -->

<b>Status Proyek:</b> 🚧 Dalam Pengerjaan & Pengembangan <br>
<b>Modul 1 Selesai:</b> 📅 28 Oktober 2026
</div>

<hr>

## 📖 Tentang Proyek

Proyek ini dikembangkan sebagai bagian dari praktikum 14 minggu menggunakan pendekatan **Modular Monolith**. Fokus utamanya adalah membangun sistem yang aman, terisolasi antar tenant, dan siap untuk operasional real-time.

---

## ✅ Inti Pengerjaan Modul 1 (Fondasi Teknis)

Pada pertemuan pertama ini, fondasi utama aplikasi berhasil dibangun dan diverifikasi:

1. **Audit Toolchain:** Memastikan PHP 8.3+, Composer, Node.js, MariaDB, dan Redis berjalan di lingkungan lokal.
2. **Instalasi Laravel 13 + Livewire 4:** Menggunakan starter kit resmi untuk fondasi autentikasi dan UI.
3. **Konfigurasi Environment:** Pemisahan database development (`kantin`) dan testing (`kantin_test`), konfigurasi Redis untuk _session/cache/queue_, serta pengaturan timezone (UTC) dan locale (ID).
4. **Pemasangan Reverb:** Menyiapkan fondasi WebSocket untuk fitur _real-time_ di masa mendatang.
5. **Quality Gate:**
    - `php artisan test` → **34 Passed** (83 assertions)
    - `vendor/bin/pint --test` → **PASS** (48 files)
    - `npm run build` → **Build Success**

---

## 📸 Dokumentasi & Evidence

Seluruh bukti teknis (hasil terminal, kualitas kode, dan antarmuka) didokumentasikan dengan rapi di dalam folder **[`docs/evidence/`](docs/evidence/)**.

### Preview Modul 1:

|                  Database & Redis Terhubung                  |               Quality Gate (Test Passed)               |
| :----------------------------------------------------------: | :----------------------------------------------------: |
| ![Database](docs/evidence/pertemuan-01/02_db_redis_ping.png) | ![Test](docs/evidence/pertemuan-01/06_test_passed.png) |

|                 Tampilan Aplikasi                 |                   Dokumentasi README                    |
| :-----------------------------------------------: | :-----------------------------------------------------: |
| ![UI](docs/evidence/pertemuan-01/10_login_ui.png) | ![Readme](docs/evidence/pertemuan-01/11_readme_doc.png) |

---

## 🚀 Panduan Instalasi (Development)

1. Clone repositori ini:
    ```bash
    git clone https://github.com/krisnaandrianwijaya-14/Recode_Kantin_Multi_Tenant_362558302029_KrisnaAndrianWijaya.git
    ```
