
<center><b><h2>Software Design Description</h2></b>

<h3>Versi 1.0<br>Maret 2018</h3>
<br>
 
 ![](http://i68.tinypic.com/24fbuvd.png)


<h2>Aplikasi Pola Hidup Sehat ( Pahat )</h2>

Nama Kelompok :

Arie Fahmi Luthfi<br>Diky Anwar<br>Shafa Dhiyanti<br>Stephan Dwiki Alkine

Jurusan D3 Teknik Informatika
<br>Politeknik Negeri Indramayu
<br>2018
</center>

<h3>BAB 1 Pendahuluan</h3>

1.1 Tujuan

Tujuan pembuatan SDD (Software Design Description) ini adalah untuk menjelaskan langkah-langkah desain dan proses-proses dalam pembuatan sistem aplikasi yang akan diterapkan pada Aplikasi Pola Hidup Sehat berbasis Android, dan juga memberi definisi kebutuhan untuk sistem, spesifikasi kebutuhan fungsional.

Dokumen perancangan ini dibuat berdasarkan spesifikasi kebutuhan Aplikasi Pola Hidup Sehat berbasis Android yang akan dibuat. Dalam rangka membangun aplikasi tersebut, tentunya deskripsi perancangan untuk aplikasi tersebut dibutuhkan, khususnya oleh para pengembang dan pembangun aplikasi tersebut.

Aplikasi Pola Hidup Sehat ini memudahkan kita untuk mengetahui aktivitas seperti jalan maupun jogging dengan GIS (Geographic Informatic System) yang dimana fungsinya memberikan statistik kepada kita tentang kecepatan, jarak dan waktu berolahraga kita. Selain itu aplikasi ini juga bisa melakukan perhitungan BMR (Basal Metabolic Rate) agar kita menerapkan pola hidup yang sehat.

1.2 Lingkup

Aplikasi Pola Hidup Sehat (Pahat) adalah sebuah aplikasi berbasis android yang mempermudah masyarakat menerapkan pola hidup sehat. Penggunaan aplikasi ini dengan Login melalui email, memilih olahraga, melakukan perhitungan BMR, melihat daftar kandungan kalori pada makanan dan minuman, menghitung konsumsi kalori, dan melihat hasil kalori dari tubuh kita. Aplikasi ini hanya menggunakan 1 user.

1.3 Definisi, Akronim dan Singkatan

| Definisi, Akronim dan Singkatan | Penjelasan |
| ----- | ----- |
| DFD | Data Flow Diagram. Diagram yan menggambarkan aliran data |
| ERD | Entity Relationship Diagram. Diagram yang menggambarkan entitas suatu objek beserta relasinya |
| SKPL | Spesifikasi Kebutuhan Perangkat Lunak. Sebuah dokumen yang berisi analisis terhadap suatu perangkat lunak yang akan dibangun yang dijabarkan dalam suatu spesifikasi kebutuhan. |
| SDD | Software Design Description. Dokumen untuk menjelaskan langkah-langkah desain dan proses-proses dalam pembuatan sistem aplikasi yang akan diterapkan pada aplikasi. |
| User | Pengguna aplikasi |

1.4 Referensi

Dokumen ini memiliki beberapa referensi dalam pembuatannya, yaitu sebagai berikut:


- IEEE Draft Standard for Software Design Descriptions

1.5 Ikhtisar Dokumen

Dokumen SDD ini berisi deskripsi rancangan perangkat lunak yang akan dikembangkan berdasarkan dokumen SRS. Dalam dokumen SDD ini dijabarkan perincian rancangan perangkat lunak yang dikembangkan, sehingga dapat diimplementasikan hingga level teknis. Gambaran umum dokumen ini terdapat pada penjelasan dibawah ini .

a. Bab 1, merupakan bab pendahuluan yang berisikan tentang overview dari rencana pengembangan perangkat lunak secara umum, seperti tujuan penulisan dokumen, lingkup masalah, definisi dan istilah, serta referensi.

b. Bab 2, merupakan deskripsi perancangan global yang berisi tentang perancangan perangkat lunak secara umum seperti lingkungan operasi yang akan digunakan untuk implementasi perangkat lunak, pemodelan data-data yang akan digunakan dalam perangkat lunak, dan daftar tabel yang digunakan sebagai database dalam perangkat lunak yang dikembangkan.

c. Bab 3, merupakan deskripsi perancangan rinci yang berisi tentang rincian keseluruhan atau detail menyeluruh dari perangkat lunak yang akan dikembangkan, seperti pendeskripsian secara rinci database yang akan digunakan didalam perangkat lunak dan rincian pemrosesan yang terjadi didalam perangkat lunak yang dikembangkan.

<h3>BAB 2 Deskripsi Perancangan Global</h3>

2.1 Rancangan Lingkungan Implementasi

Aplikasi Pola Hidup Sehat akan dikembangkan menjadi perangkat lunak berbasis android yang membutuhkan komputer dengan spesifikasi sebagai berikut :

- Sistem Operasi	: Microsoft Windows 2010

- DBMS				: 

- Development Tools	: Edraw Max

- Word Processor	: Microsoft Office Word 2010

- Bahasa pemrograman : Java

2.2 Deskripsi Data

2.2.1 Definisi Domain/Type

2.2.2 Conceptual Data Model

2.2.3 Physical Data Model

2.3 Deskripsi Modul


<h3>BAB 3 Deskripsi Perancangan Rinci</h3>

3.1 Diagram Konteks

![](http://i64.tinypic.com/28md8bm.png)

3.1.1 DFD Level 0

![](http://i67.tinypic.com/r0bnsm.png)

3.1.1.1 DFD Level 1 Proses 1 ( Mengolah data user )

![](http://i66.tinypic.com/2us917k.jpg)

3.1.1.2 DFD Level 1 Proses 2 ( Mengolah data olahraga )

![](http://i68.tinypic.com/zo2hg.jpg)

3.1.1.3 DFD Level 1 Proses 3 ( Mengolah data BMR )

![](http://i68.tinypic.com/10dtahx.jpg)

3.1.1.4 DFD Level 1 Proses 4 ( Mengolah menu food )

![](http://i64.tinypic.com/2d6taon.jpg)

3.1.1.5 DFD Level 1 Proses 5 ( Mengolah menu drink )

![](http://i68.tinypic.com/2cngtis.jpg)

3.1.1.6 DFD Level 1 Proses 6 ( Mengolah data kalori )

![](http://i63.tinypic.com/n2d0lw.jpg)

3.1.1.7 DFD Level 1 Proses 7 ( Mengolah data report kalori )



3.2 Deskripsi Rinci Tabel

     Identifikasi/Nama : Login
     
     Deskripsi Isi     : Data Login
     
     Jenis             : Tabel data Induk
     
     Volume            : 10 Record
     
     Laju              : 10 Record/bulan
     
     Primary Key       : Id User

3.2.1 Tabel A

3.3 Deskripsi Rinci Modul

3.3.1 Modul A

3.3.1.1 Fungsi Modul

3.3.1.2 Spesifikasi Layar Utama

3.3.1.3 Spesifikasi Query

(jika ada)

3.3.1.4 Spesifikasi Field Data Layar

3.3.1.5 Spesifikasi Obyek Pada Layer

3.3.1.6 Spesifikasi Proses / Algoritma

3.3.2 Modul B

3.4 Matriks Keturunan
