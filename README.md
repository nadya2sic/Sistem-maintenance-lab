<html>
<body>
<p align="center">
  <img src="https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/cover.png?raw=true" width="900" height="900"/ > 
<p align="center"><b>
</body>
</html>

**BAB I Pendahuluan**
----------
1.1 Tujuan
----------
Dokumen Software Requirement Spesification (SRS) merupakan dokumen spesifikasi perangkat lunak untuk membangun "Sistem Pengisian LogBook".Dokumen ini dibangun untuk memudahkan mahasiswa dalam mengisi logbook dan juga memudahkan kepala lab dan admin untuk melihat kondisi lab.


1.2   Lingkup
----------
Sistem Pengisian LogBook merupakan Sistem yang kami bangun untuk mempermudah kepala laboratorium dalam melihat kondisi laboratorium,memudahkan admin dalam melihat data-data nya dan juga memudahkan mahasiswa dalam mengisi logbook.

1.3 Akronim, singkatan, definisi

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
- https://media.neliti.com/media/publications/300316-aplikasi-sistem-monitoring-keadaan-kompu-f78261ed.pdf
- https://jsi.stikom-bali.ac.id/index.php/jsi/article/view/86
- IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software  Requirements Specifications. IEEE Computer Society, 1998. 1.5  Overview 
- _SRSExample-webapp.pdf_

1.5   Overview
----------
Bab selanjutnya yaitu menjelaskan sistem yang di terapkan pada aplikasi. Menjelaskan gambaran umum dari aplikasi, sistem interface aplikasi dan alur sistemnya. Bab terakhir menjelaskan tentang setiap fungsi yang digunakan secara teknisnya. Pada bab 2 dan 3 merupakan deskripsi dari aplikasi yang akan diterapkan pada aplikasi yang dibuat.

**BAB II Gambaran umum**
----------
Pada zaman era globalisasi perkembangan teknologi begitu sangat pesat, salah satunya ialah perkembangan teknologi di bidang software engineering dimana software engineering dapat digunakan dalam kehidupan sehari - hari .dalam studi kasus Proyek II ini kami menganalisis kebutuhan sekola dalam pengisian logbook kegiatan di Laboratorium. kasus yang kami peroleh yaitu Sistem Pengisian Logbook sekolah. Maka dari itu kami sebagai software engineering merancang sebuah sistem sesuai dengan kebutuhan Kepala Laboratorium dan admin dengan menerapkan Sistem Pengisian Logbook Kampus. Sehingga memudahkan Mahasiswa mengisi logbook dan Memudahkan pemantauan kegiatan yang dilakukan di Laboratorium. Software yang kami buat ini berbasis website dimana website sebagai admin Super Admin sebagai Kepala Laboratorium. Sistem yang kami buat di dalamnya terdapat logbook, laporan(untuk Kepala Laboratorium). Berikut akan kami jelaskan sistem software kami, siswa fungsi utama yaitu :
* Input Nama
* Input Kelas
* Input Guru
* Input Matkul
* Input Kondisi Peralatan Lab

Berikut ini fungsi Admin:

* View Data Logbook
* Input Laporan Kerusakan

Berikut ini fungsi Super Admin:

* Input Data Lab
* Input Data User
* Edit Data Lab
* Delete Data Lab
* View Data Lab
* Cetak Laporan

2.1   Perspektif produk
----------
Sistem LogBook adalah sebuah sistem untuk mengisi logbook yang diaplikasikan pada website.Terdapat 3 jenis yaitu Kepala Laboratorium sebagai SuperAdmin, Admin dan Mahasiswa sebagai User.Pengelolaan data dikelola oleh Kepala Laboratorium pada website,Admin hanya bisa mengisi dan melihat data-data logbook dan siswa hanya bisa mengisi logbook.

**2.1.1 Antarmuka sistem**

![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/use%20case%202.png?raw=true)

Sistem aplikasi Maintenance Labor Komputer memiliki 2 user yaitu Kepala Teknisi dan Teknisi. Kepala Teknisi mempunyai fungsi yaitu melakukan view Data Maintanance Lab, serta bisa melakukan Login ke sistem. Teknisi bertugas untuk menginput dan mengelola data, supaya data bisa di akses oleh Kepala Teknisi.


