# Praktikum PHP Dasar Menggunakan Laragon - Form Pendaftaran Event 

## Identitas  
- **Nama** : Adjie Firmansyah  
- **NPM**  : 4523210004  
- **Kelas** : P.PBW A  

---

## ✨ Tujuan  
1. Mengetahui cara instalasi **Laragon** sebagai local development environment.  
2. Mampu menjalankan web server lokal menggunakan Laragon.  
3. Menggunakan Laragon untuk pengembangan aplikasi berbasis web (PHP, MySQL, dsb).  

---

## ✨ Dasar Teori  
Laragon adalah **portable, isolated, fast & powerful universal development environment** untuk PHP, Node.js, Python, Java, Go, Ruby, dll.  

### Kelebihan Laragon:  
- Ringan & cepat.  
- Mendukung banyak bahasa pemrograman.  
- Portable (bisa dipindah folder tanpa error).  
- Auto Virtual Host (akses project langsung via `http://project.test`).  
- Sudah include database (MySQL/MariaDB) & web server (Apache/Nginx).  

---

## ✨ Langkah Instalasi  

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

## ✨ Tampilan Aplikasi
   **Tampilan Awal Form**
      ![Gambar WhatsApp 2025-09-28 pukul 13 46 19_444387bf](https://github.com/user-attachments/assets/f78e59a6-7efd-48f6-aa0f-f86cfafdf5b1)


   **Tampilan Setelah Pendaftaran Berhasil**
      ![Gambar WhatsApp 2025-09-28 pukul 13 47 38_43c97e36](https://github.com/user-attachments/assets/adf5a718-cd25-4687-b8d8-2942f27d10c1)


   **Contoh Pesan Error Validasi**
      ![Gambar WhatsApp 2025-09-28 pukul 13 48 44_e9dd9771](https://github.com/user-attachments/assets/5634e891-634a-4b40-9ddf-56ba032c87af)


   
