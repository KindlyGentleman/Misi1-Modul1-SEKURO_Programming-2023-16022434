# Git Merge Conflict
Sumber materi dapat diakses melalui [link](https://www.youtube.com/watch?v=Vfwfeve72PA&list=PLFIM0718LjIVknj6sgsSceMqlq242-jNf&index=7) berikut ini

<p>&nbsp;</p>

## Daftar Isi

1. [Merging Conflict pada Git](#merging-conflict-pada-git-)
2. [Catatan Tambahan](#catatan-tambahan-)

<p>&nbsp;</p>

## Merging Conflict pada Git <a name = "Conflict"></a>

"Merging conflict" akan terjadi apabila terdapat perbedaan pada baris yang sama pada dua `branch` yang akan di-`merge`. Untuk menyelesaikan konflik ini, `branch` harus di *review* secara manual dengan menggunakan bantuan text editor atau IDE.

Pada saat terjadi "merging conflict", bagian yang mengalami *conflict* akan ditandai dengan tanda pemisah antara `branch` yang sedang aktif dan pada `branch` yang akan di-`merge`. Baris yang mengalami konflik dapat diterima atau dihapus sesuai dengan keputusan pengguna atau orang yang melakukan *review*.

Setelah konflik ini terselesaikan atau *resolved*, `commit` seperti biasa dapat dilakukan. Terdapat cara untuk mengatasi "merge conflict" dan cara untuk `checkout` ke sebuah `commit`. Secara umum, perintah yang dapat digunakan untuk melakukan `checkout` ke `commit` adalah
```
$ git checkout [7 karakter pertama dari hash commit]
```
Lalu, buatlah `branch` baru dari `commit` tersebut dan lakukan `checkout` ke `branch` baru untuk membuat pointer HEAD yang awalnya bersifat "detached" mengarah ke `branch` tersebut.

<p>&nbsp;</p>

## Catatan Tambahan <a name = "CT"></a>

Key Points:

- "Merging Conflict" akan terjadi karena ada perbedaan baris pada dua `branch` yang ingin di-`merge` yang perlu di-*resolve* secara manual.