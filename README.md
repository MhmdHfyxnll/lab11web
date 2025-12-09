# Nama : Muhammad Hafiyainul Yakin Wahid
# NIM  : 312410164


# Praktikum 11 - PHP OOP Modular

Project ini adalah aplikasi sederhana untuk mengelola artikel menggunakan konsep **OOP** dan **modular PHP**. Semua halaman dipisah menjadi module, template, dan class agar lebih rapi.

---

## 📁 Struktur Folder
- `class/` → Database & Form  
- `template/` → header, sidebar, footer  
- `module/artikel/` → index, tambah, ubah  
- `asssets/style.css` → style  
- `index.php` → router utama  

---

## ⚙️ Database

```sql
CREATE DATABASE latihan_oop;

CREATE TABLE artikel (
    id INT AUTO_INCREMENT PRIMARY KEY,
    judul VARCHAR(255),
    isi TEXT
);
Set di config.php:

php
Salin kode
$config = [
  "host"=>"localhost", 
  "username"=>"root", 
  "password"=>"", 
  "db_name"=>"latihan_oop"
];
```
<img width="1357" height="644" alt="Screenshot from 2025-12-09 19-27-34" src="https://github.com/user-attachments/assets/4fd4f5c9-3cce-4348-9fb4-70bbf927baef" />

