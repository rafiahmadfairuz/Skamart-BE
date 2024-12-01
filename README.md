# E-Commerce Katalog Fullstack

Proyek ini adalah **website e-commerce katalog** yang dibangun dengan menggunakan **PHP Native**, **AJAX**, **jQuery**, **JavaScript**, dan **MySQL**. Dengan pendekatan **fullstack**, saya berhasil mengintegrasikan **front-end** dan **back-end** untuk menciptakan pengalaman belanja online yang cepat, responsif, dan efisien. Sistem ini mendukung dua peran utama: **Pembeli** dan **Admin**, yang masing-masing memiliki fitur yang disesuaikan untuk mempermudah pengalaman berbelanja dan pengelolaan produk.

## Fitur Utama

### Untuk Pembeli:
- **Filter Produk**: Fitur filter canggih memungkinkan pembeli untuk menyaring produk berdasarkan kategori, harga, dan atribut lainnya. Dibangun dengan **query SQL yang kompleks**, filter ini memanfaatkan **relasi antar tabel** seperti produk, kategori, dan stok, memastikan hasil pencarian yang akurat dan relevan, bahkan dengan ribuan produk di database.
- **Keranjang Belanja (Cart)**: Pengelolaan keranjang belanja yang dinamis memungkinkan pengguna untuk menambahkan, mengubah jumlah, atau menghapus produk tanpa perlu me-refresh halaman. Semua interaksi ini diatur menggunakan **AJAX**, menciptakan pengalaman belanja yang lebih lancar dan tanpa gangguan.
- **Relasi Database MySQL**: Database **MySQL** yang digunakan dalam proyek ini mengelola **relasi antar tabel** untuk produk, kategori, stok, dan transaksi. Struktur relasi yang cermat memungkinkan data dapat diakses dan diperbarui dengan efisien, mempercepat proses pencarian dan pembaruan produk di halaman.

### Untuk Admin:
- **CRUD Produk**: Admin dapat dengan mudah **menambah**, **mengedit**, atau **menghapus** produk melalui antarmuka yang sederhana namun kuat. Setiap pembaruan produk secara otomatis memperbarui stok produk di database, menjaga konsistensi informasi yang ditampilkan kepada pembeli.
- **Pengelolaan Kategori dan Stok**: Admin memiliki akses penuh untuk mengelola **kategori produk** dan memantau **stok produk**. Sistem ini memastikan informasi stok selalu akurat dan dapat diakses kapan saja.
- **Manajemen Transaksi**: Admin dapat melihat dan mengelola **daftar transaksi pembeli** yang mencakup rincian produk yang dibeli, jumlah, serta total transaksi. Fitur ini memudahkan admin untuk memantau penjualan dan mengelola operasional toko secara efisien.

## Teknologi yang Digunakan
- **HTML5 & CSS3**: Untuk **struktur dan desain halaman** yang responsif dan ramah pengguna. Penggunaan **CSS3** memastikan tampilan yang menarik dan modern, dengan desain yang menyesuaikan dengan berbagai ukuran layar.
- **PHP Native**: **Back-end** aplikasi ini dibangun menggunakan **PHP Native** untuk mengelola data produk, transaksi, dan keranjang belanja secara langsung di server. Pendekatan ini memungkinkan aplikasi berjalan dengan cepat dan ringan.
- **AJAX & jQuery**: **AJAX** digunakan untuk melakukan pembaruan data di halaman secara **real-time** tanpa me-refresh halaman. **jQuery** mempercepat proses pembuatan interaksi yang dinamis dan responsif, seperti pengelolaan keranjang belanja.
- **JavaScript**: Untuk meningkatkan fungsionalitas interaktif di sisi pengguna, termasuk **pengelolaan filter produk** dan **keranjang belanja**, serta interaksi lainnya yang memberikan pengalaman pengguna yang lebih menyenangkan.
- **MySQL Database**: Database ini mengelola data produk, kategori, stok, dan transaksi menggunakan **relasi antar tabel** yang kompleks. Relasi ini memungkinkan fitur **filter produk** dan pengelolaan stok yang efisien, serta memastikan bahwa pembeli hanya melihat produk yang tersedia.

## Fitur Relasi Database MySQL
- **Relasi Antar Tabel**: Menggunakan **JOIN** untuk menggabungkan data dari beberapa tabel seperti produk, kategori, dan stok. Ini memungkinkan fitur filter produk untuk bekerja secara **efisien**, memastikan pembeli dapat menemukan produk yang mereka cari dengan cepat, bahkan jika jumlah data sangat besar.

---

Proyek ini tidak hanya menunjukkan kemampuan saya dalam membangun sistem **e-commerce fullstack**, tetapi juga keahlian saya dalam merancang database yang efisien, serta menciptakan pengalaman pengguna yang lancar dengan menggunakan **AJAX** dan **jQuery**. Dengan integrasi **PHP Native** dan **MySQL**, saya dapat mengelola data secara dinamis dan responsif, memberikan pengalaman belanja yang tidak hanya cepat tetapi juga mudah digunakan.
