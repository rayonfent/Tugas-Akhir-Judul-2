# Tugas Akhir Modul 2 - Git & Version Control
Repository ini berisi hasil pengerjaan Tugas Akhir Modul 2 mata kuliah Praktikum Pemrograman Web.  
Tujuan dari tugas ini adalah untuk menerapkan konsep dan workflow Git, mulai dari inisialisasi repository, commit bertahap, pembuatan branch, penggabungan (merge).


## Deskripsi Proyek
Proyek ini merupakan halaman portofolio pribadi yang dibuat menggunakan HTML dan CSS eksternal.  
Website menampilkan profil singkat mahasiswa, daftar proyek, dan formulir kontak sederhana.  
Tugas ini merupakan pengembangan dari proyek sebelumnya (Judul 1) dengan pembaruan pada tampilan (Judul 2),
yaitu perubahan warna tema menjadi biru lembut di beberapa bagian halaman.


## Struktur Folder
ta-judul-1/
|-index.html
|-style.css
|-ilust.jpg
|-profil.jpg
|-README.md


## Isi index.html
File `index.html` berfungsi sebagai halaman utama website portofolio.  
Struktur utamanya terdiri atas:

1. **Header dan Navigasi**  
   Menampilkan nama lengkap, deskripsi singkat, dan tautan navigasi ke bagian Tentang, Proyek, dan Kontak.

2. **Bagian Tentang Saya**  
   Menjelaskan profil mahasiswa, minat, serta keterampilan.  
   Data disusun dengan elemen semantik HTML seperti `<section>`, `<ul>`, dan `<aside>`.

3. **Bagian Proyek**  
   Berisi informasi tentang proyek sebelumnya (Judul 1) yang menjadi dasar pengembangan halaman ini.  
   Termasuk tautan menuju repository GitHub tugas sebelumnya.

4. **Bagian Kontak**  
   Formulir sederhana dengan input teks, email, pilihan kota, dan kolom pesan.  
   Bagian ini digunakan untuk simulasi penerapan elemen form dalam HTML.

5. **Footer**  
   Menampilkan hak cipta dan navigasi tambahan.

Selain itu, pada elemen `<head>` terdapat meta tag untuk pengaturan karakter, viewport, dan deskripsi halaman, serta pemanggilan file `style.css` sebagai sumber gaya eksternal.


## Isi File style.css

File `style.css` mengatur tampilan halaman website dengan tema warna biru.  
Perubahan utama dari versi sebelumnya (Judul 1)

Struktur file `style.css` dibagi menjadi beberapa bagian, yaitu :
1. Pengaturan variabel warna dan font.
2. Gaya untuk elemen utama seperti `body`, `header`, `nav`, `main`, dan `footer`.
3. Pengaturan tata letak gambar dan teks agar responsif.
4. Komentar pembuka sebagai penanda bahwa ini adalah versi Tugas Judul 2.


## Workflow Git

Seluruh tahapan Git dilakukan di lingkungan lokal (Git Bash) dengan alur kerja berikut:

1. Inisialisasi repository menggunakan `git init`.
2. Melakukan commit bertahap pada setiap penambahan file:
   - index.html
   - style.css
   - File gambar pendukung
3. Membuat branch baru `feature-styling` untuk percobaan perubahan tema.
4. Mengedit file `style.css` dengan palet warna biru dan mengganti teks menjadi “Tugas Judul 2”.
5. Melakukan merge branch `feature-styling` ke branch utama (`main`).
6. Menambahkan file `README.md` sebagai dokumentasi proyek.
7. Menampilkan riwayat commit menggunakan perintah : git log --graph --oneline


## Author

Nama : Rayhan Danar Abiyyuendra  
NPM : 2315061098  
Mata Kuliah : Praktikum Pemrograman Web  
Judul Modul : Modul 2 - Git & Version Control  
Tahun: 2025  
Institusi : Universitas Lampung
