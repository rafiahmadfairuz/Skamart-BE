# E-Commerce Katalog Fullstack

Proyek ini adalah **website e-commerce katalog** yang dibangun dengan menggunakan **PHP Native**, **AJAX**, **jQuery**, **JavaScript**, dan **MySQL**. Dengan pendekatan **fullstack**, saya mengintegrasikan **front-end** dan **back-end** untuk menciptakan pengalaman belanja online yang cepat, efisien, dan mudah digunakan.

## Fitur Utama
- **Filter Produk**: Menampilkan filter canggih untuk menyaring produk berdasarkan kategori, harga, dan lainnya. Implementasi filter ini membutuhkan **query SQL yang Kompleks** dengan berbagai relasi antar tabel produk, kategori, dan stok.
- **Keranjang Belanja (Cart)**: Pengelolaan keranjang belanja yang dinamis, memungkinkan pengguna menambahkan, mengubah jumlah, dan menghapus produk tanpa me-refresh halaman. Dikelola dengan menggunakan **AJAX** untuk pembaruan waktu nyata.
- **Relasi Database MySQL**: Menggunakan **relasi yang kompleks** antar tabel dalam database MySQL untuk menyimpan data produk, kategori, stok, dan transaksi. Relasi ini diperlukan untuk mengelola data secara efisien dan menampilkan produk sesuai filter yang dipilih oleh pengguna.
- **Pengelolaan Produk dan Stok**: Admin dapat mengelola produk secara langsung melalui antarmuka sederhana, dengan pembaruan stok yang dinamis.

## Teknologi yang Digunakan
- **HTML5 & CSS3**: Untuk struktur dan desain halaman yang responsif dan user-friendly.
- **PHP Native**: Menangani logika **back-end** untuk mengelola data produk, transaksi, dan pengelolaan keranjang belanja secara langsung di server.
- **AJAX & jQuery**: Digunakan untuk interaksi real-time, seperti pembaruan produk di halaman tanpa me-refresh, serta pengelolaan keranjang belanja secara dinamis.
- **JavaScript**: Untuk menambahkan fungsionalitas interaktif di sisi pengguna, seperti pengelolaan filter dan cart yang efisien.
- **MySQL Database**: Menyimpan dan mengelola data produk, kategori, stok, serta transaksi. Relasi antar tabel seperti produk-kategori, produk-stok, dan transaksi-pelanggan digunakan untuk mempermudah pengelolaan data.

## Fitur Relasi Database MySQL
- **Relasi Antar Tabel**: Menggunakan **JOIN** untuk menggabungkan data dari beberapa tabel, seperti tabel produk, kategori, dan stok. Ini memungkinkan fitur **filter produk** untuk berfungsi dengan efisien, bahkan saat database memiliki ribuan produk.


