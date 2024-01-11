<html>
<body>
<p align="center">
  <img src="https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Cover.jpg?raw=true" width="900" height="1100"/ > 
<p align="center"><b>
</body>
</html>

**BAB I Pendahuluan**
----------
1.1 Tujuan
----------
Dokumen Software Requirement Spesification (SRS) merupakan dokumen spesifikasi perangkat lunak untuk membangun "Sistem Pengisian LogBook". Dokumen ini dibangun untuk memudahkan siswa dalam mengisi logbook dan juga memudahkan admin (kepala lab) untuk melihat kondisi lab.


1.2   Lingkup
----------
Sistem Pengisian LogBook merupakan Sistem yang kami bangun untuk mempermudah kepala laboratorium dalam melihat kondisi laboratorium, memudahkan admin dalam melihat data-data nya dan juga memudahkan siswa dalam mengisi logbook.

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
Pada zaman era globalisasi perkembangan teknologi sangat pesat, salah satunya ialah perkembangan teknologi di bidang software engineering. Dimana software engineering dapat digunakan dalam kehidupan sehari-hari. Dalam studi kasus ini kami menganalisis kebutuhan sekolah SMKN 1 Pekanbaru dalam pengisian logbook kegiatan di Laboratorium. Kasus yang kami peroleh yaitu Sistem Pengisian Logbook sekolah. Maka dari itu kami sebagai software engineering merancang sebuah sistem sesuai dengan kebutuhan Kepala Laboratorium (Admin) dengan menerapkan Sistem Pengisian Logbook Sekolah. Sehingga memudahkan siswa mengisi logbook dan Memudahkan pemantauan kegiatan yang dilakukan di Laboratorium. Software yang kami buat ini berbasis website, di dalamnya terdapat logbook yang dapat diisi oleh siswa dan guru yang mengajar serta laporan(untuk Kepala Laboratorium). Berikut akan kami jelaskan sistem software kami, siswa fungsi utama yaitu :
* Input Nama
* Input Kelas
* Input Guru
* Input Matkul
* Input Kondisi Peralatan Lab

Berikut ini fungsi Guru:

* View Data Logbook
* Input Laporan Kerusakan

Berikut ini fungsi Kepala Lab:

* Input Data Lab
* Input Data User
* Edit Data Lab
* Delete Data Lab
* View Data Lab


2.1   Perspektif produk
----------
Sistem LogBook adalah sebuah sistem untuk mengisi logbook yang diaplikasikan pada website. Terdapat 3 jenis yaitu Kepala Laboratorium sebagai Admin, Guru dan siswa sebagai User. Pengelolaan data dikelola oleh Admin pada website, Guru hanya bisa mengisi dan melihat data-data logbook dan siswa hanya bisa mengisi logbook.


**2.1.2 Antarmuka pengguna**

   - **Mockup Admin ( Website )**

