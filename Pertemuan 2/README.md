# Praktikum PHP Dasar Menggunakan Laragon - Form Pendaftaran Event 

## Identitas  
- **Nama** : Adjie Firmansyah  
- **NPM**  : 4523210004  
- **Kelas** : P.PBW A  

---

## Tujuan  
1. Mengetahui cara instalasi **Laragon** sebagai local development environment.  
2. Mampu menjalankan web server lokal menggunakan Laragon.  
3. Menggunakan Laragon untuk pengembangan aplikasi berbasis web (PHP, MySQL, dsb).  

---

## Dasar Teori  
Laragon adalah **portable, isolated, fast & powerful universal development environment** untuk PHP, Node.js, Python, Java, Go, Ruby, dll.  

### Kelebihan Laragon:  
- Ringan & cepat.  
- Mendukung banyak bahasa pemrograman.  
- Portable (bisa dipindah folder tanpa error).  
- Auto Virtual Host (akses project langsung via `http://project.test`).  
- Sudah include database (MySQL/MariaDB) & web server (Apache/Nginx).  

---

## Langkah Instalasi  

1. **Download Laragon**  
   - Buka [https://laragon.org/download/](https://laragon.org/download/)  
   - Pilih versi **Laragon Full** (misalnya PHP + MySQL).  

2. **Install Laragon**  
   - Jalankan installer → ikuti langkah default → pilih lokasi instalasi (contoh: `C:\laragon`).  
   - Setelah selesai, buka aplikasi Laragon.  

3. **Menjalankan Laragon**  
   - Klik tombol **Start All** untuk menjalankan Apache/Nginx & MySQL.  
   - Coba akses `http://localhost/` atau `http://project.test`.  

4. **Membuat Project Baru**  
   - Buka folder `C:\laragon\www\`  
   - Tambahkan folder project, misalnya `prak_pbw`.  
   - Isi dengan file `index.php`.  
   - Akses di browser: `[http://localhost/praktikum1/)`.  

---

## ✨ Fitur Utama
- Form pendaftaran dengan field:
  - Nama Lengkap
  - Email
  - Tanggal Lahir (DD-MM-YYYY)
- Validasi input menggunakan **Regular Expression (Regex)**:
  - Email harus sesuai format `user@domain.com`
  - Tanggal lahir harus sesuai format `DD-MM-YYYY`
- Data peserta tersimpan otomatis ke file `pendaftar.txt`
- Menampilkan daftar peserta yang sudah mendaftar dalam bentuk tabel
- Pesan **error** (validasi gagal) dan **success** (pendaftaran berhasil)

---



   
