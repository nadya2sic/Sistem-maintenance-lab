<html>
<body>
<div align="center"><h1> Sistem Maintenance Lab Komputer  <h1></div>
	
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/b/b9/Logo_Resmi_PCR.png" width="400" height="400"/ > 
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
- http://hasantarmizi.blogspot.co.id/2017/04/pengertian-sublime-text.html
- IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software  Requirements Specifications. IEEE Computer Society, 1998. 1.5  Overview 
- pcr.ac.id

- 1.5   Overview
- Bab selanjutnya yaitu menjelaskan sistem yang di terapkan pada aplikasi. Menjelaskan gambaran umum dari aplikasi, sistem interface aplikasi dan alur sistemnya. Bab terakhir menjelaskan tentang setiap fungsi yang digunakan secara teknisnya. Pada bab 2 dan 3 merupakan deskripsi dari aplikasi yang akan diterapkan pada aplikasi yang dibuat.

**BAB II Gambaran umum**
----------
Pada zaman era globalisasi perkembangan teknologi begitu sangat pesat, salah satunya ialah perkembangan teknologi dibidang software, dalam studi kasus ini kami menganalisa kebutuhan suatu sekolah di daerah Pekanbaru ini, kasus yang kami peroleh yaitu Sistem Maintenance Lab Komputer, kami merancang sistem sesuai dengan kebutuhan SMKN 1 Pekanbaru  dengan menerapkan sistem informasi, sehingga memudahkan Teknisi dalam menginputkan permasalahan di laboratorium, Kepala Teknisi dapat melihat data yang sudah diinputkan, Software yang kami buat ini berbasis website. Sistem yang kami buat di dalamnya terdapat Pemeriksaan Software/ Hardware Perangkat Sistem melacak lokasi komputer, dan mengupdate perangkat. Berikut akan kami jelaskan sistem software kami, admin fungsi utama yaitu :

  - Input Data maintenance Lab
  - Kelola data Maintenance Lab
  - Laporan

   -    Berikut ini fungsi Kepala Teknisi dalam bentuk grafik :
- Kelola data maintenance lab
- View laporan 

2.1   Perspektif produk
----------
Maintenance lab komputer Adalah sebuah sistem maintenance lab terdapat 2 jenis admin yaitu kepala teknisi, dan teknisi pengolahan data dikelola oleh kepala teknisi dan teknisi

Pada sistem manajemen administrasi data kependudukan ini akan menampilkan grafik kependudukan yang sudah di inputkan oleh admin

**2.1.1 Antarmuka sistem**

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/antarmuka%20sistem1.png)

Sistem aplikasi Maintenance Labor Komputer memiliki 2 user yaitu Kepala Teknisi dan Teknisi. Kepala Teknisi mempunyai fungsi yaitu melakukan view Data Maintanance Lab, serta bisa melakukan Login ke sistem. Teknisi bertugas untuk menginput dan mengelola data, supaya data bisa di akses oleh Kepala Teknisi.


**2.1.2 Antarmuka pengguna**

   - **Mockup Admin ( Website )**

|  |  |
|--|--|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Halaman%20Login.png) Pada halaman login admin diminta untuk mengisi username dan password.| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Halaman%20Dashboard.png) Pada Dashboard admin terdapat panel-panel seperti penduduk, pendidikan, agama, pekerjaan, laporan dan ucapan selamat datang.|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Dropdone%20Kependudukan.png) Pada halaman dashboard ada navigation bar kependudukan yang berisi dropdown angka kelahiran dan angka kematian| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Input%20Agama.png) Pada Halaman agama dapat menginputkan data agama penduduk|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Input%20Pekerjaan.png) Pada Halaman pekerjaan dapat menginputkan data pekerjaan penduduk| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Warga.png) Pada Halaman warga dapat menginputkan data warga|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Input%20Pendidikan.png) Pada Halaman pendidikan dapat menginputkan data pendidikan penduduk| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Input%20Angka%20Kelahiran.png) Pada Halaman kelahiran dapat menginputkan data kelahiran penduduk|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Input%20Angka%20Kematian.png) Pada Halaman kematian dapat menginputkan data kematian penduduk| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Grafik%20Angka%20kelahiran.png) Pada Halaman grafik kelahiran dapat melihat data angka kelahiran|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Grafik%20Angka%20kematian.png) Pada Halaman grafik kematian dapat melihat data angka kematian| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Laporan.png) Pada Halaman laporan dapat melihat dan mendownload laporan penduduk|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Halaman%20Lupa%20Password.png) Pada halaman lupa password dapat mengganti password terlebih dahulu memasukkan username dan password sebelumnya| |



 **2.1.3 Antarmuka perangkat keras**

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/antarmuka%20perangkat%20keras%202.png)

Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat Lunak Manajemen Administrasi Data Kependudukan Desa Lohbener antara lain :

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
| Hapus | Digunakan untuk menghapus data |
| Edit | Digunakan untuk mengubah data |
| View | Digunakan untuk menampilkan data |
| Simpan | Digunakan untuk menyimpan data |
| Cetak | Digunakan untuk mencetak laporan |
| Deskripsi| Digunakan untuk menambah keterangan |

