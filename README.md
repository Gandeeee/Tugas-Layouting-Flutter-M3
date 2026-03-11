# Laporan Tugas Layouting Flutter

## Identitas Mahasiswa
* **Nama:** Kadek Gandhi Wahyu Jaya Suastika
* **NIM:** 1202230017
* **Program Studi:** IT 06-01
* **Mata Kuliah:** Aplikasi Perangkat Bergerak

## Deskripsi Tugas
Proyek ini merupakan implementasi tata letak antarmuka pengguna (User Interface) statis berbasis kerangka kerja Flutter. 
Seluruh komponen antarmuka, termasuk hierarki `Container`, `Column`, `Row`, serta tipografi dan komposisi warna gradien, telah diimplementasikan secara identik dengan source code yang diberikan.

## Eksplorasi dan Modifikasi Konfigurasi
Sesuai dengan arahan dasar tugas, struktur hierarki widget dipertahankan secara utuh. Namun, untuk meningkatkan validitas dan fungsionalitas visual antarmuka, telah dilakukan satu modifikasi teknis yang terukur pada komponen profil pengguna.

Modifikasi tersebut meliputi:
1. **Integrasi Aset Statis:** Menambahkan direktori lokal `assets/` dan mengonfigurasi berkas `pubspec.yaml` untuk mendaftarkan berkas gambar secara spesifik.
2. **Implementasi Parameter Profil:** Mengaktifkan atribut `backgroundImage` pada widget `CircleAvatar` untuk memuat dan merender `AssetImage('assets/profpic.png')` ke dalam memori aplikasi, menggantikan status awal yang sebelumnya dikomentari (commented out).

## Bukti Eksekusi Aplikasi (Evidence)
Berikut adalah tangkapan layar (screenshot) yang memvalidasi bahwa seluruh baris kode telah berhasil dikompilasi tanpa galat dan dirender dengan sempurna pada perangkat pengujian.

(<img width="967" height="1119" alt="image" src="https://github.com/user-attachments/assets/e56f19fc-1340-4f04-bacf-f05add6c3763" />)
