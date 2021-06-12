# Lab9Web

# Praktikum 9

# Pemograman WEB

~~~
Nama  : Isnaini Rizkyana
NIM   : 311910254
Kelas : TI.19.C1
~~~
## Langkah-langkah Praktikum
Buat file baru dengan nama header.php
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contoh Modularisasi</title>
    <link href="style.css" rel="stylesheet" type="text/stylesheet" media="screen" />
</head>
<body>
    <div class="container">
        <header>
            <h1>Modularisasi Menggunakan Require</h1>
        </header>
    <nav>
        <a href="home.php">Home</a>
        <a href="about.php">Tentang</a>
        <a href="kontak.php">Kontak</a>
    </nav>
~~~
![header](https://user-images.githubusercontent.com/81541764/121683082-17c56280-cae7-11eb-907d-c05f8a1075a8.JPG)

Buat file baru dengan nama footer.php
~~~
    <footer>
        <p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
    </footer>
</div>
</body>
</html>
~~~
![footer](https://user-images.githubusercontent.com/81541764/121683349-72f75500-cae7-11eb-9635-242912933b67.JPG)

Buat file baru dengan nama home.php
~~~
<?php require('header.php'); ?>
<div class="content">
    <h2>Ini Halaman Home</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>
<?php require('footer.php'); ?>
~~~
![home](https://user-images.githubusercontent.com/81541764/121683684-ee590680-cae7-11eb-834f-98a262197012.JPG)

Buat file baru dengan nama about.php
~~~
<?php require('header.php'); ?>
<div class="content">
    <h2>Ini Halaman About</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>
<?php require('footer.php'); ?>
~~~
![about](https://user-images.githubusercontent.com/81541764/121683943-40019100-cae8-11eb-9dc3-51219d83a7d8.JPG)

## Pertanyaan dan Tugas
Implementasikan konsep modularisasi pada kode program praktikum 8 tentang
database, sehingga setiap halamannya memiliki template tampilan yang sama.

![data_barang](https://user-images.githubusercontent.com/81541764/121767705-2a41a980-cb84-11eb-8c1e-e68143b80730.JPG)



