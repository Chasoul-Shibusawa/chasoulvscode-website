Struktur Dasar
HTML Doctype dan Head:

<html lang="en">: Menentukan bahasa dokumen.
<head>: Berisi metadata seperti karakter set, viewport, favicon, title, deskripsi, dan kata kunci untuk SEO. Juga, menghubungkan stylesheet dashboard.css.
Body:

Header:

<header class="header" id="top">: Header utama situs dengan navigasi.
<nav class="nav">: Navigasi utama yang berisi tautan ke GitHub, Instagram, proyek, dan toko online.
<div class="header__text-box row">: Berisi informasi utama termasuk nama, deskripsi singkat, dan tombol menuju CV dan About Me.
Main Content:

Work Section:
<section class="work" id="work">: Bagian ini menampilkan proyek-proyek yang sudah dikerjakan, dengan contoh GitHub account.
Setiap proyek ditampilkan dalam <div class="work__box"> yang terdiri dari teks deskripsi proyek dan gambar ilustrasi.
Store Section:
<section class="work" id="store">: Menampilkan toko online dengan deskripsi dan link ke toko di Shopee.
About Section:
<section class="about" id="about">: Menyediakan informasi lebih detail tentang diri anda, termasuk pengalaman kerja dan tombol untuk melihat CV yang dilindungi dengan kata sandi.
JavaScript function enterPassword() digunakan untuk melindungi akses CV.
Contact Section:
<section class="contact" id="contact">: Menampilkan deskripsi singkat tentang desain portofolio web, teknologi yang digunakan, dan tautan ke GitHub.
Footer:

<footer role="contentinfo" class="footer">: Bagian footer situs dengan hak cipta dan kredit desain.
Back to Top:

Tautan yang membawa pengguna kembali ke atas halaman.
Fungsi Utama
Navigasi: Tautan navigasi memudahkan pengguna untuk berpindah antara bagian yang berbeda dari situs.
Deskripsi Proyek dan Toko: Setiap proyek dan toko online disajikan dengan deskripsi, teknologi yang digunakan, dan tautan eksternal yang relevan.
Proteksi CV: CV hanya bisa diakses dengan memasukkan kata sandi yang benar melalui fungsi JavaScript enterPassword().
Portofolio Tampilan: Desain responsif yang menggunakan kombinasi HTML, CSS, dan JavaScript untuk menampilkan informasi secara estetis.
Gambar dan Tautan
Gambar: Gambar digunakan untuk memberikan visualisasi tambahan untuk proyek dan diri anda.
Tautan: Tautan eksternal disertakan untuk GitHub, Instagram, dan toko online, memberikan pengguna akses langsung ke konten terkait.
Interaktivitas
JavaScript: Fungsi enterPassword() memberikan interaktivitas sederhana dengan validasi kata sandi untuk akses CV.
