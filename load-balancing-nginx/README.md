Judul
Load Balancing Menggunakan Nginx

Deskripsi
Task ini membahas implementasi load balancing pada sistem terdistribusi menggunakan Nginx sebagai reverse proxy. Load balancing digunakan untuk mendistribusikan permintaan client ke beberapa instance backend sehingga beban kerja dapat terbagi dan meningkatkan ketersediaan layanan.

Tujuan

Memahami konsep load balancing pada sistem terdistribusi

Mengimplementasikan Nginx sebagai load balancer

Menjalankan beberapa instance aplikasi backend

Menguji distribusi request ke backend

Tools dan Teknologi

Nginx

Docker

Docker Compose

Python Flask (Blacksheep)

Arsitektur Sistem
Client mengirim request ke Nginx. Nginx kemudian meneruskan request tersebut ke beberapa container backend secara bergantian menggunakan metode round-robin.

Langkah Implementasi

Menyiapkan aplikasi backend menggunakan framework Python Blacksheep

Membuat konfigurasi Nginx sebagai reverse proxy dan load balancer

Menjalankan beberapa instance backend menggunakan Docker Compose

Melakukan pengujian akses melalui browser

Hasil Pengujian
Hasil pengujian menunjukkan bahwa request client didistribusikan secara bergantian ke beberapa backend. Hal ini dapat dilihat dari perbedaan respon yang dikirimkan oleh masing-masing instance backend.

Video Penjelasan
Link video penjelasan:
https://drive.google.com/file/d/1njgztKZ7rLumY2SbrpolLcl__kaeTa6V/view?usp=drive_link

Source Code
Source code dan file konfigurasi terdapat pada direktori ini, meliputi file docker-compose.yml, konfigurasi Nginx, dan source code aplikasi backend.
