![](https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/Cover.png)

# BAB I Pendahuluan 

## 1.1 Tujuan

Dokumen Software Requirement Specification (SRS) merupakan dokumen
spesifikasi perangkat lunak untuk membangun "Website Profile Company
UMKM kantin Afwah". Dokumen ini dibangun untuk memudahkan public untuk
mengenal UMKM kantin afwah dan memudahkan pemilik kantin dalam
mempromosikan usahanya ke public. Sehingga dokumen ini dapat dijadikan
acuan teknis untuk membangun perangkat lunak "Website Profile Company
UMKM kantin Afwah".

## 

## 1.2 Lingkup 

Website Profile Company UMKM kantin Afwah Merupakan website Untuk
mempermudah pemilik usaha kantin afwah untuk mempromosikan usahanya
serta memberi informasi ke public tentang usahanya melalui Website
Profile Company UMKM kantin Afwah.

## 1.3 Akronim, singkatan, definisi

| Istilah                            | Definisi                                                                                     |
|------------------------------------|----------------------------------------------------------------------------------------------|
| SRS                                | Software Requirement Specification                                                           |
| Login                              | Digunakan untuk mengakses website halaman admin                                              |
| Software Requirement Specification | perangkat lunak yang akan dibuat dan sebagai penyembatani komunikasi pembuat dengan pengguna |
| Use Case                           | situasi dimana sistem anda digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian anda |

## 1.4 Referensi 

Referensi yang digunakan dalam pengembangan perangkat lunak ini adalah:

