# Lab9Web — Praktikum 9: PHP Modular

Repository ini berisi hasil praktikum **Pemrograman Web — Praktikum 9: PHP Modular** yang membahas modularisasi program, pemanggilan file (`include`, `require`, `include_once`, `require_once`), template layout bersama, pembuatan function/helper, routing berbasis parameter URL dengan whitelist, serta integrasi ke aplikasi database/CRUD dari praktikum sebelumnya[cite: 1, 2, 3, 7, 9].

---

## Tujuan Project

* Memahami pengertian, tujuan, dan manfaat modularisasi program PHP[cite: 1].
* Membedakan penggunaan `include`, `require`, `include_once`, dan `require_once` serta penggunaan konstanta `__DIR__`[cite: 1, 2].
* Menerapkan template layout bersama (`header` dan `footer`) agar tidak terjadi duplikasi kode antarmuka[cite: 1, 3].
* Membuat dan menggunakan function (termasuk helper seperti formatting, validasi, escaping, atau perhitungan) dengan parameter dan nilai kembalian (`return`)[cite: 1, 6, 10].
* Menyusun struktur direktori aplikasi PHP secara modular sesuai tanggung jawab masing-masing folder[cite: 1, 7].
* Menerapkan routing sederhana melalui `index.php` menggunakan parameter URL (`?page=...`) dengan validasi whitelist dan halaman `404`[cite: 1, 7, 8].
* Mengintegrasikan modularisasi dan routing ke aplikasi database/CRUD dari praktikum sebelumnya.

---

## Kebutuhan Perangkat

* **Web Server Lokal:** Apache (melalui XAMPP, Laragon, atau stack serupa)[cite: 1, 9].
* **Bahasa Pemrograman:** PHP (serta ekstensi database yang sesuai dengan project CRUD, misalnya PDO / MySQLi)[cite: 1, 9, 10].
* **Database:** MySQL/MariaDB (untuk fitur CRUD pada latihan integrasi)[cite: 1, 9, 10].
* **Browser:** Google Chrome, Mozilla Firefox, Microsoft Edge, atau browser modern lainnya[cite: 1].
* **Code Editor:** Visual Studio Code atau editor kode sejenis[cite: 1].
* **Version Control:** Git & akun repository (`Lab9Web`).

---

## Cara Menjalankan Aplikasi

1. Clone atau salin project ke direktori root web server lokal (misalnya `htdocs` pada XAMPP atau `www` pada Laragon)[cite: 1, 2, 11]:
   ```bash
   git clone <URL_REPOSITORY_LAB9WEB>