**2.1.2 Antarmuka pengguna**

   - **Mockup Admin ( Website )**

|  |  |
|--|--|
| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Projek%20Framework_page-0001.jpg?raw=true) Pada halaman login user diminta untuk mengisi username dan password yang telah diberikan.| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/WhatsApp%20Image%202023-11-08%20at%2023.56.51.jpg?raw=true) Pada Dashboard Teknisi terdapat isi data maintenance.|
| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/2.jpg?raw=true) Pada halaman Lab Komputer terdapat Lab A, Lab B, Lab C, dan Lab D. | ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/3.jpg?raw=true) Pada Halaman Lab Komputer tadi, jika di klik salah satu Lab nya, maka akan menampilkan susunan komputer.|
| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/4.jpg?raw=true) Pada Halaman Komputer terdapat pilihan ingin menginputkan data Software atau hardware| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/5.jpg?raw=true) Pada Halaman Software akan muncul jika kita memilih software. Terdapat Windows, Aplikasi dan Anti-Virus yang harus dicek dan diberi ceklis setelah diperiksa. Jika tidak dalam keadaan bagus, maka harus memberi keterangan apa yang tidak bagus.|
| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/6.jpg?raw=true) Pada Halaman Hardware terdapat Monitor, PC, Keyboard dan Mouse yang harus diperiksa oleh teknisi dan diberi ceklis setelahnya. Jika dalam keadaan tidak bagus, harus menginputkan keterangan.| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/7.jpg?raw=true) Pada Halaman ini akan muncul jika teknisi menekan tombol simpan setelah menginputkan data.| 

![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/siswaisifrom2.jpg?raw=true) Pada Halaman siswa mengisi form pengajuan..|
![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Projek%20Framework%20(4)_page-0004.jpg?raw=true)  Pada halaman ini siswa mengisi keterangan apa saja kerusakan yang terjadi.|


 **2.1.3 Antarmuka perangkat keras**

![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/antar%20perangkat%20keras.jpg?raw=true)

Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat Lunak Sistem LogBook Laboratorium antara lain :

PC / Laptop untuk menjalankan Aplikasi ini admin membutuhkan sebuah PC yang menggunakan OS Windows,Linux, atau MAC dan sudah terinstall browser.

**2.1.4 Antarmuka perangkat lunak**

Tidak ada

**2.1.5 Antarmuka Komunikasi**

Antarmuka komunikasi yang digunakan untuk mengoperasikan Perangkat Lunak Sistem Logbook SMK 1 PEKANBARU antara lain :

1.  Kabel Lan UTP RJ45 

2. Modem 

3. Wifi


**2.1.6 Batasan memori**

Tidak ada

**2.1.7 Operasi-operasi**

| Operasi | Fungsi |
| ------ | ------ |
| Login | Digunakan untuk mengakses aplikasi |
| Input Data | Digunakan untuk memasukkan data-data logbook |
| Kembali | Digunakan untuk kembali ke halaman sebelumnya |
| hapus | Digunakan untuk menghapus data |
| Edit | Digunakan untuk mengubah data |
| View | Digunakan untuk menampilkan data |
| Simpan | Digunakan untuk menyimpan data |
| Cetak | Digunakan untuk mencetak laporan |

**2.1.8 Kebutuhan adaptasi**

Tidak ada
   
2.2 Spesifikasi Kebutuhan fungsional
----------
![](![image](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/e2a24a34a755a0494cd8d703905ad830a9e3cff7/UseCaseDiagram2.jpg)

**2.2.1 Kepala Laboratorium Login**

Use Case: Login <br>
Diagram : 
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/e9f3dc86e44e5200cd6808327bf92e87cd3f243c/Screenshot%202023-12-04%20141536.png)

Deskripsi singkat Kepala Laboratorium melakukan login sebelum masuk ke tampilan home.
Deskripsi Langkah-Langkah:

1. Kepala Laboratorium melakukan login <br>
2. Sistem melakukan validasi <br>
3. Bila validasi berhasil akan mengarahkan ke halaman beranda<br>
4. Bila gagal sistem akan menampilkan peringatan<br>

