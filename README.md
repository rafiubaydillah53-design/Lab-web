# Praktikum Web - HTML Dasar

**Nama**: Rafi Ubaydillah
**NIM**: 312410445
**Kelas**: TI.24.A5

---

## Deskripsi Proyek

Proyek ini adalah latihan HTML dasar pada mata kuliah Pemrograman Web di Prodi Teknik Informatika Universitas Pelita Bangsa. [cite_start]Tujuan utama dari latihan ini adalah memahami penggunaan tag-tag dasar HTML untuk membuat halaman web sederhana[cite: 3]. Halaman web ini menampilkan beberapa elemen dasar HTML, di antaranya:
* [cite_start]Heading (`<h1>`, `<h2>`, dll.) [cite: 77]
* [cite_start]Paragraf (`<p>`) [cite: 91]
* [cite_start]Teks dengan format khusus (tebal, miring, `mark` / highlight) [cite: 98]
* [cite_start]Gambar (`<img>`) [cite: 118]
* [cite_start]Hyperlink (`<a>`) [cite: 108]

---

## Hasil Output

Tangkapan layar dari hasil output halaman web:

![Hasil Output](https://github.com/rafiubaydillah53-design/Lab-web/raw/87ad95836a2dfd2172bbf6b7ee53dc1d06d99140/hasil%20output.png)

---

## Penjelasan Kode

Berikut adalah penjelasan dari setiap tag HTML yang digunakan dalam kode Anda:

### `<title>`
Tag `<title>` terletak di dalam bagian `<head>` dan berfungsi untuk **menentukan judul halaman web** yang akan muncul di tab browser.

### `<h1>` dan `<h2>`
[cite_start]Tag-tag ini digunakan untuk membuat **judul** dan **sub-judul** pada halaman web[cite: 78]. Tag `<h1>` adalah judul level pertama, yang paling penting, dan `<h2>` adalah judul level kedua atau sub-judul.

### `<p>`
[cite_start]Tag `<p>` digunakan untuk membuat **paragraf**[cite: 91]. Browser akan secara otomatis menambahkan jarak di atas dan di bawah teks yang berada di dalam tag ini, membuat tampilan lebih rapi.

### Pemformatan Teks
* `<mark>`: Tag ini membuat teks menjadi **`highlight`** dengan warna latar belakang kuning.
* [cite_start]`<b>`: Tag ini membuat teks menjadi **tebal**[cite: 100].
* [cite_start]`<i>`: Tag ini membuat teks menjadi **miring**[cite: 100].
* [cite_start]`<a>`: Tag ini digunakan untuk membuat **hyperlink** atau tautan yang dapat diklik[cite: 111]. Atribut `href` di dalamnya menentukan alamat tujuan link.
    * `href="https://www.pelitabangsa.ac.id"`: Menghubungkan ke situs web eksternal Universitas Pelita Bangsa.

### Gambar
[cite_start]Tag `<img>` digunakan untuk **menyisipkan gambar** ke dalam halaman web[cite: 119]. Tag ini tidak memiliki tag penutup.
* `src="Logo upb.png"`: Atribut **`src`** (source) wajib diisi untuk menentukan **lokasi file gambar**.
* `width="200"`: Atribut **`width`** digunakan untuk **mengatur lebar gambar**.
* `alt="Logo Universitas Pelita Bangsa"`: Atribut **`alt`** (alternative text) memberikan **deskripsi teks** untuk gambar. Ini penting untuk aksesibilitas dan akan ditampilkan jika gambar gagal dimuat.
* `title="Logo Universitas Pelita Bangsa"`: Atribut **`title`** akan menampilkan **teks kecil (tooltip)** saat kursor mouse diarahkan ke gambar.

### Navigasi dan Garis Pembatas
* `<nav>`: Tag ini digunakan untuk mengelompokkan tautan-tautan navigasi.
* `<a>`: Tautan yang berada di dalam `<nav>` berfungsi untuk menghubungkan ke halaman lain.
* `<hr>`: Tag ini membuat **garis horizontal** sebagai pembatas di halaman web.