**2.1.8 Kebutuhan adaptasi**

Tidak ada
   
2.2 Spesifikasi Kebutuhan fungsional
----------
![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Use%20Case1.png)
   
**2.2.1 Teknisi Login

Use Case: ogin
Diagram 


Diagram : 
![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/use%20case%20login%20kepdes.png)

Deskripsi Singkat Teknisi melakukan login terlebih dahulu sebelum masuk ke tampilan home, Teknisi login menggunakan username dan password yang diberikan oleh admin. Deskripsi langkah-langkah :
Teknisi melakukan login dengan username dan password
Sistem melakukan validasi login
Bila sukses sistem akan mengarahkan ke halaman beranda
Bila gagal sistem akan menampilkan peringatan
Xref: Bagian 3.2.1, Login Teknisi

**2.2.2 Teknisi Menginput data maintenance lab

Use Case: Input data maintenance lab
Diagram 

Diagram: 
![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/use%20case%20kepdes%20generate%20laporan.png)

Deskripsi Singkat Sistem akan menampilkan form data Software dan Hardware teknisi dapat melakukan edit dan hapus sesuai kebutuhan. Deskripsi Langkah-langkah
Teknisi mengklik Data Software ataupun Hardware, lalu memilih bagian yang akan di edit 
Sistem akan menyimpan perubahan ke database dan menampilkan data yang telah diubah.
Teknisi bisa menghapus data yang salah atau tidak diperlukan lagi.
Xref: Bagian 3.2.3, Teknisi Mengelola Data maintenance lab

**2.2.3 Kepala Teknisi Login

Use Case: Login

Diagram :
![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/use%20case%20login.png)

Deskripsi Singkat Kepala Teknisi melakukan login terlebih dahulu sebelum masuk ke tampilan home, Teknisi login menggunakan username dan password yang diberikan oleh admin. Deskripsi langkah-langkah :
Kepala Teknisi melakukan login dengan username dan password
Sistem melakukan validasi login
Bila sukses sistem akan mengarahkan ke halaman beranda
Bila gagal sistem akan menampilkan peringatan
Xref: Bagian 3.2.1, Login Kepala Teknisi

      
**2.2.4 Kepala Teknisi Mengelola Data Maintenance Lab

Use Case: Mengelola Data Maintenance lab
Diagram 


Diagram:
![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/use%20case%20admin%20kelola%20data2.png)
      
Deskripsi Singkat Sistem akan menampilkan form data Software dan Hardware kepala teknisi dapat melakukan edit dan hapus sesuai kebutuhan. Deskripsi Langkah-langkah
Kepala Teknisi mengklik Data Software maupun Hardware, lalu memilih bagian yang akan di edit 
Sistem akan menyimpan perubahan ke database dan menampilkan data yang telah diubah.
Kepala Teknisi bisa menghapus data yang salah atau tidak diperlukan lagi.
Xref: Bagian 3.2.3, Kepala Teknisi Mengelola Data maintenance lab

**2.2.5  Kepala Teknisi Melihat Data Maintenance Lab


Use Case: View Data Maintenance lab
Diagram 

Diagram:
![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/use%20case%20lihat%20data%20kependudukan.png)

