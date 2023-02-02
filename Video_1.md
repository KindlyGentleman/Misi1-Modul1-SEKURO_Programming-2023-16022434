# Apa Itu Git dan Github?
Sumber materi dapat diakses melalui [link](https://www.youtube.com/watch?v=lTMZxWMjXQU&list=PLFIM0718LjIVknj6sgsSceMqlq242-jNf&index=1) berikut ini

<p>&nbsp;</p>

## Daftar Isi
1. [Version Control System](#version-control-system-)
2. [Git](#git-)
3. [Glosarium Git : Istilah Penting yang Sering Digunakan](#glosarium-git--istilah-penting-yang-sering-digunakan-)
4. [Github serta Hubungannya dengan Git](#github-serta-hubungannya-dengan-git-)

<p>&nbsp;</p>

## Version Control System <a name = "VCS"></a>

Secara umum, Version Control System (VCS) adalah sistem yang digunakan untuk melakukan pengolahan dan perubahan pada suatu unit informasi. 
Contoh dari unit informasi ini adalah dokumen, kode sumber (*source code*) dalam dunia pemrograman, dan lainnya. VCS akan menyimpan suatu `snapshot` perubahan
dari unit informasi tersebut. Hal ini digunakan untuk memudahkan pengerjaan terhadap suatu informasi, terutama informasi yang dikerjakan secara bersama, dan memungkinkan
orang-orang yang mengerjakan untuk melacak perubahan yang dilakukan dalam proses kerja sama. Pelacakan ini melingkupi informasi tentang siapa yang melakukan perubahan dan kapan
dia melakukan perubahan tersebut. Selain itu, VCS dapat memungkinkan penggunanya untuk mengembalikan versi file atau informasi ke dalam keadaan sebelum terjadinya perubahan (*backup*) dengan
`checkout`. Intinya, VCS akan dan sering digunakan untuk membantu suatu tim dalam melakukan kolaborasi dengan terstruktur terhadap suatu informasi dan melacak perubahan yang terjadi dalam prosesnya.

<p>&nbsp;</p>

## Git <a name = "Git"></a>

Git merupakan sebuah perangkat lunak VCS yang digunakan untuk mengelola perubahan informasi berupa file di folder (`repository/repo`). Git akan menyimpan seluruh riwayat perubahan dari file-file tersebut
dengan bantuan serangkaian `commit` yang memiliki penanda unik hash. Dengan menggunakan Git, para developer atau tim dapat melakukan kolaborasi pada suatu *codebase* yang sama dan melakukan *version control system*
dengan merekam dan menyimpan perubahan pada *source code*, sesuai dengan penjelasan pada [Version Control System (VCS)](#version-control-system-). Dalam praktiknya, cabang baru atau `branch` dapat dibuat dari suatu `commit` dan menggabungkan fitur dari
cabang-cabang berbeda yang dikerjakan secara terpisah dengan melakukan `merge`. Git dapat dijalankan dalam komputer pribadi (*local*) setelah mengunduh software Git yang dapat dilakukan dari [link berikut](https://git-scm.com/downloads). Istilah-istilah asing Git dalam bagian ini akan dibahas pada bagian selanjutnya

<p>&nbsp;</p>

## Glosarium Git : Istilah Penting yang Sering Digunakan <a name = "GG"></a>

- `Repository/repo` : Folder tempat menyimpan file dan tempat mengelola perubahan file.
- `Commit` : Sebuah riwayat perubahan file yang disimpan
- `Hash` : Penanda unik untuk setiap `commit`
- `Branch` : Cabang yang dibuat atau ada pada `commit` agar tidak mengganggu `commit` utama
- `Merge` : Proses penggabungan dua buah `branch` menjadi satu
- `Checkout` : Melakukan perpindahan ke sebuah `commit`
- `Remote` : Sumber yang memiliki `repository/repo`
- `Clone` : Mengambil suatu `repository/repo` dari remote dan menggandakannya
- `Push` : Proses pengiriman `commit` ke suatu `repository/repo`
- `Pull` : Mengambil `commit` dari `repository`

<p>&nbsp;</p>

## Github serta Hubungannya dengan Git <a name = "Github"></a>

Github merupakan suatu layanan berbasis *cloud* yang memungkinkan penggunanya untuk mengelola dan menyimpan suatu `project` atau `repository` dengan menggunakan Git.
Git dan Github dapat dianalogikan sebagai hubungan rumah dan kantor dimana Git bekerja sebagai rumah dan Github bekerja sebagai kantor. Git digunakan untuk mengerjakan tugas di komputer lokal.
Github digunakan untuk menyimpan dan membagikan tugas dengan orang lain secara kolaborasi. Git dan GitHub akan melakukan kerja sama dengan memiliki remote repo di GitHub yang di-*clone* ke komputer lokal.
Untuk mengirimkan dan mengambil tugas tersebut, kita bisa menggunakan proses `push` dan `pull`. `Push` adalah proses mengirimkan *source code* dari komputer ke GitHub, sedangkan `Pull` adalah proses mengambil *source code* dari GitHub ke komputer. Kedua proses ini melibatkan `commit`.

<p>&nbsp;</p>