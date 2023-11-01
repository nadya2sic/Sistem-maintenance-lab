<html>
<body>
<div align="center"><h1> Sistem Maintenance Lab Komputer  <h1></div>
	
<p align="center">
  <img src="https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/logo%20pcr.png?raw=true" width="900" height="200"/ > 
<p align="center"><b>
<br>Kelompok 8 <br>
<br>Octanius Anggono (2257301109)<br>
<br>Nadiya Febiola (2257301099)<br>
<br>Nurul Dwi Hariyati (2257301108)<br>
 </b></p>
 <br><br><br>
<p align="center"><b>Jurusan Sistem Informasi<br>
<br>Politeknik Caltex Riau<br>
<br>2023<br>
</b>
</p>
</body>
</html>

**BAB I Pendahuluan**
----------
1.1 Tujuan
----------
Dokumen Spesifikasi Kebutuhan Perangkat Lunak (SKPL) adalah dokumen yang merinci kebutuhan perangkat lunak yang akan dikembangkan. Dokumen ini akan menjadi panduan teknisi bagi pengembang perangkat lunak dalam tahap selanjutnya. Studi kasus yang dijelaskan dalam dokumen ini berkaitan dengan Otomatisasi Teknisi Laboratorium yang merupakan sistem yang dirancang untuk membantu teknisi melaporkan masalah, melacak lokasi komputer, dan mengupdate perangkat.Kami membuat produk inovatif yang memungkinkan untuk mempermudah pekerjaan user dengan mendapatkan informasi melalui sistem.


1.2   Lingkup
----------
Pelaporan Masalah Sistem akan memungkinkan teknisi melaporkan masalah yang terjadi di laboratorium dengan mudah dan Pembaruan Software/ Hardware Sistem akan memungkinkan teknisi merencanakan, mengelola, dan melaksanakan pembaruan perangkat lunak dan perangkat keras secara efisien. Dan Pelacakan Perangkat Sistem akan memungkinkan teknisi untuk melacak keberadaan dan status komputer di laboratorium. Hal ini dapat membantu memantau ketersediaan perangkat, memastikan bahwa mereka berfungsi dengan baik, dan menemukan komputer yang memerlukan perbaikan atau pembaruan.


1.3    Akronim, singkatan, definisi
----------
| Istilah | Definisi |
| ------ | ------ |
| SRS |Software Requirement Specification|
| Login | Digunakan untuk mengakses aplikasi |
| Software Requirement Specification | perangkat lunak yang akan dibuat dan sebagai penyembatani komunikasi pembuat dengan pengguna |
| Use Case | situasi dimana sistem anda digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian anda |

1.4   Referensi
----------
Referensi yang digunakan dalam pengembangan perangkat lunak ini adalah :
- a
-
- 

1.5   Overview
----------
Bab selanjutnya yaitu menjelaskan sistem yang di terapkan pada aplikasi. Menjelaskan gambaran umum dari aplikasi, sistem interface aplikasi dan alur sistemnya. Bab terakhir menjelaskan tentang setiap fungsi yang digunakan secara teknisnya. Pada bab 2 dan 3 merupakan deskripsi dari aplikasi yang akan diterapkan pada aplikasi yang dibuat.

**BAB II Gambaran umum**
----------
Pada zaman era globalisasi perkembangan teknologi begitu sangat pesat, salah satunya ialah perkembangan teknologi dibidang software, dalam studi kasus ini kami menganalisa kebutuhan suatu sekolah di daerah Pekanbaru ini, kasus yang kami peroleh yaitu Sistem Maintenance Lab Komputer, kami merancang sistem sesuai dengan kebutuhan SMKN 1 Pekanbaru  dengan menerapkan sistem informasi, sehingga memudahkan Teknisi dalam menginputkan permasalahan di laboratorium, Kepala Teknisi dapat melihat data yang sudah diinputkan, Software yang kami buat ini berbasis website. Sistem yang kami buat di dalamnya terdapat Pemeriksaan Software/ Hardware Perangkat Sistem melacak lokasi komputer, dan mengupdate perangkat. Berikut akan kami jelaskan sistem software kami, admin fungsi utama yaitu :

  - Input Data maintenance Lab
  - Kelola data Maintenance Lab
  - Laporan

    Berikut ini fungsi Kepala Teknisi dalam bentuk grafik :
- Kelola data maintenance lab
- View laporan 