**2.2.2 Admin melakukan Login**

Use Case: login<br>
Diagram: 
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/f9cd138f17b34bf10c2b83aa7e06faa38e14089d/Screenshot%202023-12-04%20141547.png)

Deskripsi singkat Admin melakukan login sebelum masuk ke tampilan home.
Deskripsi Langkah-Langkah:

1. Admin melakukan login
2. Sistem melakukan validasi
3. Bila validasi berhasil akan mengarahkan ke halaman beranda
4. Bila gagal sistem akan menampilkan peringatan

**2.2.3 siswa melakukan Login**

Use case : login<br>
Diagram : 
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/f9cd138f17b34bf10c2b83aa7e06faa38e14089d/Screenshot%202023-12-04%20141521.png)

Deskripsi singkat siswa melakukan login sebelum masuk ke tampilan home.
Deskripsi Langkah-Langkah:

1. Mahasiswa melakukan login
2. Sistem melakukan validasi
3. Bila validasi berhasil akan mengarahkan ke halaman beranda
4. Bila gagal sistem akan menampilkan peringatan


**2.2.4 Kepala Laboratorium Mengelola User**

Use Case: Mengelola User<br>

Diagram :
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/4eb6b3b8028f443678f711c06cc21aaf2e8bc4cc/Screenshot%202023-12-04%20143125.png)

Deskripsi singkat Kepala Lab mengelola user.
Deskripsi langkah-langkah:
1.Kepala Lab mengklik manajemen user,lalu kepala lab bisa melihat user,menghapus user,menambah user dan mengedit user <br>
2.Sistem akan menyimpan data user dan akan menampilkan data user yang dipilih <br>
3.Kepala Lab bisa menghapus hak akses user<br>

      
**2.2.5  Kepala Laboratorium Mengelola Dashboard**

Use Case: Dashboard<br>
Diagram:
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/4eb6b3b8028f443678f711c06cc21aaf2e8bc4cc/Screenshot%202023-12-04%20143237.png)
      
Deskripsi singkat Kepala Laboratorium mengelola Dashboard.
Deskripsi langkah-langkah:
1.Kepala lab masuk ke halaman dashboard SuperAdmin  <br>
2.Sistem menampilkan halaman dashboard SuperAdmin <br>
3.Kepala lab dapat Melihat data dan dapat menambah,mengedit atau menghapus data.<br>
4.Sistem melakukan validasi jika data sudah ada.<br>

**2.2.6   Kepala Laboratorium Mencetak Laporan**

Use Case: laporan<br>
Diagram:
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/4eb6b3b8028f443678f711c06cc21aaf2e8bc4cc/Screenshot%202023-12-04%20143424.png)

Deskripsi singkat Kepala Laboratorium mencetak laporan
Deskripsi langkah-langkah:
1.Kepala Lab masuk ke halaman laporan laboratorium<br>
2.Sistem menampilkan halaman laporan laboratorium dan menampilkan hasil laporan<br>
3.Kepala Laboratorium mencetak laporan<br>

**2.2.7 KKepala Laboratorium Mengelola LogBook**

Use Case: Mengelola logbook<br>
Diagram:
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/4eb6b3b8028f443678f711c06cc21aaf2e8bc4cc/Screenshot%202023-12-04%20143554.png)

Deskripsi Singkat Sistem akan mengirimkan data maintenance dan yang lainnya ke fungsi laporan. <br>
Deskripsi Langkah-langkah:
<br>
1. Sistem menampilkan laporan maintenance lab.<br>
2. Kepala teknisi memilih combobox tersebut dan klik tombol cetak.<br>
3. Sistem akan menampilkan hasil laporan.<br>
4. Kepala Teknisi mencetak laporan.<br>

Xref: Bagian 3.2.7, Cetak Laporan
<br>

**2.2.8 Admin mengelola logbook**

Use Case: Mengelola LogBook <br>
Diagram : 
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/4eb6b3b8028f443678f711c06cc21aaf2e8bc4cc/Screenshot%202023-12-04%20143659.png)

