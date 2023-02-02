# Bekerja dengan Git
Sumber materi dapat diakses melalui [link](https://www.youtube.com/watch?v=e-6OkXRqWaE&list=PLFIM0718LjIVknj6sgsSceMqlq242-jNf&index=5) berikut ini

<p>&nbsp;</p>

## Daftar Isi

1. [Git : Pengenalan dan Instalasi](#git--pengenalan-dan-instalasi-)
2. [Perintah dan Istilah dalam Git](#perintah-dan-istilah-dalam-git-)
3. [Bekerja dengan Git](#bekerja-dengan-git-dan-cara-caranya-)
4. [Catatan Tambahan](#catatan-tambahan-)

<p>&nbsp;</p>

## Git : Pengenalan dan Instalasi <a name = "Git"></a>

Git dapat diunduh dan diinstal dari [link berikut ini](https://git-scm.com/downloads). Dalam penggunaannya, Git bisa digunakan menggunakan *console* atau *command prompt*. Akan tetapi, tersedia juga perangkat lunak Git Client dengan tampilan GUI (Graphical User Interface) bagi pengguna yang memilih untuk tidak melakukan pemrograman. Setelah Anda melakukan instalasi Git, Anda bisa membuka Git Bash dan mengetik "git" untuk memunculkan bantuan mengenai Git.

<p>&nbsp;</p>

## Perintah dan Istilah dalam Git <a name = "Gitp"></a>

Untuk melakukan pengecekan versi Git, perintah yang bisa ditulis adalah:

```
git --version
```

Ada beberapa perintah yang bisa kita tulis pada *console* atau *command prompt* Git yaitu:

```
$ git init: inisialisasi repo git
$ git add <file(s)>: menambahkan file ke staging area
$ git status: mengetahui status repo
$ git commit: melakukan commit
$ git config: memasukkan konfigurasi ke dalam Git
$ git branch: membuat branch
$ git help: memunculkan perintah-perintah Git
```
Ada beberapa istilah area dalam `repository` Git:
- Working Tree: *folder* utama tempat bekerja
- Staging Area : area atau tempat yang menandakan bahwa terjadi suatu perubahan atau *file* yang mengalami perubahan
- History : tempat tersimpannya `commit`

Setelah *folder* yang kita inginkan diinisiasi sebagai `repository` Git, Git akan melihat perubahan pada *folder* tersebut. Setiap perubahan yang terjadi pada *folder* akan disimpan pada Staging Area dan dilakukan `commit`.

<p>&nbsp;</p>

## Bekerja dengan Git dan Cara-Caranya <a name = "Gitb"></a>

- Gunakan command "pwd" untuk mengecek directory aktif
```
pwd
```
- Masuk *folder* yang ingin diinisialisasi sebagai `repo` git menggunakan command:
```
cd <nama folder>
```
- Gunakan perintah "git init" untuk membuat *folder* menjadi `repo` git
```
git init
```
- Untuk melihat *folder* (.git) yang tersembunyi: 
    - buka *file explorer*
    - buka *folder* `repo`
    - buka tab "View"
    - klik Options
    - Pilih "View"
    - Klik "Show hidden files, folders, and drives" dan "unmark Hide extensions for known file types"

- Gunakan *software code editor* seperti Visual Studio Code atau Sublime Text untuk menambahkan *file* ke `repo` git
- Gunakan perintah "git status" untuk mengecek status `commit`
```
git status
```
- Tambahkan file ke Staging Area dengan perintah: 
```
git add <file>
```
- Lakukan `commit` dengan perintah:
```
git commit -m 'pesan commit'
``` 

<p>&nbsp;</p>

## Catatan Tambahan <a name = "CT"></a>

Key Points:

- Git adalah sistem pengontrol versi (VSC) yang digunakan untuk melacak perubahan yang terjadi.
- Git memiliki dua versi akses, versi akses melalui *console* atau dengan *software* Git Client berbasis GUI.
- Ada 3 area dalam `repo` Git: Working Tree, Staging Area, dan History.
- Cara kerja Git secara umum adalah inisialisasi repo, penambahan file ke Staging Area, melakukan commit, dan memantau status.

<p>&nbsp;</p>