2.1   Perspektif produk
----------
Maintenance Lab Komputer adalah sebuah sistem maintenance lab terdapat 2 jenis admin yaitu Kepala Teknisi, dan Teknisi pengolahan data dikelola oleh Kepala Teknisi dan Teknisi

Pada Sistem Maintenance Lab Komputer ini akan menghasilkan laporan data yang sudah di inputkan oleh teknisi.

**2.1.1 Antarmuka sistem**

![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Screenshot%202023-11-01%20200948.png?raw=true)

Sistem aplikasi Maintenance Labor Komputer memiliki 2 user yaitu Kepala Teknisi dan Teknisi. Kepala Teknisi mempunyai fungsi yaitu melakukan view Data Maintanance Lab, serta bisa melakukan Login ke sistem. Teknisi bertugas untuk menginput dan mengelola data, supaya data bisa di akses oleh Kepala Teknisi.


**2.1.2 Antarmuka pengguna**

   - **Mockup Admin ( Website )**

|  |  |
|--|--|
| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Projek%20Framework_page-0001.jpg?raw=true) Pada halaman login user diminta untuk mengisi username dan password yang telah diberikan.| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/1.jpg?raw=true) Pada Dashboard Teknisi terdapat isi tabel-tabel maintenance bulanan.|
| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/2.jpg?raw=true) Pada halaman dashboard ada navigation bar kependudukan yang berisi dropdown angka kelahiran dan angka kematian| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/3.jpg?raw=true) Pada Halaman agama dapat menginputkan data agama penduduk|
| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/4.jpg?raw=true) Pada Halaman pekerjaan dapat menginputkan data pekerjaan penduduk| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/5.jpg?raw=true) Pada Halaman warga dapat menginputkan data warga|
| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/6.jpg?raw=true) Pada Halaman pendidikan dapat menginputkan data pendidikan penduduk| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/7.jpg?raw=true) Pada Halaman kelahiran dapat menginputkan data kelahiran penduduk|


 **2.1.3 Antarmuka perangkat keras**

![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/antar%20perangkat%20keras.jpg?raw=true)

Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat Lunak Sistem Maintenance Lab Komputer antara lain :

1. PC / Laptop
Untuk menjalankan Aplikasi ini admin membutuhkan sebuah PC yang menggunakan OS Windows, Linux, atau MAC dan sudah terinstall browser .

**2.1.4 Antarmuka perangkat lunak**

Tidak ada

**2.1.5 Antarmuka Komunikasi**

Antarmuka komunikasi yang digunakan untuk mengoperasikan Perangkat Lunak Maintenance Lab Komputer antara lain :
1. Kabel Lan 
2. Wifi


**2.1.6 Batasan memori**

Tidak ada

**2.1.7 Operasi-operasi**

| Operasi | Fungsi |
| ------ | ------ |
| Login | Digunakan untuk mengakses aplikasi |
| Input Data | Digunakan untuk memasukkan data-data |
| Kembali | Digunakan untuk kembali ke halaman sebelumnya |
| Edit | Digunakan untuk mengubah data |
| View | Digunakan untuk menampilkan data |
| Simpan | Digunakan untuk menyimpan data |
| Cetak | Digunakan untuk mencetak laporan |
| Deskripsi| Digunakan untuk menambah keterangan |

**2.1.8 Kebutuhan adaptasi**

Tidak ada
   
2.2 Spesifikasi Kebutuhan fungsional
----------
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/123.jpg?raw=true)
   
**2.2.1 Teknisi Login**

Use Case: Login <br>
Diagram : 
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/U1.png?raw=true)

Deskripsi Singkat Teknisi melakukan login terlebih dahulu sebelum masuk ke tampilan home, Teknisi login menggunakan username dan password yang diberikan oleh admin. <br>
Deskripsi langkah-langkah :
<br>
1. Teknisi melakukan login dengan username dan password<br>
2. Sistem melakukan validasi login<br>
3. Bila sukses sistem akan mengarahkan ke halaman beranda<br>
4. Bila gagal sistem akan menampilkan peringatan<br>
Xref: Bagian 3.2.1, Login Teknisi<br>

**2.2.2 Teknisi Menginput data maintenance lab**

Use Case: Input data maintenance lab<br>
Diagram: 
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/U2.png?raw=true)

