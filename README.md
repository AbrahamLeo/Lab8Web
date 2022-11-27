# Lab8Web

## Langkah-langkah Praktikum

### Persiapan
Untuk memulai membuat aplikasi CRUD sederhana, yang perlu disiapkan adalah database server menggunakan MySQL. Pastikan MySQL Server sudah dapat dijalankan melalui XAMPP.

### Menjalankan MySQLServer
Untuk menjalankan MySQL Server dari menu XAMPP Contol.
![Tab](ss/1.png)

### Mengakses MySQL Client menggunakan PHP MyAdmin
Pastikan webserver Apache dan MySQL server sudah dijalankan. Kemudian buka melalui browser: http://localhost/phpmyadmin/

### Membuat Database
![Tab](ss/2.png)

### Membuat Tabel
![Tab](ss/3.png)

### Menambahkan Data
![Tab](ss/4.png)
Hasilnya
![Tab](ss/5.png)

### Membuat Program CRUD
Buat folder lab8_php_database pada root directory web server (d:\xampp\htdocs)
![Tab](ss/6.png)
Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL: http://localhost/lab8_php_database/
![Tab](ss/7.png)

### Membuat file koneksi database
Buat file baru dengan nama koneksi.php
![Syntax](ss/8.png)
Buka melalui browser untuk menguji koneksi database (untuk menyampilkan pesan koneksi berhasil, uncomment pada perintah echo “koneksi berhasil”;
![Hasil](ss/9.png)

### Membuat file index untuk menampilkan data (Read)
Buat file baru dengan nama index.php
![Syntax](ss/10.png)
Refresh dan hasilnya akan seperti ini
![Hasil](ss/11.png)

### Menambah Data (Create)
Buat file baru dengan nama tambah.php
![Syntax](ss/12.png)
Klik Tambah Barang lalu diinput
![Proses](ss/13.png)
Maka hasilnya akan seperti ini
![Hasil](ss/14.png)

### Mengubah Data (Update)
Buat file baru dengan nama ubah.php
![Syntax](ss/15.png)
Klik Ubah lalu ubah sesuai kebutuhan
![Proses](ss/16.png)
Maka hasilnya akan seperti ini
![Hasil](ss/17.png)

### Menghapus Data (Delete)
Buat file baru dengan nama hapus.php
![Syntax](ss/19.png)
Inilah file sebelumnya
![Proses](ss/17.png)
Klik Hapus data yang paling bawah, maka hasilnya akan seperti ini
![Hasil](ss/18.png)

