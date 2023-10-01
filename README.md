# Praktikum 1 Pemrograman Web
Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode.
2. Buat file baru dengan nama lab1_tag_dasar.html
3. Buat struktur dasar dari dokumen HTML.
4. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.
5. Lakukan validasi dokumen html dengan mengakses http://validator.w3.org

## Modul Praktikum Pemrograman Web
!
Kemudian selanjutnya, buka file tersebut pada web browser misalnya Mozilla Firefox.


!




## 1.Membuat Paragraf
```
<!-- Ini adalah paragraf pertama -->
<p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi
Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat
adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar
HTML.</p>
<!-- Ini adalah paragraf kedua -->
<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan
tag dasar html.</p>
```

!

## 2.Menambahkan Judul
```
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>
<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
```

!

## 3.Memformat teks
```
 <p align=”center”>Kami sedang belajar <mark>HTML dasar,</mark> pada matakuliah <b>Pemrograman Web</b>
        di Prodi <I>Teknik Informatika </I> <u>Universitas Pelita Bangsa</u>. Pelajaran pertama
        yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
        tag-tag dasar HTML.</p>
```

!

## 4.Menyisipkan Gambar
```
<h3>Menambahkan Gambar</h3>
    <img src="logo upb.png" width="200" title="Logo Univeritas Pelita Bangsa">
```

!


!

## 5. Menambahkan Hyperlink
```
 <nav>
        <a href="lab1_tag_dasar.html">Dasar HTML</a>
        <a href="lab1_halaman2.html">Halaman 2</a>
        <a href="http://www.google.com">Halaman Web Eksternal Google</a>
        </nav>
    <hr>
```

!

## Halaman 2

!


## Jawab Pertanyaan Berikut
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
```
Ketika saya salah dalam penulisan tag img yang seharusnya <img> menjadi </img>, gambar yang saya ingin tampilkan menjadi tidak tampil dalam web/browser.
```

2. Apa perbedaan dari tag `<p>` dengan tag `<br>`, berikan penjelasannya!
```
tag <br> melompati satu line cocok untuk memulai paragraf baru sedangkan tag <p> seperti menekan enter di software document editor 
```

3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
```
Perbedaan atribut title dan alt yaitu pada gambar yang dihasilkan. Ketika gambar berhasil ditampilkan maka akan terlihat sebuah title, sedangkan jika gambar gagal ditampilkan maka akan menampilkan teks dalam atribut alt tersebut
```

4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
```
Untuk menampilkan gambar yang proporsional sebaiknya kedua attribut tersebut diisi sesuai dengan ukuran yang kita inginkan. Dengan mengatur kedua ukuran tersebut kita dapat menyesuaikan gambar dengan lokasi penempatan gambar tersebut.
```

5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
```
Nilai _blank akan membuka link/halaman di tab baru.
Nilai _self akan membuka link/halaman di tab saat ini.
Nilai _top membuka link/halaman dan membatalkan semua frame.
Nilai _parent membuka link/halaman pada parent frame.
``