Deskripsi Singkat Sistem akan menampilkan form data Software dan Hardware teknisi dapat melakukan edit dan hapus sesuai kebutuhan. <br>
Deskripsi Langkah-langkah :
<br>
1. Teknisi mengklik Data Software ataupun Hardware, lalu memilih bagian yang akan di edit <br>
2. Sistem akan menyimpan perubahan ke database dan menampilkan data yang telah diubah.<br>
3. Teknisi bisa menghapus data yang salah atau tidak diperlukan lagi.<br>
Xref: Bagian 3.2.3, Teknisi Mengelola Data maintenance lab<br>

**2.2.3 Teknisi Mengelola data maintenance lab**

Use case : Mengelola data maintenance lab<br>
Diagram : 
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/U3.png?raw=true)

Deskripsi Singkat Sistem akan menampilkan form data Software dan Hardware teknisi dapat melakukan edit dan hapus sesuai kebutuhan. <br>
Deskripsi Langkah-langkah :
<br>
1.Teknisi mengklik Data Software ataupun Hardware, lalu memilih bagian yang akan di edit <br>
2.Sistem akan menyimpan perubahan ke database dan menampilkan data yang telah diubah.<br>
3.Teknisi bisa menghapus data yang salah atau tidak diperlukan lagi.<br>
Xref: Bagian 3.2.3, Teknisi Mengelola Data maintenance lab<br>


**2.2.4 Kepala Teknisi Login**

Use Case: Login<br>

Diagram :
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/U4.png?raw=true)

Deskripsi Singkat Kepala Teknisi melakukan login terlebih dahulu sebelum masuk ke tampilan home, Teknisi login menggunakan username dan password yang diberikan oleh admin. <br>
Deskripsi langkah-langkah :
<br>
1. Kepala Teknisi melakukan login dengan username dan password<br>
2. Sistem melakukan validasi login<br>
3. Bila sukses sistem akan mengarahkan ke halaman beranda<br>
4. Bila gagal sistem akan menampilkan peringatan<br>
Xref: Bagian 3.2.1, Login Kepala Teknisi<br>

      
****2.2.5  Kepala Teknisi Mengelola Data Maintenance Lab**

Use Case: Mengelola Data Maintenance lab<br>
Diagram:
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/U5.png?raw=true)
      
Deskripsi Singkat Sistem akan menampilkan form data Software dan Hardware kepala teknisi dapat melakukan edit dan hapus sesuai kebutuhan. <br>
Deskripsi Langkah-langkah :
<br>
1. Kepala Teknisi mengklik Data Software maupun Hardware, lalu memilih bagian yang akan di edit <br>
2. Sistem akan menyimpan perubahan ke database dan menampilkan data yang telah diubah.<br>
3. Kepala Teknisi bisa menghapus data yang salah atau tidak diperlukan lagi.<br>
Xref: Bagian 3.2.3, Kepala Teknisi Mengelola Data maintenance lab<br>

**2.2.6   Kepala Teknisi Melihat Data Maintenance Lab**


Use Case: View Data Maintenance lab<br>
Diagram:
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/U6.png?raw=true)

Deskripsi Singkat Kepala Teknisi dapat melihat data maintenance lab setelah di inputkan. <br>
Deskripsi Langkah-langkah :
<br>
1. Sistem akan menampilkan data maintenance lab.<br>
2. Kepala teknisi melihat data dan dapat mengedit atau menghapusnya.<br>
3. Sistem menampilkan edit data maintenance lab<br>
4. Kepala Teknisi mengedit data maintenance lab yang baru atau yang sudah ada<br>
5. Sistem melakukan validasi jika data sudah ada maka muncul peringatan jika belum sistem akan menyimpan<br>
Xref: Bagian 3.2.6, View data maintenance lab<br>
  
**2.2.7 Kepala Teknisi Mencetak laporan**

Use Case:  laporan<br>
Diagram:
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/U7.png?raw=true)

Deskripsi Singkat Sistem akan mengirimkan data maintenance dan yang lainnya ke fungsi laporan. <br>
Deskripsi Langkah-langkah:
<br>
1. Sistem menampilkan laporan maintenance lab<br>
2. Kepala teknisi memilih combobox tersebut dan klik tombol cetak<br>
3. Sistem akan menampilkan hasil laporan.<br>
4. Kepala Teknisi mencetak laporan<br>
Xref: Bagian 3.2.7, Cetak Laporan
<br>

2.3   Spesifikasi Kebutuhan non-fungsional
----------
- Tabel Kebutuhan Non-Fungsional 

   | No | Deskripsi |
   | ------ | ------ |
   | 1 | Semua interface dan fungsi menggunakan Bahasa Indonesia |
   | 2 | Perangkat Lunak dapat dipakai di semua platofrm OS ( Teknisi dan Kepala Teknisi )
 