|  |  |
|--|--|
| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(1).jpg?raw=true) Halaman Login untuk Admin.| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(2).jpg?raw=true) Halaman Dashboard Admin (Kepala Lab).|
| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(3).jpg?raw=true) Halaman untuk admin menambahkan user. | ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(4).jpg?raw=true) Apabila di klik Tambah User maka akan muncul tampilan ini untuk menambahkan user.|
| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(5).jpg?raw=true) Data berhasil ditambahkan. | ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(6).jpg?raw=true) Halaman untuk admin menginputkan lab yang ada. |
| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(7).jpg?raw=true) Lab berhasil diinputkan. | ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(8).jpg?raw=true) Halaman ini akan muncul saat diklik lab yang kita tambahkan sebelumnya, ini untuk menambahkan komputer yang ada di lab tersebut. | ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(9).jpg?raw=true) Data berhasil ditambahkan. | ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(10).jpg?raw=true) Halaman untuk maintenance komputer yang ada di lab. | ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(11).jpg?raw=true) Data berhasil disimpan. | ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(12).jpg?raw=true) Tampilan setelah maintenance, jika kondisi bagus maka akan berwarna hijau, jika tidak bagus akan berwarna merah. |
| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(13).jpg?raw=true) Apabila ingin menghapus Komputer. | ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(14).jpg?raw=true) Komputer berhasil dihapus. |
| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(15).jpg?raw=true) Halaman admin untuk melihat laporan kerusakan dari guru. | ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(16).jpg?raw=true) Tampilan apabila button view diklik. |
| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(17).jpg?raw=true) Halaman Login untuk Siswa dengan email dan pass yang sudah diberikan oleh admin. | ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(18).jpg?raw=true) Halaman Dashboard siswa. | ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(19).jpg?raw=true) Halaman Pengaduan siswa. | ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(20).jpg?raw=true) Halaman untuk siswa menginputkan pengaduan.|
| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(21).jpg?raw=true) Data berhasil disimpan. | ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(22).jpg?raw=true) Halaman Login Guru yang mana guru login menggunakan email dan pass yang telah diberikan oleh admin.|
| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(23).jpg?raw=true) Halaman Dashboard Guru. | ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(24).jpg?raw=true) Halam LogBook guru yang berisi pengaduan yang diinputkan oleh siswa. |
| ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(25).jpg?raw=true) Apabila button view diklik. | ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(26).jpg?raw=true) Halaman untuk menginputkan laporan kerusakan yang terjadi di lab oleh guru unutk kepala lab. | ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(27).jpg?raw=true) Data berhasil disimpan. | ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(28).jpg?raw=true) Halaman Laporan kerusakan yang berisi pengaduan dari siswa sebelumnya. | ![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/Antarmuka%20Pengguna/(29).jpg?raw=true) Apabila button view diklik. |


 **2.1.3 Antarmuka perangkat keras**

![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/AntarMukaHardware.png?raw=true)
Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat Lunak Sistem LogBook SMKN 1 antara lain :

PC / Laptop untuk menjalankan Aplikasi ini admin membutuhkan sebuah PC yang menggunakan OS Windows, Linux, atau MAC dan sudah terinstall browser.

**2.1.4 Antarmuka perangkat lunak**

Tidak ada

**2.1.5 Antarmuka Komunikasi**

Antarmuka komunikasi yang digunakan untuk mengoperasikan Perangkat Lunak Sistem Logbook SMK 1 Pekanbaru antara lain :

1. Kabel Lan UTP RJ45 

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


**2.1.8 Kebutuhan adaptasi**

Tidak ada
   
**2.2 Spesifikasi Kebutuhan Fungsional**
![image](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/2.2.png?raw=true) <br>
**2.2.1 Kepala Laboratorium Login**

Use Case : Login <br>
Diagram : <br>
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/e9f3dc86e44e5200cd6808327bf92e87cd3f243c/Screenshot%202023-12-04%20141536.png)

Deskripsi Langkah-Langkah:

1. Kepala Laboratorium melakukan login <br>
2. Sistem melakukan validasi <br>
3. Bila validasi berhasil akan mengarahkan ke halaman beranda<br>
4. Bila gagal sistem akan menampilkan peringatan<br>

**2.2.2 Guru melakukan Login**

Use Case : login<br>
Diagram : <br>
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/2.2.2.png?raw=true)

Deskripsi Langkah-Langkah:

1. Guru melakukan login
2. Sistem melakukan validasi
3. Bila validasi berhasil akan mengarahkan ke halaman beranda
4. Bila gagal sistem akan menampilkan peringatan

**2.2.3 Siswa melakukan Login**

Use case : login<br>
Diagram : <br>
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/b207b8453fb0a669f2b75f4211b5e18be5d4f0d5/Screenshot%202023-12-04%20152841.png)

Deskripsi Langkah-Langkah:

