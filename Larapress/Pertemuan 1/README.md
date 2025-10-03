# Laporan Praktikum PBW  
## Pertemuan 1 – Git Dasar  

### Identitas  
- **Nama** : Adjie Firmansyah  
- **NPM**  : 4523210004  
- **Kelas** : P.PBW A

---

### Tujuan Praktikum  
1. Memahami konsep dasar Git.  
2. Mengenal perintah dasar Git untuk mengelola repository.  
3. Menerapkan Git dalam membuat dan mengelola project sederhana.  

---

### Dasar Teori  
Git adalah **sistem kontrol versi terdistribusi** yang digunakan untuk mencatat setiap perubahan pada file atau project.  

Beberapa konsep utama:  
- **Repository (Repo)** : Tempat penyimpanan project beserta riwayat perubahannya.  
- **Commit** : Catatan perubahan yang disimpan ke dalam repository.  
- **Branch** : Cabang pengembangan yang memungkinkan pengerjaan paralel.  
- **Remote** : Repository yang disimpan di server (contoh: GitHub).  

---

### Langkah Praktikum  

1. **Membuat Repository Baru**  
   ```bash
<<<<<<< HEAD
   git init
   git remote add origin https://github.com/Fana-Dzi/Prak_PBW.git
   
=======
   git init (Membuat repository Git baru di lokal)
   git remote add origin https://github.com/Fana-Dzi/Prak_PBW.git (Menghubungkan repository lokal dengan repository remote di GitHub)
   git add . (Menambahkan semua file di folder project ke staging area)
   git commit (Menyimpan perubahan dari staging area ke repository lokal)
   git branch -m master main (Mengganti nama branch default dari master → main)
   git push (Mengirim commit dari repository lokal ke repository remote (GitHub)

2. **Code**
    <img width="686" height="124" alt="Image" src="https://github.com/user-attachments/assets/0ed4b76e-d95e-4454-9614-f9191fda2142" />
    <img width="582" height="161" alt="Image" src="https://github.com/user-attachments/assets/5e54fdc5-5a19-4905-ab53-5f9b2fe69069" />
    <img width="567" height="265" alt="Image" src="https://github.com/user-attachments/assets/8f560e1c-1e95-48c1-b35c-93905540f94c" />
>>>>>>> ae89cd1220224e92657f83ceaf425e54de96509b