2.4   Karakteristik pengguna
----------
Perangkat lunak ini memungkinkan pengguna berinteraksi dengan sistem secara langsung tanpa membutuhkan level autentikasi atau hak akses. 

2.5   Batasan-batasan
----------
Perangkat lunak web hanya dapat digunakan di Windows (7,8,10), dan karena waktu pengembangan yang singkat, mungkin tidak semua fungsi dapat digunakan.

2.6   Asumsi-asumsi
----------
Maksimal penginputan id atau memassukkan kode pada alipikasi ini adalah 9999, lebih dari itu program akan muncul peringatan”Anda telah melebihi batas maksimum


2.7   Kebutuhan Penyeimbang
----------
Tidak ada


BAB III Requirement specification
----------
3.1 Persyaratan Antarmuka Eksternal
----------
Salah satu cara untuk mengakses aplikasi ini adalah dengan menggunakan akses yang diberikan oleh admin, login melalui aplikasi ini dengan memasukkan username dan password yang diberikan, kemudian sistem akan mencocokkan nama pengguna. Setelah berhasil login, teknisi dapat menginput dan mengelola data maintenance lab komputer

      
3.2 Functional Requirement
----------
Logika Struktur terdapat pada bagian 3.3.1
      
**3.2.1 Teknisi Login**

|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.1, Login Teknisi |
| Trigger | Membuka Aplikasi Sistem Informasi Maintenance Lab Komputer
| Precondition | Halaman Login|
| Basic Path | 1. Teknisi mengisi form login dengan username dan password <br> 2. Kepala desa mengklik tombol login <br> 3. Sistem melakukan validasi login <br> 4. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 5. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Kepala Teknisi dan Teknisi dapat login dan mengakses aplikasi Sistem Informasi Maintenance Lab Komputer |
| Exception Push | Username dan password salah |

<br>

**3.2.2 Teknisi Menginput Data Maintenance Lab Komputer**

|  |  |
|--|--|
| Nama Fungsi | Menginput data |
| Xref | Bagian 2.2.2, Teknisi menginputkan data Maintenance Lab Komputer |
| Trigger | Membuka halaman Input Data |
| Precondition | Halaman input data |
| Basic Path | 1.Setelah login, teknisi membuka halaman lab komputer <br> 2.Teknisi menginputkan data Software dan Hardware sesuai dengan lab dan komputer  <br> 3. Menyimpan data yang telah diinputkan  <br> 4. Kembali ke halaman dashboard |
| Alternative | Tidak ada |
| Post Condition | Teknisi dapat menginputkan dan menyimpan inputan data |
| Exception Push | Tidak ada |

<br>

**3.2.3 Teknisi Mengelola data maintenance lab**

|  |  |
|--|--|
| Nama Fungsi | Mengelola data maintenance lab  |
| Xref | Bagian 2.2.3, Teknisi mengelola data maintenance lab |
| Trigger | Membuka Aplikasi Sistem Informasi Maintenance Lab Komputer |
| Precondition | Halaman Utama Teknisi |
| Basic Path | 1. Setelah login <br> 2. teknisi membuka halaman maintenance Lab komputer <br> 3. Teknisi mengelola data maintenance lab <br> 4. Setelah itu teknisi mengirim pengelohan data kepada kepala teknisi |
| Alternative | Tidak ada |
| Post Condition | Teknisi dapat menginputkan dan menyimpan inputan data |
| Exception Push | Tidak ada  |

<br>
   
**3.2.4 Kepala Teknisi Login**
|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.4, Login Kepala Teknisi |
| Trigger | Membuka Aplikasi Sistem Informasi Maintenance Lab Komputer
| Precondition | Halaman Login|
| Basic Path | 1. Teknisi mengisi form login dengan username dan password <br> 2. Kepala desa mengklik tombol login <br> 3. Sistem melakukan validasi login <br> 4. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 5. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Teknisi dapat login dan mengakses aplikasi Sistem Informasi Maintenance Lab Komputer |
| Exception Push | Username dan password salah |

<br>

**3.2.5 Kepala Teknisi Mengelola data maintenance lab**

