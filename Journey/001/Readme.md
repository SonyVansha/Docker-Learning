# 1 Pengenalan Docker

![image](https://github.com/SonyVansha25/Docker-Learning/assets/152833966/9b9aec6b-2c15-4d62-9b6c-eacc27e26c86)


## Apa itu Docker?

Docker adalah layanan yang menyediakan kemampuan untuk mengemas dan menjalankan sebuah aplikasi dalam sebuah lingkungan terisolasi yang disebut dengan <b>container</b>

Docker ini diperkenalkan pada tahun 2013 oleh Solomon Hykes pada acara PyCon. Beberapa bulan setelahnya docker secara resmi diluncurkan, tepatnya pada tahun 2014.

## Fitur - fitur Docker

- <b color="blu">Docker engine</b> : digunakan untuk membuat image dan container
- <b>Docker Hub</b> : Registry (layanan yang menyimpan container) yang berisikan kumpulan dari image-image
- <b>Docker Compose</b> : berfungsi menjalankan beberapa container (<i>multi-container</i>) sehingga dapat menghemat banyak waktu
- <b>Docker for Mac</b> : memungkinkan pengguna Docker menjalankan container pada OS Mac
- <b>Docker for Linux</b> : memungkinkan pengguna Docker menjalankan container pada OS Linux
- <b>Docker for Windows</b> : memungkinkan pengguna Docker menjalankan container pada OS Windows

## Kelebihan & Kekurangan menggunakan Docker

### Kelebihan
- Memiliki konfigurasi yang sederhana
- Tingkat keamanan yang baik
- Dapat dijalankan pada beberapa platform cloud
- Dapat melakukan debugging
- Dapat digunakan pada berbagai sistem operasi

### Kekurangan
- lebih lambat dibandingkan dengan menjalankan aplikasi secara native pada server fisik


## Fungsi Docker
- <b>Mencoba Software Baru</b>
- <b>Mempelajari CLI</b>
- <b>Mengurangi Resiko Insiden (kegagalan)</b>

## Architecture docker

![image](https://github.com/SonyVansha25/Docker-Learning/assets/152833966/ce832c7f-e929-484d-bcd4-32177ad94fd5)

- <b>Docker Client</b> : pengguna menggunakan Docker Client untuk membuat, mengelola, dan menjalankan kontainer melalui command-line interface (CLI) atau antarmuka grafis. Ketika gunakan perintah <i>docker run</i> atau <i>docker build</i>, sebenarnya berkomunikasi dengan Docker Daemon (host) melalui Docker Client.
- <b>Docker Host (Docker Daemon)</b> : Docker Daemon berjalan di mesin tujuan (biasanya disebut host) dan bertanggung jawab atas membuat dan mengelola kontainer.
- <b>Docker Registry</b> : Docker Registry adalah tempat penyimpanan untuk image Docker. 
