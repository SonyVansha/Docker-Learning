# Pengenalan Container

![image](https://github.com/SonyVansha25/Docker-Learning/assets/152833966/7e7527ed-084b-4bd5-8bc7-06498262b5d6)

## Apa itu Container?

Containers adalah salah satu implementasi Container manager yang digunakan untuk mempermudah pengembangan aplikasi dengan cara mengemas dan mengisolasi suatu aplikasi secara virtual.

Perbedaan dengan VM adalah dapat mem-package aplikasi dan dependency tanpa harus menggabungkan Sistem Operasi

## Fungsi Container

- Memungkinkan aplikasi untuk berjalan di lingkungan yang terisolasi dari lingkungan lain di dalam mesin yang sama
- aplikasi beserta semua dependensinya dikemas bersama dalam satu unit yang dapat dijalankan di lingkungan apapun
- memanfaatkan sumber daya secara efisien dengan membagi sumber daya host (seperti CPU, RAM, dan penyimpanan) di antara kontainer-kontainer yang berjalan.
- memudahkan dalam skalabilitas aplikasi karena dapat dengan mudah membuat dan menghapus kontainer sesuai dengan kebutuhan

## Dimana Container berjalan?

Container menggunakan <b>OS host</b> dimana COntainer Manager berjalan, karena hal itu lebih hemat resource dan lebih cepat, karena tidak butuh OS sendiri