Deskripsi singkat Dosen AIL mengelola logbook
Deskripsi langkah-langkah:

1.Admin masuk ke halaman admin <br>
2.Sistem menampilkan halaman admin<br>
3.Admin mengisi logbook dan melihat data logbook<br>

**2.2.9 siswa mengisi logbook**

Use Case: Mengisi LogBook <br>
Diagram : 
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/4eb6b3b8028f443678f711c06cc21aaf2e8bc4cc/Screenshot%202023-12-04%20143727.png)

Deskripsi singkat mahasiswa mengisi logbook
Deskripsi langkah-langkah:
1.siswa masuk ke halaman user<br>
2.Sistem menampilkan halaman user<br>
3.siswa mengisi data logbook dan mengirim atau menyimpan data ke sistem logbook.<br>
4.Sistem akan menyimpan data logbook yang telah di isi.<br>

2.3   Spesifikasi Kebutuhan non-fungsional
----------
- Tabel Kebutuhan Non-Fungsional 

   | No | Deskripsi |
   | ------ | ------ |
   | 1 | Semua interface dan fungsi menggunakan Bahasa Indonesia |
   | 2 | Perangkat Lunak dapat dipakai di semua platform OS ( Admin,Kepala Laboratorium dan siswa)
 
2.4   Karakteristik pengguna
----------
Karakteristik pengguna dari perangkat lunak ini adalah pengguna langsung berinteraksi dengan sistem tanpa harus dihubungkan dengan hak akses atau level autentikasi. 

2.5   Batasan-batasan
----------
Perangkat lunak web hanya dapat digunakan di Windows (7,8,10), dan karena waktu pengembangan yang singkat, mungkin tidak semua fungsi dapat digunakan.

2.6   Asumsi-asumsi
----------
Tidak ada

2.7   Kebutuhan Penyeimbang
----------
Tidak ada


BAB III Requirement specification
----------
3.1 Persyaratan Antarmuka Eksternal
----------
Salah satu cara mengakases aplikasi ini yaitu dengan hak akses yang di berikan oleh Kepala Laboratorium, login melalui aplikasi ini dengan mencantumkan username kemudian sistem akan mencocokkan username Kepala Laboratorium dan Laboratorium. Setelah login berhasil Kepala Laboratorium dapat melihat kegiatan yang dilakukan di laboratorium dan dapat mencetak laporan perminggu dan perbulan.

      
3.2 Functional Requirement
----------
Logika Struktur terdapat pada bagian 3.3.1
      
**3.2.1Kepala Laboratorium Login**

|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.1, Login Kepala Lab |
| Trigger | Membuka aplikasi Sistem Pengisian LogBook  Lab |
| Precondition | Halaman Login|
| Basic Path | 1. Kepala Laboratorium mengisi form login dengan username dan password <br> 2. Kepala Laboratorium mengklik tombol login<br> 3. Sistem melakukan validasi login <br> 4. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 5. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Kepala Laboratorium dapat login dan mengakses aplikasi MSistem Pengisian LogBook |
| Exception Push | Username dan password salah |

<br>

**3.2.2 Admin Login**

|  |  |
|--|--|
| Nama Fungsi | Menginput data |
| Xref | Bagian 2.2.2 Login admin |
| Trigger | Membuka aplikasi Sistem Pengisian LogBook    Lab |
| Precondition | Halaman login Admin |
| Basic Path | 1., Admin melakukan login dengan username dan password <br> 2. Sistem melakukan validasi login  <br> 3. Bila sukses sistem akan mengarahkan ke halaman beranda<br> 4. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Admin berhasil login dan mengakses Sistem Pengisian LogBook |
| Exception Push | Username dan password salah |

<br>

**3.2.3 siswa login**

|  |  |
|--|--|
| Nama Fungsi | login|
| Xref | Membuka aplikasi Sistem Pengisian LogBook Lab |
| Trigger | Membuka Aplikasi Sistem Informasi Maintenance Lab Komputer |
| Precondition | Halaman login |
| Basic Path | 1. Mahasiswa mengisi form login dengan username dan password<br> 2. Mahasiswa mengklik tombol login <br> 3. Sistem melakukan validasi login <br> 4. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 5.  |Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | siswa dapat login dan mengakses aplikasi Sistem Pengisian LogBook|
| Exception Push | Username dan password salah |

