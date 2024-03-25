# PSI-24-04 Sistem Informasi Stok Obat Dinas Kesehatan Balige SISOB

## General Discription
Sistem Informasi Stok Obat Dinas Kesehatan Balige merupakan sebuah platform yang dirancang untuk membantu Dinas Kesehatan Balige dalam mengelola dan memantau persediaan obat obatan yang tersedia. Dengan adanya website ini, Dinas Kesehatan Balige dapat lebih efisien dalam mengatur distribusi obat. Website ini akan membantu Dinas Kesehatan Balige dalam pelaporan dan analisis data terkait obat dan memungkinkan untuk mengambil keputusan yang lebih baik.

## Features

Fitur fitur yang terdapat pada sistem informasi SISOB yaitu :

- Fitur Dinas Kesehatan
  - Registrasi : Memungkinkan pengguna dari Dinas Kesehatan untuk membuat atau mendaftarkan akun baru.
  - Verifikasi : Memverifikasi akun pengguna sebelum pengguna mengakses fitur fitur lain yang ada pada website.
  - About Us : Berisi informasi mengenai Dinas Kesehatan Balige, Tujuan berdirinya Dinas Kesehatan Balige, Visi dan Misi Dinas Kesehatan Balige.
  - Search Obat : Membantu admin dalam mencari obat tertentu dalam sistem.

 
- Fitur PSDK
  - Verifikasi Obat : Memverifikasi obat obat yang di request oleh puskesmas sebelum ditambahkan dan disetujui.
  - About Us : Berisi informasi mengenai bidang PSDK di Dinas Kesehatan Balige, serta visi dan Misi Dinas Kesehatan Balige.


- Fitur Puskesmas 
    - Input Edit Data Obat : Memungkinkan puskesmas untuk memasukkan data data obat baru yang diperlukan ke dalam sistem, dan jika diperlukan pengeditan juga dapat dilakukan.
    - About Us : Berisi informasi mengenai Puskesmas, Tujuan berdirinya Puskesmas, Visi dan Misi Puskesmas tersebut.
    - Pencarian Obat : Puskesmas dapat mencari nama obat obat menggunakan fitur ini yang dapat kita lihat dalam sistem.
    - Pengiriman Data Obat : Membantu puskesmas untuk mengirimkan data obat ke PSDK untuk diverifikasi dan disetujui.

## Architectural Design

Desain arsitektur yang terdapat pada sistem ini menggunakan model berbasis website dengan komponen yaitu :

- Frontend : Antarmuka pengguna yang dapat dilihat dan diakses melalui website, yang memungkinkan pengguna untuk berinteraksi dengan sistem.

- Backend : Salah satu bagian yang terdapat pada sistem yang berfungsi untuk menangani permintaan oengguna, manajemen stok obat, dan hal lainnya.

- Database : Tempat untuk menyimpan data data stok obat, informasi pengguna, laporan pengguna, dan hal lainnya.

## Database Design

Basisdata pada sistem ini terdiri dari beberapa tabel seperti :

- Tabel Obat : Berisi mengenai informasi obat obat yang tersedia.
- Tabel User : Berisi mengenai informasi pengguna sistem

## Installation Guide

Langkah langkah instalasi yang dapat dilakukan untuk menjalankan Sistem Informasi Stok Obat Dinas Kesehatan Balige (SISOB) di perangkat anda yaitu

- Pastikan perangkat terhubung ke internet.
- Lakukan clone repositori SISOB dari github dan hubungkan ke direktori htdocs.
- Sediakan database kosong pada phpMyAdmin.
- Ubah file '.env'.
- Buka terminal pada direktori SISOB
- Instal semua dependensi laravel menggunakan perintah **composer install**
- Untuk menghasilkan kunci aplikasi laravel gunakan perintah **php artisan key:generate**
- Jalankan perintah migrasi untuk membuat skema basis data menggunakan perintah **php artisan migrate**
- Jika diperlukan, jalankan perintah **php artisan db:seed** untuk memasukkan data awal.
- Untuk menjalankan server gunakan perintah **php artisan serve**
- Buka pada web browser http://localhost:8000 atau alamat yang dihasilkan oleh printah diatas


### Minimum Hardware Requirements

Pesyaratan perangkat keras yang dibutuhkan dalam membangun sistem ini yaitu : 

- Prosesor : Intel Core i5-10300H
- Sistem Operasi : Windows 10 Home/Windows 11 Home
- Memori : 8 GB DDR4, 2933Hz
- Penyimpanan : 512 GB SSD M.2 PCIe NVMe

### Minimum Software Requirements

Perasyaratan perangkat lunak yang dibutuhkan dalam membangun sistem ini yaitu :

- Web Server : Apache
- Text Editor : Visual Studio Code
- Microsoft Office : Microsoft Word 2010
- Database : MariaDB, PhpMyAdmin
- Image Editor : Figma, Canva
- Diagram Editor : Bizagi Modeler, Star UML
- Framework : Laravel
- Testing Application : Postman


# Contributors
+ 12S21009 - Mikhael Janugrah Pakpahan (@GMikhaelJP)
+ 12S21011 - Aldi Jeremy Simamora (@aldijeremysimamora)
+ 12S21012 - Walker Valentinus Simanjuntak (@walkervalentinuss)
+ 12S21047 - Elshaday Prida Simamora (@elshadaysimamora)
+ 12S21056 - Endang Siregar (@endangsiregar)
