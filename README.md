# RPL

<h2>1.	Rekayasa Perangkat Lunak (Software Engineering):</h2>

Penjelasan: 
Rekayasa Perangkat Lunak adalah disiplin ilmu yang berkaitan dengan pengembangan perangkat lunak (software) yang melibatkan proses perencanaan, perancangan, pengembangan, pengujian, dan pemeliharaan perangkat lunak. Tujuannya adalah untuk menghasilkan perangkat lunak yang berkualitas, efisien, dan dapat diandalkan.
Sejarah: Sejarah rekayasa perangkat lunak dimulai pada tahun 1960-an ketika pemahaman akan kompleksitas perangkat lunak mulai berkembang. Metodologi pengembangan perangkat lunak seperti Waterfall, V-Model, dan Agile telah berkembang seiring waktu.
Metodenya: Terdapat berbagai metode dalam rekayasa perangkat lunak, termasuk Waterfall, Agile, Scrum, dan lainnya. Metode tersebut memandu langkah-langkah yang harus diikuti dalam pengembangan perangkat lunak.
Perkembangannya: Perkembangan rekayasa perangkat lunak melibatkan inovasi teknologi, seperti penggunaan bahasa pemrograman yang lebih canggih, paradigma pengembangan yang lebih modern seperti pengembangan berbasis komponen, dan fokus pada aspek keamanan perangkat lunak. Selain itu, praktik DevOps dan Continuous Integration/Continuous Deployment (CI/CD) juga menjadi bagian penting dalam pengembangan perangkat lunak.

<h2>2.	Analisis dan Perancangan Sistem dengan Pendekatan Terstruktur:</h2>
Analisis: Dalam pendekatan terstruktur, analisis sistem melibatkan pemahaman mendalam tentang masalah yang ingin dipecahkan. Ini melibatkan identifikasi kebutuhan, pengumpulan data, pemodelan proses, dan dokumentasi persyaratan.

Perancangan: Perancangan sistem dengan pendekatan terstruktur melibatkan pembuatan diagram alur data (DFD), tabel-tabel data, dan struktur pemrograman yang terdiri dari modul-modul yang terdefinisi dengan baik.

<h2>3.	Analisis dan Perancangan Sistem dengan Pendekatan Berorientasi Objek (OO):</h2>

Analisis: Dalam pendekatan berorientasi objek, analisis sistem berfokus pada identifikasi objek-objek yang mewakili entitas dunia nyata dan hubungan antara objek-objek tersebut. Ini melibatkan pemodelan kelas, atribut, dan metode.

Perancangan: Perancangan sistem berorientasi objek melibatkan pembuatan diagram kelas, diagram sekuen, dan diagram aktivitas. Kelas-kelas dan objek-objek yang diidentifikasi dalam analisis digunakan untuk merancang struktur sistem.

<h2>4.	Unified Modeling Language (UML):</h2>

Penjelasan: UML adalah bahasa pemodelan visual yang digunakan dalam rekayasa perangkat lunak. Ini memungkinkan para pengembang untuk menggambarkan, merancang, dan berkomunikasi mengenai struktur dan perilaku sistem perangkat lunak. UML mencakup berbagai jenis diagram, termasuk diagram kelas, diagram sekuen, diagram aktivitas, dan lainnya.

<h2>5.	Program Desain:</h2>

Penjelasan: Program desain adalah proses merinci bagaimana komponen perangkat lunak akan dibangun setelah perancangan umum sistem selesai. Ini melibatkan pemilihan teknologi, pemodelan struktur data, perencanaan tata letak kode, dan merinci algoritma yang digunakan.

<h2>Project RPL: Sistem Manajemen Perpustakaan</h2>

Tahap Analisa:

a. Permasalahannya:

Perpustakaan XYZ menghadapi masalah dalam manajemen koleksi buku dan peminjaman. Mereka ingin meningkatkan efisiensi dan akurasi dalam pelacakan inventaris buku dan transaksi peminjaman. Masalah lain adalah akses terbatas untuk anggota perpustakaan dalam mencari informasi buku yang tersedia.

b.	Kebutuhan sistemnya:

•	Sistem perlu dapat mencatat informasi lengkap tentang setiap buku dalam koleksi, termasuk judul, pengarang, nomor ISBN, dan status ketersediaan.<br>
•	Anggota perpustakaan harus dapat mendaftar, masuk, mencari buku, meminjam, mengembalikan, dan memperpanjang buku secara online.<br>
•	Sistem harus memungkinkan administrator perpustakaan untuk mengelola anggota, buku, dan transaksi peminjaman.<br>
•	Sistem harus memiliki tampilan yang mudah digunakan, dan harus responsif terhadap perangkat seluler.<br>

c.	Use Case Diagram:

