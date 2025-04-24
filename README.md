# Github

upload di github.

## Instruksi Pengaturan Git

1. **Inisialisasi Repositori Git**
   - Jika kamu belum menginisialisasi repositori Git di proyek ini, jalankan perintah berikut untuk memulai repositori Git di direktori proyek kamu:

     ```bash
     git init
     ```

     Perintah ini akan membuat direktori `.git` di proyek kamu dan mengonfigurasi repositori Git lokal.

2. **Menambahkan Remote Repository**
   - Setelah repositori Git berhasil diinisialisasi, kamu dapat menambahkan remote repository untuk menghubungkan repositori lokal dengan GitHub. Gunakan salah satu perintah berikut untuk menambahkan remote dengan URL HTTPS atau SSH.
   
   - **Untuk HTTPS**:

     ```bash
     git remote add origin https://github.com/1/2.git
     ```

   - **Untuk SSH** (lebih disarankan jika kamu telah mengatur SSH Key):

     ```bash
     git remote add origin git@github.com:1/2.git
     ```

     Gantilah `1 = gitkamu` dengan nama pengguna GitHub dan `2 = repositori` dengan nama repositori yang sesuai.

3. **Mengatur URL Remote untuk Repositori (Jika diperlukan)**
   - Jika kamu sudah menambahkan remote sebelumnya menggunakan HTTPS dan ingin beralih ke SSH, kamu dapat mengubah URL remote dengan:

     ```bash
     git remote set-url origin git@github.com:1/2.git
     ```
3. **Mengatur URL Remote untuk Repositori (Jika diperlukan)**
   - Jika kamu sudah menambahkan remote sebelumnya menggunakan SSH dan ingin beralih ke HTTPS, kamu dapat mengubah URL remote dengan:

     ```bash
     git remote set-url origin https://github.com/USERNAME/NAMA-REPO.git
     ```
     

4. **Menambahkan File dan Melakukan Commit**
   - Untuk menambahkan semua file yang telah diubah ke staging area, jalankan:

     ```bash
     git add .
     ```

   - Kemudian, buat commit dengan pesan yang menggambarkan perubahan yang telah dilakukan:

     ```bash
     git commit -m "Pesan commit kamu"
     ```

5. **Menetapkan Branch ke `main` (Jika perlu)**
   - Jika kamu ingin mengganti nama branch utama ke `main`, jalankan perintah ini:

     ```bash
     git branch -M main
     ```

6. **Mengirimkan Perubahan ke GitHub (Push)**
   - Setelah commit selesai, gunakan perintah berikut untuk mengirim perubahan ke GitHub:

     ```bash
     git push -u origin main
     ```

     Perintah ini akan mengirim commit kamu ke branch `main` di remote GitHub.

7. **Menarik Perubahan dari Remote Repository dengan Rebase**
   - Sebelum melakukan `push`, kamu mungkin ingin menarik (pull) perubahan dari remote branch `main` dan menggabungkannya dengan rebase, sehingga riwayat commit kamu tetap rapi (terhindar dari merge commit yang tidak perlu).

     Untuk melakukan pull dengan rebase, jalankan perintah berikut:

     ```bash
     git pull origin main --rebase
     ```

     **Penjelasan**:
     - **`git pull`**: Menarik perubahan terbaru dari remote repository.
     - **`origin`**: Nama remote repository yang mengarah ke GitHub.
     - **`main`**: Nama branch yang ingin kamu tarik perubahannya.
     - **`--rebase`**: Menggabungkan perubahan dari remote dengan cara rebase, menjaga riwayat commit agar lebih bersih.

## Lisensi

gak ada..

## Kontak

Nama: Muhammad Misbakhul Munir 
Email: [belom..]  
GitHub: [https://github.com/pepeng28](https://github.com/pepeng28)
