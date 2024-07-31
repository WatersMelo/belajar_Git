# menghubungkan Git ke github dan menambahkan file ke github
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
![[Screenshot 2024-07-31 073417.jpg]]
## Langkah-langkah

1. **Buat Repositori GitHub Baru**:
   - Login ke akun GitHub Anda.
   - Klik tombol "New" untuk membuat repositori baru.
   ![[Pasted image 20240725004628.png]]
   - Berikan nama repositori, pilih apakah akan bersifat publik atau privat, lalu klik "Create repository".![[Pasted image 20240725004734.png]]

2. **Konfigurasi Git Lokal**:
   - Buka git di laptop/komputer anda.
   - Jalankan perintah berikut untuk mengatur identitas Anda:
    ```cs
     git config --global user.name "Nama Anda"
     git config --global user.email "email@example.com"
     ```
    **Note:** untuk melihat apakah sudah terhubung konfigurasi git nya silakan ketik 
         `git config --list`
 **contohnya:** ![[GIT CONFIG LIST.jpg]]
     
3. **Inisialisasi Git Lokal**:
   -  Buat direktori baru untuk proyek Anda dan navigasikan ke direktori tersebut menggunakan Git bash. Kemudian, inisialisasi Git di direktori tersebut dengan menjalankan perintah:
     ```cs
     git init
     ```
     **contohnya:**
      ![[git_init.jpg]]
     
4. **Hubungkan ke Repositori GitHub**:
   - Jalankan perintah berikut untuk menghubungkan repositori lokal Anda ke repositori GitHub yang telah Anda buat sebelumnya:
     ```cs
     git remote add origin https://github.com/username/nama-repository.git
     ```
   Ganti `username` dan `nama-repository` dengan nama pengguna GitHub Anda dan nama repositori yang Anda buat.kalo dah ada tulisan (master),berarti sudah terhubung ke repositori Githubnya
   **contohnya:**
     ![[git remote .jpg]]
     
5. **Tambahkan file ke repositori**: 
   - Perintah ini akan menambahkan semua file di direktori saat ini ke repositori.
   - Tambahkan file yang ingin Anda simpan di repositori Git dengan menjalankan perintah:
     ```cs
     git add .
     ```
   **contohnya:**![[git_add.jpg]]

6. **Buat Commit:**
   - Jalankan perintah berikut untuk membuat commit dengan pesan yang jelas:
   - Perintah git commit -m ***"Pesan commit"*** digunakan untuk menyimpan perubahan yang telah dilakukan pada repositori Git dengan menambahkan pesan
     ```cs
     git commit -m "Pesan commit"
     ```
     **contohnya:**
     ![[commit.jpg]]
   Unggah ke GitHub   (git push origin master):
   Terakhir, jalankan perintah berikut untuk mengunggah kode Anda ke GitHub:

7. **Unggah ke GitHub**:
   - Terakhir, jalankan perintah berikut untuk mengunggah kode Anda ke GitHub:
     ```cs
     git push -u origin master
     ```
     **contohnya:**
     ![[git push origin.jpg]]
     maka akan tetampil bgini,berarti anda disuruh untuk login akun github mu yang sudh kamu buat 
     ![[login.jpg]]
   Perintah ini akan mengunggah kode Anda ke repositori GitHub. Setelah ini, setiap kali Anda membuat perubahan pada kode, Anda dapat mengulangi langkah 4, 5,6 dan 7 untuk mengunggah perubahan tersebut ke GitHub.
   
***Itulah langkah-langkah dasar untuk mengirim kode dari Git ke GitHub menggunakan aplikasi Obsidian. Jika Anda membutuhkan bantuan lebih lanjut, jangan ragu untuk bertanya.***
## cd 
- Fungsi: Digunakan untuk berpindah ke direktori (folder) lain dalam sistem file.
- Contoh penggunaan:
```css
cd 'nama document'
```
  - `cd Documents` - Berpindah ke direktori "Documents".
  - `cd ..` - Berpindah ke direktori induk (satu level di atas).
  **tampilannya:**
  ![[cd.jpg]]

## ls 
- Fungsi: Digunakan untuk melihat daftar file dan direktori yang ada di dalam direktori saat ini.
- Contoh penggunaan:
```css
ls
```
  - `ls` - Menampilkan daftar fle di dalam direktori saat ini
  ![[ls.jpg]]

## pwd
- Fungsi: Digunakan untuk melihat path (jalur) direktori kerja saat ini.
- Contoh penggunaan:
```css
pwd
```
`pwd` - Menampilkan path direktori kerja saat ini.
![[pwd.jpg]]