1. Siswa melakukan login
2. Sistem melakukan validasi
3. Bila validasi berhasil akan mengarahkan ke halaman beranda
4. Bila gagal sistem akan menampilkan peringatan


**2.2.4 Kepala Laboratorium Mengelola User**

Use Case : Mengelola User<br>

Diagram :<br>
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/4eb6b3b8028f443678f711c06cc21aaf2e8bc4cc/Screenshot%202023-12-04%20143125.png)

Deskripsi langkah-langkah: <br>
1.Kepala Lab mengklik manajemen user, lalu kepala lab bisa melihat, menghapus, menambah dan mengedit user <br>
2.Sistem akan menyimpan data user dan akan menampilkan data user yang dipilih <br>
3.Kepala Lab bisa menghapus hak akses user<br>

      
**2.2.5  Kepala Laboratorium Mengelola Dashboard**

Use Case : Dashboard<br>
Diagram : <br>
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/4eb6b3b8028f443678f711c06cc21aaf2e8bc4cc/Screenshot%202023-12-04%20143237.png)
      
Deskripsi langkah-langkah: <br>
1.Kepala lab masuk ke halaman dashboard Admin  <br>
2.Sistem menampilkan halaman dashboard Admin <br>
3.Kepala lab dapat Melihat data dan dapat menambah,mengedit atau menghapus data.<br>
4.Sistem melakukan validasi jika data sudah ada.<br>

**2.2.6   Kepala Laboratorium Mencetak Laporan**

Use Case : laporan<br>
Diagram :<br>
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/4eb6b3b8028f443678f711c06cc21aaf2e8bc4cc/Screenshot%202023-12-04%20143424.png)

Deskripsi langkah-langkah: <br>
1.Kepala Lab masuk ke halaman laporan laboratorium<br>
2.Sistem menampilkan halaman laporan laboratorium dan menampilkan hasil laporan<br>
3.Kepala Laboratorium mencetak laporan<br>

**2.2.7 Kepala Laboratorium Mengelola LogBook**

Use Case : Mengelola logbook<br>
Diagram : <br>
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/4eb6b3b8028f443678f711c06cc21aaf2e8bc4cc/Screenshot%202023-12-04%20143554.png)

Deskripsi Langkah-langkah:
<br>
1. Kepala Laboratorium masuk ke halaman admin.<br>
2. Sistem menampilkan halaman Admin.<br>
3. Kepala Laboratorium memilih menu laporan serta pengaduan
4. Sistem akan menampilkan halaman.<br>
5. Kepala Laboratorium melihat laporan serta pengaduan yang masuk.<br>

**2.2.8 Guru mengelola logbook**

Use Case : Mengelola LogBook <br>
Diagram : <br>
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/2.2.8.png?raw=true)

Deskripsi langkah-langkah:

1. Guru masuk ke halaman utama <br>
2. Sistem menampilkan halaman utama<br>
3. Guru mengisi logbook dan melihat data logbook<br>

**2.2.9 Siswa mengisi logbook**

Use Case : Mengisi LogBook <br>
Diagram : <br>
![](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/2.2.9.png?raw=true)

Deskripsi langkah-langkah:
1. Siswa masuk ke halaman user<br>
2. Sistem menampilkan halaman user<br>
3. Siswa mengisi data logbook dan mengirim atau menyimpan data ke sistem logbook.<br>
4. Sistem akan menyimpan data logbook yang telah di isi.<br>
5. Siswa mengisi pengaduan jika ada kesalahan atau kerusakan yang terjadi.<br>
6. Sistem akan menyimpan data pengaduan jika ada yang di isi.<br>

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
Perangkat lunak web hanya dapat digunakan di Windows (7,8,10,11), dan karena waktu pengembangan yang singkat, mungkin tidak semua fungsi dapat digunakan.

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
Salah satu cara mengakases aplikasi ini yaitu dengan hak akses yang di berikan oleh Kepala Laboratorium, login melalui aplikasi ini dengan mencantumkan email kemudian sistem akan mencocokkan email Kepala Laboratorium dan Laboratorium. Setelah login berhasil Kepala Laboratorium dapat melihat kegiatan yang dilakukan di laboratorium dan dapat mencetak laporan.
      