<br>
   
**3.2.4 Kepala Laboratorium Mengelola User**
|  |  |
|--|--|
| Nama Fungsi | MEngelola User|
| Xref | Bagian 2.2.4, Mengelola User |
| Trigger |Membuka aplikasi Sistem LogBook Lab |
| Precondition | Halaman utama Kepala Laboratorium|
| Basic Path | 1. Sistem menampilkan form.<br> 2. Kepala Laboratorium mengklik manajemen user, lalu kepala lab bisa melihat user, menghapus user,menambah user dan mengedit <br> 3. Sistem akan menyimpan data user ke database |
| Post Condition |Halaman user |
| Exception Push |Tidak ada koneksi, data user ke database |

<br>

**3.2.5 Kepala Laboratorium Mengelola Dashboard**

|  |  |
|--|--|
| Nama Fungsi |Mengelola Dashboard |
| Xref |Bagian 2.2.5, Mengelola Dashboard |
| Trigger | Membuka Sistem Pengisian LogBook Lab |
| Precondition | Halaman utama Kepala Laboratorium |
| Basic Path | 1. istem menampilkan halaman dashboard SuperAdmin <br> 2. Kepala lab  dapat melihat data dan menambah, mengedit atau menghapus data <br> 3. Sistem melakukan validasi jika data sudah ada|
| Post Condition | Halaman SuperAdmin |
| Exception Push |Tidak ada koneksi, data belum diinput |
   
**3.2.6 Kepala Laboratorium Mencetak Laporan**

|  |  |
|--|--|
| Nama Fungsi | laporan |
| Xref | Bagian 2.2.6 Cetak Laporan |
| Trigger |Membuka aplikasi Sistem Pengisian LogBook Lab |
| Precondition | halaman utama Kepala Lab|
| Basic Path | 1. Kepala Lab mengklik tombol laporan <br> 2. Sistem menampilkan halaman laporan Laboratorium dan menampilkan hasil Laporan <br> 3. Kepala Laboratorium mencetak laporan |
| Alternative | Tidak ada |
| Post Condition |Halaman Laporan|
| Exception Push | Tidak ada koneksi, data belum diinput |
   
**3.2.7 Kepala Laboratorium Mengelola LogBook**
|  |  |
|--|--|
| Nama Fungsi |laporan|
| Xref | Bagian 2.2.7 Mengelola LogBook  |
| Trigger | Membuka aplikasi Sistem Pengisian LogBook Lab|
| Precondition | halaman utama Kepala Lab|
| Basic Path | 1. Sistem menampilkan halaman SuperAdmin  <br> 2.Kepala Laboratorium melihat data logbook |  
| Post Condition | Halaman Laporan|
| Exception Push | Tidak ada koneksi, data belum diinput |


**3.2.8. Admin Mengelola LogBook**
|  |  |
|--|--|
| Nama Fungsi | Laporan |
| Xref | Bagian 2.2.8 Mengelola LogBook|
| Trigger | Membuka aplikasi Sistem LogBook Lab |
| Precondition | halaman utama  Admin|
| Basic Path | 1.Sistem menampilkan halaman Admin <br> 2. Admin melihat data logbook |
| Post Condition | Halaman Laporan |
| Exception Push | Tidak ada koneksi, data belum diinput|


**3.2.9.Mahasiswa Mengisi LogBook**
|  |  |
|--|--|
| Nama Fungsi |laporan|
| Xref | Bagian 2.2.9 Mengisi LogBook | 
| Trigger | Membuka aplikasi Sistem Pengisian LogBook Lab |
| Precondition | halaman utama  user |
| Basic Path |  1.Sistem menampilkan halaman user <br> 2 mahasiswa mengisi data logbook dan mengirim atau menyimpan data ke sistem logbook<br> 3. Sistem akan menyimpan data logbook yang telah diisi |
| Post Condition | Halaman Laporan |
| Exception Push |Tidak ada koneksi, data belum diinput |

   
3.3 Struktur Detail Kebutuhan Non-Fungsional
----------
**3.3.1 Logika Struktur Data**
Struktur data logika pada Sistem Aplikasi Logbook dijelaskan menggunakan ERD.

