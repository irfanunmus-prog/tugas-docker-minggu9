# Tugas Docker Minggu 9

## Identitas
Nama: Muhammad Irfan
NIM: 202557201062
Mata Kuliah: Teknologi Open Source

## Deskripsi
Proyek ini merupakan tugas kontainerisasi halaman profil
menggunakan Docker dan Nginx.

## Cara Build Image
docker build -t profil-muhammadirfan:1.0 .

## Cara Menjalankan Container
docker run -d --name profil-muhammadirfan -p 8082:80 profil-muhammadirfan:1.0

## Memeriksa Container
docker ps

## Membuka Halaman
http://localhost:8082

## File Proyek
- Dockerfile
- index.html
- README.md