3.2 Functional Requirement
----------
Logika Struktur terdapat pada bagian 3.3.1
      
**3.2.1 Kepala Laboratorium Login**

|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.1, Login Kepala Lab |
| Trigger | Membuka aplikasi Sistem Pengisian LogBook Lab |
| Precondition | Halaman Login|
| Basic Path | 1. Kepala Laboratorium mengisi form login dengan email dan password <br> 2. Kepala Laboratorium mengklik tombol login<br> 3. Sistem melakukan validasi login <br> 4. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 5. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Kepala Laboratorium dapat login dan mengakses aplikasi Sistem Pengisian LogBook |
| Exception Push | Username dan password salah |

<br>

**3.2.2 Guru Login**

|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.2 Login guru |
| Trigger | Membuka aplikasi Sistem Pengisian LogBook Lab |
| Precondition | Halaman login Guru |
| Basic Path | 1. Guru melakukan login dengan email dan password <br> 2. Sistem melakukan validasi login  <br> 3. Bila sukses sistem akan mengarahkan ke halaman beranda<br> 4. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Guru berhasil login dan mengakses Sistem Pengisian LogBook |
| Exception Push | Username dan password salah |

<br>

**3.2.3 Siswa login**

|  |  |
|--|--|
| Nama Fungsi | Login|
| Xref | Bagian 2.2.3 Siswa Login |
| Trigger | Membuka Aplikasi Sistem LogBook Laboratorium |
| Precondition | Halaman login |
| Basic Path | 1. Siswa mengisi form login dengan email dan password masing-masing<br> 2. Siswa mengklik tombol login <br> 3. Sistem melakukan validasi login <br> 4. Bila sukses sistem akan mengarahkan ke halaman beranda <br>  |Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Siswa dapat login dan mengakses aplikasi Sistem Pengisian LogBook|
| Exception Push | Username dan password salah |

<br>
   
**3.2.4 Kepala Laboratorium Mengelola User**
|  |  |
|--|--|
| Nama Fungsi | Mengelola User|
| Xref | Bagian 2.2.4 Mengelola User |
| Trigger |Membuka aplikasi Sistem LogBook |
| Precondition | Halaman utama Kepala Laboratorium|
| Basic Path | 1. Sistem menampilkan form.<br> 2. Kepala Laboratorium mengklik manajemen user, lalu kepala lab bisa melihat user, menghapus user,menambah user dan mengedit <br> 3. Sistem akan menyimpan data user ke database |
| Post Condition |Halaman user |
| Exception Push |Tidak ada koneksi, data user ke database |

<br>

**3.2.5 Kepala Laboratorium Mengelola Dashboard**

|  |  |
|--|--|
| Nama Fungsi |Mengelola Dashboard |
| Xref |Bagian 2.2.5 Mengelola Dashboard |
| Trigger | Membuka Sistem Pengisian LogBook Laboratorium |
| Precondition | Halaman utama Kepala Laboratorium |
| Basic Path | 1. Sistem menampilkan halaman dashboard Admin <br> 2. Kepala laboratorium dapat melihat data dan menambah, mengedit atau menghapus data <br> 3. Sistem melakukan validasi jika data sudah ada|
| Post Condition | Halaman Admin |
| Exception Push |Tidak ada koneksi, data belum diinput |
   
**3.2.6 Kepala Laboratorium Mencetak Laporan**

