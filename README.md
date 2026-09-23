# Praktikum 1 – HTML Dasar

Repository ini berisi hasil Praktikum 1 mata kuliah **Pemrograman Web** dengan materi **HTML Dasar**.

## Identitas

**Nama:** Chaya Aulia

**Program Studi:** Teknik Informatika

**Mata Kuliah:** Pemrograman Web

**Praktikum:** Praktikum 1 – HTML Dasar

---

## Tujuan Praktikum

Praktikum ini bertujuan untuk memahami struktur dasar HTML, mengenal tag dan atribut HTML, serta membuat halaman web sederhana menggunakan HTML. Materi yang dipraktikkan meliputi heading, paragraf, pemformatan teks, gambar, hyperlink, list, komentar, dan penggabungan beberapa elemen HTML.

---

## Tools yang Digunakan

* Visual Studio Code
* Web Browser
* Git dan GitHub

---

## Proses Praktikum

### 1. Membuat Folder Praktikum

Pertama, dibuat folder kerja dengan nama:

`praktikum-1-html-dasar`

Di dalam folder tersebut dibuat file `index.html` sebagai halaman utama.

**Struktur awal:**

```text
praktikum-1-html-dasar/
└── index.html
```

### 2. Membuat Struktur Dasar HTML

File `index.html` dibuat dengan struktur dasar HTML yang terdiri dari `<!DOCTYPE html>`, `<html>`, `<head>`, dan `<body>`.

Screenshot:

![Struktur Dasar HTML](screenshots/01-struktur-html.png)

---

### 3. Membuat Paragraf

Selanjutnya dibuat beberapa paragraf menggunakan tag `<p>`. Setelah kode disimpan, file HTML dibuka melalui browser untuk melihat hasilnya.

Screenshot:

![Hasil Paragraf](screenshots/02-paragraf.png)

---

### 4. Menambahkan Heading

Ditambahkan heading menggunakan tag `<h1>` dan `<h2>` sebagai judul utama dan subjudul.

Contoh:

```html
<h1>Belajar Dasar HTML</h1>
<h2>Paragraf pada HTML</h2>
```

Screenshot:

![Hasil Heading](screenshots/03-heading.png)

---

### 5. Memformat Teks

Pada tahap ini dilakukan pemformatan teks menggunakan beberapa tag HTML seperti `<b>`, `<i>`, `<strong>`, `<sub>`, dan `<sup>`. Beberapa tag pemformatan lainnya juga dicoba untuk melihat perbedaannya.

Screenshot:

![Hasil Pemformatan Teks](screenshots/04-format-teks.png)

---

### 6. Menambahkan Gambar

Sebuah gambar dimasukkan ke dalam halaman HTML menggunakan tag `<img>`. Gambar disimpan di dalam folder `images`.

Struktur folder menjadi:

```text
praktikum-1-html-dasar/
├── index.html
└── images/
    └── profil.jpg
```

Contoh:

```html
<img src="images/profil.jpg"
     width="200"
     alt="Foto profil mahasiswa"
     title="Foto Profil Mahasiswa">
```

Screenshot:

![Hasil Gambar](screenshots/05-gambar.png)

---

### 7. Mengatur Ukuran Gambar

Ukuran gambar kemudian dicoba diubah menggunakan atribut `width` dan `height` untuk melihat perubahan ukuran gambar pada halaman web.

Screenshot:

![Hasil Ukuran Gambar](screenshots/06-ukuran-gambar.png)

---

### 8. Menambahkan Hyperlink

Pada tahap ini dibuat file kedua dengan nama `halaman2.html`. Kemudian dibuat hyperlink untuk berpindah dari `index.html` ke `halaman2.html` serta hyperlink menuju website eksternal.

Contoh:

```html
<a href="index.html">Dasar HTML</a>
<a href="halaman2.html">Halaman 2</a>
<a href="https://www.google.com">Website Eksternal</a>
```

Screenshot:

![Hasil Hyperlink](screenshots/07-hyperlink.png)

---

### 9. Menambahkan List

Dibuat dua jenis daftar, yaitu:

* **Unordered List (`<ul>`)** untuk daftar tanpa nomor.
* **Ordered List (`<ol>`)** untuk daftar yang berurutan.

Contoh:

```html
<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>

<ol>
    <li>Mempelajari struktur HTML</li>
    <li>Mempelajari tag dan atribut</li>
    <li>Membuat halaman HTML</li>
</ol>
```

Screenshot:

![Hasil List](screenshots/08-list.png)
---

### 10. Menambahkan Komentar HTML

Komentar ditambahkan menggunakan `<!-- ... -->`. Komentar tidak ditampilkan pada browser dan digunakan untuk memberikan penanda atau keterangan pada bagian kode.

Contoh:

```html
<!-- Bagian Profil Mahasiswa -->
<h2>Profil Mahasiswa</h2>
```

Screenshot:

![Komentar HTML](screenshots/09-komentar.png)

---

### 11. Menggabungkan Semua Elemen

Pada tahap terakhir, seluruh elemen HTML yang telah dipelajari digabungkan menjadi sebuah halaman **Profil Mahasiswa**.

Halaman tersebut berisi:

* Navigasi
* Heading
* Gambar
* Data diri
* Paragraf
* Daftar keahlian
* Target belajar

Screenshot:

![Hasil Akhir](screenshots/10-hasil-akhir.png)

---

## Struktur Repository

Hasil akhir repository memiliki struktur:

```text
Lab1Web/
├── index.html
├── halaman2.html
├── images/
│   └── profil.jpg
└── README.md
```

Struktur tersebut sesuai dengan ketentuan output Praktikum 1.

---

## Hasil Praktikum

Setelah menyelesaikan praktikum, saya dapat memahami dasar-dasar HTML dan mencoba membuat halaman web sederhana menggunakan berbagai elemen HTML, seperti heading, paragraf, pemformatan teks, gambar, hyperlink, list, dan komentar.

Praktikum ini juga membantu memahami bagaimana kode HTML ditulis dan bagaimana browser menampilkan hasil dari kode tersebut.

---

## Kesimpulan

Praktikum 1 memberikan pemahaman dasar mengenai struktur dan elemen HTML. Dari praktikum ini, saya dapat membuat dokumen HTML sederhana dan menggabungkan berbagai elemen menjadi sebuah halaman web. Seluruh hasil praktikum kemudian disimpan dalam repository GitHub dan dilakukan commit sesuai instruksi praktikum.
