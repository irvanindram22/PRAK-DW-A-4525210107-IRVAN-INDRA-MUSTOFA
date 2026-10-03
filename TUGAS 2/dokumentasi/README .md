# README - Profil SEMA FT-KMUP

## Ringkasan Perubahan, Masalah, dan Solusi

Program dibuat dengan struktur HTML dasar yang terdiri dari `<!DOCTYPE html>`, elemen `<html>`, `<head>`, dan `<body>`. Pada bagian `<head>` digunakan `meta charset="UTF-8"` agar karakter dapat ditampilkan dengan benar serta `meta viewport` agar halaman dapat menyesuaikan ukuran layar. Judul halaman dibuat menggunakan elemen `<title>`.

Pada bagian isi, ditambahkan heading untuk profil organisasi, kemudian gambar logo SEMA FT-KMUP dan dokumentasi kegiatan TPBD Jilid IX. Gambar menggunakan atribut `src`, `alt`, dan `width` agar sumber gambar, teks alternatif, serta ukuran gambar dapat ditentukan. Selanjutnya dibuat daftar struktur kepengurusan menggunakan unordered list (`<ul>`) dan alur pendaftaran anggota menggunakan ordered list (`<ol>`).

Masalah yang dapat muncul dalam program adalah gambar tidak tampil apabila lokasi atau nama file pada atribut `src` tidak sesuai dengan struktur folder project. Solusinya adalah memastikan folder `images` berada pada lokasi yang benar dan nama file ditulis sama persis, termasuk huruf besar dan kecil. Selain itu, link email pada bagian kontak sebelumnya tidak menggunakan format `mailto:` sehingga tidak langsung membuka aplikasi email, dan tampilan konten sempat ter-center akibat aturan CSS `margin: 0 auto` sehingga perlu ditambahkan aturan khusus agar konten rata kiri. Dengan perbaikan tersebut, halaman menjadi lebih rapi, konsisten, dan mudah dikembangkan.

## Source Code

![Screenshot Program](images/code.png)

## Output

![Screenshot Output](images/Output1.png)
![Screenshot Output](images/Output2.png)
![Screenshot Output](images/Output3.png)