|  |  |
|--|--|
| Nama Fungsi | Mengelola data maintenance lab |
| Xref | Bagian 2.2.5, Kepala Teknisi mengelola data maintenance lab |
| Trigger | Membuka Aplikasi Sistem Informasi Maintenance Lab Komputer |
| Precondition | Halaman Utama Teknisi |
| Basic Path | 1. Setelah login, kepala teknisi, membuka halaman Maintenance Lab komputer <br> 2. Setelah itu kepala teknisi melihat data yang sudah di olah dari teknisi bakal diolah lebih detail lagi <br> 3. Kepala teknisi mengirim data-data yang terjadi di Maintenance Lab Komputer|
| Alternative | Tidak ada |
| Post Condition | Teknisi dapat menginputkan dan menyimpan inputan data  |
| Exception Push | Tidak ada |
   
**3.2.6 Kepala Teknisi Melihat Data Maintenance Lab Komputer**

|  |  |
|--|--|
| Nama Fungsi | Melihat Data Maintenance Lab Komputer |
| Xref | Bagian 2.2.6, Kepala Teknisi Melihat data Maintenance Lab Komputer |
| Trigger | Membuka halaman hasil laporan maintenance lab dari teknisi |
| Precondition | Halaman hasil laporan maintenance lab |
| Basic Path | 1. Setelah login kepala teknisi membuka halaman data dari maintenance  <br> 2. Sistem akan menampilkan hasil laporan |
| Alternative | Tidak ada |
| Post Condition |Teknisi dapat menginputkan dan menyimpan inputan data Tidak ada |
| Exception Push | Tidak ada |
   
**3.2.7 Kepala Teknisi Mencetak Laporan**
|  |  |
|--|--|
| Nama Fungsi |Mencetak Laporan|
| Xref | Bagian 2.2.7 Kepala Teknisi mencetak laporan data Maintenance Lab Komputer  |
| Trigger | Membuka halaman hasil laporan dari teknisi |
| Precondition | Halaman hasil laporan maintenance lab |
| Basic Path | 1. Setelah login Kepala Teknisi membuka halaman laporan dari maintenance  <br> 2. Kepala teknisi melihat halaman laporan  <br> 2. Setelah itu kepala teknisi mencetak laporan dari maintenance  |
| Alternative | Tidak ada  |
| Post Condition | Tidak ada|
| Exception Push | Tidak ada |

   
3.3 Struktur Detail Kebutuhan Non-Fungsional
----------
**3.3.1 Logika Struktur Data**
Struktur data logika pada Sistem Aplikasi presensi menggunakan kehadiran terdapat struktur Database yang dijelaskan menggunakan ERD.

![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/erd.png?raw=true)

**Tabel Akun**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_akun| int | Nomer auto increment Id_akun|
| Username | varchar | berisikan username untuk akses login user dan username untuk akses admin |
| Password | varchar | berisikan password untuk login admin dan user |

**Tabel Teknisi**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_teknisi | int | Nomer auto increment Id_teknisi |
| Username | varchar | berisikan username untuk akses login user dan username untuk akses admin |
| Password | varchar | berisikan password untuk login admin dan user |

**Tabel Kepala Teknisi**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_kepala_teknisi | int | Nomer auto increment Id_kepala_teknisi|
| Id_user| int | untuk mengambil username dan password admin pada tabel user|
| Username | varchar | berisikan username untuk akses login user dan username untuk akses admin |
| Password | varchar | berisikan password untuk login admin dan user |

**Tabel Hardware**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_software| int | Nomer auto increment Id_kelahiran|
| Id_teknisi| int | foreignt key tabel teknisi |
| monitor| varchar | Keterangan rusak atau tidak rusak |
| pc| varchar |Keterangan rusak atau tidak rusak|
| keyBoard | varchar | Keterangan rusak atau tidak rusak|
| mouse | varchar |Keterangan rusak atau tidak rusak|

**Tabel Software**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_hardware| int | Nomer auto increment Id_hardware|
| Id_teknisi| int | foreignt key tabel teknisi |
| windows| varchar | Keterangan rusak atau tidak rusak |
| aplikasi| varchar | Keterangan rusak atau tidak rusak |
| anti-virus | varchar | Keterangan rusak atau tidak rusak |

**Tabel Laporan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_laporan| int | Nomer auto increment Id_laporan|
| Id_teknisi| int | foreignt key tabel teknisi |
| laporan | varchar | berisi laporan maintenance |

**Pembagian Laporan**

| Nama | Tugas | 
| ------ | ------ | 
| Octanius Anggono | ERD, | 
| Nurul Dwi Hariyati |  | 
| Nadiya Febiola |  | 



