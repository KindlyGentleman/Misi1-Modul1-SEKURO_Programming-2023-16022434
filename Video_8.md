# Gitignore
Sumber materi dapat diakses melalui [link](https://www.youtube.com/watch?v=LK3kX4n-vLM&list=PLFIM0718LjIVknj6sgsSceMqlq242-jNf&index=12) berikut ini

<p>&nbsp;</p>

## Daftar Isi

1.[Apa itu Gitignore?](#apa-itu-gitignore-)
2.[Catatan Tambahan](#catatan-tambahan-)

<p>&nbsp;</p>

## Apa itu Gitignore? <a name = "Ignore"></a>

Secara umum, gitignore merupakan suatu file yang biasanya disimpan di dalam folder atau `repository` git. Fungsi penempatan dari file ini adalah memberi tahu proses `add` dan `commit` agar mengabaikan file tertentu.

Cara menggunakannya adalah
- Buat file dengn nama .gitignore pada `repo`
- Edit isi dari file tersebut dengan menulis nama file, folder, atau ekstensi tertentu yang ingin diabaikan
- Simpan file tersebut setelah melakukan edit
- lakukan `commit`

Penulisan file .gitignore adalah
```
file.md: mengabaikan file tertentu

*.exe: mengabaikan seluruh file dengan ekstensi .exe

data/: mengabaikan seluruh item di dalam folder data
```

<p>&nbsp;</p>

## Catatan Tambahan <a name = "CT"></a>

Key Points:
- Gitignore adalah file yang digunakan untuk mengabaikan file, folder, atau ekstensi tertentu saat melakukan `add` atau `commit` pada `repo` git.
- Cara menambahkan informasi yang akan diabaikan adalah dengan menulis nama file dalam file .gitignore, lalu menyimpannya dan melakukan `commit`.
