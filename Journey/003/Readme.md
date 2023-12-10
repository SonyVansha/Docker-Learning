# 03 Management Docker

![image](https://github.com/SonyVansha25/Docker-Learning/assets/152833966/68517005-6aa1-4307-9aaf-230c98a2ef83)

### Pengelolaan Container

- docker create (name_image): Membuat kontainer baru dari image.
- docker start : Menjalankan kontainer yang sudah dibuat
- docker stop : Menghentikan kontainer yang sedang berjalan
- docker restart : Restart kontainer yang berjalan.
- docker rm (container/id): Menghapus satu atau beberapa Container
- docker ps : Menampilkan daftar kontainer yang sedang berjalan
- docker ps -a : Menampilkan semua kontainer, termasuk yang sudah berhenti
- docker inspect : Menampilkan informasi detail tentang kontainer

### Pengelolaan Image:

- docker build : Membuat image dari Dockerfile
- docker build -t (name):(name new) : Membuat image dan nama baru dari Dockerfile
- docker pull (image) : Mengunduh image dari registry ke lokal
- docker push : Mengunggah image lokal ke Registry
- docker images : Menampilkan daftar image yang ada di lokal
- docker rmi : Menghapus satu atau beberapa image
- docker history : Menampilkan riwayat perubahan pada suatu image
- docker run --name (container) (redis:2.0) : Mengganti nama Tags container

### Pengaturan Jaringan:

- docker network ls : Menampilkan daftar jaringan yang ada.
- docker network create (name) : Membuat jaringan baru
- docker network connect : Menghubungkan kontainer ke jaringan tertentu
- docker network disconnect : Mencabut koneksi kontainer dari jaringan

### Manajemen Sumber Daya:

- docker stats : Menampilkan statistik penggunaan sumber daya kontainer
- docker exec -it (name/id) : Menjalankan perintah di dalam kontainer yang sedang berjalan
- docker attach : Menghubungkan terminal Anda ke kontainer yang sedang berjalan
- docker logs (container/id) : menampilkan log sebuah container
- docker volume ls : menampilkan daftar semua Volume
- docker volume prune : menghapus semua Volume Anonymous

### Lainnya:

- docker version : Menampilkan informasi versi Docker yang terpasang
- docker info : Menampilkan informasi detail tentang konfigurasi Docker
- docker login : Masuk ke registry Docker
- docker logout : Keluar dari registry Docker
