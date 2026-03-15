<div align="center">

<br>

# LAPORAN PRAKTIKUM

# APLIKASI BERBASIS PLATFORM

<br>

## MODUL 1

## GIT

<br>

<img src="logo.jpeg" width="300">

<br><br>

### Disusun Oleh

**Avrizal Setyo Aji Nugroho**  
**2311102145**  
**S1 IF-11-REG01**

<br>

### Dosen Pengampu

**Dimas Fanny Hebrasianto Permadi, S.ST., M.Kom**

<br>

### Asisten Praktikum

**Apri Pandu Wicaksono**  
**Rangga Pradarrell Fathi**

<br><br>

### LABORATORIUM HIGH PERFORMANCE

### FAKULTAS INFORMATIKA

### UNIVERSITAS TELKOM PURWOKERTO

### 2026

</div>

---

# 1. Dasar Teori

Git adalah sebuah sistem pengontrol versi (**Version Control System**) ciptaan **Linus Torvalds** yang sangat umum digunakan dalam rekayasa perangkat lunak. Fungsi utamanya adalah untuk melacak dan merekam segala modifikasi pada dokumen atau kode proyek, baik untuk pengerjaan secara mandiri maupun kolaborasi tim.

Git juga termasuk dalam kategori **Distributed Version Control System** (sistem kontrol versi terdistribusi). Artinya, basis data penyimpanan riwayat versi tidak hanya terpusat di satu server utama, melainkan salinannya terdistribusi secara lengkap di perangkat masing-masing pengembang.

---

# 2. Setup Repository via CLI

Di bawah ini langkah-langkah menginisiasi serta mengonfigurasi repositori dari perangkat lokal agar terhubung ke GitHub dengan menggunakan **Command Line Interface (CLI)**.

---

## Langkah 1: Pembuatan Repositori Baru di GitHub

Tahap pertama dilakukan dengan membuat sebuah repositori baru pada platform **GitHub**. Repositori tersebut akan digunakan sebagai tempat penyimpanan proyek berbasis _cloud_, sehingga kode program yang dikembangkan dapat dikelola, disimpan, dan dibagikan dengan lebih mudah serta efisien.

<img src="New.png" width="500">

---

## Langkah 2: Panduan Perintah Dasar Git

Setelah repositori berhasil dibuat, antarmuka GitHub secara otomatis menampilkan panduan berupa serangkaian perintah Git. Perintah-perintah tersebut berfungsi sebagai instruksi penting untuk menghubungkan folder proyek yang berada di penyimpanan lokal komputer dengan repositori _online_ di GitHub.

<img src="setup.png" width="500">
hasil
<img src="hasilsetup.png" width="500">

---

## Langkah 3: Penyiapan Folder Proyek dan File Awal

Langkah berikutnya adalah menyiapkan direktori proyek pada komputer, misalnya dengan membuat folder bernama **Modul_1**. Di dalam folder tersebut, buat minimal satu file contoh seperti **test.txt** sebagai isi awal repositori. Selain itu, Anda juga dapat menambahkan file lain yang diperlukan sesuai kebutuhan proyek.

<img src="file.png" width="500">

---

## Langkah 4: Membuka Terminal dari Direktori Proyek

Buka **Command Prompt (CMD)** atau terminal bawaan di sistem operasi Anda, lalu arahkan _path_ atau direktorinya menuju folder proyek yang baru saja dibuat. Langkah ini wajib dilakukan agar seluruh instruksi Git yang dieksekusi nantinya tepat sasaran pada folder yang dimaksud.

<img src="cmd.png" width="500">

---

## Langkah 5: Eksekusi Perintah Git (Proses Push ke GitHub)

Pada tahap ini, jalankan instruksi Git yang telah diberikan oleh GitHub sebelumnya secara berurutan di dalam terminal. Rangkaian alur kerjanya meliputi:

- Menginisialisasi pelacakan Git pada direktori lokal (`git init`)
- Memasukkan perubahan file ke dalam _staging area_ (`git add`)
- Menyimpan riwayat perubahan secara permanen di lokal (`git commit`)
- Menautkan repositori lokal ke repositori _remote_ GitHub
- Mengunggah kumpulan file dan riwayat tersebut ke GitHub (`git push`)

<img src="upload.png" width="500">

---

## Langkah 6: Pembaruan Repositori Berhasil

Jika proses _push_ berjalan sukses tanpa adanya pesan _error_, seluruh file dan struktur folder yang tadinya hanya berada di perangkat lokal kini otomatis tersimpan di repositori GitHub. Dengan demikian, proyek sudah siap untuk diakses dan dikembangkan lebih lanjut secara bersama-sama.

<img src="hasil.png" width="500">
