# Pratikum 8 Pemgrograman web

Nama    : Aka erlanda

Nim     : 312010207

Kelas   : TI.20.B.1

# Lab8Web

<b>Persiapan</b>

Untuk memulai membuat aplikasi CRUD sederhana, yang perlu disiapkan adalah database server menggunakan MySQL. Pastikan MySQL Server sudah dapat dijalankan melalui XAMPP.

1. Menjalankan MySQL Server

![img](gambar/png.1.PNG)

2. Mengakses MySQL Client menggunakan PHP MyAdmin

Pastikan webserver Apache dan MySQL server sudah dijalankan. Kemudian buka melalui browser: http://localhost/phpmyadmin/

3. Membuat Database: Studi Kasus Data Barang

- <b>Membuat Database</b>

CREATE DATABASE latihan1;

 <b>Membuat Tabel :</b>

 ![img](gambar/png.2.PNG)

 Berikut contoh tabelnya :

 ![img](gambar/png.3.png)

 <b>Menambahkan Data</b>

 ![img](gambar/png.4.PNG)

 Hasilnya akan seperti berikut :

 ![img](gambar/png.5.png)

 4. Membuat Program CRUD

Buat folder<b> "lab8_php_database" </b>pada root directory web server (d:\xampp\htdocs)

![img](gambar/png.6.PNG)

Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL: http://localhost/lab8_php_database/

![img](gambar/png.7.PNG)

5. Membuat file koneksi database
Buat file baru dengan nama koneksi.php

![img](gambar/png.8.PNG)

Buka melalui chrome untuk menguji koneksi database (untuk menyampilkan pesan koneksi berhasil, uncomment pada perintah echo “koneksi berhasil” :

![img](gambar/png.9.png)

<b>Membuat file index untuk menampilkan data (Read)</b>

![img](gambar/png.10.PNG)

Disini saya menambahkan css style untuk memperbagus table nya.

berikut output nya :

![img](gambar/png.11.png)

<b>Menambah Data (Create)</b>

Buat file baru dengan nama "tambah.php"

![img](gambar/png.12.PNG)
![img](gambar/png.13.PNG)

di source kode nya saya menambahkan file css untuk memperbagus  halamannya.
Maka hasilnya outputnya seperti berikut :

![img](gambar/png.14.png)
![img](gambar/png.15.PNG)

<b>Mengubah Data</b>

Buat file baru dengan nama "ubah.php"

![img](gambar/png.16.PNG)
![img](gambar/png.17.PNG)
![img](gambar/png.18.PNG)

lalu buka dengan chrome.tapi pas outputnya seperti "ada yang salah" tapi setelah saya periksa kode input nya "tidak ada yang salah"

Berikut output nya : 

![img](gambar/png.19.PNG)

<b>Menghapus Data (Delete)</b>

Buat file baru dengan nama hapus.php

Berikut output nya :

![img](gambar/png.20.PNG)

# Terima kasih 





