# Github : Branch
Sumber materi dapat diakses melalui [link](https://www.youtube.com/watch?v=k1QXd-8VbPY&list=PLFIM0718LjIVknj6sgsSceMqlq242-jNf&index=3) berikut ini

<p>&nbsp;</p>

## Daftar Isi

1. [Apa itu Branch?](#apa-itu-branch-)
2. [Merging dan Pull Request](#merging-dan-pull-request-)
3. [Catatan Tambahan](#catatan-tambahan-)

<p>&nbsp;</p>

## Apa itu Branch? <a name = "What-Branch"></a>

Buat apa cabang ranting kayu ada Github? Sebenarnya, `branch` itu merepresentasikan cabang dalam `repository`. Dalam segi pengertian, `branch` adalah fitur yang dapat digunakan untuk menciptakan `snapshot` dari `repository` tanpa menganggu `repository` utama atau jalur utama yang biasa disebut dengan `Master Branch`. 

Implementasi dari branch dalam praktiknya adalah memudahkan orang atau anggota dalam suatu tim untuk bekerja pada `repository` *project* yang sama dengan membuat "cabang" tersendiri.

Untuk membuat sebuah cabang atau `branch`, cara yang dapat dilakukan adalah:
- Tentukan dan buka `repository` yang ingin dibuat `branch`-nya
- Pilih menu "branch"
- Tulis nama "branch" yang Anda inginkan
- Pilih "create branch"

<p>&nbsp;</p>

## Merging dan Pull Request <a name = "Merge-Pull"></a>

Dalam Github, istilah `merge` dikenal dengan proses penggabungan sebuah `branch` anak atau cabang kembali ke `branch` utama atau `Master Branch`.

Istilah `Pull Request` akan sering ditemukan dalam Github yang menjelaskan tentang proses permintaan untuk memasukan sebuah perubahan yang telah kita lakukan di `branch` kita ke `Master Branch`. Dalam kasus pull request ke `Master Branch` tertentu, kita perlu menunggu konfirmasi dari pemiliknya untuk menerima perubahan atau modifikasi yang kita lakukan.

Langkah-langkah yang yang bisa dilakukan dalam melakukan proses `merge` dan `pull request` adalah:
- Pilih menu "Compare & pull request"
- Apabila kedua `commit` dari `branch` pribadi dan `Master Branch` dapat digabung yang ditandai dengan tulisan  “Able to merge”, silakan buat `pull request`
- Apabila kedua `commit` belum bisa digabung atau terdapat "merge conflict", silakan bandingkan atau *compare* terlebuh dahulu keduanya lalu buat pull request
- Pilih menu "Create pull request" untuk membuat `pull request`
- Klik "merge" untuk melakukan penggabungan

Perlu diperhatikan bahwa ada kasus "merge conflict" dimana adanya perubahan yang sama pada `branch` dan `Master Branch`. Masalah ini bisa diselesaikan oleh orang yang memiliki akses pada `Master Branch`, biasanya pemiliknya.

<p>&nbsp;</p>

## Catatan Tambahan <a name = "CT"></a>

Key Points:

- `Branch` adalah fitur untuk membuat `snapshot` di Github tanpa mengganggu `Master Branch`
- `Merge` adalah proses penggabungan `branch` yang dibuat kembali ke `Master Branch`
- `Pull request` adalah permintaan untuk memasukan perubahan ke `Master Branch`
- Pehatikan tentang masalah "merge conflict" yang terjadi bila ada perubahan yang sama pada `branch` dan `Master Branch`