Deskripsi Singkat Kepala Teknisi dapat melihat data maintenance lab setelah di inputkan. Deskripsi Langkah-langkah 
Sistem akan menampilkan data maintenance lab.
Kepala teknisi melihat data dan dapat mengedit atau menghapusnya.
Sistem menampilkan edit data maintenance lab
Kepala Teknisi mengedit data maintenance lab yang baru atau yang sudah ada
Sistem melakukan validasi jika data sudah ada maka muncul peringatan jika belum sistem akan menyimpan
Xref: Bagian 3.2.6, View data maintenance lab
  
**2.2.6 Kepala Teknisi Mencetak laporan

Use Case:  laporan
Diagram 

Diagram:
![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/use%20case%20admin%20generate%20laporan.png)

Deskripsi Singkat Sistem akan mengirimkan data maintenance dan yang lainnya ke fungsi laporan. Deskripsi Langkah-langkah
Sistem menampilkan laporan maintenance lab
Kepala teknisi memilih combobox tersebut dan klik tombol cetak
Sistem akan menampilkan hasil laporan.
Kepala Teknisi mencetak laporan
Xref: Bagian 3.2.7, Cetak Laporan


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
| Basic Path | 1. Teknisi mengisi form login dengan username dan password <br> 2. Kepala desa mengklik tombol login <br> 3. Sistem melakukan validasi login <br> 4. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 5. Bila gagal sistem akan menampilkan|peringatan |
| Alternative | Tidak ada |
| Post Condition | Teknisi dapat login dan mengakses aplikasi Sistem Informasi Maintenance Lab Komputer |
| Exception Push | Username dan password salah |

      
**3.2.2 Teknisi Menginput Data Maintenance Lab Komputer**

|  |  |
|--|--|
| Nama Fungsi | Menginput data |
| Xref | Bagian 2.2.2, Teknisi menginputkan data Maintenance Lab Komputer |
| Trigger | Membuka halaman Input Data |
| Precondition | Halaman input data |
| Basic Path | 1.Setelah login, teknisi membuka halaman maintenance lab komputer <br> 2.Teknisi menginputkan data Software dan Hardware  <br> 3. Menyimpan data yang telah diinputkan  <br> 4. Kembali ke halaman dashboard |
| Alternative | Tidak ada |
| Post Condition | Teknisi dapat menginputkan dan menyimpan inputan data |
| Exception Push | Tidak ada |

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


   
**3.2.3 Kepala Teknisi Login**
|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.1, Login Teknisi |
| Trigger | Membuka Aplikasi Sistem Informasi Maintenance Lab Komputer
| Precondition | Halaman Login|
| Basic Path | 1. Teknisi mengisi form login dengan username dan password <br> 2. Kepala desa mengklik tombol login <br> 3. Sistem melakukan validasi login <br> 4. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 5. Bila gagal sistem akan menampilkan|peringatan |
| Alternative | Tidak ada |
| Post Condition | Teknisi dapat login dan mengakses aplikasi Sistem Informasi Maintenance Lab Komputer |
| Exception Push | Username dan password salah |
   
**3.2.4 Kepala Teknisi Mengelola data maintenance lab**

|  |  |
|--|--|
| Nama Fungsi | Mengelola data maintenance lab |
| Xref | Bagian 2.2.3, Teknisi mengelola data maintenance lab |
| Trigger | Membuka Aplikasi Sistem Informasi Maintenance Lab Komputer |
| Precondition | Halaman Utama Teknisi |
| Basic Path | 1. Setelah login, kepala teknisi, membuka halaman Maintenance Lab komputer <br> 2. Setelah itu kepala teknisi melihat data yang sudah di olah dari teknisi bakal diolah lebih detail lagi <br> 3. Kepala teknisi mengirim data data yang terjadi di Maintenance Lab Komputer|
| Alternative | Tidak ada |
| Post Condition | Teknisi dapat menginputkan dan menyimpan inputan data  |
| Exception Push | Tidak ada |
   
**3.2.5 Kepala Teknisi Melihat Data Maintenance Lab Komputer**

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
   
