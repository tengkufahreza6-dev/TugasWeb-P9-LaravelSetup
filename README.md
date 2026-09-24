# 🚀 Tugas Rutin 9 — Setup & Fundamental Framework Laravel

Repositori ini memuat implementasi dasar, konfigurasi lingkungan lokal, arsitektur MVC, serta sistem routing dinamis pada **Framework Laravel** sebagai pemenuhan tugas mata kuliah Pemrograman Web (Tugas Rutin 9).

---

## 🔗 Tautan Repositori

- **GitHub Repository:** [TugasWeb-P9-LaravelSetup](https://github.com/tengkufahreza6-dev/TugasWeb-P9-LaravelSetup)

---

## 📌 Ringkasan Proyek
Aplikasi ini dirancang menggunakan arsitektur **Model-View-Controller (MVC)** dengan antarmuka berbasis *Console/Dashboard Operations* yang memanfaatkan styling Tailwind CSS. Proyek ini membuktikan keberhasilan pengintegrasian infrastruktur backend lokal (PHP 8.3 & MySQL via Laragon) hingga perenderan komponen tampilan Blade secara dinamis[cite: 2, 4].

---

## Checklist Persyaratan Tugas (Requirements)

| No | Kriteria Tugas | Status | Keterangan / Implementasi |
|---|---|---|---|
| 1 | **Instalasi Laravel** | ✅ Done | Diinstal via Composer `composer create-project` |
| 2 | **Konfigurasi Database** | ✅ Done | Terhubung ke MySQL `tugasweb_p9` melalui file `.env` |
| 3 | **Eksekusi Server** | ✅ Done | Berjalan stabil via `php artisan serve` |
| 4 | **Custom Routing** | ✅ Done | Memiliki route `/`, `/about`, `/contact`, dan `/hello/{nama}` |
| 5 | **Data Dinamis View** | ✅ Done | Menerima & merender data array dinamis dari Controller |
| 6 | **Generator MVC** | ✅ Done | Tergenerasi `MainController` dan Model `Barang` beserta migration |
| 7 | **Dokumentasi README** | ✅ Done | Penjelasan struktur folder & langkah eksekusi lengkap |
| 8 | **Repositori GitHub** | ✅ Done | Disinkronkan ke repo `TugasWeb-P9-LaravelSetup` |
| 9 | **Fitur Bonus** | ✅ Done | Styling UI Tailwind CSS CDN & Route Parameter Dinamis |

---

---

## 📷 Tangkapan Layar Antarmuka

| Welcome Page Laravel | Halaman Dashboard (Route `/`) |
| :---: | :---: |
| ![Welcome](ss-welcome.png) | ![Home](ss-home.png) |

| Halaman About (Route `/about`) | Halaman Contact (Route `/contact`) |
| :---: | :---: |
| ![About](ss-about.png) | ![Contact](ss-contact.png) |

| Route Parameter Dinamis (`/hello/{nama}`) |
| :---: |
| ![Hello](ss-hello.png) |

---
## 📂 Struktur Utama Folder Proyek

```text
TugasWeb-P9-LaravelSetup/
├── app/
│   ├── Http/
│   │   └── Controllers/
│   │       └── MainController.php  <-- Penanganan logika bisnis & penyedia data array
│   └── Models/
│       └── Barang.php              <-- Model ORM dasar (Eloquent)
├── database/
│   └── migrations/                 <-- Skema struktur tabel MySQL
├── resources/
│   └── views/                      <-- Blade Templating Engine (UI Layouts)
│       ├── home.blade.php          <-- Tampilan utama dashboard
│       ├── about.blade.php         <-- Tampilan informasi arsitektur
│       └── contact.blade.php       <-- Tampilan kontak operasional
├── routes/
│   └── web.php                     <-- Deklarasi titik akses URL (Routing)
├── .env                            <-- Konfigurasi kredensial environment & database
└── README.md                       <-- Dokumentasi teknis proyek
```
---

## 👤 Identitas Mahasiswa

| Keterangan | Detail |
| :--- | :--- |
| **Nama** | Tengku Fahreza |
| **NIM** | 4252550005 |
| **Kelas** | PSIK 25B |
| **Program Studi** | S1 Ilmu Komputer |
| **Mata Kuliah** | Pemrograman Web |
| **Instansi** | Universitas Negeri Medan (UNIMED) |