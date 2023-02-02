# Git Branch dan Merge
Sumber materi dapat diakses melalui [link](https://www.youtube.com/watch?v=EGl7KxVOyNs&list=PLFIM0718LjIVknj6sgsSceMqlq242-jNf&index=6) berikut ini

<p>&nbsp;</p>

## Daftar Isi
1. [Git : Apa itu Branch?](#git--apa-itu-branch-)
2. [Git : Apa itu Merge?](#git--apa-itu-merge-)
3. [Command yang Sering Muncul dan Cara Menggunakannya](#command-yang-sering-muncul-)
4. [Catatan Tambahan](#catatan-tambahan-)

<p>&nbsp;</p>

## Git : Apa itu Branch? <a name = "Branch"></a>

`Branch` merupakan salah satu fitur yang ada di dalam Git untuk membuat cabang dari `Master Branch`, secara pengertian memiliki kesamaan seperti `branch` pada Github. Sama dengan `branch` pada umumnya, `branch` pada Git digunakan agar kita bisa menambahkan suatu fitur baru tanpa melakukan perubahan atau memengaruhi `Master Branch` atau `main`.

Command yang bisa digunakan untuk membuat `branch`:

```
$ git branch (nama_branch)
```
Command yang bisa digunakan untuk memindahkan ke `branch`:
```
$ git checkout (nama_branch)
```

<p>&nbsp;</p>

## Git : Apa itu Merge? <a name = "Merge"></a>
Sama seperti pada Github, `merge` pada Git merupakan suatu proses penggabungan `branch` yang terpisah menjadi satu di `Main Branch`. Dalam Git, terdapat dua jenis `merge` yang dapat dilakukan:
- Fast Forward:
    - Fast Forward akan terjadi ketika `branch` berada dalam jalur langsung dalam prosesnya (*direct path*).
    ```
    $ git merge (nama_branch)
    ```
- Three-way Merge:
    - Three-way Merge akan terjadi ketika kedua `branch` yang ingin digabungkan tidak berada dalam jalur langsung dimana `commit` baru akan dibuat. *Command* yang digunakan adalah sama
    ```
    $ git merge (nama_branch)
    ```

<p>&nbsp;</p>

## Command yang Sering Muncul dan Cara Menggunakannya <a name = "Command"></a>

Beberapa perintah yang sering muncul dalam melakukan proses `branch` dan `merge`:

```
$ git branch (nama_branch): membuat branch
$ git branch: melihat branch yang tersedia
$ git checkout (nama_branch): pindah branch
$ git branch -d (nama_branch): menghapus branch
$ git merge (nama_branch): merge branch 
$ git log --all --decorate --oneline --graph: melihat graph
```

Dalam kasus `branch` dan `merge`, beberapa fungsi yang akan sering digunakan adalah membuat `branch` baru dengan *command* "git branch", memindahkan ke `branch` yang diinginkan dengan *command* "git checkout", dan menggabungkan `branch` ke `Main Branch` dengan menggunakan *command* "git merge".

Dalam kasus kolaborasi Git dengan Visual Studio Code (VSCode), terdapat sedikit kemudahan dalam melakukan proses ini dan memiliki penanda yang sedikit berbeda. Saat di VSCode, file dengan tanda huruf "U" di samping menandakan *file* belum dimasukkan ke dalam Staging Area dan bisa ditambahkan ke Staging Area. Apabila pengguna tetap ingin menggunakan VSCode tetapi tetap ingin menggunakan perintah ketikan, VSCode memiliki terminal sendiri yang bisa digunakan untuk menjalankan perintah Git.

<p>&nbsp;</p>

## Catatan Tambahan <a name = "CT"></a>

Key Points:
-`Branch` pada Git akan membuat cabang dari jalur utama untuk memisahkan fitur baru dalam proses pengerjaannya.
- `Merge` adalah proses penggabungan `branch` menjadi satu.
- Terdapat dua jenis `merge` yaitu Fast Forward dan Three-way Merge.
- Terminal pada VSCode bisa digunakan juga untuk melakukan perintah Git.