**3.2.6 Kepala Teknisi Mencetak Laporan**
|  |  |
|--|--|
| Nama Fungsi |Mencetak Laporan|
| Xref | Bagian 2.2.7 Kepala Teknisi mencetak laporan data Maintenance Lab Komputer  |
| Trigger | Membuka halaman hasil laporan dari teknisi |
| Precondition | Halaman hasil laporan maintenance lab |
| Basic Path | 1. Setelah login Kepala Teknisi membuka halaman laporan dari maintenance  <br> 2. Kepala teknisi melihat halaman laporan  <br> 2. Setelah itu kepala teknisi mencetak laporan dari maintenance  |
| Alternative | Tidak ada  |
| Post Condition | |
| Exception Push | Tidak ada |

   
3.3 Struktur Detail Kebutuhan Non-Fungsional
----------
**3.3.1 Logika Struktur Data**
Struktur data logika pada sistem Aplikasi presensi menggunakan kehadiran terdapat struktur Database yang dijelaskan menggunakan ERD.

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/erd_proyek2.png)

**Tabel User**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_user| int | Nomer auto increment Id_user|
| Username | varchar | berisikan Nik untuk akses login user dan username untuk akses admin |
| Password | varchar | berisikan password untuk login admin dan user |
| level | varchar | untuk membedakan level saat login antara admin dan user

**Tabel Warga**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| NIK | varchar | nomer kependudukan|
| Nama | varchar | nomer kependudukan|
| jns_kelamin | varchar | Identifikasi jenis kelamin|
| Tgl_lahir | date | tanggal lahir peserta |
| Agama | varchar | Identifikasi agama |

**Tabel Pegawai**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pegawai| int | Nomer auto increment Id_bioadmin|
| Id_user| int | untuk mengambil username dan password admin pada tabel user|
| nik| varchar | nik admin|
| jabatan | varchar | mendefinisikan level user |
| tgl_masuk | date | awal jabatan|
| tgl_keluar | date | akhir jabatan|

**Tabel Kelahiran**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_kelahiran| int | Nomer auto increment Id_kelahiran|
| Id_warga| int | foreignt key tabel warga |
| tgl_lahir| date | tanggal lahir anak |
| jns_kelamin| varchar | jenis kelamin anak|
| ayah | varchar | nama ayah|
| ibu | varchar | nama ibu|
| tmp_lahir| varchar | tempat lahir anak |
| rt | int | nomor rt|
| rw | int | nomor rw|

**Tabel Kematian**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_kematian| int | Nomer auto increment Id_kematian|
| Id_warga| int | foreignt key tabel warga |
| tmp_kematian| varchar | tempat lahir anak |
| tgl_kematian| date | tanggal lahir anak |
| rt | int | nomor rt|
| rw | int | nomor rw|

**Tabel Pekerjaan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pekerjaan| int | Nomer auto increment Id_pekerjaan|
| Id_warga| int | foreignt key tabel warga |
| pekerjaan| varchar | pekerjaan masyarakat  |
| tgl_input | date | tanggal input pekerjaan |

**Tabel Pendidikan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pendidikan| int | Nomer auto increment Id_pendidikan|
| Id_warga| int | foreignt key tabel warga |
| pendidikan| varchar | pendidikan masyarakat  |
| tgl_masuk | date | tanggal masuk pendidikan |

**Tabel ktp**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_ktp| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| status_ktp| varchar | Identifikasi memiliki atau belum memiliki ktp |
| masa_berlaku | date | tanggal berlaku ktp |

**Tabel kk**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_kk| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| kepala_keluarga| varchar | nama kepala keluarga |
| no_kk | varchar | nomor kk |

**Tabel pindah**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pindah| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| tgl_pindah | date | tanggal akan pindah |
| ket | varchar | alamat pindah |

**Tabel datang**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_datang| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| tgl_datang | date | tanggal kedatangan |
| ket | varchar | alamat sebelum datang |

**Tabel pilih**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pilih| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| status_pilih | varchar | hak pilih |

**Tabel kawin**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_kawin| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| status_kawin | varchar | status warga |

**Tabel Laporan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_laporan| int | Nomer auto increment Id_laporan|
| Id_warga| int | foreignt key tabel warga |
| laporan | varchar | berisi laporan kependudukan |

**Tabel Agama**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_agama| int | Nomer auto increment Id_laporan|
| Id_warga| int | foreignt key tabel warga |
| agama| varchar | berisi agama penduduk |