![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/erd%203.png?raw=true)

**Tabel User**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_user| int | Nomer auto increment Id_user|
| Username | varchar | berisikan username untuk akses login user dan username untuk akses admin |
| Password | varchar | berisikan password untuk login admin dan user |
| nama | varchar | berisikan nama dari user yang masuk |
| no_hp | number | berisikan no_hp dari user yang masuk|
| roles | varchar | berisikan user yang memiliki akses yang berbeda |

**Tabel Pengaduan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pengaduan | int | Nomer auto increment Id_pengaduan |
| Id_user| int | untuk mengambil username, password dan roles admin pada tabel user |
| pc | varchar | berisikan pc dari siswa yang melakukan pengaduan |
| lab | varchar | berisikan lab dari siswa yang melakukan pengaduan |
| nama | varchar | berisikan nama dari siswa yang melakukan pengaduan |
| kelas | varchar | berisikan kelas dari siswa yang melakukan pengaduan |
| jam | datetime | berisikan jam kelas dari siswa yang melakukan pengaduan |
| mata_pelajaran | varchar | berisikan mata pelajaran dari siswa yang melakukan pengaduan |
| keluhan | teks | berisikan keluhan dari siswa yang melakukan pengaduan |

**Tabel Perangkat**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_perangkat | int | Nomer auto increment Id_perangkat|
| Id_Lab| int | foreignt key tabel lab |
| Id_Laporan| int | foreignt key tabel Laporan |
| nama | varchar | berisikan nama perangkat yang diinput |
| deskripsi | teks | berisikan deskripsi yang menjelaskan kondisi dari perangkat |

**Tabel Lab**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_Lab| int | Nomer auto increment Id_lab|
| Id_Laporan| int | foreignt key tabel Laporan |
| pic_lab | varchar | orang yang memeriksa lab |

**Tabel Laporan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_laporan| int | Nomer auto increment Id_laporan|
| Id_user| int | untuk mengambil username, password dan roles admin pada tabel user |
| catatan | teks | berisi laporan maintenance |

**Job Desc** <br>
**BAB 1 PENDHULUAN** <br>
1.1 Tujuan : Nurul <br>
1.2 Lingkup : Nadya <br>
1.3 Akronim, singkatan, definisi : Nadya <br>
1.4 Referensi : Nurul <br>
1.5 Overview : Nadya, Nurul, Octa <br>
**BAB 2 Gambaran Umum** <br>
2.1 Perspektif Produk : Nadya <br>
2.1.1 Antarmuka Sistem : Octa <br>
2.1.2 Antarmuka pengguna : Nurul <br>
2.1.3 Antarmuka perangkat keras : Nurul <br>
2.1.4 Antarmuka perangkat lunak : Nadya, Nurul, Octa <br>
2.1.5 Antarmuka Komunikasi : Nadya, Nurul, Octa <br>
2.1.6 Batasan memori : Nadya, Nurul, Octa <br>
2.1.7 Operasi-operas : Octa <br>
2.1.8 Kebutuhan adaptasi : Nadya, Nurul, Octa <br>
2.2 Spesifikasi Kebutuhan fungsional : Nurul <br>
2.3 Spesifikasi Kebutuhan non-fungsional : Nadya, Nurul, Octa <br>
2.4 Karakteristik pengguna : Nadya, Nurul, Octa <br>
2.5 Batasan-batasan : Nadya, Nurul, Octa <br>
2.6 Asumsi-asumsi : Nadya, Nurul, Octa <br>
2.7 Kebutuhan Penyeimbang : Nadya, Nurul, Octa <br>
**BAB 3 Requirement specification** <br>
3.1 Persyaratan Antarmuka Eksternal : Nadya, Nurul, Octa <br>
3.2 Functional Requirement : Nadya, Nurul, Octa <br>
3.3 Struktur Detail Kebutuhan Non-Fungsional : Octa <br>
FIGMA : Nurul <br>
GitHub : Nadya, Nurul, Octa <br>


