# INSTALASI Git Bash
Silahkan kalian tuliskan langkahnya mulai dari download sampai selesai instalasi 

# MASUK KE GITHUB
Silahkan kalian tuliskan langkah mengakses github dan login menggunakan akun github
buat repisotery

# menghubungkan Project Git bash ke github
## Persiapan
1. Pastikan Anda telah memiliki akun GitHub. Jika belum, buatlah akun baru di [github.com](https://github.com/).
2. Instal Git di komputer Anda jika belum terpasang.
### Git version
perintah  dalam Git version:
   Perintah git --version digunakan untuk menampilkan versi Git yang terinstall pada komputer Anda.
    *Fungsi*: Perintah ini berguna untuk memeriksa versi Git yang Anda gunakan, yang dapat bermanfaat dalam mengidentifikasi dan mengatasi masalah kompatibilitas.
```cs
git --version
```
<<<<<<< HEAD



=======
![](ASSETS/git_version.jpg)
>>>>>>> a73ca95c002e938034e1c529748b12d0adc3c668
## Langkah-langkah

1. **Buat Repositori GitHub Baru**:
   - Login ke akun GitHub Anda.
   - Klik tombol "New" untuk membuat repositori baru.
<<<<<<< HEAD

=======
![](ASSETS/CREATE.PNG)
>>>>>>> a73ca95c002e938034e1c529748b12d0adc3c668
   - Berikan nama repositori, pilih apakah akan bersifat publik atau privat, lalu klik "Create repository".!

2. **Konfigurasi Git Lokal**:
   - Buka git di laptop/komputer anda.
   - Jalankan perintah berikut untuk mengatur identitas Anda:
    ```cs
     git config --global user.name "Nama Anda"
     git config --global user.email "email@example.com"
     ```
    **Note:** untuk melihat apakah sudah terhubung konfigurasi git nya silakan ketik 
         `git config --list`
 **contohnya:** 
 
	 
3. **Inisialisasi Git Lokal**:
   -  Buat direktori baru untuk proyek Anda dan navigasikan ke direktori tersebut menggunakan Git bash. Kemudian, inisialisasi Git di direktori tersebut dengan menjalankan perintah:
     ```cs
     git init
     ```
     **contohnya:**
      
4. **Hubungkan ke Repositori GitHub**:
   - Jalankan perintah berikut untuk menghubungkan repositori lokal Anda ke repositori GitHub yang telah Anda buat sebelumnya:
     ```cs
     git remote add origin https://github.com/username/nama-repository.git
     ```
   Ganti `username` dan `nama-repository` dengan nama pengguna GitHub Anda dan nama repositori yang Anda buat.kalo dah ada tulisan (master),berarti sudah terhubung ke repositori Githubnya
   **contohnya:**
   
     
5. **Tambahkan file ke repositori**: 
   - Perintah ini akan menambahkan semua file di direktori saat ini ke repositori.
   - Tambahkan file yang ingin Anda simpan di repositori Git dengan menjalankan perintah:
     ```cs
     git add .
     ```
   **contohnya:**!

6. **Buat Commit:**
   - Jalankan perintah berikut untuk membuat commit dengan pesan yang jelas:
   - Perintah git commit -m ***"Pesan commit"*** digunakan untuk menyimpan perubahan yang telah dilakukan pada repositori Git dengan menambahkan pesan
     ```cs
     git commit -m "Pesan commit"
     ```
     **contohnya:** 
     
   Unggah ke GitHub   (git push origin master):
   Terakhir, jalankan perintah berikut untuk mengunggah kode Anda ke GitHub:

7. **Unggah ke GitHub**:
   - Terakhir, jalankan perintah berikut untuk mengunggah kode Anda ke GitHub:
     ```cs
     git push origin master
     ```
     **contohnya:**
     
     maka akan tetampil bgini,berarti anda disuruh untuk login akun github mu yang sudah kamu buat 
      
   Perintah ini akan mengunggah kode Anda ke repositori GitHub. Setelah ini, setiap kali Anda membuat perubahan pada kode, Anda dapat mengulangi langkah 4, 5,6 dan 7 untuk mengunggah perubahan tersebut ke GitHub.
   
***Itulah langkah-langkah dasar untuk mengirim kode dari Git ke GitHub menggunakan aplikasi Obsidian. Jika Anda membutuhkan bantuan lebih lanjut, jangan ragu untuk bertanya.***

# Akses Folder Proyek di Git Bash
## cd 
- Fungsi: Digunakan untuk berpindah ke direktori (folder) lain dalam sistem file.
- Contoh penggunaan:
```shell
cd 'nama document'
```
  - `cd Documents` - Berpindah ke direktori "Documents".
  - `cd ..` - Berpindah ke direktori induk (satu level di atas).
  **tampilannya:**


## ls 
- Fungsi: Digunakan untuk melihat daftar file dan direktori yang ada di dalam direktori saat ini.
- Contoh penggunaan:
```shell
ls
```
  - `ls` - Menampilkan daftar fle di dalam direktori saat ini


## pwd
- Fungsi: Digunakan untuk melihat path (jalur) direktori kerja saat ini.
- Contoh penggunaan:
```cs
pwd
```
`pwd` - Menampilkan path direktori kerja saat ini.

# Hubungkan Folder proyek Lokal Ke Github
1. inisialisasi repository `git init`
2. Hubungkan ke repository github `git remote`
3. Tampilkan status commit / koneksi file ke github `git status`
4. Tambahkan semua file baru atau perubahan menggunakan `git add`
5. tampilkan status commit / koneksi file ke github `git status`
<<<<<<< HEAD
6. . Tambahkan pesan commit menggunakan git commit -m 
7. Unggah seluruh perubahan menggunakan git push origin 8. Login ke akun github atau gunakan token
=======
>>>>>>> a73ca95c002e938034e1c529748b12d0adc3c668
