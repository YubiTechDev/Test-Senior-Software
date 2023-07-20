# Tes Teknikal: Website E-commerce 

Deskripsi:

Anda bertugas untuk mengembangkan fungsionalitas untuk sebuah website e-commerce . Website ini akan memungkinkan pengguna untuk menjelajahi produk, menambahkan item ke keranjang belanja, melanjutkan ke proses pembayaran, dan menyelesaikan pembelian. Juga, implementasikan fungsionalitas autentikasi pengguna dan pencarian produk.

## Fungsi yang harus diimplementasikan:

### Manajemen Produk:
- Implementasikan fungsionalitas CRUD (Create, Read, Update, Delete) untuk mengelola produk di dalam database. Setiap produk harus memiliki nama, deskripsi, harga, dan stok yang tersedia.

### Autentikasi Pengguna:

- Implementasikan fungsionalitas registrasi dan login pengguna dengan validasi yang tepat dan penyimpanan kata sandi yang aman.
- Pengguna harus dapat memperbarui informasi profil mereka.

### Keranjang Belanja:

- Implementasikan fungsionalitas keranjang belanja untuk pengguna agar dapat menambahkan produk, memperbarui jumlah barang, dan menghapus item dari keranjang.
- Tampilkan harga total dan jumlah barang di keranjang setiap saat.

### Proses Pembayaran:

- Izinkan pengguna untuk melanjutkan ke proses pembayaran dari halaman keranjang belanja.
- Implementasikan proses pembayaran yang sederhana dengan gateway pembayaran palsu (tidak ada pembayaran sebenarnya yang diperlukan).

### Pencarian Produk:

- Implementasikan fungsionalitas pencarian produk untuk memungkinkan pengguna menemukan produk berdasarkan nama atau deskripsi.


### Skema Database Minimum:

- users: id, name, email, password, created_at, updated_at

- products: id, name, description, price, stock, created_at, updated_at

- carts: id, user_id, product_id, quantity, created_at, updated_at

- orders: id, user_id, total_price, created_at, updated_at

## Kriteria Penilaian:

- ### Fungsionalitas (60 poin): 
    Semua fitur berjalan dengan baik

- ### Kualitas Kode (25 poin):
    Menerapkan pola desain Clean ataupun modular, struktur file system terogranisir

- ### Desain Database (10 poin):
    Menerapkan ORM secara efisien dan optimal.

- ### Pencarian Produk (5 poin): 
    Evaluasi ketepatan dan kecepatan fungsionalitas pencarian produk.

## Pemilihan framework
Kandidat bisa memilih tools/framework untuk digunakan
- Backend : Laravel, NodeJs, .Net
- Frontend : VueJS, React JS
- State Management : Vue (Pinia, Vuex), React (Redux Toolkit, React Query)
- ORM : Eloquent, TypeORM, Sequallize, Prisma
- Auth : JWT, SSO, OAuth
- Database : MySQL, PostgreSQL, atau lainnya - (Wajib RDBMS)
## Submisi Tes:

    Kandidat harus menyerahkan kode sumber backend beserta dokumen singkat yang menjelaskan arsitektur secara keseluruhan, keputusan desain penting yang diambil, dan instruksi tentang cara menjalankan backend secara lokal untuk pengujian.