|  |  |
|--|--|
| Nama Fungsi | laporan |
| Xref | Bagian 2.2.6 Cetak Laporan |
| Trigger |Membuka aplikasi Sistem Pengisian LogBook Lab |
| Precondition | halaman utama Kepala Lab|
| Basic Path | 1. Kepala Laboratorium mengklik menu laporan <br> 2. Sistem menampilkan halaman laporan Laboratorium dan menampilkan hasil Laporan <br> 3. Kepala Laboratorium mencetak laporan |
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
| Basic Path | 1. Sistem menampilkan halaman Admin  <br> 2.Kepala Laboratorium melihat data logbook<br> 3.Kepala laboratorium melihat menu pengaduan<br> |  
| Post Condition | Halaman Laporan dan Pengaduan|
| Exception Push | Tidak ada koneksi, data belum diinput |


**3.2.8. Guru Mengelola LogBook**
|  |  |
|--|--|
| Nama Fungsi | Laporan |
| Xref | Bagian 2.2.8 Mengelola LogBook|
| Trigger | Membuka aplikasi Sistem LogBook Lab |
| Precondition | halaman utama Guru|
| Basic Path | 1. Sistem menampilkan halaman Guru <br> 2. Guru melihat data logbook |
| Post Condition | Halaman Laporan |
| Exception Push | Tidak ada koneksi, data belum diinput|


**3.2.9. Siswa Mengisi LogBook**
|  |  |
|--|--|
| Nama Fungsi |Laporan|
| Xref | Bagian 2.2.9 Mengisi LogBook | 
| Trigger | Membuka aplikasi Sistem Pengisian LogBook Lab |
| Precondition | Halaman utama user |
| Basic Path |  1. Sistem menampilkan halaman user <br> 2. Siswa mengisi data logbook dan mengirim atau menyimpan data ke sistem logbook<br> 3. Sistem akan menyimpan data logbook yang telah diisi<br> 4. Siswa mengisi form pengaduan jika ada kerusakan yang dialami<br> |
| Post Condition | Halaman Laporan |
| Exception Push |Tidak ada koneksi, data belum diinput |

   
3.3 Struktur Detail Kebutuhan Non-Fungsional
----------
**3.3.1 Logika Struktur Data**
Struktur data logika pada Sistem Aplikasi Logbook dijelaskan menggunakan ERD.

![enter image description here](https://github.com/nadya2sic/Sistem-maintenance-lab/blob/main/Image%20SRS/ERD.png?raw=true)

**Tabel User**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_user| int | Nomer auto increment Id_user|
| nama | varchar | berisikan nama untuk akses login |
| Username | varchar | berisikan username untuk akses login |
| email | varchar | berisikan email untuk akses login |
| Password | varchar | berisikan password untuk login |
| roles | varchar | berisikan user yang memiliki akses yang berbeda |

**Tabel Pengaduan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pengaduan | varchar | Nomer auto increment Id_pengaduan |
| nama_lab | varchar | berisikan nama lab yang digunakan |
| nama_komputer | varchar | berisikan no komputer yang digunakan |
| nama | varchar | berisikan nama dari siswa yang melakukan pengaduan |
| kelas | varchar | berisikan kelas dari siswa yang melakukan pengaduan |
| mata_pelajaran | varchar | berisikan mata pelajaran |
| keterangan | teks | berisikan keluhan dari siswa yang melakukan pengaduan |
| jam | time | berisikan jam saat pengaduan dibuat|


**Tabel LogBook**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id | varchar | Nomer auto increment id_logkegiatan|
| tanggal | date | berisikan tanggal kelas dari siswa |
| pc | varchar | berisikan pc dari siswa yang menggunakan |
| nama | varchar | berisikan nama dari siswa |
| kelas | varchar | berisikan kelas dari siswa |
| mata pelajaran | varchar | berisikan mata pelajaran yang sedang berlangsung |
| jam masuk | time | berisikan jam masuk siswa saat menggunakan lab |
| jam keluar | time | berisikan jam keluar siswa setelah siap menggunakan lab |

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
GitHub : Nadya, Nurul, Octa <br>


