# Latihan1
# Tutorial Penggunaan Git

**Apa itu Git?**

Git adalah salah satu sistem pengontrol versi (Version Control System) pada proyek perangkat lunak yang diciptakan oleh Linus Torvalds. Pengontrol versi bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri. Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.

# Menambahkan Global Config
Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user name dan user email konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository. apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan saat menjalankan perintah git commit Lakukan "git config --global user.name dan emal " supaya bisa login github ketika push.

# Perintah Dasar Git
- git init: perintah untuk membuat repository local
- git add: perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.
- git commit: perintah untuk menyimpan perubahan kedalam database git.
- git push -u origin master: perintah untuk mengirim perubahan pada repository local menuju server repository.
- git clone [url]: perintah untuk membuat working directory yang diambil dari repositry sever.
- git remote add origin [url]: perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)

# Membuat Repository Local
- Open gitbash, ketik cd /D
- Buat direktory project praktikum pertama dengan nama Latihan Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah cd (change directory)
- Direktory aktif menjadi: D/latihan1, kemudian masuk ke direktory tersebut 
- Ketik "echo" untuk membuat file README.md
- Lalu Lakukan "git init" untuk menjadikan repository lokal 
- kemudian tambahkan file tersebut ke repository dengan " git add README.md " 
- file yang berhasil ditambahkan akan terlihat seperti di gambar, dengan "ls -l" 
- Untuk Menyimpan perubahan sebuah file ke repository local gunakan perintah git commit -m "Nama perintahnya" 

# Membuat Repository Server
- Server reopsitory yang akan kita gunakan adalah http://github.com
- Anda harus mempunyai akun terlebih dahulu.
- Pada laman github, dari menu (icon +) klik New Repository
- Isi nama repositorynya, misal: latihan1, lalu klik tombol Create repository

# Menambahkan Remote Repository
- Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user.
- Untuk menambahkan remote repository server, gunakan perintah git remote add origin [url] 

# Push (Mengirim perubahan ke server)
- Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
- Gunakan printah git push -u origin master 
- Perintah ini akan meminta memasukkan username dan password pada akun github.com 
- Proses push berhasil, maka akan muncul gambar seperti ini 

# Melihat Hasil nya pada Repository
- Buka laman github.com, lalu refresh page.
- Maka perubahan akan terlihat pada laman tersebut.