[[https://www.mcdonalds.co.id/]{.underline}](https://www.mcdonalds.co.id/)

## 1.5 Overview

Bab selanjutnya yaitu menjelaskan sistem yang di terapkan pada website.
Menjelaskan gambaran umum dari aplikasi, sistem interface aplikasi dan
alur sistemnya. Bab terakhir menjelaskan tentang setiap fungsi yang
digunakan secara teknisnya. Pada bab 2 dan 3 merupakan deskripsi dari
aplikasi yang akan diterapkan pada website yang dibuat.

# BAB II Gambaran Umum

Kantin Afwah merupakan suatu UMKM yang bergerak pada bidang makanan dan
minuman.Dalam project ini,kami merancang website company profile dari
Kantin Afwah yang bertujuan untuk menampilkan informasi - informasi dari
Kantin ini.Selain itu,pada website ini juga menyediakan berbagai fitur
lainya seperti menu,kontak,lokasi,dan juga customer dapat menyampaikan
pesan beserta sarannya.Berikut adalah penjelasan dari fitur - fitur yang
kami sediakan,

Customer fungsi utama yaitu:

1.View Menu

2.Input Pesan Saran

3.View Promo

4.View Gallery

5.View About Us

6.View Kutipan

7.View Slider

Berikut Fungsi admin:

1.Login

2.Input Pesan Saran

3.Input Promo

4.Input Gallery

5.Input About Us

6.Input Kutipan

7.Input Slider

8.Edit Pesan Saran

9.EditPromo

10.EditGallery

11.Edit About Us

12.Edit Kutipan

13.Edit Slider

14.Delete Pesan Saran

15.Delete Promo

16.Delete Gallery

17.Delete Kutipan

18.Delete Slider

## 2.1 Perspektif produk 

Sistem Kantin Afwah adalah sebuah sistem yang menyediakan informasi
Kantin Afwah yang diaplikasikan pada website. Terdapat 2 aktor yaitu
admin dan pengunjung. Data informasi pada website dikelola oleh admin
dan pengunjung hanya dapat melihat informasi tersebut pada websit

###  2.1.1 Antarmuka Sistem

![](https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/antarmukasistem.png)

Sistem Kantin Afwah memiliki 2 pengguna yaitu admin dan pengunjung.
Admin berfungsi mengelola data informasi dan Pengunjung bisa melihat
informasi serta memberi pesan dan saran.

###  2.1.2 Antarmuka Pengguna 

Halaman Admin

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p><img src="https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/loginn.png"
style="width:3.10417in;height:1.47222in" /></p>
<p>Halaman login, admin diminta untuk memasukkan username dan
password</p></th>
<th><p><img src="https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/dashboardadmin.png"
style="width:3.10417in;height:1.43056in" /></p>
<p>Setelah login, admin akan masuk ke Dashboard admin</p></th>
</tr>
<tr class="odd">
<th><p><img src="https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/dashboardadmin.png"
style="width:3.10417in;height:1.43056in" /></p>
<p>Pada halaman ini juga terdapat halaman untuk admin mengelola data
menu, bukan hanya menu tetapi admin juga dapat mengelola data about us,
kutipan, slider, promo, galeri, pesan saran pada halaman ini</p></th>
<th><p><img src="https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/tambahmenu.png"
style="width:3.10417in;height:1.44444in" /></p>
<p>Pada halaman menu, admin dapat menambah daftar menu baru. Begitu juga
pada pengelolaan data lain nya</p></th>
</tr>
<tr class="header">
<th><p><img src="https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/editmenu.png"
style="width:3.10417in;height:1.47222in" /></p>
<p>Pada halaman menu juga terdapat aksi untuk mengedit daftar
menu</p></th>
<th><p><img src="https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/menuadmin.png"
style="width:3.10417in;height:3.88889in" /></p>
<p>Pada halaman menu, selain untuk menambahkan dan mengedit, admin juga
dapat menghapus data menu</p></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

Halaman User

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>
<p><img src="https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/home.png"
style="width:3.10417in;height:1.44444in" /></p>
<p><img src="https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/homekutipan.png"
style="width:3.10417in;height:1.22222in" /></p>
<p><img src="https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/homepromo.png" /></p>
<p>Pada halaman pengunjung terdapat sebuah beranda yang berisi tampilan
scrolling yang berisi konten seperti slider, promo, kutipan dan
menu</p></th>
<th><p><img src="https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/menu.png"
style="width:3.10417in;height:1.45833in" /></p>
<p>Pada halaman pengunjung terdapat Menu yang berisi nama makanan,
harga, gambar dan deskripsi harga serta daftar menu makanan dan minuman
dipisah</p></th>
</tr>
<tr class="odd">
<th><p><img src="https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/promo.png"
style="width:3.10417in;height:1.48611in" /></p>
<p>Pada halaman pengunjung juga terdapat halaman promo yang berisikan
informasi promo promo yang ada</p></th>
<th><p><img src="https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/galery.png"
style="width:3.10417in;height:1.44444in" /></p>
<p>Pada halaman pengunjung terdapat Galery yang menampilkan foto foto
seputar UMKM</p></th>
</tr>
<tr class="header">
<th><p><img src="https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/aboutus.png"
style="width:3.10417in;height:1.45833in" /></p>
<p>Pada halaman pengunjung terdapat halaman About Us yang berisi
informasi pengelola dan UMKM</p></th>
<th><p><img src="https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/pesansaran.png"
style="width:3.10417in;height:1.47222in" /></p>
<p>Pada halaman pengunjung terdapat halaman Pesan Saran yang berisi
informasi Pesan saran dari pengunjung</p></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

###  2.1.3 Antarmuka perangkat keras 

![](https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/antarmukahardware.jpeg)

Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat
Lunak Sistem kantin Afwah yaitu :

PC / laptop Untuk Menjalankan Aplikasi

###  2.1.4 Antarmuka Perangkat lunak 

Tidak ada

###  2.1.5 Antarmuka Komunikasi

Antarmuka komunikasi yang digunakan untuk mengoperasikan Perangkat Lunak
Sistem kantin Afwah yaitu :

- PC

- Jaringan/Wifi

###  2.1.6 Batasan Memory

Tidak ada

###  2.1.7 Operasi-operasi 

| Operasi    | Fungsi                             |
|------------|------------------------------------|
| Login      | Digunakan untuk mengakses aplikasi |
| Input Data | DIgunakan untuk memasukkan data    |
| Hapus      | Digunakan untuk menghapus data     |
| Edit       | Digunakan untuk mengubah data      |
| View       | Digunakan untuk menampilkan data   |
| Simpan     | Digunakan untuk menyimpan data     |

### 

###  2.1.8 Kebutuhan Adaptasi

Tidak ada

## 

## 2.2 Spesifikasi kebutuhan fungsional

![](https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/fungsional.png)

### 2.2.1 Admin Login

Use Case: Login

Diagram:

![](https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/2.2.1%20Admin%20Login.png)
Deskripsi Singkat

Admin melakukan login terlebih dahulu sebelum masuk ke tampilan home
admin, apabila gagal login akan muncul pesan alert error login.

Deskripsi Langkah-Langkah

1.  Admin melakukan login dengan username dan password.

2.  Sistem melakukan validasi login.

3.  Bila sukses sistem akan mengarahkan ke home admin.

4.  Bila gagal sistem akan menampilkan peringatan.

Xref: Bagian 3.2.1, Login Admin

### 

### 2.2.2 Admin input Menu

Deskripsi Singkat  
Sistem dapat menampilkan halaman input menu dan Admin menginputkan menu.

![](https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/2.2.2%20Admin%20Input%20Menu.png)

Deskripsi Langkah- langkah:

1.  Sistem akan menampilkan tampilan daftar menu.

2.  Admin dapat melihat,menambahkan, dan mengupload gambar menu.

3.  Sistem akan menyimpan ke database.

Xref: Bagian 3.2.2, Input data Menu

### 2.2.3 Admin input Slide 

Deskripsi Singkat  
Sistem dapat menampilkan halaman input slide dan Admin menginputkan
slide.

![](https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/2.2.3%20Admin%20Input%20Slide.png)

Deskripsi Langkah- langkah:

1.  Sistem akan menampilkan tampilan daftar slide.

2.  Admin dapat melihat,menambahkan, dan mengupload gambar slide.

3.  Sistem akan menyimpan ke database.

4.  sudah disimpan sistem akan menampilkan peringatan.

Xref: Bagian 3.2.3, Input data slide

### 2.2.4 Admin input about us

Deskripsi Singkat  
Sistem dapat menampilkan halaman input about dan Admin menginputkan
about.

![](https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/2.2.4%20Admin%20Input%20About%20Us.png)

Deskripsi Langkah- langkah:

1.  Sistem akan menampilkan tampilan daftar about.

2.  Admin dapat melihat,menambahkan, dan mengupload gambar about.

3. Sistem akan menyimpan ke database.

Xref: Bagian 3.2.4, Input data about

### 2.2.5 Admin input galery 

Deskripsi Singkat  
Sistem dapat menampilkan halaman input galery dan Admin menginputkan
galery..

![](https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/2.2.5%20Admin%20Input%20Galery.png)

Deskripsi Langkah- langkah:

1. Sistem akan menampilkan tampilan daftar galery.

2. Admin dapat melihat,menambahkan, dan mengupload gambar galery.

3. Sistem akan menyimpan ke database.

4. sudah disimpan sistem akan menampilkan peringatan.

Xref: Bagian 3.2.5, Input data galery

### 2.2.6 Admin input Promo

Deskripsi Singkat Sistem dapat menampilkan halaman input promo dan Admin
menginputkan promo.

![](https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/2.2.6%20Admin%20Input%20Promo.png)

Deskripsi Langkah- langkah:

1. Sistem akan menampilkan tampilan daftar promo.

2. Admin dapat melihat,menambahkan, dan mengupload gambar promo.

3. Sistem akan menyimpan ke database.

4. sudah disimpan sistem akan menampilkan peringatan.

Xref: Bagian 3.2.6, Input data promo

### 2.2.7 Admin input Kutipan

Deskripsi Singkat Sistem dapat menampilkan halaman input kutipan dan
Admin menginputkan kutipan.

![](https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/2.2.7%20Admin%20Input%20Kutipan.png)

Deskripsi Langkah- langkah:

1. Sistem akan menampilkan tampilan daftar kutipan.

2. Admin dapat melihat,menambahkan, dan mengupload gambar kutipan.

3. Sistem akan menyimpan ke database.

Xref: Bagian 3.2.7, Input data kutipan

### 2.2.8 Admin Mengelola Pesan Saran

Deskripsi Singkat Sistem dapat menampilkan halaman mengelola pesan saran
dan Admin menginputkan pesan saran.

![](https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/2.2.8%20Admin%20Input%20Pesan%20Saran.png)

Deskripsi Langkah- langkah:

1. Sistem akan menampilkan tampilan daftar pesan saran.

2. Admin dapat melihat,membalas pesan saran..

3. Sistem akan menyimpan ke database.

4. sudah disimpan sistem akan menampilkan peringatan.

Xref: Bagian 3.2.8, Input data pesan saran

### 2.2.9 Pengunjung mengunjungi website

![](https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/2.2.9%20Pengunjung%20Mengunjungi%20Website.png)

Deskripsi Singkat

pengunjung mengunjungi website dan melihat informasi yang ada pada
website seperti informasi seputar menu makanan, pengunjung juga dapat
memberikan pesan saran.

Deskripsi Langkah-Langkah

- Sistem akan menampilkan halaman-halaman konten.

- pengunjung melihat melihat informasi yang ada pada website seperti
  > informasi seputar menu makanan, pengunjung juga dapat memberikan
  > pesan saran..

## 

## 2.3 Spesifikasi Kebutuhan non Fungsional

- Table Kebutuhan non fungsional

| no  | Deskripsi                                                                |
|-----|--------------------------------------------------------------------------|
| 1   | Semua interface dan fungsi menggunakan Bahasa Indonesia                  |
| 2   | Perangkat Lunak dapat dipakai di semua platform OS ( Admin, pengunjung ) |

## 2.4 Karakteristik Pengguna 

Karakteristik pengguna dari perangkat lunak ini adalah pengguna langsung
berinteraksi dengan website, dan login untuk admin.

## 2.5 Batasan-batasan

Tidak ada

## 2.6 Asumsi-asumsi 

Tidak ada

## 2.7 Kebutuhan Penyeimbang

Tidak ada

# 

# BAB III Requirement Specification

## 3.1 Persyaratan Antarmuka Eksternal 

Untuk admin yang akan mengakses website ini diperlukan registrasi
terlebih dahulu, kemudian akan login dengan memasukkan username dan
password, lalu sistem akan validasi login. Setelah login berhasil Admin
dapat melihat tampilan admin yang ada di website tersebut. Untuk
pengunjung hanya perlu membuka halaman website, kemudian pengunjung
dapat melihat konten yang ada di website tersebut.

## 3.2 Functional Requirement

## 3.2.1 Admin Login 

<table>
<colgroup>
<col style="width: 23%" />
<col style="width: 76%" />
</colgroup>
<thead>
<tr class="header">
<th>Nama Fungsi</th>
<th>Login</th>
</tr>
<tr class="odd">
<th>Xref</th>
<th>Bagian 2.2.1 Admin Login</th>
</tr>
<tr class="header">
<th>Trigger</th>
<th>Admin Membuka Website Kantin Afwah</th>
</tr>
<tr class="odd">
<th>Precondition</th>
<th>Halaman Login</th>
</tr>
<tr class="header">
<th>Basic Path</th>
<th><ol type="1">
<li><blockquote>
<p>Admin melakukan login dengan username dan password</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="2" type="1">
<li><blockquote>
<p>Sistem memvalidasi login</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th></th>
<th><ol start="3" type="1">
<li><blockquote>
<p>Jika berhasil, sistem akan mengarahkan ke home admin</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="4" type="1">
<li><blockquote>
<p>Jika gagal, sistem akan menampilkan peringatan</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th>Alternative</th>
<th>Tidak Ada</th>
</tr>
<tr class="odd">
<th>Post Condition</th>
<th>Admin dapat login dan mengakses website Kantin Afwah</th>
</tr>
<tr class="header">
<th>Exception Push</th>
<th>Username dan password salah</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 3.2.2 Admin Input Menu

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 75%" />
</colgroup>
<thead>
<tr class="header">
<th>Nama Fungsi</th>
<th>Input Menu</th>
</tr>
<tr class="odd">
<th>Xref</th>
<th>Bagian 2.2.2 Admin Input Menu</th>
</tr>
<tr class="header">
<th>Trigger</th>
<th>Admin dapat menginputkan menu</th>
</tr>
<tr class="odd">
<th>Precondition</th>
<th>Admin menginputkan menu Kantin Afwah ke website</th>
</tr>
<tr class="header">
<th>Basic Path</th>
<th><ol type="1">
<li><blockquote>
<p>Sistem akan menampilkan tampilan menu Kantin Afwah</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="2" type="1">
<li><blockquote>
<p>Admin dapat melihat, menambahkan, mengedit dan menghapus menu</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th></th>
<th><ol start="3" type="1">
<li><blockquote>
<p>Sistem akan menyimpan ke database</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th>Alternative</th>
<th>Tidak Ada</th>
</tr>
<tr class="header">
<th>Post Condition</th>
<th>Admin dapat menginputkan menu makanan Kantin Afwah seperti nama
makanan, harga, deskripsi dan gambar makanan</th>
</tr>
<tr class="odd">
<th>Exception Push</th>
<th>Tidak Ada</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 

## 3.2.3 Admin Input Slide 

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 75%" />
</colgroup>
<thead>
<tr class="header">
<th>Nama Fungsi</th>
<th>Input Slide</th>
</tr>
<tr class="odd">
<th>Xref</th>
<th>Bagian 2.2.3 Admin Input Slide</th>
</tr>
<tr class="header">
<th>Trigger</th>
<th>Admin dapat menginputkan slide</th>
</tr>
<tr class="odd">
<th>Precondition</th>
<th>Admin menginputkan slide ke website</th>
</tr>
<tr class="header">
<th>Basic Path</th>
<th><ol type="1">
<li><blockquote>
<p>Sistem akan menampilkan tampilan slide</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="2" type="1">
<li><blockquote>
<p>Admin dapat melihat, menambahkan, mengedit dan menghapus slide</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th></th>
<th><ol start="3" type="1">
<li><blockquote>
<p>Sistem akan menyimpan ke database</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="4" type="1">
<li><blockquote>
<p>Sistem akan menampilkan peringatan</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th>Alternative</th>
<th>Tidak Ada</th>
</tr>
<tr class="odd">
<th>Post Condition</th>
<th>Admin dapat menginputkan slide berupa foto</th>
</tr>
<tr class="header">
<th>Exception Push</th>
<th>Tidak Ada</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

> 3.2.4 Admin Input About Us

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 75%" />
</colgroup>
<thead>
<tr class="header">
<th>Nama Fungsi</th>
<th>Input About Us</th>
</tr>
<tr class="odd">
<th>Xref</th>
<th>Bagian 2.2.4 Admin Input About Us</th>
</tr>
<tr class="header">
<th>Trigger</th>
<th>Admin dapat menginputkan about us</th>
</tr>
<tr class="odd">
<th>Precondition</th>
<th>Admin menginputkan about us ke website</th>
</tr>
<tr class="header">
<th>Basic Path</th>
<th><ol type="1">
<li><blockquote>
<p>Sistem akan menampilkan tampilan about us</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="2" type="1">
<li><blockquote>
<p>Admin dapat melihat, menambahkan, dan mengedit about us</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th></th>
<th><ol start="3" type="1">
<li><blockquote>
<p>Sistem akan menyimpan ke database</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th>Alternative</th>
<th>Tidak Ada</th>
</tr>
<tr class="header">
<th>Post Condition</th>
<th>Admin dapat menginputkan about us seperti foto kantin, deskripsi
kantin, foto pemilik, deskripsi pemilik, email, alamat dan kontak</th>
</tr>
<tr class="odd">
<th>Exception Push</th>
<th>Tidak Ada</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 3.2.5 Admin Input Galery 

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 75%" />
</colgroup>
<thead>
<tr class="header">
<th>Nama Fungsi</th>
<th>Input Galery</th>
</tr>
<tr class="odd">
<th>Xref</th>
<th>Bagian 2.2.5 Admin Input Galery</th>
</tr>
<tr class="header">
<th>Trigger</th>
<th>Admin dapat menginputkan galery</th>
</tr>
<tr class="odd">
<th>Precondition</th>
<th>Admin menginputkan galery ke website</th>
</tr>
<tr class="header">
<th>Basic Path</th>
<th><ol type="1">
<li><blockquote>
<p>Sistem akan menampilkan tampilan galery</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="2" type="1">
<li><blockquote>
<p>Admin dapat melihat, menambahkan dan mengupload galery</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th></th>
<th><ol start="3" type="1">
<li><blockquote>
<p>Sistem akan menyimpan ke database</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="4" type="1">
<li><blockquote>
<p>Sistem akan menampilkan peringatan</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th>Alternative</th>
<th>Tidak Ada</th>
</tr>
<tr class="odd">
<th>Post Condition</th>
<th>Admin dapat menginputkan galery seperti judul galeri, tanggal,
deskripsi dan gambar</th>
</tr>
<tr class="header">
<th>Exception Push</th>
<th>Tidak Ada</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 3.2.6 Admin input Promo

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 75%" />
</colgroup>
<thead>
<tr class="header">
<th>Nama Fungsi</th>
<th>Input Promo</th>
</tr>
<tr class="odd">
<th>Xref</th>
<th>Bagian 2.2.6 Admin Input Promo</th>
</tr>
<tr class="header">
<th>Trigger</th>
<th>Admin dapat menginputkan promo</th>
</tr>
<tr class="odd">
<th>Precondition</th>
<th>Admin menginputkan promo ke website</th>
</tr>
<tr class="header">
<th>Basic Path</th>
<th><ol type="1">
<li><blockquote>
<p>Sistem akan menampilkan tampilan about us</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="2" type="1">
<li><blockquote>
<p>Admin dapat melihat, menambahkan, mengedit dan menghapus promo</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th></th>
<th><ol start="3" type="1">
<li><blockquote>
<p>Sistem akan menyimpan ke database</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="4" type="1">
<li><blockquote>
<p>Sistem akan menampilkan peringatan</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th>Alternative</th>
<th>Tidak Ada</th>
</tr>
<tr class="odd">
<th>Post Condition</th>
<th>Admin dapat menginputkan promo seperti judul, tanggal awal, tanggal
akhir, deskripsi, syarat ketentuan, dan gambar</th>
</tr>
<tr class="header">
<th>Exception Push</th>
<th>Tidak Ada</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 3.2.7 Admin Input Kutipan 

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 75%" />
</colgroup>
<thead>
<tr class="header">
<th>Nama Fungsi</th>
<th>Input Kutipan</th>
</tr>
<tr class="odd">
<th>Xref</th>
<th>Bagian 2.2.7 Admin Input Kutipan</th>
</tr>
<tr class="header">
<th>Trigger</th>
<th>Admin dapat menginputkan kutipan</th>
</tr>
<tr class="odd">
<th>Precondition</th>
<th>Admin menginputkan kutipan ke website</th>
</tr>
<tr class="header">
<th>Basic Path</th>
<th><ol type="1">
<li><blockquote>
<p>Sistem akan menampilkan tampilan kutipan</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="2" type="1">
<li><blockquote>
<p>Admin dapat melihat, menambahkan, mengedit dan menghapus kutipan</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th></th>
<th><ol start="3" type="1">
<li><blockquote>
<p>Sistem akan menyimpan ke database</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th>Alternative</th>
<th>Tidak Ada</th>
</tr>
<tr class="header">
<th>Post Condition</th>
<th>Admin dapat menginputkan kutipan seperti judul, isi kutipan dan
gambar</th>
</tr>
<tr class="odd">
<th>Exception Push</th>
<th>Tidak Ada</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 3.2.8 Admin Mengelola Pesan Saran 

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 75%" />
</colgroup>
<thead>
<tr class="header">
<th>Nama Fungsi</th>
<th>Admin Mengelola Pesan Saran</th>
</tr>
<tr class="odd">
<th>Xref</th>
<th>Bagian 2.2.8 Admin Mengelola Pesan Saran</th>
</tr>
<tr class="header">
<th>Trigger</th>
<th>Admin dapat mengelola pesan saran pada website</th>
</tr>
<tr class="odd">
<th>Precondition</th>
<th>Admin melihat pesan saran</th>
</tr>
<tr class="header">
<th>Basic Path</th>
<th><ol type="1">
<li><blockquote>
<p>Sistem akan menampilkan tampilan pesan saran</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="2" type="1">
<li><blockquote>
<p>Admin dapat melihat, menghapus dan membalas pesan saran dari
pengunjung</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th></th>
<th><ol start="3" type="1">
<li><blockquote>
<p>Sistem akan menyimpan ke database</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="4" type="1">
<li><blockquote>
<p>Sistem akan menampilkan peringatan</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th>Alternative</th>
<th>Tidak Ada</th>
</tr>
<tr class="odd">
<th>Post Condition</th>
<th>Admin dapat membalas dan menghapus pesan saran dari pengunjung</th>
</tr>
<tr class="header">
<th>Exception Push</th>
<th>Tidak Ada</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 3.2.9 Pengunjung Mengunjungi Website

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 75%" />
</colgroup>
<thead>
<tr class="header">
<th>Nama Fungsi</th>
<th>Pengunjung Mengunjungi Website</th>
</tr>
<tr class="odd">
<th>Xref</th>
<th>Bagian 2.2.8 Pengunjung Mengunjungi Website</th>
</tr>
<tr class="header">
<th>Trigger</th>
<th>Pengunjung dapat mengunjungi website dan melihat informasi yang ada
pada website Kantin Afwah yang telah disediakan</th>
</tr>
<tr class="odd">
<th>Precondition</th>
<th>Pengunjung Mengunjungi Website</th>
</tr>
<tr class="header">
<th>Basic Path</th>
<th><ol type="1">
<li><blockquote>
<p>Sistem akan menampilkan halaman halaman konten</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="odd">
<th></th>
<th><ol start="2" type="1">
<li><blockquote>
<p>Pengunjung melihat informasi yang ada pada website dan juga dapat
memberikan pesan saran pada website yang tersedia</p>
</blockquote></li>
</ol></th>
</tr>
<tr class="header">
<th>Alternative</th>
<th>Tidak Ada</th>
</tr>
<tr class="odd">
<th>Post Condition</th>
<th>Pengunjung mengunjungi website dan melihat informasi yang tersedia
pada website</th>
</tr>
<tr class="header">
<th>Exception Push</th>
<th>Tidak Ada</th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## 3.3 Struktur Detail Kebutuhan Non - Fungsional 

![](https://github.com/DimasAdrian29/Webiste_CompanyProfile_UMKM_KantinAfwah/blob/main/public/erd.png)
3.3.1 Logika Struktur Data

Struktur data logika pada sistem Kantin Afwah terdapat struktur Database
yang dijelaskan menggunakan ERD

**Tabel Users**

| **Data Item**     | **Tipe Data** | **Deskripsi**                                         |
|-------------------|---------------|-------------------------------------------------------|
| id                | bigint        | Auto increment dari id untuk admin                    |
| name              | varchar(255)  | Berisikan name dari admin untuk mengakses sistem      |
| email             | varchar(255)  | Berisikan email admin untuk mengakses sistem          |
| password          | varchar(255)  | Berisikan password admin untuk mengakses sistem       |
| email_verified_at | timestamp     | Berisikan email admin yang terverifikasi              |
| remember_konten   | varchar(255)  | Berisikan remerber token admin untuk mengakses sistem |
| created_at        | timestamp     | Berisikan kapan akun admin dibuat                     |
| updated_at        | timestamp     | Berisikan kapan akun admin diperbarui                 |

**Tabel About**

| **Data Item**     | **Tipe Data** | **Deskripsi**                                     |
|-------------------|---------------|---------------------------------------------------|
| id                | int           | Auto increment dari id untuk About                |
| email             | varchar(255)  | Berisi email dalam sistem Kantin Afwah            |
| alamat            | varchar(255)  | Berisi alamat dalam sistem Kantin Afwah           |
| kontak            | varchar(255)  | Berisi kontak dalam sistem Kantin Afwah           |
| gambar_kantin     | text          | Berisi gambar kantin dalam sistem Kantin Afwah    |
| deskripsi_kantin  | text          | Berisi deskripsi kantin dalam sistem Kantin Afwah |
| gambar_pemilik    | text          | Berisi gambar pemilik dalam sistem Kantin Afwah   |
| deskripsi_pemilik | text          | Berisi deskripsi pemilik dalam sistemKantin Afwah |

**Tabel Galery**

| **Data Item** | **Tipe Data** | **Deskripsi**                                |
|---------------|---------------|----------------------------------------------|
| id_galery     | int           | Auto increment dari id_galery                |
| judul_galery  | varchar(255)  | Berisi judul galery dalam sistemKantin Afwah |
| deskripsi     | varchar(255)  | Berisi deskripsi dalam sistem Kantin Afwah   |
| foto          | varchar(255)  | Berisi foto dalam sistem Kantin Afwah        |
| tanggal       | date          | Berisi tanggal dalam sistem Kantin Afwah     |

**Tabel Kutipan**

| **Data Item** | **Tipe Data** | **Deskripsi**                                |
|---------------|---------------|----------------------------------------------|
| id            | int           | Auto increment dari id untuk kutipan         |
| judul         | varchar(255)  | Berisi judul dalam sistem Kantin Afwah       |
| isi_kutipan   | varchar(255)  | Berisi isi kutipan dalam sistem Kantin Afwah |
| gambar        | text          | Berisi gambar dalam sistem Kantin Afwah      |

**Tabel Menu**

| **Data Item** | **Tipe Data** | **Deskripsi**                               |
|---------------|---------------|---------------------------------------------|
| id            | int           | Auto increment dari id untuk menu           |
| nama_menu     | varchar(255)  | Berisi nama menu dalam sistem Kantin Afwah  |
| dekripsi      | varchar(255)  | Berisi deskripsi dalam sistem Kantin Afwah  |
| harga         | int           | Berisi harga dalam sistem Kantin Afwah      |
| gambar        | text          | Berisi gambar dalam sistem Kantin Afwah     |
| jenis_menu    | varchar(255)  | Berisi jenis menu dalam sistem Kantin Afwah |

**Tabel Promo**

| **Data Item**        | **Tipe Data** | **Deskripsi**                                         |
|----------------------|---------------|-------------------------------------------------------|
| id_promo             | int           | Auto increment dari id_promo                          |
| judul                | varchar(255)  | Berisi judul dalam sistem Kantin Afwah                |
| deskripsi            | text          | Berisi deskripsi dalam sistem Kantin Afwah            |
| gambar               | varchar(255)  | Berisi gambar dalam sistem Kantin Afwah               |
| tanggal_awal_promo   | date          | Berisi tangga awal promo dalam sistem Kantin Afwah    |
| tanggal_akhir_promo  | date          | Berisi tanggal akhir promo dalam sistem Kantin Afwah  |
| syarat_dan_ketentuan | text          | Berisi syarat dan ketentuan dalam sistem Kantin Afwah |

**Tabel Sliders**

| **Data Item** | **Tipe Data** | **Deskripsi**                                  |
|---------------|---------------|------------------------------------------------|
| id            | bigint        | Auto increment dari id_promo                   |
| created_at    | timestamp     | Berisi kapan ditambahkan slidernya             |
| updated_at    | timestamp     | Berisi kapan sliderny diperbarui               |
| gambar_slider | varchar(255)  | Berisi gambar slider dalam sistem Kantin Afwah |

**Pembagian Tugas Laporan**

BAB 1 -\> Dimas

BAB 2 -\> Kibran

2.1 -\> Syafrisar

2.2 -\> Dimas

2.3 - 2.4 -\> Dimas

BAB 3

3.1 -\> Syafrisar

3.2 -\> Syafrisar

3.3 -\> Kibran

**Pembagian Kerja Projek**

Syafrisar :

> CRUD Menu
>
> CRUD About Us
>
> CRUD Kutipan
>
> Halaman About Us
>
> Halaman Menu

Dimas :

> CRUD galery
>
> CRUD Promosi
>
> Halaman Promosi
>
> Halaman Pesan Saran

Kibran :

> CRUD slider
>
> CRUD pesan saran
>
> Halaman home
>
> Halaman Galery
