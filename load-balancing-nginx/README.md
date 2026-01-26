Judul
Load Balancing Menggunakan Nginx

Deskripsi
Task ini membahas implementasi load balancing pada sistem terdistribusi menggunakan Nginx sebagai reverse proxy. Load balancing digunakan untuk mendistribusikan permintaan client ke beberapa instance backend sehingga beban kerja dapat terbagi dan meningkatkan ketersediaan layanan.

Tujuan

Memahami konsep load balancing pada sistem terdistribusi

Mengimplementasikan Nginx sebagai load balancer

Menjalankan beberapa instance aplikasi backend

Menguji distribusi request ke backend

Nginx

Docker

Docker Compose

Arsitektur Sistem
Client mengirim request ke Nginx. Nginx kemudian meneruskan request tersebut ke beberapa container backend secara bergantian menggunakan metode round-robin.

Langkah Implementasi

Membuat konfigurasi Nginx sebagai reverse proxy dan load balancer

Menjalankan beberapa instance backend menggunakan Docker Compose

Melakukan pengujian akses melalui browser

Hasil Pengujian
Hasil pengujian menunjukkan bahwa request client didistribusikan secara bergantian ke beberapa backend. Hal ini dapat dilihat dari perbedaan respon yang dikirimkan oleh masing-masing instance backend.

Video Penjelasan
Link video penjelasan:(maaf videonya ada di loom yang mode free pakai tidak ada fitur downloadnya jadi gak bisa saya upload ke google drive)
https://www.loom.com/share/39e7215b70224d34a1abbc2e5368f837

Source Code
Source code dan file konfigurasi terdapat pada direktori ini, meliputi file docker-compose.yml, konfigurasi Nginx.