![image](https://github.com/zidanperdana/RPL/assets/116040175/baae6e5a-4c66-408f-9136-3b78cd7c06b5)

 
<h3>-	Aktor:</h3>

•	Anggota Perpustakaan<br>
•	Petugas Perpustakaan<br>
•	Kepala Perpustakaan<br>

<h3>-	Use Case:</h3>

•	Mendaftar<br>
•	Login<br>
•	Mencari Buku<br>
•	Meminjam Buku<br>
•	Mengembalikan Buku<br>
•	Pembayar Denda<br>
•	Menghitung Denda<br>
•	Memperpanjang Buku<br>
•	Mengelola Anggota<br>
•	Mengelola Buku<br>

d.	Activity Diagram:

![Screenshot 2023-11-08 162803](https://github.com/zidanperdana/RPL/assets/116040175/14a0d96c-363a-49d1-a916-eb0cb4cf354c)

Berikut adalah diagram aktivitas yang disederhanakan untuk proyek RPL (Rancangan Program Layanan) sistem manajemen perpustakaan:

1.	Mulai: Proses dimulai saat sistem diinisiasi
2.	Autentikasi Pengguna:<br>
•	Pengguna login atau diotentikasi.<br>
•	Jika autentikasi gagal, sistem kembali ke halaman login.<br>
3.	Menu Utama:<br>
•	Setelah autentikasi berhasil, pengguna disajikan dengan opsi menu utama.<br>
4.	Operasi Perpustakaan:<br>
Pengguna dapat melakukan berbagai operasi perpustakaan seperti:<br>
•	Cari buku.<br>
•	Pinjam buku.<br>
•	Kembalikan buku.<br>
•	Pesan buku.<br>
•	Perpanjang pinjaman buku.<br>
•	Bayar denda.<br>
•	Lihat informasi akun.<br>
•	Keluar.<br>
5.	Cari Buku:<br>
•	Pengguna dapat mencari buku berdasarkan judul, penulis, atau ISBN.<br>
•	Sistem mengambil dan menampilkan hasil pencarian.<br>
6.	Pinjam Buku:<br>
•	Pengguna memilih satu atau lebih buku untuk dipinjam.<br>
•	Sistem memeriksa ketersediaan buku yang dipilih.<br>
•	Jika buku tersedia, buku tersebut ditandai sebagai dipinjam, dan tanggal jatuh tempo diatur.<br>
7.	Kembalikan Buku:<br>
•	Pengguna mengembalikan buku ke perpustakaan.<br>
•	Sistem memperbarui status buku yang dikembalikan dan menghitung denda jika ada.<br>
8.	Pesan Buku:<br>
•	Pengguna dapat memesan buku yang saat ini sedang dipinjam oleh orang lain.<br>
•	Sistem menambahkan pengguna ke daftar tunggu untuk buku yang diminta.<br>
9.	Perpanjang Buku:<br>
•	Pengguna dapat memperpanjang buku yang dipinjam.<br>
•	Sistem memperpanjang tanggal jatuh tempo jika buku dapat diperpanjang.<br>
10.	Bayar Denda:<br>
•	Pengguna dapat membayar denda atau biaya yang belum dibayar.<br>
•	Sistem mencatat pembayaran dan memperbarui akun pengguna.<br>
11.	Lihat Informasi Akun:<br>
•	Pengguna dapat memeriksa detail akun mereka, termasuk buku yang dipinjam, pemesanan, dan denda.<br>
12.	Keluar:<br>
•	Pengguna keluar dari sistem.<br>
13.	Selesai: Proses berakhir.

Diagram aktivitas ini memberikan gambaran tingkat tinggi tentang interaksi dan aktivitas yang terlibat dalam sistem manajemen perpustakaan. Anda dapat lebih merinci dan memperluas diagram ini untuk mencakup lebih banyak detail, seperti proses khusus dan aliran data antara komponen berbeda dalam sistem. Selain itu, Anda mungkin ingin mempertimbangkan pengecualian dan penanganan kesalahan dalam sistem untuk memastikan operasi yang lancar.

e.	Sequence Diagram:

[Gambar Sequence Diagram]

Menunjukkan urutan interaksi antara anggota perpustakaan, sistem, dan administrator dalam proses peminjaman buku, dari pencarian hingga pengembalian.

<h3>Tahap Perancangan atau Desain:</h3>

a.	Class Diagram:

![Screenshot 2023-11-08 165429](https://github.com/zidanperdana/RPL/assets/116040175/8a8387ea-9fdc-4154-89cd-b788ac7f8dd1)

Kelas:

•	Buku<br>
•	Anggota Perpustakaan<br>
•	Transaksi Peminjaman<br>
•	Pertugas Perpustakaan<br>
• Kepala Perpustakaan<br>

b.	Deployment Diagram:

[Gambar Deployment Diagram]

Menunjukkan bagaimana komponen-komponen sistem ditempatkan di server, database, dan perangkat pengguna (klien).

c.	Data Model Diagram:

[Gambar Data Model Diagram]

Menunjukkan struktur basis data yang mencakup tabel-tabel untuk buku, anggota, dan transaksi.

d.	User Interface:

Desain tampilan antarmuka pengguna yang mencakup halaman masuk, halaman pencarian buku, halaman detail buku, halaman peminjaman, dan halaman pengelolaan anggota dan buku. Antarmuka harus mudah digunakan dan responsif terhadap berbagai perangkat.

