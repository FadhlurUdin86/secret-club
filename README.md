# Proyek Akhir HTML: Klub Detektif Rahasia

Repositori ini berisi proyek percontohan website statis multi-halaman yang dibangun murni menggunakan HTML dasar. Proyek ini dirancang sebagai acuan tugas akhir kelas coding untuk memahami struktur semantik, manajemen aset, tabel data, multimedia, dan formulir web.

---

## Daftar Isi
- [Tujuan Pembelajaran](#tujuan-pembelajaran)
- [Struktur Direktori](#struktur-direktori)
- [Fitur dan Tag HTML yang Digunakan](#fitur-dan-tag-html-yang-digunakan)
- [Checklist Evaluasi Proyek](#checklist-evaluasi-proyek)
- [Cara Menjalankan Proyek](#cara-menjalankan-proyek)
- [Langkah Penerbitan (Hosting)](#langkah-penerbitan-hosting)

---

## Tujuan Pembelajaran

1. Memahami pembuatan website multi-halaman dengan sistem navigasi internal.
2. Menerapkan pengorganisasian file dan aset media menggunakan jalur relatif (relative path).
3. Menggunakan elemen semantik HTML5 untuk menyusun tata letak halaman yang logis.
4. Menyajikan data terstruktur menggunakan elemen tabel.
5. Memasang elemen multimedia mandiri (audio dan video).
6. Membangun formulir interaktif dengan berbagai tipe input data.

---

## Struktur Direktori

```text
secret-club-demo/
├── assets/
│   ├── audio/
│   │   └── secret-club-theme-song.mp3
│   ├── images/
│   │   ├── buku-catatan.jpg
│   │   ├── kaca-pembesar.jpg
│   │   └── secret-laboratory.jpg
│   └── videos/
│       └── radar-scan.mp4
├── index.html
├── members.html
├── mission.html
├── join.html
└── README.md
```

---

## Fitur dan Tag HTML yang Digunakan

### 1. Beranda (`index.html`)
* Struktur Semantik: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`.
* Tipografi: `<h1>`, `<h3>`, `<p>`, `<strong>`, `<em>`, `<small>`.
* Gambar Utama: `<img>` dengan atribut `src`, `alt`, dan `width`.
* Pemutar Audio: `<audio>` dengan atribut `controls` dan tag `<source>`.
* Daftar Tak Berurutan: `<ul>` dan `<li>` untuk aturan klub.

### 2. Daftar Agen (`members.html`)
* Navigasi Internal: Tautan `<a>` yang menghubungkan seluruh berkas halaman.
* Tabel Data: `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, dan `<td>`.
* Atribut Tabel Dasar: `border`, `cellpadding`, dan `cellspacing`.

### 3. Galeri dan Arsip Misi (`mission.html`)
* Figur Gambar: `<figure>`, `<img>`, dan `<figcaption>`.
* Pemutar Video: `<video>` dengan atribut `width`, `height`, `controls`, dan tag `<source>`.

### 4. Formulir Pendaftaran (`join.html`)
* Elemen Form: `<form>`, `<fieldset>`, dan `<legend>`.
* Masukan Teks: `<input type="text">` dan atribut `placeholder`, `required`.
* Masukan Tanggal: `<input type="date">`.
* Pilihan Radio: `<input type="radio">` untuk pemilihan kategori tunggal.
* Area Teks Panjang: `<textarea>`.
* Kotak Centang Persetujuan: `<input type="checkbox">`.
* Tombol Aksi: `<button type="submit">` dan `<button type="reset">`.

---

## Checklist Evaluasi Proyek

Gunakan daftar periksa berikut sebelum mengumpulkan atau mempublikasikan web:

* [ ] Seluruh halaman memiliki struktur dasar standar (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`).
* [ ] Seluruh menu navigasi dapat diklik bolak-balik tanpa memicu galat halaman tidak ditemukan (404).
* [ ] File gambar, audio, dan video tersimpan di subdirektori `assets/` yang sesuai.
* [ ] Penulisan nama berkas dan folder menggunakan huruf kecil tanpa spasi.
* [ ] Tabel memiliki baris judul kolom (`<th>`) yang jelas.
* [ ] Seluruh input pada form memiliki atribut `name` dan label pendukung.

---

## Cara Menjalankan Proyek

1. Unduh atau salin seluruh folder proyek `secret-club-demo`.
2. Buka folder tersebut melalui text editor (misal: Visual Studio Code).
3. Buka berkas `index.html` dengan cara klik dua kali langsung dari file manager, atau gunakan ekstensi live preview di editor teks.

---

## Langkah Penerbitan (Hosting)

Proyek ini siap diunggah ke platform hosting statis publik (seperti Netlify, Vercel, atau GitHub Pages):

1. Masuk ke dasbor Netlify (bagian Netlify Drop).
2. Tarik (drag-and-drop) folder utama `secret-club-demo`.
3. Tunggu hingga proses unggah selesai dan salin tautan website yang dihasilkan untuk dibagikan.