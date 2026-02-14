# Laporan Tugas P08: Containerized Application
**Nama:** Jeky Setyawan  
**NIM:** 235410083  
**Mata Kuliah:** Sistem Terdistribusi dan Terdesentralisasi

## Deskripsi Tugas
Tugas ini bertujuan untuk melakukan pembungkusan (containerization) aplikasi web berbasis Flask ke dalam sebuah Docker Image. Dengan menggunakan Docker, aplikasi dapat dijalankan secara konsisten di berbagai lingkungan tanpa masalah dependensi.

## Komponen Utama
1. **Dockerfile**: Berisi instruksi langkah demi langkah untuk membangun image aplikasi.
2. **Flask-App**: Source code aplikasi web yang akan dijalankan di dalam container.
3. **Python 3.13**: Digunakan sebagai base image utama dalam proses pembangunan.

## Progres Implementasi
- [x] Inisialisasi folder tugas di GitHub.
- [x] Upload source code dan Dockerfile ke repository.
- [ ] Proses `docker build` (Sedang berlangsung/Extracting base image).
- [ ] Menjalankan container dengan `docker run`.
- [ ] Verifikasi aplikasi melalui browser di `localhost:5000`.

## Kendala yang Dihadapi
Proses pembangunan image memakan waktu cukup lama pada tahap penarikan (pulling) data dari Docker Hub karena ukuran base image Python yang cukup besar, namun proses tetap berjalan stabil di tahap ekstraksi.

## Video Penjelasan
Link video penjelasan: (maaf pak di loom fitur downloadnya terkunci jadi saya unggah langsung dari loom tanpa dipindah ke google drive dulu)
(https://www.loom.com/share/7ec530addb4f4e578dfff3b848ce5956)


## Source Code
Source code dan file konfigurasi terdapat pada direktori ini, meliputi:
* **Dockerfile**: Konfigurasi build image.
* **flaskr/**: Folder utama kode program Flask.
